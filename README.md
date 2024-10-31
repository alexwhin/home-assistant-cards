# Home Assistant Custom Cards Collection

![Home Assistant Compatibility](https://img.shields.io/badge/Home%20Assistant-2024.10.4+-blue)
![License](https://img.shields.io/github/license/alexwhin/home-assistant-cards)
![Last Commit](https://img.shields.io/github/last-commit/alexwhin/home-assistant-cards)

This repository features custom dashboard cards that I’ve crafted and actively use in my own [Home Assistant](https://www.home-assistant.io/) setup. Designed to streamline the UI and match my personal preferences, each card is built to be effortlessly integrated—no templates or advanced configurations required. I’m excited to share these with the community, making it easy for anyone to enhance their setup with minimal effort.

---

## Samsung Animated Washing Machine Card

The **Samsung Animated Washing Machine Card** brings your washing machine’s status to life with real-time animations. This card integrates seamlessly with [Samsung SmartThings](https://www.home-assistant.io/integrations/smartthings/) to reflect the current state of your washing machine, displaying whether it’s off, on, or actively washing including a more "human readable" completion time.

### Screenshots

The following images illustrate the card’s appearance in different states:

| Idle State                                    | Wash State                                      |
| --------------------------------------------- | ----------------------------------------------- |
| ![Off State](cards/screenshots/off-state.png) | ![Wash State](cards/screenshots/wash-state.png) |

### Setup Guide

To get started, follow these steps to add the Samsung Animated Washing Machine Card to your Home Assistant dashboard:

1. **Install the Button Card**: Follow the [Button Card installation guide](https://github.com/custom-cards/button-card).
2. **Set Up SmartThings Integration**: Connect your Samsung washing machine to Home Assistant through the SmartThings integration.
3. **Add the Custom Card**: Use the YAML configuration stored in [`cards/samsung-washing-machine.yaml`](cards/samsung-washing-machine.yaml).
