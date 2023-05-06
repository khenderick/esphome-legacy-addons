# ESPHome legacy addons

## About

Even though the developers of ESPHome take care of not breaking any devices out there (and even 
publishing beta and dev versions to be able to catch bugs early on with the community's help),
it happens that some functionality breaks when installing a new version.

Awaiting a fix, users might want to install one of these addons to be able to "revert" to the old
version. As soon as a new version is published, the old version will be added here.

Given that the versions (e.g. 2023.1.2) have a major.minor.patch format, the plan is that the latest patch
will be used. There is no plan to support multiple patch versions within the same major/minor. If the need
for those would ever arise, it can be reconsidered.

## Rules

Do _not_ report bugs about ESPHome here, but only on
the [ESPHome issue tracker](https://github.com/esphome/issues) and _only for the latest version_. So first
update your device to the latest version, try to reproduce the issue, and if still persistent, consider
logging a bug on the previously mentioned location taking their bug reporting rules into account.

I repeat, the ESPHome versions in the addons on this repo are _not_ supported anymore, and are here just
as an archive to bridge the time between a bug appearing in a new version, and it being fixed in a
later version.

Using this repo to rant about bugs introduced in ESPHome will _not_ be tolerated. The team behind ESPHome
and the tons of volunteers try there best to get everything working as good as possible.

If you find an issue with this addon or have a good idea to enhance its functionality, feel free to
report here.

## How to install

Go to you Home Assistant's Add-on Store and add this as repository. Check for updates (and if needed, refresh),
and you should be able to install any of these versions.

[![Install this repository](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fkhenderick%2Fesphome-legacy-addons)

If nothing shows up after adding the repo, refresh the page.

## Credits

Thanks to the ESPHome team for making such an awesome product.
