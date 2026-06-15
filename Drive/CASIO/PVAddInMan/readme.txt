Add-In-Manager for the Casio Pocketviewer

PVAddInMan V4.35
Thomas Gaertner - thomas.gaertner@t-online.de
----------------------------------------------------------

PVAddInMan based on Johannes Steingraeber's PackMenu. 
Thanks to him for his ideas and sources.
All development steps are well supported by Johannes


1. Usage

You can install the PVAddInMan as a normal add-in on your PV  
using the PV Applications Manager. To use the full functionality 
of PVAddInMan and the entire program memory, PVAddInMan should be
installed in an add-in collection as first add-in. For details,
please see the instruction of Johannes' PackMenu.
PVAIM4.35 seizes 3 blocks (each 16 kB) in a packed file 
using AddInPack.exe.


2. Functionality

After starting the PVAddInMan as single or packed application on the PV, 
a list of all useable add-ins is shown. It includes all the unpacked (single)
and packed add-ins.
In the bottom line you can see the battery status, refreshed by any touch or
action wheel using.
In the headline, the usage of each of the 16 add-in spaces is shown.


2.1 Defragmentation
By touching the headline, the program memory will be defragmented.


2.2 Run an Add-In
Using the action wheel or the touchscreen, you can chose an add-in. 
By pressing the action wheel or touching the program name, the add-in will be
started.


2.3 Show the Add-In information
By touching the icon at the add-in name, all the specific dates about the add-in
will be shown.
Using the arrow pads or the action wheel, you can scroll from add-in to add-in.
On the top, the usage of the 16kB memory segments and the position of the
current add-in is shown.
Additional, you can start an add-in from here too.

2.3 Delete Add-Ins
Regular (single) add-ins or package heads, you can delete this by touching 
the del-button.
You cannot delete pre-installed programs like pocketsheet.


3. Management of archived Files

3.1 Archive of Files
PVAddInManager is able to manage an archive of files. You have to create this
in the following way :

-Create an archive on the PC using the freeware LHA (see the conditions of
 usage), path details should be used
-An archive can contain program files (add-ins), data files (*.adt) and text
 files. PVAIM can manage the program and data files, to read the text files
 you should use Johannes' Textviewer.
-If you use the powerarchiver, you must not use the compression method 6, use
 method 5. 
-Prepare the archive for using on the Pocketviewer by a treatment with Johannes'
 adt.exe or adtgui.exe (http://mcpvc.gmxhome.de)

     e.g.: adt archiv.lzh (creates archiv.lzh.adt)

-Transfer of the file (e.g. archiv.lzh.adt) in the data memory of the
 Pocketviewer (e.g. using PV Application Manager)

-As alternate you should use Johannes' bootstrap patch. In this case, you 
 do not need to convert the archiv file in an adt file.

3.2 Reading of the Archiv
By touching the plus sign in the right corner in the top on the start screen, 
a menu will be opened where you can select an archive file, a subdirectory,
and, finally, an file.


3.3 Details and Installation of an  Add-In from the Archive
By touching the file name, the details of the program or data file will be shown.
Using the arrow buttons or the action wheel, you can scroll through the list.
You can start the installation of the add-in or the data file from the archive 
into the program or data memory, respectively, by touching the Inst button or 
pressing the action wheel.
Is enough joined memory space or an empty data file slot and enough data memory,
respectively,available, the add-in or the data file will be installed. 
If not, you will get an error message.


4. The author this software will not take
responsibility for any damage that may result from the use of this
software.
This program is tested in the simulator, on a PV-450X, a PV-S450,
and a PV-S660. 
But I cannot give any warranty that the program is runnig on 
each PV system.
Before you install the program, you should do the usual precautions (new batteries, 
backup, ...)


5. Development

To improve this program, please, let me know all your comments, problems, and recommendations.

thomas.gaertner@t-online.de

19.08.2002