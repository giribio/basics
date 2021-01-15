### Compiled by Girinath G Pillai, [Webpage](https://bit.ly/giribio20)

# Installation Steps on Anaconda
How to start with Jupyter, Python (pip), library, streamlit, heroku, pickle, Github along with Anaconda (conda)

I personally recommend you to start with Python 3.8+ (2.x versions are going to depreciate)

[Installation Video Tutorial](https://www.youtube.com/watch?v=n0ln_41Dq0g)
[KNIME and Orange Quick Tutorial](https://youtu.be/R7FYypCUasc?t=2499) - to generate ML, Stat models, deploy and others without coding

### 1. Install Anaconda (ensure the environments are set properly after installation)

Jupyter Notebook, numpy, pandas, matplotlib, spyder, seaborn and few others are installed along with Anaconda.
If you have Python already installed set the environment variables properly.

Installation Link
```bash
https://www.anaconda.com/products/individual#Downloads
```

Instructions on installations
```bash
https://docs.anaconda.com/anaconda/install/windows/
          
https://docs.anaconda.com/anaconda/install/linux/
          
https://docs.anaconda.com/anaconda/install/mac-os/
```

### 2. To set environments (already installed)
  
You could choose set the conda 'base' environment as default or not..
If you choose anaconda 'base'environment not to be default, then follow the steps:
Run the following commands on your terminal or command-prompt
```bash 
  source ~/anaconda3/bin/activate
  conda init
```

### 3. To upgrade existing version (already installed)
  
Run the following commands on your terminal or command-prompt
```bash 
  source ~/anaconda3/bin/activate
  conda update conda
  conda update anaconda=VersionNumber
```
More details

```bash
https://docs.anaconda.com/anaconda/install/update-version/
```

### 3. Verification of installation
  
  Open the Anaconda Prompt or the terminal, choose any of the following methods to verify:

  a. Enter 'conda list'. If Anaconda is installed and working, this will display a list of installed packages and their  versions.
  
  b. Enter the command 'python'. This command runs the Python shell. If Anaconda is installed and working, the version information it displays when it starts up will include “Anaconda”. To exit the Python shell, enter the command quit().
  
  c. Open Anaconda Navigator with the command 'anaconda-navigator'. If Anaconda is installed properly, Anaconda Navigator (GUI) will open.

### 4. 'conda' helps you to install other libraries mainly required for cheminformatics, analysis, machine learning, image analysis, SAR studies, forcefield analysis, MD analysis and many others including plotting graphs.

### 5. The codes in the notebook would be mandatory for any newbie or a good practice if you wanted the notebook to be used by anybody around the globe expecting they do not have any library for the research area installed in their computer.

Install the following before running cells in the Jupyter Notebook

### 6. Install wget or curl (very useful for you to download any files via terminal or command-promp tin Win, Linux or MacOSX)

        Windows  --  https://eternallybored.org/misc/wget/1.20.3/64/wget.exe

# Installation of Deployment Tools

### 1. Without installation, online coding!

Google CoLab Link
```bash
https://colab.research.google.com/
```

### 2. Without installation, online coding with databases!

Kaggle Notebook Link
```bash
https://www.kaggle.com/
```

### 3. Without installation, online deployment is possible, for any deployment have a GitHub account with repositories ready!

Web Link
```bash
https://mybinder.org/
```

### 4. Install Streamlit (ensure anacoda environments set properly)

conda/pip Installation
```bash
pip install streamlit
streamlit hello
```

Online depolyment account request
```bash
https://share.streamlit.io/
```

### 5. Install Git (ensure you run from terminal/command-line and then source conda)

Installation Link
```bash
https://git-scm.com/downloads
```

### 6. Install Github Desktop (to push/pull repositories)

Direct Installation Link
```bash
https://desktop.github.com/
```

### 7. Install Heroku (ensure you run from terminal/command-line and then source conda to push to heroku)

Direct Installation Link
```bash
https://devcenter.heroku.com/articles/heroku-cli#download-and-install
```

conda Installation Link
```bash
https://anaconda.org/search?q=heroku
```

### 8. Publish codes with DOI (release from GitHub)

Direct Link
```bash
https://zenodo.org/
```

### 9. Learn coding and participate in competitions

Direct Link
```bash
https://leetcode.com/
```


Happy Coding!
