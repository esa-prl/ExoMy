# CAD Design Guidelines

ExoMy was designed using SolidWorks 2018. No additional toolboxes were used.

## Folder Structure
Assemblies and 3D printed parts are to be stored in the main folder.

```
- Mechanical Design
Assemblies and parts go here.
-- Cables
-- Drawings
-- Fasteners
-- Purchased Parts
-- Templates
```

## Part Naming
The file naming convention is as follows:

**Assemblies**
Axx_Name_with_underscore.SLDASM

**3D-Printed Parts**
Pxx_Name_with_underscores.SLDPRT

Replace xx with a new two-digit part-/assemby-number.

**Always** use a new number for a new part/assembly. Don't try to fill in the gaps that occur if old parts are deleted.

## Configurations
Configurations are used to generate variations of parts (rear/side bogie, left/right wheelbracket, various hats.). They are also used to create drawings and bill of materials. All AI_* drawings are linked to a specific configuration of the main assembly or a subassembly. This allows the generation of a bill of materials, which can then be exported into Excel.

The naming should be kept consist to simply the referencing in the wiki in case of new releases.

## Exporting and Releases
Refer to the [wikipage](https://github.com/esa-prl/ExoMy/wiki/Release-Procedure#solidworks).