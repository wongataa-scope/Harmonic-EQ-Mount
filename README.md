This is my design for a GoTo telescope mount using strainwave gears (harmonic drives).  As strainwave gear telescope mounts, such as the ZWO AM5, started to become more available I thought why not make my own.

My mount is made from CNC machined aluminium, 3D printed aluminium, and 3D printed plastic.

The RA and DEC axes have a reduction ration of 450:1. The strainwave gears are 100:1 and there is 4:1 belt drive between the stepper motors and the strainwave gears.  The stepper motors are NEMA 17 size.

The strainwave gears are hollow so cables can pass through them.  This means there are no wires dangling off the telescope and mount.

The RA and DEC axes have hall sensors for automatic homing.

This mount has motorised altitude and azimuth axes so the mount does not have to be touched when polar aligning.  Everything is controlled by the computer controlling the mount.  The M4 ends of the azimuth and altitude leadscrews need to have thread locker applied before screwing into the parts they fit in to.  I use Loctite 243.

I have my mount connected to a EQ5 tripod.  The tripod interface will need to be modified if you wish to use a different tripod.  The 4040 aluminium extrusions do not have to be the length they are in the CAD files.  They can be any length.

I would recommend the CNC aluminium parts are made from 6061-T6 or 6082-T6 aluminium.  These grades are readily available, easily machined, and strong.  The T6 denotes the temper level.  T6 is stronger than non-tempered aluminium.
I used PETG for the 3D printed plastic.  I used heat set thread inserts in the 3D printed plastic where screws are screwed into them.

The first sheet of the BOM is a list of every part used.  The second sheet contains the BOMs broken down for each sub assembly.

The ‘Complete_Assembly_Neutral’ folder has a STEP and Parasolid file of the entire mount.

The ‘Solidworks_Makers_Files’ folder has the source Solidworks part, assembly, and drawing files.  These files were created in the Solidworks Makers version so cannot be opened with the educational or commercial versions of Solidworks.

The ‘Part_Drawing_PDF’ folder contains every drawing in PDF format.

The ‘3D_Print_Aluminium’ folder contains the files sent for aluminium 3D printing for the parts that underwent machining after printing.  These parts were machined on a lathe to fit bearings.

This is very much a version 1 design.  I’m sure there are ways it could be improved.  It hasn’t had much testing yet, but it does work.  I use the OpenAstroTech control system but it could also be made to work with OnStep.
