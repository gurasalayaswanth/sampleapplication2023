ANSYS Products 18.1 Win64 setup media includes embedded Electromagnetics 2017.1 module that can be found after setup in folder <ANSYS 181 program folder>\Electronics (by default C:\Program Files\ANSYS Inc\v181\Electronics )

But using of that embedded Electronics is locked (first there are no links for embedded Electronics executables in ANSYS, second there are no features in ANSYS license to run embedded Electronics executables because they are licensed by vendor ANSOFTD, not ANSYSLMD

To unlock embedded Electronics in ANSYS Product 18.1 with functionality almost equal of standalone version of ANSYS Electromagnetics Suite 18.1 do the next:


1. Make a backup copy of files:
 
<ANSYS 181 program folder>\Electronics\Win64\config\admin.xml (by default C:\Program Files\ANSYS Inc\v181\Electronics\Win64\config\admin.xml)

 and 

<ANSYS 181 program folder>\Electronics\Win64\syslib\Materials.amat (by default C:\Program Files\ANSYS Inc\v181\Electronics\Win64\syslib\Materials.amat )

2. Replace original folder <ANSYS 181 program folder> (by default C:\Program Files\ANSYS Inc\v181) with cracked one

3. To create shortcuts for Electronics applications run <ANSYS 181 program folder>\Electronics\Win64\config\ConfigureThisMachine.exe  (by default C:\Program Files\ANSYS Inc\v181\Electronics\Win64\config\ConfigureThisMachine.exe )

ATTENTION!
Some files in this unlock release are written for default setup of ANSYS 18.1 in folder C:\Program Files\ANSYS Inc\v181
If you install ANSYS 18.1 not in the default folder:

4. Open in text editor file ..\v181\commonfiles\registry\winx64\AnsoftPreferences.XML and replace every string with

	C:\Program Files\ANSYS Inc\v181\Electronics\Win64

for real path to corresponding folder on your computer

5. Run as Administrator "SolidSQUADLoaderEnabler.reg" and confirm to add info into Windows Registry

6. REBOOT!


7. Enjoy!

Note:

If after Electronics applications start you have warning that license file can not be found create environment variable 

LM_LICENSE_FILE=full path to <ANSYS 181 program folder>\Electronics\admin\Win64\ansoftd_SSQ.lic

 (by default C:\Program Files\ANSYS Inc\v181\Electronics\admin\Win64ansoftd_SSQ.lic


Cracked by TeAM SolidSQUAD-SSQ
