# basics
How to start with Jupyter, Python (pip), libs, Github along with Anaconda (conda)

I personally recommend you to start with Python 3.5+ (no more support for 2.x versions)

1. Install Anaconda (ensure the environments are set properly after installation)
  
  a. Windows 64bit: https://repo.anaconda.com/archive/Anaconda3-2020.02-Windows-x86_64.exe
          
          Instructions on installation : https://docs.anaconda.com/anaconda/install/windows/
          
  b. Linux 64bit :  https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh
          
          Instructions on installation : https://docs.anaconda.com/anaconda/install/linux/
          
          Extended dependencies for Qt are required, execute commands as per your distro.
          
  c. MacOSX 64bit : https://repo.anaconda.com/archive/Anaconda3-2020.02-MacOSX-x86_64.pkg
          
          Instructions on installation : https://docs.anaconda.com/anaconda/install/mac-os/

2. To upgrade existing version (already installed)
  
  Run the following commands on your terminal or command-prompt
  
  conda update conda
  
  conda update anaconda=VersionNumber
          
          More details : https://docs.anaconda.com/anaconda/install/update-version/

3. Verification of installation
  
  Open the Anaconda Prompt or the terminal, choose any of the following methods to verify:

  a. Enter 'conda list'. If Anaconda is installed and working, this will display a list of installed packages and their  versions.
  
  b. Enter the command 'python'. This command runs the Python shell. If Anaconda is installed and working, the version information it displays when it starts up will include “Anaconda”. To exit the Python shell, enter the command quit().
  
  c. Open Anaconda Navigator with the command 'anaconda-navigator'. If Anaconda is installed properly, Anaconda Navigator will open.

4. 'conda' helps you to install other libraries mainly required for cheminformatics, analysis, machine learning, image analysis, SAR studies, forcefield analysis, MD analysis and many others including plotting graphs.

5. The codes in the notebook would be mandatory for any newbie or a good practice if you wanted the notebook to be used by anybody around the globe expecting they do not have any library for the research area installed in their computer.

Install the following before running cells in the Jupyter Notebook

6. Install wget (very useful for you to download any files via terminal or command-promp tin Win, Linux or MacOSX.

  Windows  --  https://eternallybored.org/misc/wget/1.20.3/64/wget.exe

Happy Coding!
