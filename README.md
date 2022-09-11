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




https://user-images.githubusercontent.com/26037455/189528016-9dde2bd8-9e60-47cd-badc-e6db38d072b2.mp4



**Version 0.2**
1) First of all go to `Project>ProjectSettings>InputMap` and create your own inputMap
2) Go in ``LoadSave Input Map`` Tab 
3) Insert an alphaNumeric name(nospaces or special letters are allowed)
4) Click on Save inputMap it will save a file inside a new folder on your documents, the folder name is "inputMapsSaves"
5) The new file will be avaible on the file list

### Loading your inputMap




https://user-images.githubusercontent.com/26037455/189528036-101c9551-f640-4343-91ca-0a7f0bab5b31.mp4




1) Start a new project 
2) Import the plugin and activate it 
3) Go to `Project/ProjectSettings/LoadSave Input Map` and select a an inputmap file from the file list
4) Click on Load
5) Reload your project

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

