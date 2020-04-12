# Nord Nights

Dark theme based on Nord, with an all black background and extra consideration for PowerShell syntax highlighting. Incorporates the Windows Terminal "One Half Dark" theme for the integrated terminal.

Available on VS Code [Marketplace](https://marketplace.visualstudio.com/items?itemName=WillT.nord-nights)

## Installation

To install this extension, download the _nord-nights.vsix_ file to your computer and then start VS code with the following command `code --install-extension nord-nights.vsix`

## Build from code

To build yourself, install node.jsm npm and git, then clone the repo and make any changes you want to `themes/Nord Nights-color-theme.json`. Test by copying the root folder to your VS Code extensions folder (typically `~/.vscode/extensions/`) and restarting VS Code. You can then make any changes you like/need to `packages.json` in the extension root folder. Once done, run the following commands:

```powershell
npm install -g yo generator-code
npm install -g vsce
vsce package
```

You should then get a fresh copy of the VSIX file to distribute. If you wish to publish to the extensions marketplace, you will need to generate a PAT for Azure DevOps and follow the [instructions here](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#publishing-extensions).
