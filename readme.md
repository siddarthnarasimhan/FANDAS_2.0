# FANDAS 2.0

## License:
Please Cite FANDAS 2.0 if you have used it in your research:  
https://doi.org/10.1007/978-1-4939-7386-6_6  
The user is free to modify FANDAS in any way. However, we recommend that the modifications are 
reported to us, so as to make it available to the wider community.  
  
## Introduction to FANDAS 2.0

Fast Analysis of multidimensional NMR DAta Sets (FANDAS) is an analysis tool
 built on Python to predict peaks in multidimensional NMR experiments on proteins.
 FANDAS accepts a variety of inputs, with the protein sequence being the only minimum
 required input. The output generated by FANDAS can be opened using the NMR visualization 
software: SPARKY. Description of all the features that FANDAS offers is described in our 
publication described above.

## System Requirements

1. Linux/ Mac/ Windows operating system  
2. git (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)  
3. Python 2.7 or higher (https://www.python.org/downloads/)  
4. pip python package manager (https://pypi.python.org/pypi/pip)  
5. numpy package (tested version 1.11.2) (https://www.scipy.org/scipylib/download.html)  

## Installing Required Packages and FANDAS 2.0

### For Linux:  
Ensure that you have installed Python (Link is given above)  
  
Open the terminal on BASH environment and execute the following:
  
Install python2.7, pip, python-dev and git:  
`$ sudo apt-get install python2.7 python-pip python-dev git`  
  
Install numpy:  
`$ sudo pip install numpy`  
  
Clone FANDAS 2.0:  
`$ git clone http://github.com/siddarthnarasimhan/FANDAS_2.0`  
  
Test if all requirements are met by running the help feature:  
`$ cd FANDAS_2.0`    
`$ python fandas.py -h`  
If you see the usage message, and no errors then, FANDAS is ready to use!  
  
### For Mac:  
To install packages easily, we recommend the user to install Homebrew: http://brew.sh/  
  
Open your favorite terminal emulator on BASH environment and execute the following:  
  
Install python:  
`$ brew install python`  
  
Install pip:  
`$ sudo easy_install pip`  
  
Install numpy:  
`$ pip install numpy`  
  
Install git:  
`$ brew install git`  
  

Clone FANDAS 2.0:  
`$ git clone http://github.com/siddarthnarasimhan/FANDAS_2.0`  
  
Test if all requirements are met by running the help feature:  
`$ cd FANDAS_2.0`    
`$ python fandas.py -h`  
If you see the usage message, and no errors then, FANDAS is ready to use!  
  
### For Windows:
Tip: If you are using Windows 10, we recommend the user to try the BASH on Ubuntu on
 Windows feature that is offered with the Millenium update: https://msdn.microsoft.com/en-us/commandline/wsl/about 
that Windows 10 offers. Then on, follow the instructions for Linux mentioned above.  
  
Ensure Python 2.7, pip and numpy by following the links in the above System Requirements section.  
  
Install git on Windows from https://git-scm.com/download/win  
During installation, when prompted chose "Use Git from Git Bash only", which would install Git BASH which can be used to run FANDAS  
  
Open Git BASH and execute the following:  
  
Clone FANDAS 2.0:  
`$ git clone http://github.com/siddarthnarasimhan/FANDAS_2.0`  
  
Test if all requirements are met by running the help feature:  
`$ cd FANDAS_2.0`    
`$ python fandas.py -h`  
If you see the usage message, and no errors then, FANDAS is ready to use!  

Notes: distance_calculator.py
This script is used to calculate distances between homonuclear pairs of atoms from a PDB file.  

The script currently does not support mmCIF format of PDB. Please convert the files accordingly.
