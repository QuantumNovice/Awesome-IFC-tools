# Awesome IFC Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source tools, libraries, viewers, validators, and automation utilities for Industry Foundation Classes (IFC) workflows.

IFC is the open data model used for BIM exchange across architecture, engineering, construction, and facility management. This list focuses on projects with public source code that can read, write, inspect, validate, convert, visualize, or automate IFC data.

## Contents

- [Authoring and Editing](#authoring-and-editing)
- [Libraries and SDKs](#libraries-and-sdks)
- [Conversion and Geometry](#conversion-and-geometry)
- [Viewing and Web Apps](#viewing-and-web-apps)
- [Validation and QA](#validation-and-qa)
- [Collaboration and Servers](#collaboration-and-servers)
- [Data, BCF, and IDS Utilities](#data-bcf-and-ids-utilities)
- [Contributing](#contributing)

## Authoring and Editing

- [Bonsai](https://bonsaibim.org/) - Native IFC authoring platform built as a Blender add-on. It supports IFC modeling, drawing generation, scheduling, costing, auditing, and BIM data editing.
- [FreeCAD](https://github.com/FreeCAD/FreeCAD) - Open-source parametric CAD and BIM application with IFC import, export, Python automation, and architecture-oriented workflows.
- [IfcPatch](https://docs.ifcopenshell.org/ifcpatch.html) - IfcOpenShell utility for applying batch fixes and model transformations, such as offsets, schema migrations, owner history cleanup, and data edits.
- [IfcCSV](https://docs.ifcopenshell.org/ifccsv.html) - Exports IFC data to CSV, ODS, XLSX, and Pandas dataframes, then imports edited spreadsheet data back into IFC models.
- [COMPAS IFC](https://pypi.org/project/compas-ifc/) - High-level Python interface for inspecting, editing, extracting geometry from, and creating IFC data inside COMPAS workflows.

## Libraries and SDKs

- [IfcOpenShell](https://github.com/IfcOpenShell/IfcOpenShell) - Open-source IFC library and geometry engine with C++ and Python APIs, schema support, geometry processing, and many command-line tools.
- [xBIM Essentials](https://github.com/xBimTeam/XbimEssentials) - .NET toolkit for reading, writing, validating, and querying IFC and COBie data.
- [web-ifc](https://github.com/ThatOpen/engine_web-ifc) - JavaScript and WebAssembly IFC parser for reading and writing IFC files at native speeds in browsers and Node.js.
- [That Open Components](https://github.com/ThatOpen/engine_components) - TypeScript components for building browser-based BIM applications with Three.js, model interaction, measurements, sections, and IFC-oriented workflows.
- [IfcPlusPlus](https://github.com/ifcquery/ifcplusplus) - C++ IFC class model, STEP reader and writer, and sample Qt/OpenSceneGraph viewer.
- [XbimGeometry](https://github.com/xBimTeam/XbimGeometry) - Geometry engine for xBIM, used to compute and process IFC model geometry in .NET applications.

## Conversion and Geometry

- [IfcConvert](https://docs.ifcopenshell.org/ifcconvert.html) - Command-line converter from IFC to formats such as OBJ, DAE, GLB, SVG, STEP, IGES, XML, HDF5, and JSON variants.
- [xeokit-convert](https://github.com/xeokit/xeokit-convert) - Node.js CLI and library for converting IFC, GLB, CityJSON, STL, LAS, and other AEC formats into xeokit's XKT format.
- [IfcCityJSON](https://docs.ifcopenshell.org/ifccityjson.html) - IfcOpenShell utility for CityJSON and IFC interoperability in geospatial and city-model workflows.
- [Ifc2CA](https://docs.ifcopenshell.org/ifc2ca.html) - Converts IFC structural analysis models to Code_Aster input files.
- [IFC-glTF](https://github.com/geoblocks/ifc-gltf) - Client-side TypeScript library that converts IFC files to glTF using web-ifc, Three.js, and the Three.js glTF exporter.
- [IFCConverter](https://github.com/CubiCasa/IFCConverter) - Command-line converter that uses IfcOpenShell libraries to export IFC geometry to OBJ and STL.

## Viewing and Web Apps

- [xeokit-bim-viewer](https://github.com/xeokit/xeokit-bim-viewer) - Browser-based 2D and 3D BIM viewer for IFC-derived models, BCF viewpoints, object trees, sections, and large model navigation.
- [BIMsurfer](https://github.com/opensourceBIM/BIMsurfer) - Open-source WebGL viewer for IFC models in the browser, maintained by the open source BIM collective.
- [XbimXplorer](https://github.com/xBimTeam/XbimWindowsUI) - Windows WPF IFC viewer and desktop UI components built on the xBIM Toolkit.
- [XbimWebUI](https://github.com/xBimTeam/XbimWebUI) - TypeScript and JavaScript web components for presenting BIM models with xBIM.
- [web-ifc-viewer](https://github.com/ThatOpen/web-ifc-viewer) - Deprecated but still useful reference implementation for IFC viewing tools built on web-ifc and Three.js.
- [IfcPlusPlus Viewer](https://github.com/ifcquery/ifcplusplus) - Example IFC viewer application included with IfcPlusPlus, built with Qt and OpenSceneGraph.

## Validation and QA

- [IfcTester](https://docs.ifcopenshell.org/ifctester.html) - IDS authoring and validation tool that can audit IFC models and export reports to console, HTML, JSON, ODS, or BCF.
- [IfcClash](https://docs.ifcopenshell.org/ifcclash.html) - CLI and library for clash detection across one or more IFC models using JSON clash-set definitions.
- [IfcDiff](https://docs.ifcopenshell.org/ifcdiff.html) - Compares IFC models and reports differences in geometry, properties, and relationships.
- [Xbim.IDS.Validator](https://github.com/xBimTeam/Xbim.IDS.Validator) - .NET library and console application for validating IFC and COBie models against IDS 1.0 specifications.
- [buildingSMART Validate](https://github.com/buildingSMART/validate) - IFC validation service stack for syntax checks, schema checks, Gherkin rules, and related validation workflows.
- [Model Checker](https://github.com/opensource-construction/model-checker) - Browser-based IFC and IDS validation application powered by Pyodide, IfcOpenShell, and IfcTester.

## Collaboration and Servers

- [BIMserver](https://github.com/opensourceBIM/BIMserver) - Open-source BIM server platform that stores IFC data as objects and supports checking, versioning, merging, querying, and model management.
- [BIMserver JavaScript API](https://github.com/opensourceBIM/BIMserver-JavaScript-API) - JavaScript client API for integrating web applications with BIMserver.
- [python-bimserver-client](https://github.com/aothms/python-bimserver-client) - Python client for automating BIMserver workflows and accessing IFC model data.

## Data, BCF, and IDS Utilities

- [BCF library](https://docs.ifcopenshell.org/bcf.html) - IfcOpenShell package for reading and writing BCF-XML and interacting with BCF API workflows.
- [bSDD client](https://docs.ifcopenshell.org/bsdd.html) - IfcOpenShell package for querying the buildingSMART Data Dictionary API.
- [bsdd-ids-validator](https://github.com/BIM-Tools/bsdd-ids-validator) - TypeScript library for validating ifcJSON data against bSDD and IDS-derived JSON schema rules.
- [IfcFM](https://docs.ifcopenshell.org/ifcfm.html) - Audits and converts IFC facility management data using COBie and FMH-EM workflows.
- [Ifc4D](https://docs.ifcopenshell.org/ifc4d.html) - Converts schedule and task data between IFC and project management formats.
- [Ifc5D](https://docs.ifcopenshell.org/ifc5d.html) - Quantity takeoff and cost-estimation utility for IFC-based 5D workflows.

## Contributing

Contributions are welcome. Please see [Contributing.md](Contributing.md).

## License

MIT
