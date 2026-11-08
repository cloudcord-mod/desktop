<div align="center">

<img src="https://raw.githubusercontent.com/cloudcord-mod/release-hub/main/assets/cloudcord-logo.png" width="250" alt="CloudCord logo">

# CloudCord Desktop

**The Windows installer, desktop runtime, and browser builds.**

[**Downloads**](https://getcloudcord.com/#download) · [**Release Hub**](https://github.com/cloudcord-mod/release-hub) · [**Builds**](https://github.com/cloudcord-mod/desktop/actions) · [**Status**](https://getcloudcord.com/status)

</div>

---

## Install

- **Windows** · Run the [CloudCord installer](https://getcloudcord.com/download/windows), pick Discord Stable, PTB, or Canary, and choose **Install**. Use the installer again to repair or uninstall CloudCord.
- **Browser** · Download the [Chrome / Brave extension](https://getcloudcord.com/download/browser/chrome), [Firefox extension](https://getcloudcord.com/download/browser/firefox), or [userscript](https://getcloudcord.com/download/browser/userscript). Follow the instructions in the [browser download menu](https://getcloudcord.com/#download).
- **macOS** · Choose the DMG for your processor in the [CloudCord macOS repository](https://github.com/cloudcord-mod/macos).

## What ships here

The desktop client includes Fake Profile, BotCord, and an Add-ons page for plugins, themes, and tweaks. Supported CX add-ons use the shared catalog maintained in Release Hub.

The [desktop workflow](.github/workflows/build.yml) assembles the source under [`desktop/client/`](desktop/client) with pinned Release Hub inputs. It checks the client and uploads Windows, runtime, and browser artifacts. Official packages are published through [Release Hub releases](https://github.com/cloudcord-mod/release-hub/releases).

[Source and history before the repository split](https://github.com/cloudcord-mod/release-hub/commit/69bdb299aad1032b898a8d2904d9024b52721349).

## Credits and license

CloudCord is maintained by [Xohus](https://xohus.lol/). Desktop builds on Sincord and Vencord and includes contributions from Equicord, Endcord, and the wider add-on community. BetterDiscord inspired parts of the add-on interface. [Desktop credits](desktop/client/CREDITS.md) · [Desktop GPL license](desktop/client/LICENSE) · [CloudCord license](https://github.com/cloudcord-mod/release-hub/blob/main/license)
