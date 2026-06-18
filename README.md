![GitHub Release](https://img.shields.io/github/v/release/98juju98/CCJM?include_prereleases&style=flat)
![GitHub All Releases](https://img.shields.io/github/downloads/98juju98/CCJM/total?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/98juju98/CCJM?style=flat)
![GitHub issues](https://img.shields.io/github/issues/98juju98/CCJM?style=flat)

# CCJM (plugin Revit)
<img width="1600" height="168" alt="ruban CCJM" src="https://github.com/user-attachments/assets/34c23e22-ba9b-4a08-9292-5809de9abe72" />

## Language

The CCJM plugin is available in three languages: 🇬🇧 English, 🇫🇷 French, and 🇪🇸 Spanish.

## Description

CCJM is a plugin for Autodesk Revit designed to enhance productivity by providing additional features such as managing shortcuts, hyperlinks, and your favorite commands. Export multiple sheets in 1 dwg, export several sheets according to a name codification. Generated the center of gravity. Triangulation from vertical points. Sum volumes, area, length ... Join elements in active view, Generated motion in revit, 4D phasage, copy filter, export/import schedules to excel, align views on several sheets, change the phases of the active view with a button.

## Installation with admin rights and without admin rights
1. **Download**: Obtain the `InstallCCJM2024.exe`, `InstallCCJM2025.exe`, `InstallCCJM2026.exe` file from the [Releases](https://github.com/98juju98/CCJM/releases) section of this repository.

2. **Install**: Click on: `InstallCCJM2024.exe` for revit 2024, `InstallCCJM2025.exe` for revit 2025, `InstallCCJM2026.exe` for revit 2026.

3. **Protection**: Select `Additional information` and `Execute`.     

![install1](https://github.com/user-attachments/assets/6b1bf1b8-7474-4d51-b7c1-7f8390524df1)

4. **Installation**: A window will open to start the installation. Press any key when the installation is complete.

<img width="735" height="293" alt="instal" src="https://github.com/user-attachments/assets/4412f900-daa1-427c-8bfc-bd08ebb16881" />

Note: If you have installed a previous version and there is an error during the installation, delete the CCJM.addin file and CCJM folder in: 
`C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\202x\`

5. **Revit**: Open Revit, then click on `Always Load` when the popup appears.

<img width="339" height="150" alt="revit" src="https://github.com/user-attachments/assets/8562b1f0-212d-44ca-a560-db9c019d12eb" />

6. **CCJM**: Find `CCJM` in the Ribbon.

<img width="1228" height="124" alt="ajout CCJM Ruban V3" src="https://github.com/user-attachments/assets/a07c185d-c940-45d0-bc3d-c8fad9d38c0d" />
  
## Uninstallation

To uninstall CCJM:

- Delete the `CCJM` folder and the `CCJM.addin` file from the directory:
  
  ```
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2024
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2025
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2026
  ```

## Features

- **Show DockablePane**: Displays the DockablePane to manage your shortcuts, hyperlinks, panels, and favorite commands.

- **Export**: Export "Fusion" a set of sheets into a single DWG file, pdf. Export "Multiple" a set of sheets according to a name codification

- **Sum**: Adds the values of elements with the same parameter name (Volume, surface, length...).

- **Join Elements**: Join elements (Roof, walls, colums, floor ...) in active view.

- **Align Sheets**: Align views on several sheets.

- **Your Saved Path**: Retrieve all your saved paths and hyperlinks from the DockablePane.

- **Copy filter**: Copy filter from a view to another view with override graphics.  

- **Excel**: Export/Import schedule to excel.

- **Recollation Diaphragm Wall**: Creates a Delaunay triangulation on a vertical element from a DWG file containing points (one DWG per side of the triangulation).

- **Center Of Gravity**: Places a family at the center of gravity of one or more selected elements.

- **Phase**: Change phase faster with button `Phase+1, Phase-1` and retrieve information on the project phases `Info Phases`.

- **4D**: Create a 4D phasage.

- **Settings 4D**: Set the dates of the 4D phasing

- **Information on this Document**: Exports various information about the current Revit document to Excel.

- **Information CCJM**: Check for information, video, github, linkedin, remove CCJM global paremeter.

- **Move**: Moves the panel and saves your most used buttons from the DockablePane. You can also customize the icons of this panel (16x16 pixel images).

## Video

You can find some video to explain features on this channel: https://www.youtube.com/@pluginCCJM

## Compatibility

This plugin is compatible with Autodesk Revit 2025, Autodesk Revit 2026, Autodesk Revit 2027.

## Support and Contact

For any questions or assistance, please open an issue on the GitHub repository or contact the author directly on LinkedIn: https://www.linkedin.com/in/julien-moreaux/

## License

The CCJM plugin is provided free of charge, but remains proprietary.
See [LICENSE](https://github.com/98juju98/CCJM/blob/main/LICENSE) for the full End-User License Agreement (EULA).
This plugin is developed on a personal basis outside of my professional activity.
He is not affiliated with my employer.
