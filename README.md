# Dead by Daylight FModel Mappings
This repository provides **mapping files (.usmap)** for use with [FModel](https://fmodel.app/), making setup faster and easier.

> [!NOTE]
> If you see any mapping missing in this repository and you know how to generate one, please make pull request providing generated mapping and update index.json following **exact** scheme as all the previous ones.

---

## Usage
To use these mappings in **FModel**, configure the [Mapping Endpoint](https://github.com/4sval/FModel/wiki/Settings-Explanation#endpoint-configuration) in your settings as follows:
- **Endpoint:**  https://masusder.github.io/FModel-DbdMappings/index.json
- **Expression:** `$['<version>']['url', 'fileName']`

Replace `<version>` in expression with the exact game version displayed on the splash screen when you launch the game, for example `9.2.0`. If you're on [Public Test Build](https://deadbydaylight.wiki.gg/wiki/Public_Test_Build) then `_ptb` suffix has to be added to the version, for example `9.2.0_ptb`.

You can use this expression `$['latest']['url', 'fileName']` instead if you want to always use latest available version there is, keep in mind PTB one will always be treated as latest if available.

Endpoint configuration can be found in FModel settings, open them using this button:

<img width="765" height="35" alt="image" src="https://github.com/user-attachments/assets/12cc25c2-ddf7-4c50-bf10-d68219a1964f" />

Properly configured endpoint should look like below:

<img width="968" height="678" alt="image" src="https://github.com/user-attachments/assets/67d6f686-e3c7-4708-a97d-5faaf11038a4" />
