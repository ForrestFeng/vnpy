## Usage of the Setup folder

The main purpose is to automate the setup process to install vnpy on a ubuntu desktop os. (tested on Linux ubuntu24.04 6.14.0-33-generic)


### It mainly helps you do 3 tasks 

1. Setup the vnpy trading system
```
sudo ./setup_vnpy 
```

The setup_vnpy must be run with sudo, and inside it it will 
invoke 
a. install_dependency
b. install_miniconda_clone_vnpy
c. install.sh (from vnpy sourcecode)
d. install_vnpackages
e. install_mysql (optinal)


2. give an sample vt_setting.json 
You can place it into /home/<user>/.vntrader/vt_setting.json as global configuratoin for vnpy.


3. give an run.py to start vnpy trader GUI, a Qt app, with sub-engines and gateways.
Update it as needed



