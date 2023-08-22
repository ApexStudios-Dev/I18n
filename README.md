# ApexStudios - Localization
Public repo which holds all translation data for our projects.

Each folder in this Repository holds translation files (`.json`) for one of our mods.<br>
Each translation file holds translation entries a mod.

To add support for a new language create a translation file for the language you wish to add support for and provide translation values inside of it.<br>
[See here](https://minecraft.fandom.com/wiki/Language) for full list of languages Minecraft Natively supports.

---
Accepting pull requests is currently on hold, due to Multi-Loader development taking priority.<br>
You are however free to still make PRs, just be aware they will not be merged until Multi-Loader is ready for release.

[_See this PR for active Multi-Loader development._](https://github.com/ApexStudios-Dev/ApexCore/pull/11)

---
### `to_be_validated/` files

Translations under this directory need to be validated before any new PRs can be accepted.<br>
If you know any languages under this directory, feel free to validate them and open a PR for them.

For a translation to be validated a matching English translation must exist in `en_us.json` and must translate to the newly validated value.

---
Pull requests attempting to modify the **en_us** language file **WILL BE** rejected as it is protected & auto-generated.
This file is provided as an example of what other languages should attempt to translate to.

If you believe an English translation is incorrect, [join our Discord](https://discord.apexstudios.xyz/) and notify us via the `#issues` forum-channel.