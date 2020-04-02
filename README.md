# Visual-Studio-Code
My works related to Visual Studio Code.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Visual Studio Code developers.](#developers)
4. [Visual Studio Code shortcuts.](#shortcuts)
5. [Using code command in Command Prompt.](#code) 
6. [Selecting Google Chrome as default live server.](#liveserver)
7. [Selecting Git Bash in integrated terminal.](#gitbash)
8. [GitHub notes.](#github)
9. [GitHub repository calculation.](#calculation)

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

**_Visual Studio Code questions and answers_** <br />
Stack Overflow official website : https://stackoverflow.com <br />

**_Visual Studio Code documentation by code.visualstudio.com_** <br />
Emmet in Visual Studio Code by code.visualstudio.com : https://code.visualstudio.com/docs/editor/emmet <br />
Accessibility by code.visualstudio.com : https://code.visualstudio.com/docs/editor/accessibility <br />
Debugging by code.visualstudio.com : https://code.visualstudio.com/docs/editor/debugging <br />

**_Visual Studio Code marketplace_** <br />
React-Native/React/Redux snippets for es6/es7 version Standard : https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux-snippets-for-es6-es7-version-standard <br />

**_Visual Studio Code extensions_** <br />
Create Files & Folders : On The Go by Ritwick Dey : https://marketplace.visualstudio.com/items?itemName=ritwickdey.create-file-folder <br />
Live Server by Ritwick Dey : https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer <br />
DupChecker by Jianbing Fang : https://marketplace.visualstudio.com/items?itemName=jianbingfang.dupchecker <br />

**_Visual Studio Code related articles_** <br />
code . is not recognized as an internal or external command by Stack Overflow : https://stackoverflow.com/questions/46638944/code-is-not-recognized-as-an-internal-or-external-command <br />

**_Visual Studio Code questions and answers by Stack Overflow_**
How to change default browser with VS Code's “open with live server”? by Stack Overflow : https://stackoverflow.com/questions/49289233/how-to-change-default-browser-with-vs-codes-open-with-live-server/51580183 <br />
How do I use Bash on Windows from the Visual Studio Code integrated terminal? : https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal <br />

<a name="developers"></a>
## 3. Visual Studio Code developers.
Jianbing Fang : https://github.com/jianbingfang <br />
Ritwick Dey : https://github.com/ritwickdey, https://twitter.com/dey_ritwick <br />

<a name="shortcuts"></a>
## 4. Visual Studio Code shortcuts.
**_Visual Studio Code EXPLORER bar_** <br />
**[ Ctrl ]** + **[ B ]** : hide the EXPLORER bar (first hit) <br />
**[ Ctrl ]** + **[ B ]** : show the EXPLORER bar (second hit) <br />
**[ Ctrl ]** + **[ Shift ]** + **[ E ]** : show the EXPLORER bar <br />
**[ Ctrl ]** + **[ Shift ]** + **[ X ]** : show extensions menu <br />
**[ Fn ]** + **[ F2 ]** : rename the file <br />

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
**[ Fn ]** + **[ F2 ]** : rename symbol <br />

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

**_Visual Studio Code keyboard management_** <br />
**[ Ctrl ]** + **[ K ]**, **[ Ctrl ]** + **[ S ]** : open Keyboard Shortcuts menu <br />

**_Visual Studio Code Prettier formatter_** <br />
**[ Shift ]** + **[ Alt ]** + **[ F ]** : format document <br />

**_Visual Studio references_** <br />
**[ Shift ]** + **[ Fn ]** + **[ Alt ]** + **[ F12 ]** : find all references <br />

Official reference for Visual Studio Code shortcuts : https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf

<a name="code"></a>
## 5. Using code command in Command Prompt.
To use code command in Command Prompt, you need to add `C:\Users\username\AppData\Local\Programs\Microsoft VS Code\bin` into the windows environment PATH, follow this instructions. On the right hand side of **[ ⊞ ]**, type `edit environment` and then **[ Mouse Left Click ]** the shown text `edit environment variables for your account`, **Environment Variables** menu will appear, press **[ P ]**, make sure the `Path` is highlighted on the screen, then press **[ Tab ]**, **[ E ]**,**[ Tab ]**, **[ N ]**, and then type `C:\Users\username\AppData\Local\Programs\Microsoft VS Code\bin`, then press **[ Enter ]**, **[ Enter ]**, **[ Enter ]**.

Press **[ ⊞ ]** + **[ R ]**, then press **[ C ]**, **[ M ]**, **[ D ]**, **[ Ctrl ]** + **[ Shift ]** + **[ Enter ]**, **[ ← ]**, **[ Enter ]**. Press **[ C ]**, **[ O ]**, **[ D ]**, **[ E ]**, **[ Enter ]**, to test whether the code command in Command Prompt is working or not using the window operating system.

<a name="liveserver"></a>
## 6. Selecting Google Chrome as default live server.
Press **[ Ctrl ]** + **[ , ]**, on the text box that shown `Search settings`, type `live server` and wait for the **live server** menu to appear on the screen. Find the text `Live Server > Settings: Custom Browser`, under its combo box, **[ Mouse Left Click ]** the `v` symbol and then select `chrome`.

On the open `index.html` file, press **[ Alt ]** + **[ L ]**, **[ Alt ]** + **[ O ]** to test whether the selected browser is opening on the screen or not.

<a name="gitbash"></a>
## 7. Selecting Git Bash in integrated terminal.
To select Git Bash using Visual Studio code, press **[ Ctrl ]** + **[ Shift ]** + **[ P ]** on your keyboard, then type `Terminal: Select Default Shell` and press **[ Enter ]** on your keyboard. From the selection menu, **[ Mouse Left Click ]** on `Git Bash` text. Then press **[ Ctrl ]** + **[ \` ]** to open the integrated Visual Studio Code terminal. on the right upper most of the integrated terminal menu combo box, click on `+` symbol, and then **[ Mouse Left Click ]** on the `v` symbol on the combo box and then from the selection show, **[ Mouse Left Click ]** the text `<number:> bash`, to make the bash terminal active on the screen.

<a name="github"></a>
## 8. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Visual-Studio-Code.git
$ cd Visual-Studio-Code/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 9. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1             15              0             82
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
