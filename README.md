# Trash-Guide-TokenMinal-Supplement-Template

This repository serves as a direct supplement to the [TRaSH Guide](https://trash-guides.info/) for use with [Recyclarr](https://recyclarr.dev/). It provides an alternative Sonarr v4 Anime configuration that targets **WEB releases only**.

## Prerequisite

This repository is designed to be used specifically with:

* [Trash-Guide-TokenMinal-Supplement](https://github.com/TokenMinal/Trash-Guide-TokenMinal-Supplement)

## Features

* **WEB-Exclusive Anime Profile**: Includes a dedicated `Web-1080p - Anime` quality profile that prioritizes WEBDL/WEBRip while excluding Bluray and Remux sources.
* **Native Repack & Upgrade Logic**: Standard TRaSH Guide logic often fails to trigger upgrades for Anime REPACKs using p2p naming. This supplement fixes that by natively implementing Custom Formats (such as `repack+v2`) that explicitly catch and trigger these upgrades.

## License

This project is licensed under the MIT License.
