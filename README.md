# Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![Community Forum][forum-shield]][forum]

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, add-ons that allow you to take your automated home to the next level.

## Installation

Adding this add-ons repository to your Home Assistant instance is pretty easy.
In the Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
[![Add this repository to your Home Assistant instance.][repository-badge]][repository]
```

## Add-ons provided by this repository

### &#10003; [Snapmaker Monitor][addon-snapmaker-monitor]

![Latest Version][snapmaker-monitor-version-shield]
![Supports armv7 Architecture][snapmaker-monitor-armv7-shield]
![Supports aarch64 Architecture][snapmaker-monitor-aarch64-shield]
![Supports amd64 Architecture][snapmaker-monitor-amd64-shield]

Python script to monitor Snapmaker 2.0 printer status and send updates to Home Assistant.

[:books: Snapmaker Monitor add-on documentation][addon-doc-snapmaker-monitor]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You can open an issue here on GitHub. Note, we use a separate GitHub
repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Snapmaker Monitor][snapmaker-monitor-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2025 Steven 'NemesisRE' Kurz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-snapmaker-monitor]: https://github.com/NRE-Com-Net/hassio-addon-snapmaker-monitor/tree/v1.0.1
[addon-doc-snapmaker-monitor]: https://github.com/NRE-Com-Net/hassio-addon-snapmaker-monitor/blob/v1.0.1/README.md
[snapmaker-monitor-issue]: https://github.com/NRE-Com-Net/hassio-addon-snapmaker-monitor/issues
[snapmaker-monitor-version-shield]: https://img.shields.io/badge/version-v1.0.1-blue.svg
[snapmaker-monitor-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[snapmaker-monitor-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[snapmaker-monitor-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[repository-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[repository]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FNRE-Com-Net%2Fhassio-addons
[forum-NemesisRE]: https://community.home-assistant.io/u/NemesisRE/?u=NemesisRE
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen
[forum]: https://community.home-assistant.io?u=NemesisRE
[NemesisRE]: https://github.com/NemesisRE
[gitlabci-shield]: https://gitlab.com/NRE-Com-Net/hassio-addons/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/NRE-Com-Net/hassio-addons/pipelines
[issue]: https://github.com/NRE-Com-Net/hassio-addons/issues
[license-shield]: https://img.shields.io/github/license/NRE-Com-Net/hassio-addons/repository
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen
[semver]: http://semver.org/spec/v2.0.0.html