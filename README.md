# Mouse Click Simulator for TT Rewritten

This is a new implementation of the [**TT Mouse Click Simulator**](http://old.preisser-it.de/tt-mausklick/) that is intended to work with TT Rewritten. It is implemented in C# and runs on Windows on .Net 4.6 or higher.

To build it, you should use [Visual Studio 2015](https://www.visualstudio.com/).

![mousesim-screenshot](https://cloud.githubusercontent.com/assets/15179430/10711743/3f540cec-7a85-11e5-9909-23a7998c5687.png)

### WARNING
Use this program at your own risk!
Toontown Rewritten states in their Terms of Use that you should not use automation software, so you might risk a ban if you use this program.

## Status

Currently, the implementation contains actions for pressing keys, writing text, SpeedChat, Doodle Interaction Panel and the Automatic Fishing Function.

The GUI allows to load projects from an XML file. There are some predefined projects included in the "SampleProjects" folder but you can also create your own XML Simulator Project files. You can use the ["Sample Actions.xml"](https://github.com/TTExtensions/MouseClickSimulator/blob/master/TTMouseclickSimulator/SampleProjects/Sample%20Actions.xml) as a template for creating your own project.

The GUI does not yet show what actions a project contains.

### TODOs:
- In the GUI, show the actions of a project in a tree-like structure and show which action is currently running.
- Document how to build the Mouse Click Simulator using Visual Studio or the .Net 4.6 SDK.
- Document how to use the Mouse Click Simulator.
- Document how to create own XML Simulator Porject files.
