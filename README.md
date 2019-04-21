# VSCode Config

This repository aims to share usefull VSCODE configuration for Frontend, JS, React Developers.


## Extensions
You can see the url and the installation commands:

* Live Share
  - https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare
  - ext install MS-vsliveshare.vsliveshare

* WakaTime
  - https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime
  - ext install WakaTime.vscode-wakatime

* TSLint 
  - https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin
  - ext install ms-vscode.vscode-typescript-tslint-plugin

* Beautify
  - https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify
  - ext install HookyQR.beautify
  
* ESLint
  - https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
  - ext install dbaeumer.vscode-eslint

* JSHint
  - https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint
  - ext install dbaeumer.jshint

* npm
  - https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script
  - ext install eg2.vscode-npm-script

* npm Intellisense
  - https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense
  - ext install christian-kohler.npm-intellisense

* Bracket Pair Colorizer
  - https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer
  - ext install CoenraadS.bracket-pair-colorizer


## Custom keyboard shortcuts

### console.log
If you wanna a shortcut for console.log('') add this config on Files > Preferences > Keyboard Shortcuts > {} symbol on top right.

Paste the following code object there:
~~~~
[
    {
        "key": "ctrl+shift+0",
        "command": "editor.action.insertSnippet",
        "when": "editorTextFocus",
        "args": {
          "snippet": "console.log('${TM_SELECTED_TEXT}$1')$2;"
        }
      }
]
~~~~
You can change the shortcut.
