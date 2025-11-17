# Awesome IFC Tools
A curated list of compiled command line tools for IFC manipulation, conversion, geometry extraction, validation, and automation.  
Only standalone CLI executables are included. No libraries and no GUI only tools.

## Conversion
[IfcConvert](https://github.com/IfcOpenShell/IfcOpenShell) - converts IFC to OBJ, DAE, GLB, SVG and performs triangulation  
[Ifc2Gltf](https://github.com/kebakcz/IfcGltf) - converts IFC to glTF or GLB using a Rust based pipeline  
[FreeCAD headless](https://github.com/FreeCAD/FreeCAD) - imports and exports IFC using the `freecadcmd` executable

## Geometry
[IfcConvert](https://github.com/IfcOpenShell/IfcOpenShell) - extracts triangulated geometry and optimized meshes  
[IfcGeomServer](https://github.com/tomvandig/ifcgeomserver) - headless geometry server with CLI entry for mesh generation

## Validation and QA
[IfcCheck](https://github.com/lutraconsulting/ifccheck) - fast C++ IFC rule validator for QA checking

## Diff and Change Tracking
[IfcDiff](https://github.com/IfcOpenShell/IfcOpenShell/tree/master/ifcdiff) - compares two IFC files and reports changes

## Patching and Editing
[IfcPatch](https://github.com/IfcOpenShell/IfcOpenShell/tree/master/src/ifcpatch) - applies batch edits and targeted corrections to IFC models

## Servers and Automation
[IfcGeomServer](https://github.com/tomvandig/ifcgeomserver) - lightweight headless geometry processing daemon  
[xBIM tools](https://github.com/xBimTeam) - compiled dotnet executables for property extraction and batch workflows

## Misc
[IfcPlusPlus tools](https://github.com/ifcquery/ifcplusplus) - C++ IFC parser with compiled example utilities for testing

## Contributing
See CONTRIBUTING.md

## License
MIT
