# Zanix's Home Assistant Blueprints

| zanix/home-assistant-blueprints | Home Assistant Community |
| :---: | :---: |
| [![Last Commit][github-last-commit]][github-main] [![Github Linter Status][github-linter-status-shield]][github-linter-status] | [![Home Assistant Community Forum][forum-shield]][forum] |
| [![GitHub Activity][commits-shield]][commits] | [![Discord][discord-shield]][discord] |

## Current Blueprints

### Script

#### Inovelli Blue LED (Zigbee2MQTT)

Set LED effects for Inovelli VZM31-SN Blue Series 2-1 Switches

[Forum](https://community.home-assistant.io/t/z2m-inovelli-blue-series-switch-led-notification-script-vzm31-sn-vzm35-sn/489620)
 | [YAML](https://github.com/zanix/home-assistant-blueprints/blob/main/script/inovelli_blue_led_zigbee2mqtt.yaml)

[![Import Blueprint][blueprint-import]](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fzanix%2Fhome-assistant-blueprints%2Fblob%2Fmain%2Fscript%2Finovelli_blue_led_zigbee2mqtt.yaml)

## Thanks

- [@brianhanifin](https://github.com/brianhanifin) ([HA Profile](https://community.home-assistant.io/u/brianhanifin)) - Original "Inovelli Z-Wave Red Series Notification LED" script
- [@kschlichter](https://github.com/kschlichter) ([HA Profile](https://community.home-assistant.io/u/kschlichter)) - Logic for multiple areas, devices, and entities
- [@romamix](https://github.com/romamix) ([HA Profile](https://community.home-assistant.io/u/romamix)) - Idea to override MQTT command path
- [@dmoralesdev](https://github.com/dmoralesdev) ([HA Profile](https://community.home-assistant.io/u/diegomorales17)) - Loop optimization ideas

---

**All files are edited with [Visual Studio Code](https://code.visualstudio.com).**

[github-linter-status-shield]: https://img.shields.io/github/actions/workflow/status/zanix/home-assistant-blueprints/linters.yaml?branch=main&style=flat-square&label=linters&logo=github-actions&logoColor=838B95
[github-linter-status]: https://github.com/zanix/home-assistant-blueprints/actions/workflows/linters.yaml

[github-last-commit]: https://img.shields.io/github/last-commit/zanix/home-assistant-blueprints/main?style=flat-square&logo=github&logoColor=838B95
[github-main]: https://github.com/zanix/home-assistant-blueprints/commits/main

[commits-shield]: https://img.shields.io/github/commit-activity/m/zanix/home-assistant-blueprints/main?style=flat-square&logo=github&logoColor=838B95
[commits]: https://github.com/zanix/home-assistant-blueprints/commits/main

[forum-shield]: https://img.shields.io/discourse/topics?style=flat-square&label=community&logo=discourse&color=46B4ED&logoColor=46B4ED&server=https%3A%2F%2Fcommunity.home-assistant.io
[forum]: https://community.home-assistant.io

[discord-shield]: https://img.shields.io/discord/330944238910963714?style=flat-square&color=7289da&label=discord&logo=discord
[discord]: https://discord.gg/c5DvZ4e

[blueprint-import]: https://my.home-assistant.io/badges/blueprint_import.svg
