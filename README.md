# buildswin.bat
Using this .bat file, SwinGame's C# version no longer requires the usage of Visual Studio or Xamarin Studio in order to 
build.

This version only supports .Net Framework 4 however this can easily be changed by editing the location of your .Net directory in the batch file. The `.vscode` folder contains a task runner which adds support for building in Visual Studio Code `Ctrl + Shift + B`

## Usage Instructions
This does require .Net Framework 4.0 by default, this can easily be changed by changing the set path line to the directory of any other valid .Net framework. 
Keep this batch file in your games top directory with the .csproj files and .sln files and such. 

Note that this works when using the pre-made csproj downloadable from [here.](http://www.swingame.com/images/downloads/SwinGame3.6/CSharp_SwinGame_3_6_VS10PROJ.zip)

This doesn't allow you to debug the code with breakpoints and such but is very handy for someone who'd prefer to use the lightweight nature of a text editor.
