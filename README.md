# venv-for-py3.6
To those who for a reason or two can't CREATE a virtualenv in Python 3.6.

# Acclaration

  **You _must_ have `pip` and `virtualenv` already installed in your computer in order for this to work, you can know if you have them by typing in the console 
      $ pip -V
    And if you already have it, you can proceed to the guide below**
    
   If you don't have it, be sure to check the site to download the `get-pip.py` file and open it with python
      **$ python get-pip.py**
   Also, if you want to upgrade it:
      **$ python -m pip install -U pip**
      
# Usage guide

If you can't create or initialize a new virtual environment in Python via the console **(I've only tested on Windows, don't know about Linux or Mac)**, just download this folder which contains **(at least for the version 3.6)** all the default stuff you need in order to `activate` the virtual environment.

Copy the `venv` folder to wherever you need it, and in order to activate it, just navigate like this:
  
*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-

  $ cd venv --> cd Scripts --> activate.bat **(Used _cd_ to demonstrate the navigation in Windows, use _ls_ for Mac and Linux)**

*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-
 
After you execute the commands above, you should be **in** the virtual environment, from there you can do whatever you want; however you may want to install something as Flask in order to verify the integrity of your `virtualenv`

  **$ pip install flask**
  
Then, type 

  **$ pip freeze**
  
To verify eveything that has been configured in your `virtualenv`.

# Finally

Please, let me know any thought or error or anything, I'm kind of new to this xD
