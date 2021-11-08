# SPC_ValidationTool

SPC_ValidationTool is designed for annotation of images of plankton and validation of 
automated classifications. The app is designed for identification of taxonomic 
groups or species specific to a project, but specific groups/species can be modified. 
For the app manual refer to the repo Wiki. 


## SPC_ValidationTool Executable
Size on disk after installation: 52.8 MB

### 1. Prerequisites for Deployment 

Verify that version 9.9 (R2020b) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
```
    >>mcrinstaller
```   
at the MATLAB prompt.
_NOTE: You will need administrator rights to run the MATLAB Runtime installer._

Alternatively, download and install the Windows version of the MATLAB Runtime for R2020b 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

### 2. Files to Deploy and Package

Files to Package for Standalone 
================================
-SPC_ValidationTool.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



### 3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.




