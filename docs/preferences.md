# Preferences

You can customize the addon behavior in **Edit > Preferences > Add-ons > B2RUVL**.

## General
*   **Tab Name**: Allows you to rename the category where the panel appears in the Sidebar (N-Panel). Default is `B2RUVL`.

## Headus UVLayout Settings
*   **Use UVLayout**: Enables the UVLayout section in the panel.
*   **Executable Path**: Full path to the `headus` executable.
*   **Export Options**:
    *   **Surface Type**: `SUBD` or `Poly`.
    *   **Cut and Drop by sharp edges**: Uses Blender's sharp edges to define cuts in UVLayout.

## RizomUV Settings
*   **Use RizomUV**: Enables the RizomUV section in the panel.
*   **Executable Path**: Full path to the `rizomuv.exe`.
*   **Scripts Path**: Path to the Lua scripts used for automation. Default is the `scripts` folder inside the addon directory.
*   **Connection**:
    *   **Fixed TCP Port**: Define a specific port for communication. Set to `0` for automatic assignment.
*   **Sync Active UV Set**: When enabled, the addon automatically ensures the correct UV set is active in RizomUV.
