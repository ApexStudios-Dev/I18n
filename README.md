# ApexStudios - Localization
Public repo which holds all translation data for our projects.

Each folder in this Repository holds translation files (_.json_) for one of our mods.<br>
Each translation file holds translation entries a mod.

To add support for a new language create a translation file for the language you wish to add support for and provide translation values inside of it.<br>
[See here](https://github.com/ApexStudios-Dev/Registrator/blob/1.16.5/src/main/java/xyz/apex/forge/utility/registrator/provider/RegistrateLangExtProvider.java#L34-L160) for full list of languages Minecraft Natively supports.

---

Pull requests attempting to modify the following language files **WILL BE** rejected as they are auto-generated
- **en_us**
- **en_ud**
- **en_gb**

If you belive the a translation value for these languages are incorrect, create a Pull request on the respective mod modifying the generator code (using _Registrator_).<br>
_The `.lang()` in most cases_
