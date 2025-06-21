## MayaRubiks Python Plug-in

**[Video Demo Link](https://www.youtube.com/watch?v=ClZvq8PXw0g)**

### Overview:

A Maya plug-in that provides a comprehensive Rubik's Cube solving interface within Maya.

Given a scrambled cube, the plug-in applies the Kociemba algorithm (supported by muodov's kociemba
PyPi package) to create a full animation of the cube being solved step-step.

### Installation:
Clone the git repository onto your local machine. Locate the correct `Maya.env` file for the Maya app and version you
intend to use, and add the following line to the document:

```
MAYA_MODULE_PATH = "{LocalPathToClonedMayaRubiksPluginRepoDirectory}"
```

### Usage:
Locate the new `MayaRubiks` loadable plug-in within the Maya Plug-in Manager Window. Press `Load`.

Use the newly created `MayaRubiks` shelf and its attached interactive UI to create and solve infinite Rubik's Cubes.

**That's it, thank you for using!**
