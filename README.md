# oide-vnc
VNC App for the OIDE.
**Installing OIDE VNC**

The OIDE VNC requires that you first install [The OIDE](https://github.com/ResearchComputing/OIDE)

Once the OIDE is installed, clone the OIDE VNC repository and enter the project directory:
```
git clone https://github.com/ResearchComputing/oide-vnc.git
cd oide-vnc
```
Then, build the dependencies for the front-end components:
```
cd oidevnc
bower install
```

Now configure your local OIDE VNC app settings, if they diverge from the defaults. The settings file may be modified directly, or be overridden with a `local_settings.py` file in the `oidevnc` directory:

Switch back to the project root and install the python package (a virtualenv is recommended):
```
python setup.py install
```
The OIDE, which will now include the OIDE VNC app, can now be run with the following command:
```
oide
```
To use the OIDE, point your browser to `localhost:8888`.
