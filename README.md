# 2018 Cell Modeling Workshop installation instructions

## CellBlender 1.2 Bundle (Day 1)

The latest CellBlender bundle consists of Blender 2.79, CellBlender 1.2, the latest version of MCellR (using libNFsim), Python 3.5.2 (with the following additional libraries: numpy, scipy, matplotlib, libxml, python-libsbml, etc), and GAMer. If you run into any problems with installing or running CellBlender, please contact us at mcell-devel@salk.edu.

### Linux installation instructions

Download the Linux bundle here: https://goo.gl/z6tRWP

After downloading the bundle, you can extract it by typing this at the command line:

    tar xf Blender-2.79-CellBlender.Linux.bz2

This will create a folder named "Blender-2.79-CellBlender". Change into the directory and start Blender like this:

    cd Blender-2.79-CellBlender
    ./blender

### OSX installation instructions

Download the OSX bundle here: https://goo.gl/Nvnv3U

After downloading the bundle, you can extract it by typing this at the command line:

    tar xf Blender-2.79-CellBlender.MacOSX_HS.20180226.tar.gz

This will create a folder named "Blender-2.79-CellBlender". For the software to work correctly you must move this whole folder into the main "/Applications" folder (note the leading slash).  The embedded python framework in the bundle expects to find itself under:
 
    /Applications/Blender-2.79-CellBlender/

so do not rename it. Also you cannot run the Blender applications by double clicking on the Blender icon. We have provided a command line shell script to handle starting Blender. From a terminal window you can fire up Blender by typing:

    /Applications/Blender-2.79-CellBlender/my_blender

From the Blender user preferences menu you will need to activate the CellBlender addon and save your preferences in the usual way.

### Windows Installation Instructions

We recommend that you use OSX or Linux for the workshop, since we don’t currently have a new CellBlender bundle for Windows. If you only have a Windows laptop, you can use the following Xubuntu VirtualBox image we have created: https://goo.gl/3qqMd8

Verify CellBlender is working properly

To verify that CellBlender is working properly, click Examples and select the Lipid Raft model from the list.



The hit Ctrl-s and save your file. The name of the blend doesn’t matter.



Hit Run Simulation and Export & Run. After a minute, you should see a green arrow indicating that it has run successfully. Note: You will also see a warning about reaction probabilities. This is expected behavior.



## RuleBender and BioNetGen (Day 2)

You can get RuleBender and BioNetGen for any major platform here: http://bionetgen.org 

## CellOrganizer (Day 3)

For information about the latest stable release, please visit 
http://www.cellorganizer.org

For detailed instructions about using CellOrganizer on this workshop, please visit
http://www.cellorganizer.org/mmbios/2018/ 
