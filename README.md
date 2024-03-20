# CDPR_4cables kinematics library
Repository of the code used for the calculation of the inverse and direct kinematics of the suspended 4-cable Cable-Driven Parallel Robot prototype used in the "Integrated Simulation and Control Environment for the Development and Safe Start-up of Cable Driven Parallel Robots" scientific article.

# Environment Requirements:
TwinCAT XAE Shell 4024.33 or higher

# Setup Procedure:
In order to use CDPR_4cables library you need to add a reference to the library in your project. Firstly, download "CDPR_4cables.library". Next, open a TwinCAT PLC project, and right-click on the "References" under the PLC-project and click on "Add library". Add library reference and next go to the "Miscellaneous" group, and select "CDPR_4cables_kinematics_library" and click OK.

# Test Procedure:
The "MAIN.xml" file contains a "MAIN" program that can be executed to test the results returned by the implemented kinematics. 
For a program developed in the TwinCAT automation environment. To add the test program, just right click on the PLC project in the POU folder and select "Import PLCopenXML".

# Source code:
"CDPR_4cables.tnzip" contains the source code of the project in TwinCAT 3.
To open the project, select "Open solution from Archive" in the programming environment.

# Contributions
Developers that contributes in this repository: J. Garrido, D. Silva-Muñiz, J. Rivera-Andrade. E. Riveiro.
