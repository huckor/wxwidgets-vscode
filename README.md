# wxWidgets "Hello World" project for Visual Studio Code
wxWidgets "Hello World" project made in Visual Studio Code. Can be used for making Windows, Linux and macOS GUI applications using C++ language. Project support compiling & debugging & intellisense in Visual Studio Code. 
Motivation for make this project was to use one IDE and one source code for all 3 major OS's.

## Different versions of wxWidgets
This Visual Studio Code project keep changing because wxWidgets are in active development. For this reason I'm keeping few permanent branches in this repository. You need to pick correct branch or release according wxWidgets version you decide to use. 

**Pick according this list**

- wxWidgets 3.2.3: 
[Git Branch](https://github.com/huckor/wxwidgets-vscode/tree/master) or [Release](https://github.com/huckor/wxwidgets-vscode/releases/tag/wx_3.2.3)

- wxWidgets 3.1.6: 
[Git Branch](https://github.com/huckor/wxwidgets-vscode/tree/develop_wx_3.1.6) or [Release](https://github.com/huckor/wxwidgets-vscode/releases/tag/wx_3.1.6)

- wxWidgets 3.1.4 or 3.1.5: 
[Git Branch](https://github.com/huckor/wxwidgets-vscode/tree/develop_wx_3.1.5) or [Release](https://github.com/huckor/wxwidgets-vscode/releases/tag/wx_3.1.4_v2)

- wxWidgets 3.0.5: 
[Git Branch](https://github.com/huckor/wxwidgets-vscode/tree/develop_wx_3.0.5) or [Release](https://github.com/huckor/wxwidgets-vscode/releases/tag/wx_3.0.5_v2)

## Prerequisites
1. Install Visual Studio Code with C/C++ extension for VS Code. You can follow this [official tutorial](https://code.visualstudio.com/docs/cpp/config-mingw)

2. wxWidgets have to be compiled before you'll be able to compile this project. See /doc folder for info how to do it. There is separate pdf document per Operating System. 
Project is using wxWidgets libraries from folders structure as it's explained in /doc folder. In case you use different folders structure you need to modify tasks.json, launch.json and c_cpp_properties.json.

3. When you pass step 2 of prerequisites section then your environment should be ready for compiling this project. Which means compiler, linker, SDK and libraries are installed. 
MacOS project possibly require few changes in tasks.json file in case you used different MacOS SDK than one mentioned in /doc/mac.pdf. Required changes are explained in /doc/mac.pdf file on second page.

## Compile
* In vscode hit CTRL + SHIFT + B for Linux & Windows
* In vscode hit CMD + SHIFT + B for macOS.
* Or in vscode select Terminal -> Run Build Task ...

## What's new
* Update project to comply with wxWidgets 3.1.6

## How to Contribute

Contributions are highly encouraged and appreciated! If you have any ideas, suggestions, or bug fixes, please feel free to contribute. Here's how you can get started:

1. Fork this repository to your GitHub account.
2. Make the desired changes or add new features to your forked repository.
3. Write test cases for your changes.
4. Submit a pull request, explaining the changes you have made and why they are beneficial.
5. I will review your pull request as soon as possible and provide feedback if needed.
6. Once your changes are approved, they will be merged into the main repository.
7. Congratulations! You have successfully contributed to this project.

## Code Style and Guidelines

To maintain code consistency and readability, please adhere to the following guidelines:

- Write clean and self-explanatory code.
- Use meaningful variable and function names.
- Follow the established coding style and formatting.
- Add comments where necessary to improve code understanding.

## Issues and Bug Reports

If you come across any issues or bugs while using this project, please report them using the GitHub issue tracker. Include a detailed description of the problem, steps to reproduce it, and any relevant information that might help in resolving the issue.

## Support

If you need any assistance or have questions regarding this project, feel free to reach out to me. I'll do my best to help you.

## Spread the Word

If you find this project helpful or interesting, consider giving it a star on GitHub. Also, sharing it with others who might benefit from it would be greatly appreciated.

Thank you for your interest in this project.