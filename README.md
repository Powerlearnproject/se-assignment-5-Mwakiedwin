[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15348647&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Go to your browser and search vs code from the browser.
   download vscode for windows 11 and download.
   once downloaded install vscode into your windows ,mac os, or linux computer.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

Several configurations are made once vscod is installed. Such configurations include installing prettier,life server, remote ssh and other extensions such as web develoopment extentions such as css peek that are mainly used for web development .Other extensions such as node js may be installed.
3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.


Ativity Bar
-it is situated on the fsr lr=eft of the vscode window.
It allows switching from search ,explorer,source control, debug and extesions.

Side bar 
It is located on the left side o the vscode editor.
it allows one to access files ,folders ,and resources one is working on.

Editor group.
 This is the main editing area. This allows one to effectively make changes and their code effectively.

 Status bar
 This is located at the bottom of the vscode window.It contains information and actions related to the workspace being worked on at the time.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

command pallette is a powerful tools that allows access to various settingd ,commands, and extensions using keyboard shortcuts.

its is accessed through input of various keyboard commands or shortcuts.
Various tasks performed using command pallette include:
1.File and workspace operations 
2 .Editing and formatting code
3 .Navigation and search
4 .Extensions and searching
5 .Tasks and debugging

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extension play a significant role in vs code .
this roles includes determination or choice of languages to be used.
customization of cide on vs code through custom workflows.
this makes vs code fully customizzable according to ones prefences.

eaxamples of these esxtentions include:prettier code formater,bookmarks,codespell.gitlens and live share


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

Opening the Integrated Terminal:
Keyboard Shortcut:
Press Shift + Backtick () (Windows/Linux).
This opens the integrated terminal at the root of your workspace.
Menu Commands:
From the menu, go to Terminal > New Terminal or View > Terminal.
This creates a new terminal instance.
Command Palette:
Open the Command Palette  or Ctrl+Shift+P.
Search for View: Toggle Terminal and select it.
This toggles the terminal panel.
Explorer Context Menu:
In the Explorer, right-click a folder or file.
Choose Open in Integrated Terminal.
This opens a terminal with the folder as the working directory.
Advantages of the Integrated Terminal:
Seamless Integration:
The integrated terminal is tightly integrated with VS Code.
It shares the same workspace context, making it easy to switch between code editing and terminal tasks.
Single Window Workflow:
No need to switch between VS Code and an external terminal window.
You can code, run commands, and debug within the same window.
Customization and Shell Integration:
Customize the terminal appearance, fonts, and colors.
Use various shells installed on your machine (e.g., Bash, PowerShell).
Benefit from shell integration features like tracking where commands are run.
Task Automation:
Run build tasks, tests, or other scripts directly from the terminal.
Automate repetitive tasks using scripts or task runners.
Workspace Context:
The integrated terminal starts at the root of your workspace.
It inherits the environment variables and settings from your project.
Shell Profiles:
Easily switch between different shell profiles (such as Git Bash, PowerShell).
Configure terminal shells according to your preferences.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   New folders can be created clicking extentions from the the activity bar create a new folder while new files can be created through rightclicking on the desired folders.

   Users can navigate between different files and directories by employing use of command pallettes to efficiently and quickly change files and folders.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
Certainly In Visual Studio Code (VS Code), you can find and customize settings using the following methods:

Settings Editor:

To open the Settings editor, navigate to File > Preferences > Settings.
Alternatively, use the keyboard shortcut Ctrl + , (Windows/Linux) or Cmd + , (Mac).
Here are some examples of customization:
Change Theme:

Go to Color Theme in the Settings editor.
Select a theme from the dropdown list (e.g., “Solarized Dark”).
The active theme is stored in your user settings.
Adjust Font Size:

In the Settings editor, select Text Editor > Font.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?


Create a Sample Project:

First, create a simple project  that you want to debug.
Ensure that the project has a main entry point.

Open the Project in VS Code:

Open VS Code and navigate to your project folder using the File Open Folder option.
Create a Launch Configuration

VS Code uses a launch.json file to configure debugging settings.
Press F5 or click the Run and Debug icon in the sidebar.
If no launch.json exists, VS Code will prompt you to create one. Choose the appropriate environment

Configure Launch Settings:
Edit the generated launch.json file to specify the program you want to debug (e.g., the path to your app.js or Python script).
Set breakpoints in your code by clicking on the left margin of the editor.
Start Debugging:
Press F5 or click the green play button in the top toolbar.
VS Code will launch your program in debug mode, and execution will pause at the breakpoints.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

