#GameCollectionApp

[![Join the chat at https://gitter.im/ChapmanCPSC370/TriviaGame](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ChapmanCPSC370/TriviaGame?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
The original project was just a c# console  application that took in data from a text file, and made a simple trivia game. 
I am changing this to a collection of gui games. The user will be able to choose from different trivia formats or choose other classic games to play. Using .Net Framework 4.5. Platform is limited to Windows.

##Mission Statement
A place to make a collection of games. I enjoy making little games like this. Its a fun hobby and exercises my programming skills. I am also learning how to use github for OSS projects. If you also like creating games and want to see where your programming skills are, then feel free to contribute.

##Ways To Contribute
1. Code
  * Clone the repo: git clone https://github.com/ChapmanCPSC370/TriviaGame.git
  * Make changes
  * Create a Pull Request
  * Add changes to the Development branch
  * If reporting issues, please label them and be specific about the problem.
  * For UI elements, please [use these prefix nameing conventions](https://msdn.microsoft.com/en-us/library/aa263493(v=vs.60).aspx)
  * For example, txtName for a textbox that takes in name or btnOk for an okay button
2. Art
  * Add art work to the README
  * Add artwork to games by following instruction from above
3. Documentation
  * If you have good communication skills, please feel free to add to the wiki page
  
##Prerequisites
  * Knowledge of [C#](https://msdn.microsoft.com/en-us/library/67ef8sbd.aspx)
  * Knowledge of [SQLite](https://www.sqlite.org) is a plus
  * Use a version of Visual Studio that supports .Net 4.5 Framework

##Installation
If you don't have Visual Studio installed, then download the free version of visual studio [here](https://www.visualstudio.com/downloads/download-visual-studio-vs) and follow install directions. A microsoft account may be neccesary for set up after the installation has completed.

##Run in Visual Studio
Open Visual Studio.
Click on the File menu, then click Open, then choose Project/Solution.
Find the project folder, and open the TriviaGame.sln file.

To view the code, click on the View menu, and then click on Code, or press F7.

To view the designer, click on the View menu and then click on Designer, or press shift+F7

#####Run in MonoDevelop
Developers can choose to do this in MonoDevelop but it will need to be started from scratch and be a separate project because MonoDevelop only supports winforms for .Net 2.0.
You can install MonoDevelop from [here](http://www.monodevelop.com/download/) . It is supported on Linux, Mac OSX, and Windows. Depending on what OS you are using, you will follow different instruction to download and install.

[Mono Documentation](http://www.monodevelop.com/documentation/)

For UI elements, you will want to use [WinForms](http://www.mono-project.com/docs/gui/winforms/)

##License
[MIT License](http://opensource.org/licenses/MIT)

##Communication
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ChapmanCPSC370/TriviaGame?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
Developers can now communicate in the Gitter chat room.

##Updates:
11/3/2015: Set up sqlite DB. Program has code to get info from DB. Having issues with inheritance. Don't want to commit code for a program that is getting a runtime error. Added a new issue to the issue tracker. Will try to get this resolved soon. Have been using this as a resource: [https://msdn.microsoft.com/en-us/library/7h62478z(v=vs.110).aspx](https://msdn.microsoft.com/en-us/library/7h62478z(v=vs.110).aspx) and this: [https://msdn.microsoft.com/en-us/library/5h0k2e6x(v=vs.110).aspx](https://msdn.microsoft.com/en-us/library/5h0k2e6x(v=vs.110).aspx)
