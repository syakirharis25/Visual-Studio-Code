# Visual-Studio-Code
My works related to Visual Studio Code.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Visual Studio Code shortcuts.](#shortcuts)
4. [GitHub notes.](#github)

<a name="introduction"></a>
## 1. Introduction.
<img src="vscode.png" height="150"> 
Visual Studio Code is a source-code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control and GitHub, syntax highlighting, intelligent code completion, snippets, and code refactoring. It is highly customizable, allowing users to change the theme, keyboard shortcuts, preferences, and install extensions that add additional functionality. The source code is free and open source and released under the permissive MIT License. The compiled binaries are freeware and free for private or commercial use. <br /><br />

Visual Studio Code is based on Electron, a framework which is used to develop Node.js applications for the desktop running on the Blink layout engine. Although it uses the Electron framework, the software does not use Atom and instead employs the same editor component (codenamed "Monaco") used in Azure DevOps (formerly called Visual Studio Online and Visual Studio Team Services).

In the Stack Overflow 2019 Developer Survey, Visual Studio Code was ranked the most popular developer environment tool, with 50.7% of 87,317 respondents claiming to use it.

<a name="references"></a>
## 2. Official references websites.
Official Visual Studio Code website : https://code.visualstudio.com/ <br />
Official Visual Studio Code documentations : https://code.visualstudio.com/docs <br />
Official Microsoft website : https://www.microsoft.com <br />

**_Visual Studio Code extensions_** <br />
Create Files & Folders : On The Go by Ritwick Dey : https://marketplace.visualstudio.com/items?itemName=ritwickdey.create-file-folder <br />
Live Server by Ritwick Dey : https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer <br />

<a name="shortcuts"></a>
## 3. Visual Studio Code shortcuts.
**_Visual Studio Code EXPLORER bar_** <br />
**[ Ctrl ]** + **[ B ]** : hide the EXPLORER bar (first hit) <br />
**[ Ctrl ]** + **[ B ]** : show the EXPLORER bar (second hit) <br />

**_Visual Studio Code text management_** <br />
**[ Ctrl ]** + **[ F ]** : find certain text, press [ → ] to unselect the text, but continue with multiple cursor option <br />
**[ Ctrl ]** + **[ D ]** : find the same text <br />
**[ Ctrl ]** + **[ / ]** : commenting <br />
**[ Ctrl ]** + **[ Shift ]** + **[ D ]** : duplicate the whole line to the next line below it <br />
**[ Shift ]** + **[ PgUp ]** : go to the top of the line <br />
**[ Shift ]** + **[ PgDown ]** : go to the bottom of the line <br />
**[ Alt ]** + **[ MOUSE LEFT CLICK ]** : adding multiple cursors <br />
**[ Ctrl ]** + **[ Shift ]** + **[ K ]** : delete entire line <br />
**[ Ctrl ]** + **[ S ]** : copy selected text <br />
**[ Ctrl ]** + **[ X ]** : cut selected text <br />
**[ Ctrl ]** + **[ V ]** : paste selected text <br />
**[ Alt ]** + **[ ↓ ]** : move the whole line down <br />
**[ Alt ]** + **[ ↑ ]** : move the whole line up <br />
**[ Ctrl ]** + **[ ↓ ]** : lock the screen and scroll down <br />
**[ Ctrl ]** + **[ ↑ ]** : lock the screen and scroll up <br />
**[ Ctrl ]** + **[ [ ]** : indentation to the left <br />
**[ Ctrl ]** + **[ ] ]** : indentation to the right <br />
**[ Ctrl ]** + **[ Enter ]** : if inside certain text, skip it, and add a new blank line below it <br />
**[ Ctrl ]** + **[ Shift ]** + **[ Enter ]** : if inside certain text, skip it, and add a new blank line above it <br />
**[ Alt ]** + **[ Z ]** : toggle word wrap, if text is out of the screen, wrap it inside the screen; if text is wrap inside the screen, then unwrap it <br />

**_Visual Studio Code actions management_** <br />
**--- { Z } --- { current action } --- { Y } ---** <br />
**[ Ctrl ]** + **[ Z ]** : revert back the previous (current action) - refer to the timeline above <br />
**[ Ctrl ]** + **[ Y ]** : do back the previous (current action) - refer to the timeline above <br />

**_Visual Studio Code file management_** <br />
**[ Ctrl ]** + **[ S ]** : save the active file <br />
**[ Ctrl ]** + **[ Shift ]** + **[ S ]**: save the active file with desired name <br />
**[ Ctrl ]** + **[ O ]** : open certain file <br />
**[ Ctrl ]** + **[ N ]** : create new file <br />
**[ Ctrl ]** + **[ P ]** : open certain file <br />
**[ Ctrl ]** + **[ Fn ]** + **[ F4 ]** : close certain file <br />
**[ Ctrl ]** + **[ K ]**,  **[ Ctrl ]** + **[ W ]**: close all files <br />

**_Visual Studio Code integrated terminal_** <br />
**[ Ctrl ]** + **[ \` ]** : show integrated terminal (first hit) <br />
**[ Ctrl ]** + **[ \` ]** : hide integrated terminal (second hit) <br />
**[ Ctrl ]** + **[ Shift ]** + **[ \` ]** : open new integrated terminal <br />

**_Visual Studio Code command pallete_** <br />
**[ Ctrl ]** + **[ Shift ]** + **[ P ]** : open the command palette <br />

**_Visual Studio Code window management_** <br />
**[ Ctrl ]** + **[ Shift ]** + **[ P ]** : open Visual Studio Code in new window <br />
**[ Ctrl ]** + **[ Shift ]** + **[ W ]** : close Visual Studio Code whole window <br />
**[ Ctrl ]** + **[ Shift ]** + **[ X ]** : show close Visual Studio Code extensions <br />
**[ Fn ]** + **[ F11 ]** : toggle full screen window <br />
**[ Ctrl ]** + **[ + ]** : zoom in <br />
**[ Ctrl ]** + **[ - ]** : zoom out <br />

**_Visual Studio Code settings management_** <br />
**[ Ctrl ]** + **[ ,]** : open Visual Studio Code user settings <br />
**[ Ctrl ]** + **[ K ]**,  **[ Ctrl ]** + **[ S ]**: open Keyboard Shortcuts <br />

**_Visual Studio Code tabs management_** <br />
**[ Ctrl ]** + **[ K ]**, **[ Ctrl ]** +   **[ ↓ ]** : close current active tab <br />
**[ Ctrl ]** + **[ K ]**, **[ U ]** : close current active tab and save the file <br />
**[ Ctrl ]** + **[ K ]**, **[ W ]** : close all tabs <br />
**[ Ctrl ]** + **[ Tab ]** : switch between open working files <br />

**_Visual Studio Code live server management, need to install Live Server extension by Ritwick Dey_** <br />
**[ Alt ]** + **[ L ]**, **[ Alt ]** +   **[ O ]** : open live server for the current opened file <br />
**[ Alt ]** + **[ L ]**, **[ Alt ]** +   **[ C ]** : close live server for the current opened file <br />

**_Visual Studio Code file and folder management, need to install Create Files & Folders : On The Go by Ritwick Dey_** <br />
**[ Ctrl ]** + **[ Alt ]** + **[ N ]** : create new file <br />
**[ Ctrl ]** + **[ Alt ]** + **[ Shift ]** + **[ N ]** : create new folder <br />
**[ Ctrl ]** + **[ K ]**, **[ F ]** : close the active folder <br />
**[ Ctrl ]** + **[ K ]**, **[ Ctrl ]** + **[ O ]** : open new folder <br />

Official reference for Visual Studio Code shortcuts : https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf

<a name="github"></a>
## 4. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Visual-Studio-Code.git
$ cd Visual-Studio-Code/
$ git remote -v
$ git status
```
