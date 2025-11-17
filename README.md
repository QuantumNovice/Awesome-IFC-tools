# Awesome IFC Tools
A curated list of compiled command line tools for IFC manipulation, validation, and conversion.  
Only standalone executables are included. No libraries, no API only packages, no GUI only tools.

## Tools

## IfcConvert
Compiled IFC to mesh and format converter  
Supports OBJ, DAE, GLB, SVG, various triangulation options  
Source: https://github.com/IfcOpenShell/IfcOpenShell  
Binary: distributed in releases  
CLI: `ifcconvert`

## IfcClash
Clash detection using compiled IFCOpenShell routines  
Source: https://github.com/IfcOpenShell/IfcOpenShell/tree/master/src/ifcclash  
Binary: included in releases  
CLI: `ifcclash`

## IfcPatch
Binary tool for patching and editing IFC files  
Useful for batch corrections  
Source: https://github.com/IfcOpenShell/IfcOpenShell/tree/master/src/ifcpatch  
Binary: included in releases  
CLI: `ifcpatch`

## IfcDiff
Compiled tool to detect changes between IFC revisions  
Source: https://github.com/IfcOpenShell/IfcOpenShell/tree/master/ifcdiff  
Binary: included in releases  
CLI: `ifcdiff`

## Ifc2Gltf
Standalone IFC to glTF converter  
Source: https://github.com/kebakcz/IfcGltf  
Binary: compiled Rust executable  
CLI: `ifc2gltf`

## IfcCheck
Fast checker for IFC rule violations  
Compiled C++ executable  
Source: https://github.com/lutraconsulting/ifccheck  
CLI: `ifccheck`

## IfcPlusPlus CLI utilities
C++ based IFC parser project with compiled example tools  
Source: https://github.com/ifcquery/ifcplusplus  
CLI: various sample binaries included in build output

## IfcGeomServer CLI
Simplified geometry processing server with CLI interface  
Source: https://github.com/tomvandig/ifcgeomserver  
Binary: distributed per platform  
CLI: `ifcgeomserver`

## xbim Essentials Command Tools
Some xBIM components ship compiled dotnet executables  
Source: https://github.com/xBimTeam  
Binary: check xbim.tools releases  
CLI: varies by tool

## FreeCAD ifc cli mode
FreeCAD supports headless IFC import and export  
Source: https://github.com/FreeCAD/FreeCAD  
CLI: `freecadcmd`

## Contributing
See CONTRIBUTING.md

## License
MIT
