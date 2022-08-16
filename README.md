# Load-Save-InputMap-Godot
A plugin that helps to Load and Save your InputMap in Godot

## PLEASE BE AWARE THIS IS NOT OFFICIAL, THIS MIGHT BREAKE YOUR PROJECT YOUR CHOISE ON USING IT, PLEASE LOAD YOUR INPUT MAP BEFORE YOU START WORKING ON YOUR PROJECT
###### Sorry for my macherony code

### How does it work?
The plugin acts directly on the project.godot file. This is why it might be distructive and dangerous if you use on a project that it is on later stages but new.
The plugin checks the [input] section inside the project.godot file and eventually saves that as a test into a .input file. 
When it loads it, the plugin checks inside project.godot if there exists an [input] section, if it exists it erases that section and adds myInputMap.input ass a text, godot autodetects and autoformats it once the project is reloaded.
If the [input] section doesn't exists it just adds that section.

**The plugin comes with a deafult inputmap**

## How to use it
### Installation
1) Copy the `"LoadSaveInputMap"` folder inside the `"addon"` folder of your project or you can import it from `AssetLib>import>LoadSaveInputMap.zip`
2) Activate the plugin, `Project>ProjectSettings>Plugins>LoadSaveInputMap` enable it.
3) You should see a new Tab `LoadSave Input Map`

### Saving you inputMap
1) First of all go to `Project>ProjectSettings>InputMap` and create your own inputMap
2) Go in ``LoadSave Input Map`` Tab and click on Save inputMap it will save a file called `myInputMap.input `
3) `myInputMap.input` needs to be inside `LoadSaveInputMap` folder this way you can load it.
4) So make sure that myInputMap.input is inside your pluginFolder each time you want to load it in a new project (I suggest creating a .zip file that has everything inside and import it each time you start a new project)

### Loading your inputMap
1) Start a new project 
2) Import the plugin with the your own `myInputMap.input` inside the plugin folder (the one you exported previously)
3) Go to `Project/ProjectSettings/LoadSave Input Map > Load `
4) Reload your project

### The default myInputMap.input file content

- RMB = Right mouse Button,
- LMB = Left Mouse Button,
- MMB = Middle Mouse Button,
- WHEEL UP = Mouse Wheel Up,
- WHEEL DOWN = Mouse Wheel Down,
- LEFT = Left Arrow, A, Left Stick Left,
- RIGHT = Right Arrow , D, Left Stick Right,
- UP = Up Arrow , W, Left Stick Up,
- DOWN = Down Arrow , S, Left Stick Down,
- JUMP = Space , A Button 


This plugin is born for my personal use since every time I start a new project I need to reMap my Inputs

