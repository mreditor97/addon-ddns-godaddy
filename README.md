# Home Assistant Add-on: GoDaddy Dynamic DNS Updater

Automatically update your GoDaddy DNS IP address with integrated HTTPS support via Let's Encrypt.

[![Release][release-shield]][release]
![Supports aarch64 Architecture][aarch64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports i386 Architecture][i386-shield]

## About

This add-on updates your DNS records that are hosted on [GoDaddy][godaddy] to an IP address of your choice.
It includes the support for creating and renewing your Let's Encrypt certificate automatically.

**You must have a domain hosting account with GoDaddy and must have a GoDaddy API key before being able to use this addon.**

_This is a modified version of [mrmichaelrb's][mrmichaelrb] GoDaddy Dynamic DNS Updater - so all credit goes to him! Thanks!_

[release-shield]: https://img.shields.io/github/v/release/mreditor97/addon-ddns-godaddy?color=blue&include_prereleases
[release]: https://github.com/mreditor97/addon-ddns-godaddy/releases
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/mreditor97/addon-ddns-godaddy/issues
[godaddy]: https://www.godaddy.com
[mrmichaelrb]: https://github.com/mrmichaelrb/hassio-addons
