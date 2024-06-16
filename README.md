[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15243722&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Questions:

1.  Installation of VS Code:

    - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

# Step 1: Download Visual Studion Code Installer

Ensure you have windows 11 successfuly installed in your pc

Open your favourit browser (eg chrome, firefox or microsoft edge) got to the Visual Studio Code official website: https://code.visualstudio.com/

click on the 'Download' button. This will download the installer (named as `vsCodeSetup-x64.exe`).

# Step 2: Run the Installer

Once the download is complete, open the downloads here you will find your installer. Open it by double-clicking the downloaded file(`vsCodeSetup-x64.exe`).

If prompted by the User Account Control, click "Yes" to allow the installer to make changes to your device.

# Step 3: Setup the Wizard

Once Visual Studion Code Setup Wizard is open click "Next" to proceed.

# Step 4: License Agreement

Once the setup for Visual Studio Code is done the Licence Agreement will open so you click on "I accept the agreement" option and click next.

# Step 5: Select Destination Location

Choose the destination folder where you want Visual Studio Code to be installed. The default location(C:\Users\[YourUsername]\AppData\Local\Programs\Microsoft VS Code) usually is fine. Then click on "Next" to continue.

# Step 6: Select Additional Tasks

On the "Select Additional Tasks" screen, you can choose to create a desktop icon, add Visual Studio Code to the PATH(recommended), and other options. selectthe options you prefer and click "Next".

# Step 7: Ready to Install

Click "Install" after reviewing that everything looks correct to begin the installation process.

# Step 8: Complete Installation

Once the installation is complete, look out for completion screen. Here you can choose to launch Visual Studion Code by checking the "Launch Visual Studion Code " box then click "Finish".

# Step 9: Additional configuartion (optional)

To install Extensions open Visual Studion Code, then go to Extension view(Ctrl+Shift+X) and search for the extensions you prefere(e.g Python, javascript).

If you Use Visual Studion Code on multiple machines , enable sync to keep your settings consistent across devices.

2.  First-time Setup:

- After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

# .Theme and Layout

Choose a comfortable color theme. Go to `File > Preferences > color theme ` and select from Dark+ and Light+ options

# .Auto Save

Enable auto-saving files to avoid losing work. Go to `File` then scroll down to `Autosave`.

# .Essential Extensions

On the left side of Vs Code click on the square-like icon for extensions, then search the extension you like

Python- Install Python extension by microsoft for code linting, intelliSense and debugging

JavaScript/Typescript- Install ESLint for linsting and prettier for code formatting.

# .Productivity Tools

Live Server - This extension allows you to launch a development local server with a live reload feature for static and dynamic pages.

# .Settings sync

Enable Settings Sync to keep your Vs Code settings consistent across multiple devices.

Go to `File > Preferences > Settings Sync` and sign in with your MicroSoft or GitHub account to Synchronize your settings, extensions and keybindings.

3.  User Interface Overview:
    - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

# .Activity Bar

The Activity Bar is located on the far left side of the VS Code window.

It provides quick access to different views and functionalities within VS Code.

Components:
Explorer- View and manage files and folders in your workspace.
Search- Perform text searches across files in your workspace.
Source Control- Manage version control using Git or other source control systems.
Run and Debug- Access debugging and run configurations for your code.
Extensions- Browse and install extensions to add new features to VS Code.

# .Side Bar

The Side Bar is adjacent to the Activity Bar on the left side of the window.

It displays different panels based on the selected Activity Bar item, providing detailed views and tools.

Components:
Explorer Panel- Shows the file and folder structure of the current workspace.
Search Panel- Allows for text search and replace operations across files.
Source Control Panel- Displays changes, commits, and branches in the version control system.
Extensions Panel- Lists installed extensions and allows searching for new ones.
Debug Panel- Provides controls and information for running and debugging code.

# .Editor Group

The Editor Group occupies the central area of the VS Code window.

This is where you write and edit your code. You can open multiple files in tabs, split the editor into multiple panes, and switch between them easily.

Components:
Tabs- Each open file is represented by a tab at the top of the Editor Group.
Editor Panes: You can split the Editor Group into multiple panes to view and edit files side by side.
Minimap- A small preview of your code located on the right side of the editor, useful for quick navigation.

# .Status Bar

The Status Bar is located at the bottom of the VS Code window.

It provides information about the current state of the editor and workspace, as well as shortcuts to various settings and commands.

Components:
Information Displays- Show details like the current branch, file encoding, line and column numbers, and language mode.
Background Tasks- Indicate ongoing processes like building, running tasks, or debugging sessions.
Interactive Elements- Provide quick access to settings like the file encoding, end-of-line sequence, and indentation settings.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

# .What a command peette is

The Command Palette is a significant feature in Visual Studio Code that lets you easily access and perform a wide range of commands and functionality. It functions as a central command center, allowing you to perform activities without having to navigate menus or remember keyboard commands.

# .How to access the command palette

To open the Command Palette, use the shortcut: Ctrl + Shift + P (or F1).
You may also access it from the menu by selecting View > Command Palette.

# .Common Command Palette Tasks

(a). Opening files and folders.
Type `Open File` and select a file from your workspace.
Type `Open Folder` to open a folder in a new or current window.

(b). Searching and Replacing text
Find in Files- Type `Find in Files` to search for all files in your workspace.

Replace in Files- Enter `Replace in Files` to find and replace text in multiple files.

(c). Running Commands and Tasks
Type `Run Task` to start predefined actions like developing your project or running scripts.

Type Run Build` Task to compile or build your project using the chosen build task.

(d). Version Control Operations
Git: Clone- Type` Git: Clone` to clone a repository from a remote source.

Git: Commit- Type` Git: Commit` to commit staged changes with a message.

(e). Extension Management
Install Extensions- Type `Extensions: Install Extensions` to browse and install new extensions.

Disable Extensions- Type `Extensions: Disable Extensions` to disable installed extensions.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

# .Role of Extensions in VS Code

Extensions add syntax highlighting, IntelliSense (code completion), linting, and debugging capabilities for various programming languages.

Extensions provide tools and features tailored for specific frameworks and libraries, making development more efficient.

Extensions enhance productivity by adding features like code snippets, version control integrations, task runners, and much more.

Extensions allow users to personalize their coding environment with themes, icon packs, and custom settings.

# .Finding, Installing, and Managing Extensions

---Finding extensions---
Visit the Visual Studio Code Marketplace to browse and search for extensions.
Within VS Code, open the extension’s view by clicking the Extensions icon in the Activity Bar or pressing `Ctrl + Shift + X.`

---Installing the extensions---

Open the Extensions view (`Ctrl + Shift + X`).
Search for the desired extension using the search bar at the top.
Then click the Install button next to the extension you want to install.

---Managing extensions---

To View the installed extensions
Visit the Extensions view (`Ctrl + Shift + X`), the installed extensions are listed under the "Installed" section.

To disable or enable extensions
In the Extensions view, click the gear icon next to the extension and select Disable or Enable.

To Uninstall Extensions
Click the gear icon next to the extension and select Uninstall.

To Update Extensions:
Extensions with available updates will have an update button next to them in the Extensions view. Click Update to install the latest version.

# .Essential Extensions for Web Development

---HTML, CSS, and JavaScript Support---
HTML Snippets- Provides HTML code snippets.
CSS IntelliSense- Adds CSS class and id name autocomplete to VS Code.

JavaScript (ES6) Code Snippets- Adds JavaScript ES6 code snippets.

---Framework and Library Support---
Prettier- This is a code formatter Code. It automatically formats your code to ensure consistency.

ESLint- Integrates ESLint into VS Code for identifying and fixing JavaScript code issues.

React Native Tools- Provides a development environment for React Native projects.

---Version Control and Collaboration---
Debugger for Chrome- Debug JavaScript code in the Chrome browser directly from VS Code.

Jest- Provides integration with the Jest testing framework.

---Productivity support---
Path Intellisense- Autocompletes filenames as you type.

Live Server- Launches a local development server with a live reload feature for static and dynamic pages.

6. Integrated Terminal:

- Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

  The integrated terminal in Visual Studio Code (VS Code) is a useful feature that allows developers to run command-line tasks directly from within the editor. This seamless integration boosts productivity by eliminating the need to switch between the editor and a separate terminal.

# .Opening the Integrated Terminal

Using the Menu
Go to the menu bar at the top of VS Code.
Select Terminal > New Terminal.

Using Keyboard Shortcuts:
Press Ctrl + (backtick) to open the integrated terminal.

Using the Command Palette:
Open the Command Palette by pressing Ctrl + Shift + P.
Type Terminal: Create New Integrated Terminal and press Enter.

# .Using the Integrated Terminal

Running Commands
Use the integrated terminal to run commands just as you would in any external terminal. For example, you can run build scripts, version control commands, or any other command-line tools relevant to your project.

Multiple Terminals
You can create multiple terminal instances. Click the `+` icon in the terminal tab to open a new terminal instance.
Each terminal instance can be switched between using the drop-down menu in the terminal tab or by using the `Ctrl + Shift +` (backtick) shortcut.

Split Terminals
Split the terminal view by clicking the split terminal icon (two rectangles) next to the `+` icon. This allows you to view and use multiple terminals side by side.

Customization
You can change the default shell used by the terminal. Go to ` File > Preferences > Settings` and search for `terminal.integrated.shell.` Select your preferred shell (e.g., PowerShell, Git Bash, Command Prompt).

# .Advantages of Using the Integrated Terminal

The integrated terminal allows you to run commands and see output without leaving the editor. This eliminates the need to switch between applications, saving time and maintaining focus.

The integrated terminal automatically opens in the context of the current workspace. This means you don’t need to navigate to your project directory manually, as the terminal is already set to the correct path.

By having the terminal within the same window, you can quickly reference code, copy and paste commands, and see real-time updates to your project without disruption.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

# .Creating Files

Using the Explorer
Open the Explorer by clicking the Explorer icon in the Activity Bar or pressing `Ctrl + Shift + E`.
Right-click on a folder in the Explorer and select `New File`.
Enter the desired file name and press `Enter`.

# .Creating Folders

Using the Explorer:
Right-click on a folder in the Explorer and select `New Folder`.
Enter the desired folder name and press `Enter`.

# .Opening Files

Using the Explorer:
Double-click on a file in the Explorer to open it.
Single-click to preview the file (opens in a temporary tab).

# .Opening Folders

Using the Menu
Go to `File > Open Folder`.
Browse to the desired folder and select it.

Renaming Files and Folders
Right-click on the file or folder in the Explorer and select `Rename`.
Enter the new name and press `Enter`.

Moving Files and Folders
Drag and drop the file or folder to a new location within the Explorer.
Alternatively, right-click the item, select Cut, navigate to the new location, right-click, and select Paste.

Deleting Files and Folders
Right-click on the file or folder and select Delete.
Confirm the deletion when prompted.

# .Navigating Between Files and Directories

(a). Quick Open
Press `Ctrl + P` to open the Quick Open box.
Start typing the name of the file or directory, and select it from the list.

(b). Go to Definition
Place the cursor on a function or variable and press F12 to jump to its definition.
Alternatively, right-click and select `Go to Definition`.

(c). Go to File
Press `Ctrl + T` to open the Go to Symbol in Workspace, where you can search for symbols across all files.

(d). File Explorer
Use the Explorer to navigate through the file structure by expanding and collapsing folders.
You can quickly jump to files by clicking on them in the Explorer.

(e). Sidebar Navigation
Switch between different views like Explorer, Search, Source Control, Run and Debug, and Extensions using the Activity Bar on the left.

(f). Open Editors View
The Open Editors section at the top of the Explorer shows all currently open files, allowing quick switching between them.

8. Settings and Preferences:

- Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

# .Accessing Settings

Using the Menu

Go to `File > Preferences > Settings` (on Windows/Linux).
Go to `Code > Preferences > Settings` (on macOS).

Using the Command Palette
Press `Ctrl + Shift + P` to open the Command Palette.
Type `Preferences: Open Settings` and select it.

Using Keyboard Shortcut
Press `Ctrl + ,` (comma) to directly open the Settings.

# .Changing the Theme

Using the Settings UI

Open Settings as described above.
In the search bar at the top, type theme.
Click on Color Theme under Preferences.
Browse through the available themes and click on the one you want to apply.

Using the Command Palette
Press Ctrl + Shift + P to open the Command Palette.
Type Preferences: Color Theme and select it.
Browse through the list of themes and click on the one you want to apply.

# .Changing the Font Size

Using the Settings UI

Open Settings as described above.
In the search bar, type font size.
Under `Editor: Font Size`, enter the desired font size value (e.g., 16).

# .Changing Keybindings

Using the Keybindings UI

Go to `File > Preferences > Keyboard Shortcuts` (or press Ctrl + K Ctrl + S).
In the search bar, type the command you want to change (e.g., copy for Copy command).
Click on the pencil icon next to the command and press the desired key combination (e.g., Ctrl +
C).

9. Debugging in VS Code:

- Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Step 1: Install Necessary Extensions
Ensure you have the appropriate language extension installed. For example, if you're debugging a Python program, install the Python extension by Microsoft from the Extensions view (`Ctrl + Shift + X`).

Step 2: Open Your Project
Open your project folder in VS Code by selecting `File > Open Folder` and navigating to your project directory.

Step 3: Configure the Debugger
Open the Run and Debug view by clicking the Debug icon in the Activity Bar or pressing `Ctrl + Shift + D`.

Click on `create a launch.json file` or select `Run and Debug > Add Configuration…` from the top dropdown menu.

VS Code will suggest configurations based on the files in your workspace. Choose the appropriate configuration for your language/runtime.

For example, for a simple Python program, your launch.json might look like this:

json
Copy code
{
"version": "0.2.0",
"configurations": [
{
"name": "Python: Current File",
"type": "python",
"request": "launch",
"program": "${file}",
"console": "integratedTerminal"
}
]
}

Step 4: Set Breakpoints
Open the file you want to debug.
Click in the gutter to the left of the line numbers where you want to set a breakpoint. A red dot will appear indicating the breakpoint.

Step 5: Start Debugging

In the Run and Debug view, select the configuration you created from the dropdown menu.
Click the green play button or press `F5` to start debugging.

# .Key Debugging Features in VS Code

(a)Breakpoints
Conditional Breakpoints- Right-click on a breakpoint and select `Edit Breakpoint` to set conditions under which the breakpoint should trigger.
Logpoints- Instead of pausing the program, logpoints print a message to the debug console.

(b) Step Through Code
Step Over (F10)- Move to the next line of code, skipping over function calls.
Step Into (F11)- Step into functions to debug code inside them.
Step Out (Shift + F11)- Step out of the current function and return to the caller.

(c) Variable Inspection
Variables View- Displays variables in the current scope, allowing you to inspect and modify them.
Hover- Hover over a variable in the editor to see its current value.

(d) Watch Expressions
Add expressions to the Watch panel to monitor their values as you step through the code.

(e) Debug Console
Use the debug console to execute commands and evaluate expressions in the context of the current debugging session.

(f) Integrated Terminal:
Run and debug code within the integrated terminal, which is synchronized with your debugging session.

10. Using Source Control:

- How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

# Initializing a repository

(1). open project folder in Vs Code
open Vs Code.
Then select `File > OPen Folder` and navigate to your project directory.

(2). Open Git Bash
Right-click in your project folder in the File Explorer
Select `Git Bash Here` to open the Git Bash i the project

(3). Initialize Git Repository
Run the following command in Git Bash
(`git init`)
This command initializes a new git repository in your project directory

# Making Commits

(1). To stage all changes run
(`git add .`)

(2). To stage specific files , run
(`git add <file1> <file2>`)

# Commit changes

(1). Run the following command , replacing `<commit message >` with your message.
(`git commit -m "<commit message>"`)

REFRENCES

Lin, S. T., Yousefi, M., & Bercher, P. T. A Visual Studio Code Extension for Automatically Repairing Planning Domains. In ICAPS 2024 System's Demonstration track.

Liu, A., & Coblenz, M. Debugging Techniques in Professional Programming. Plateau Workshop.

Skoulikari, A. (2023). Learning Git. " O'Reilly Media, Inc.".

Tan, J., Chen, Y., & Jiao, S. (2023). Visual Studio Code in Introductory Computer Science Course: An Experience Report. arXiv preprint arXiv:2303.10174.

Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 23 june
