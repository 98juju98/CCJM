![GitHub Release](https://img.shields.io/github/v/release/98juju98/CCJM?include_prereleases&style=flat)
![GitHub All Releases](https://img.shields.io/github/downloads/98juju98/CCJM/total?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/98juju98/CCJM?style=flat)
![GitHub issues](https://img.shields.io/github/issues/98juju98/CCJM?style=flat)

# CCJM (plugin Revit)
![CCJM ruban](https://github.com/user-attachments/assets/f2244591-a7f6-4878-9c5e-3871cb36a49d)

## Description

CCJM is a plugin for Autodesk Revit designed to enhance productivity by providing additional features such as managing shortcuts, hyperlinks, and your favorite commands. Export multiple sheets in 1 dwg. Generated the center of gravity. Traingulation from vertical points. Sum volumes, area, length ...

## Installation
1. **Download**: Obtain the `CCJM.zip` file from the [Releases](https://github.com/98juju98/CCJM/releases) section of this repository.

2. **Unblock**: After downloading, right-click on `CCJM.zip`, select `Properties`, and check `Unblock` if available.

   ![Unblock](https://github.com/user-attachments/assets/cc84592a-ba80-4226-8712-c710b2fb59de)

3. **Extract**: Unzip the contents of `CCJM.zip`.

4. **Install**: Copy the `2023` `2024` `2025` folder to the following directory:
  ```
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins`
  ```

> *Note: The `AppData` folder is hidden by default. To reveal it, open File Explorer, go to the `View` tab, and check `Hidden items`.*

5. **Prerequisites**: Ensure that the .NET Framework 4.8 is installed on your system. It is included by default in Windows 11 and Windows 10 version 21H2 and later. If not present, download it from the official Microsoft website: [https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48).
  
## Uninstallation

To uninstall CCJM:

- Delete the `CCJM` folder and the `CCJM.addin` file from the directory:
  
  ```
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2023`
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2024`
  C:\Users\[Your_Name]\AppData\Roaming\Autodesk\Revit\Addins\2025`
  ```

## Features

- **Show DockablePane**: Displays the DockablePane to manage your shortcuts, hyperlinks, and favorite commands.

- **Multiple Sheets To One DWG**: Exports a set of sheets into a single DWG file without title block.

- **Center Of Gravity**: Places a family at the center of gravity of one or more selected elements.

- **Your Saved Path**: Retrieve all your saved paths and hyperlinks from the DockablePane.

- **Sum**: Adds the values of elements with the same parameter name (Volume, surface, length...).

- **Recollation Diaphragm Wall**: Creates a Delaunay triangulation on a vertical element from a DWG file containing points (one DWG per side of the triangulation).

- **Information on this Document**: Exports various information about the current Revit document to Excel or TXT format.

- **Information CCJM**: Check for the latest version of the plugin.

- **Move**: Moves the panel and saves your most used buttons from the DockablePane. You can also customize the icons of this panel (16x16 pixel images).


## Customizing Your Panel

- **Customize your icons**:

![Button1](https://github.com/user-attachments/assets/2976d138-f73f-4ee7-97fb-c28294647224)

- **Move your panel**:

![Move Panel](https://github.com/user-attachments/assets/2f5e1042-0d3c-494e-bbef-959431285b0e)

- **Edit the actions of your buttons with the DockablePane**:

![Transaction Panel](https://github.com/user-attachments/assets/9bf6384b-02e2-413f-afe0-ed319363753f)

## Compatibility

This plugin is compatible with Autodesk Revit 2023, Autodesk Revit 2024, Autodesk Revit 2025.

## Support and Contact

For any questions or assistance, please open an issue on the GitHub repository or contact the author directly.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/98juju98/CCJM/blob/main/LICENSE) file for details.


