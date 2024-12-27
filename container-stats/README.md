# 🚨 Addons are moved 🚚

__I moved my addons to a own organisation for easier maintaining and maybe allowing contributers to maintain one addon as well. Please switch to the new repository to get future updates.__

The new home of my addons is: https://github.com/Poeschl-HomeAssistant-Addons/repository

A migration guide is available here: [migrate_from_Poeschl_repository.md](https://github.com/Poeschl-HomeAssistant-Addons/repository/docs/migrate_from_Poeschl_repository.md)

---

# Docker Container Stats (Home Assistant Addon)

# 🕸️ Depreciated

It contains [Docker Container Stats](https://github.com/virtualzone/docker-container-stats) to monitor all running containers / addons.

![Addon Stage][stage-badge]
![Supports aarch64 Architecture][aarch64-badge]
![Supports amd64 Architecture][amd64-badge]
![Supports armhf Architecture][armhf-badge]
![Supports armv7 Architecture][armv7-badge]
![Supports i386 Architecture][i386-badge]

[![Add repository on my Home Assistant][repository-badge]][repository-url]
[![Install on my Home Assistant][install-badge]][install-url]
[![Donate][donation-badge]][donation-url]

## 🧪 Experimental Addon

During long-term usage I noticed that the addon fills up all available memory when getting the data for a week.
Especially on a Raspberry Pi with Home Assistant this means death in a few minutes.
__Use this addon on your own risk!__

## Security

Since the addon accesses the docker api, the security rating is this low.
Unfortunately there is now way to access the docker api without disabling the *Protection Mode* of the addon.
Technically with disabling it, the addon can access and control other addons and the core on a HA supervised system.
But without it we can not retrieve the statistics of the running container and this addon don't work at all.


[aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg?style=for-the-badge
[amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg?style=for-the-badge
[armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg?style=for-the-badge
[armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg?style=for-the-badge
[i386-badge]: https://img.shields.io/badge/i386-yes-green.svg?style=for-the-badge
[stage-badge]: https://img.shields.io/badge/Addon%20stage-experimental%20🧪-yellow.svg?style=for-the-badge
[install-badge]: https://img.shields.io/badge/Install%20on%20my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl
[repository-badge]: https://img.shields.io/badge/Add%20repository%20to%20my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge

[install-url]: https://my.home-assistant.io/redirect/supervisor_addon?addon=243ffc37_container-stats
[repository-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FPoeschl%2FHassio-Addons
