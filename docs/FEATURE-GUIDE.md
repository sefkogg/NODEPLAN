# NODEPLAN feature guide

## NetPlan — red workspace

Use NetPlan to sketch physical layouts. The **2D editor** is the top-down workspace for placing rooms, furniture, and equipment. **3D view** gives a spatial perspective of the plan. The **equipment controls** add supported objects; **selection/inspector controls** modify available properties. **Cable tools** represent planned links between objects.

**Typical workflow:** create a room → place desks and network equipment → connect devices → review the design in 2D/3D.

## CableTrace — blue workspace

CableTrace is the documentation side of the app. The **connection register** displays cable records; each record can include a name or cable ID, source and destination devices, ports, cable type, status, and notes. **Search** helps find records, **manual entry** adds documentation, **Refresh** syncs available planner connections, **route tracing** follows a path through documented links, and **CSV export** downloads a spreadsheet-compatible file.

**Typical workflow:** add devices and cables in NetPlan → open CableTrace → refresh → fill in ports and cable IDs → trace a documented route → export CSV.

## Help & Diagnostics — green workspace

**Run Diagnostics** checks basic browser/application capabilities. **Quick fixes** explains common issues. **Report an Issue** creates a text report that can be copied or downloaded. **About** describes the workspaces. **License & Credits** provides attribution and licensing information.

**Important:** issue reports are not sent automatically; you must share the downloaded/copied report yourself.

## Desktop and phone

NODEPLAN uses one responsive application, not separate PC and phone editions. The phone layout rearranges navigation and controls to fit a smaller screen. Project data stored in one browser remains on that browser unless exported and transferred; the app does not offer cloud synchronization.

## Key terms

- **Endpoint:** a device or port where a cable starts or ends.
- **Patch panel:** a termination and organization point for structured cabling.
- **Switch port:** the physical Ethernet interface used by a connected device.
- **Cable register:** a list of physical connections and their identifying information.
- **Route trace:** a lookup through entered connections, not a live test or discovery scan.
