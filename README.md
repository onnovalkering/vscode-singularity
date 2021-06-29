[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/onnovalkering.vscode-singularity)](https://marketplace.visualstudio.com/items?itemName=onnovalkering.vscode-singularity)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/onnovalkering.vscode-singularity)](https://marketplace.visualstudio.com/items?itemName=onnovalkering.vscode-singularity)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/onnovalkering.vscode-singularity)](https://marketplace.visualstudio.com/items?itemName=onnovalkering.vscode-singularity)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/onnovalkering.vscode-singularity)](https://marketplace.visualstudio.com/items?itemName=onnovalkering.vscode-singularity)

# Singularity support for Visual Studio Code

This extension provides syntax highlighting for Singularity definition files.

## GitHub
Syntax highlighting of Singularity definition files on GitHub is also based on this extension. 
Currently, only files that have `Singularity` as the exact file name are recognized. 
To recognize other files, e.g., `Singularity.*` and `*.def`, a `.gitattribute` file with additional rules/patterns can be added to GitHub repositories ([example](https://github.com/onnovalkering/vscode-singularity/blob/master/.gitattributes)).

## Preview

<img src="https://raw.githubusercontent.com/onnovalkering/vscode-singularity/master/images/preview.png" alt="preview" width="900"/>

## Acknowledgements
The `interpolation`, `keyword`, `string`, and `variable` patterns (Bash) originate from [microsoft/vscode](https://github.com/microsoft/vscode).