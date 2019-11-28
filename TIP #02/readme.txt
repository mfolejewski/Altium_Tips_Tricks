Altium Designer Tips&Tricks - TIP #02 -> create your own folder structure for the source files.

Let imagine that you working on the complex PCB design in the AD environment, so your design can contain a large number of the single source files. Especially that design can consist of many schematic sheets, the settings files and the output files (see the first drawing).

Manage that project can be difficult. You may be a bit confused which files are as the source files and which files are the output files.

So my advice for you: just create your own folder and file structure for the AD projects and for the source files and use this as a your own standard.

Suggested folders purpose is as following:
/cfg -> config files (e.g. OutJob wizard, BOM and Draftsman templates), 
/doc -> documentation files (e.g. datasheets or drawings);
/lib -> local libraries (SchLib/PcbLib files, Pad Via libraries);
/out -> generated output files, such as the CAM files, BOMs, assembly drawings.;
/pcb -> PCB source files (PcbDoc files);
/prj -> system project files (e.g. PcbPrj, PcbPrjStructure files);
/sch -> schematic sheets (SchDoc/Harness files);
/tmp -> other temporary files;

Folder structure can be as a part of your global standard for the Altium Designer projects.
