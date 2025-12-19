# Features & Usage

B2RUVL exposes its functionality through a panel in the 3D Viewport.

## RizomUV Workflow

### Connection Management
*   **Start RizomUV**: Launches the RizomUV application.
*   **Close RizomUV**: Closes the running RizomUV instance.

### Data Transfer
*   **Send UV**: Exports the selected object(s) to RizomUV.
*   **Get UV**: Imports the UVs back from RizomUV to Blender.
    *   *Note*: This updates the existing object's UVs.

### Remote Operations
These operations allow you to trigger actions in RizomUV directly from Blender:
*   **Unfold**: Performs an Unfold operation.
*   **Optimize**: Optimizes the UV map.
*   **Pack**: Packs the UV islands.
*   **Cut**: Performs a cut operation on selected edges.
*   **Weld**: Welds selected edges.

### Selection Sync
Transfer Blender selection attributes to RizomUV:
*   **Select Seams**: Selects edges marked as Seams.
*   **Select Sharp**: Selects edges marked as Sharp.
*   **Select Crease**: Selects edges with Crease weight.
*   **Select Current**: Syncs the current selection from Blender to RizomUV.

### Utilities
*   **Sync UV Set**: Ensures the active UV naming and index matches between Blender and RizomUV.

## Headus UVLayout Workflow

*   **Send UV**: Sends the selected mesh to Headus UVLayout.
    *   *Surface Type Option*: Choose between Poly or SUBD depending on your mesh type.
    *   *Sharp Edges*: Check "Cut and Drop by sharp edges" to automatically cut along sharp edges.
