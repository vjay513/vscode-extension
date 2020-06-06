# vscode-extension
Building extension in vscode

you have Node.js and Git installed, then install Yeoman and VS Code Extension Generator with

```npm install -g yo generator-code```

The generator scaffolds a TypeScript or JavaScript project ready for development. Run the generator and fill out a few fields for a TypeScript project:

```yo code```

##### What type of extension do you want to create? New Extension (TypeScript)
#####  What's the name of your extension? HelloWorld
##### Press <Enter> to choose default for all options below #####

#####  What's the identifier of your extension? helloworld
#####  What's the description of your extension? LEAVE BLANK
#####  Initialize a git repository? Yes
#####  Which package manager to use? npm

```code ./helloworld```

To start editing with Visual Studio Code, use the following commands:

     cd console-cleaner
     code .

Open vsc-extension-quickstart.md inside the new extension for further instructions
on how to modify, test and publish your extension.

For more information, also visit http://code.visualstudio.com and follow us @code.


## Publishing Extensions

you can package an extension into the installable VSIX format and share it with other users.

- Using vsce, the CLI tool for managing VS Code extensions
- Packaging, publishing and unpublishing extensions
- Registering a publisherId necessary for publishing extensions

## vsce
vsce, short for "Visual Studio Code Extensions", is a command-line tool for packaging, publishing and managing VS Code extensions.

### Installation
Make sure you have Node.js installed. Then run:

```npm install -g vsce```

### Usage
You can use vsce to easily package and publish your extensions:

```$ cd myExtension
$ vsce package
# myExtension.vsix generated
$ vsce publish
# <publisherID>.myExtension published to VS Code MarketPlace
```

vsce can also search, retrieve metadata, and unpublish extensions. 

For a reference on all the available vsce commands, ```run vsce --help```.

### Publishing extensions

