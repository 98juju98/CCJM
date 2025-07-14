![GitHub Release](https://img.shields.io/github/v/release/98juju98/CCJM?include_prereleases&style=flat)
![GitHub All Releases](https://img.shields.io/github/downloads/98juju98/CCJM/total?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/98juju98/CCJM?style=flat)
![GitHub issues](https://img.shields.io/github/issues/98juju98/CCJM?style=flat)

# CCJM (plugin Revit)
<img width="1412" height="101" alt="CCJM ruban" src="https://github.com/user-attachments/assets/68bf9692-0603-470d-938b-549968e9986f" />

## Language

The CCJM plugin is available in three languages: 🇬🇧 English, 🇫🇷 French, and 🇪🇸 Spanish.

## Description

CCJM is a plugin for Autodesk Revit designed to enhance productivity by providing additional features such as managing shortcuts, hyperlinks, and your favorite commands. Export multiple sheets in 1 dwg. Generated the center of gravity. Traingulation from vertical points. Sum volumes, area, length ... Join elements in active view, Generated motion in revit, 4D phasage, copy filter, export/import schedules to excel.

## Installation with admin rights and without admin rights
1. **Download**: Obtain the `InstallCCJM.7z` file from the [Releases](https://github.com/98juju98/CCJM/releases) section of this repository.

2. **Extract**: After downloading, right-click on `InstallCCJM.7z`, select `Extract All...`, and select `Extract`.  

3. **Install**: Open folder `InstallCCJM` Click on: `InstallCCJM2024.exe` for revit 2024, `InstallCCJM2025.exe` for revit 2025, `InstallCCJM2026.exe` for revit 2026.

4. **Protection**: Select `Additional information` and `Execute`.     

![install1](https://github.com/user-attachments/assets/6b1bf1b8-7474-4d51-b7c1-7f8390524df1)
  
## Uninstallation

To uninstall CCJM:

- Delete the `CCJM` folder and the `CCJM.addin` file from the directory:
  
  ```
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2024
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2025
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2026
  ```

## Features

- **Show DockablePane**: Displays the DockablePane to manage your shortcuts, hyperlinks, and favorite commands.

- **Multiple Sheets To One DWG**: Exports a set of sheets into a single DWG file without title block.

- **(Beta) Multiple Sheets To One DWG**: Exports a set of sheets into a single DWG file with title block.

- **Your Saved Path**: Retrieve all your saved paths and hyperlinks from the DockablePane.

- **Excel**: Export/Import schedule to excel.

- **Copy filter**: Copy filter from a view to another view with override graphics.

- **Sum**: Adds the values of elements with the same parameter name (Volume, surface, length...).

- **Join Elements**: Join elements (Roof, walls, colums, floor ...) in active view.

- **Recollation Diaphragm Wall**: Creates a Delaunay triangulation on a vertical element from a DWG file containing points (one DWG per side of the triangulation).

- **Center Of Gravity**: Places a family at the center of gravity of one or more selected elements.

- **Move Elements**: Generate movement in revit with one or more elements on model curve (option: generate pdf).

- **Phase**: Change phase faster with button `Phase+1, Phase-1` and scroll through the phases every second with button `Play`.

- **4D**: Create a 4D phasage.

- **Information on this Document**: Exports various information about the current Revit document to Excel.

- **Information CCJM**: Check for information, video, github, linkedin.

- **Move**: Moves the panel and saves your most used buttons from the DockablePane. You can also customize the icons of this panel (16x16 pixel images).

## Video

You can find some video to explain features on this channel: https://www.youtube.com/@pluginCCJM

## Compatibility

This plugin is compatible with Autodesk Revit 2024, Autodesk Revit 2025, Autodesk Revit 2026.

## Support and Contact

For any questions or assistance, please open an issue on the GitHub repository or contact the author directly.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/98juju98/CCJM/blob/main/LICENSE) file for details.
