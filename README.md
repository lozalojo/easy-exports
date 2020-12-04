# Easy Exports
NEW! Now you can re-import your backup into a Compendium to selectively recover lost Actors, Journals, etc.

* **Author**: Spetzel#0103
* **Version**: 0.4.2
* **Foundry VTT Compatibility**: 0.6.5-0.7.7
* **System Compatibility (If applicable)**: N/A
* **Translation Support**: en, es


## Description
Easy Exports speeds up exports for backups of your [Foundry VTT](https://foundryvtt.com/) world. Instead of right-clicking every Journal, Scene, Actor, etc. simply right-click the section in the Sidebar and pick the Easy Export option from the pop-up window (next to the Close button). Works for Macros too!

## Install

1. Go to the "Add-on Modules" tab in Foundry Setup
2. Click "Install Module" and search for Easy Exports OR paste this link in the Manifest URL field: https://github.com/spetzel2020/easy-exports/releases/download/v0.4.2/module.json`
3. Open your world and go to Settings>Manage Modules and enable Easy Exports

## Using Easy Exports
### Exporting
1. Start your world
2. Right-click on the tab in the Sidebar (Scenes, Actors, Items, Journals, Rollable Tables, or Playlists) to open the pop-out (for Macros, just click the file icon in the Macro bar)
3. Click on Easy Export in the title bar of the pop-out (next to the Close option); choose Export
4. The contents of the window will be exported in one concatenated JSON file to a backup location you pick on your local machine.
5. To recover individual entities, edit the relevant JSON into a separate file for import

### Importing
1. Right-click any Sidebar tab
2. Click on Easy Export and choose Import
3. Select the previously exported file and click Import
4. If the file is recognized, it will be imported into a custom Compendium - a dialog will show when the Compendium is ready to view (may take a few seconds or several minutes depending on size and bandwidth)
5. You can then import from the Compendium in the normal way to recover your entities
6. Don't forget to delete the Compendium when done!
## Contributions
*Coming Soon!*

## License
**Easy Exports for Foundry VTT** is licensed under the [GNU General Public License v3.0](https://github.com/spetzel2020/easy-exports/blob/master/LICENSE)

This work is licensed under Foundry Virtual Tabletop [EULA - Limited License Agreement for module development v 0.1.6](http://foundryvtt.com/pages/license.html).
