# RTSS_Crosshair
Crosshair overlay for RivaTuner Statistics Server <br/>
At this point it's a simple app that prints '+' symbol in rtss shared memory and lets you control position and size of the symbol. <br/>
## Usage
All controls are shown on launch, for some reason order of pressing RightShift combination matters. <br/>
If you set "Onscreen display zoom" setting in rivatuner above zero, center coordinates gonna move past screen borders. If you need that zoom setting, you have to manually move symbol from default position. <br/>
## Building your own binary
You need an "nmake" and "cl" installed and have their path be in PATH variable. <br/>
If you have Visual Studio installed you already got them, just launch "VS Command Prompt" via Tools->Command Prompt, then change directory to one where you downloaded the files and execute "nmake /f makefile". <br/>
## Credits
Thank you, ShittyCodeMan for creating and sharing [RTSS_Timer](https://github.com/ShittyCodeMan/RTSS_Timer). <br/>
