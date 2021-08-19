   ![Background2021-01](https://user-images.githubusercontent.com/87783981/127431233-2fc765ab-81e2-4fa7-a6ac-e5d73e79f0f8.png)
## 👋 Hi, I’m [@Jyothi-Jaci](https://github.com/Jyothi-Jaci)!!!
✨🎉🎊🎇🎆✨🎊🎉✨🎇🎆🎇✨🎉🎈✨🎉🎊🎆🧨🎊🎉✨🎇✨🎆🎇🎊🎉🎈
- 🌍 I love Opensource, Rust and most of all . . . Python!!
- 👀 I’m a researcher interested in Python, Rust, Django, Qt, Unreal Engine, Blender, Devops, and Mathematics!
 
# What Code Looks Like:

## Free Tutorials:

### How To Run A Python Script In The Git Bash Terminal:
   
   https://stackoverflow.com/questions/4377109/shell-script-execute-a-python-program-from-within-a-shell-script

     python python_script.py
     
### How To Run A Javescipt Script In The Git Bash Terminal:
   
   https://gist.github.com/rosswd/acceded358c664b13174

     node javascript_script.js
     
### How To Upgrade Pip:

     python3 -m pip install --user --upgrade pip 
### Extra Tips:

- To navigate to your home directory, use "cd" or "cd ~"

- To navigate up one directory level, use "cd .."

- To navigate to the previous directory (or back), use "cd -"

- To navigate into the root directory, use "cd /"

# Repositories Of Interest:

# Useful Repositories:

   - https://github.com/Jyothi-Jaci/public-apis

   - https://github.com/Jyothi-Jaci/ant-design
   
   - https://github.com/Jyothi-Jaci/jekyll
   
   - https://github.com/Jyothi-Jaci/30-seconds-of-interviews
   
   - https://github.com/Jyothi-Jaci/30-seconds-of-code
   
   - https://github.com/Jyothi-Jaci/openshot-qt
   

## Python Repositories:

   - https://github.com/Jyothi-Jaci/Games
   
   - https://github.com/Jyothi-Jaci/PyMMO
   
   - https://github.com/Jyothi-Jaci/python-8

### Extra Python Links:

   - https://pypi.org/project/cocos2d/
   
## Rust Repositories:

   - https://github.com/Jyothi-Jaci/awesome-rust
   
   - https://github.com/Jyothi-Jaci/enginesound
   
   - https://github.com/Jyothi-Jaci/axolotl.py-api
   
## C Repositories

   - https://github.com/Jyothi-Jaci/awesome-cpp
   
## C++ Repositories

  - https://github.com/Jyothi-Jaci/pctation

## C# Repositories

  - https://github.com/Jyothi-Jaci/ProjectPSX
   
## Web Development Repositories:
   
  - https://github.com/Modernizr/Modernizr
   
  - https://github.com/foundation/foundation-sites
   
  - https://github.com/h5bp/html5-boilerplate
   
  - https://github.com/designmodo/Flat-UI
   
  - https://github.com/Jyothi-Jaci/ionicons
   
  - https://github.com/Jyothi-Jaci/normalize.css
   
  - https://github.com/Jyothi-Jaci/animate.css
   
# Additional Information:

   If you are _interested_ in "code" . . . that is great!
   
✨🎉🎊🎇🎆✨🎊🎉✨🎇🎆🎇✨🎉🎈✨🎉🎊🎆🧨🎊🎉✨🎇✨🎆🎇🎊🎉🎈
 
🌌 Thanks for checking out my Github!!! 🌌
##

<!---

More Links & Resources:

### How To Run Virtual Environments In Git Bash Terminal:

## 12.2. Creating Virtual Environments:

   The module used to create and manage virtual environments is called venv. venv will usually install the most recent version of Python that you have available. If you have multiple versions of Python on your system, you can select a specific Python version by running python3 or whichever version you want.

To create a virtual environment, decide upon a directory where you want to place it, and run the venv module as a script with the directory path:

python3 -m venv tutorial-env

This will create the tutorial-env directory if it doesn’t exist, and also create directories inside it containing a copy of the Python interpreter, the standard library, and various supporting files.

A common directory location for a virtual environment is .venv. This name keeps the directory typically hidden in your shell and thus out of the way while giving it a name that explains why the directory exists. It also prevents clashing with .env environment variable definition files that some tooling supports.

Once you’ve created a virtual environment, you may activate it.

On Windows, run:

tutorial-env\Scripts\activate.bat
On Unix or MacOS, run:

source tutorial-env/bin/activate
(This script is written for the bash shell. If you use the csh or fish shells, there are alternate activate.csh and activate.fish scripts you should use instead.)

Activating the virtual environment will change your shell’s prompt to show what virtual environment you’re using, and modify the environment so that running python will get you that particular version and installation of Python. For example:

$ source ~/envs/tutorial-env/bin/activate
(tutorial-env) $ python
Python 3.5.1 (default, May  6 2016, 10:59:36)
  ...
>>> import sys
>>> sys.path
['', '/usr/local/lib/python35.zip', ...,
'~/envs/tutorial-env/lib/python3.5/site-packages']
>>>

## 12.3. Managing Packages with pip
You can install, upgrade, and remove packages using a program called pip. By default pip will install packages from the Python Package Index, <https://pypi.org>. You can browse the Python Package Index by going to it in your web browser.

pip has a number of subcommands: “install”, “uninstall”, “freeze”, etc. (Consult the Installing Python Modules guide for complete documentation for pip.)

You can install the latest version of a package by specifying a package’s name:

(tutorial-env) $ python -m pip install novas
Collecting novas
  Downloading novas-3.1.1.3.tar.gz (136kB)
Installing collected packages: novas
  Running setup.py install for novas
Successfully installed novas-3.1.1.3
You can also install a specific version of a package by giving the package name followed by == and the version number:

(tutorial-env) $ python -m pip install requests==2.6.0
Collecting requests==2.6.0
  Using cached requests-2.6.0-py2.py3-none-any.whl
Installing collected packages: requests
Successfully installed requests-2.6.0
If you re-run this command, pip will notice that the requested version is already installed and do nothing. You can supply a different version number to get that version, or you can run pip install --upgrade to upgrade the package to the latest version:

(tutorial-env) $ python -m pip install --upgrade requests
Collecting requests
Installing collected packages: requests
  Found existing installation: requests 2.6.0
    Uninstalling requests-2.6.0:
      Successfully uninstalled requests-2.6.0
Successfully installed requests-2.7.0
pip uninstall followed by one or more package names will remove the packages from the virtual environment.

**Update Readme.md 1.2.0**
--->
