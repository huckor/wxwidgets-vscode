# wxWidgets "Hello World" project for Visual Studio Code
wxWidgets "Hello World" project made in Visual Studio Code. Can be used for making Windows, Linux and macOS GUI applications using C++ language. Project support compiling & debugging & intellisense in Visual Studio Code. 
Motivation for make this project was to use one IDE and one source code for all 3 major OS's.

## This is branch for wxWidgets 3.1.4
In case you want to use wxWidgets 3.0.5 then switch to wx_3.0.5 release https://github.com/huckor/wxwidgets-vscode/tree/wx_3.0.5.

## Prerequisites
1. Install Visual Studio Code with C/C++ extension for VS Code. You can follow this official tutorial: https://code.visualstudio.com/docs/cpp/config-mingw

2. wxWidgets have to be compiled before you'll be able to compile this project. See /doc folder for info how to do it. There is separate pdf document per Operating System. 
Project is using wxWidgets libraries from folders structure as it's explained in /doc folder. In case you use different folders structure you need to modify tasks.json, launch.json and c_cpp_properties.json.

3. When you pass step 2 of prerequisites section then your environment should be ready for compiling this project. Which means compiler, linker, SDK and libraries are installed. 
MacOS project possibly require few changes in tasks.json file. Required changes are explained in /doc/mac.pdf file.

## Compile
* In vscode hit CTRL + SHIFT + B for Linux & Windows
* In vscode hit CMD + SHIFT + B for macOS.
* Or in vscode select Terminal -> Run Build Task ...
