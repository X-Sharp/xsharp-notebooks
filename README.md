# XSharp Notebooks
[English](README.md)|[简体中文](README_CN.md)

Welcome to the home of **X# Notebooks**.  
Get started learning X# with X# notebooks powered by .NET Interactive and VS Code.  
All the Notebooks have been written using the **Core** *dialect* of X#, but don't forget that the full version of X# Language support several xBase Dialects : Visual Objects, Vulcan.NET, xBase++, Harbour, Visual FoxPro and more.  

## How to Install

### Prerequisite
1. Install [.NET 8 for Windows](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
2. Install [Git For Windows](https://git-scm.com/download/win)

### VS Code
1. Install VS Code for [Windows](https://code.visualstudio.com/Download).
2. Install the [C# Dev Kit for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)
3. Install the [Polyglot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) extension.
4. If you want some syntax coloring, Install the [X# Lang](https://marketplace.visualstudio.com/items?itemName=InfomindsAG.xsharp-lang) extension.

### XSharp
1. Install the latest version of [XSharp](https://www.xsharp.eu/itm-downloads?folder=installers).  
2. ~~Download the X# Language Kernel for Polyglot Notebooks, known as [XSharpInteractive](https://github.com/X-Sharp/XSharpInteractive), and follow the [installation instructions](https://github.com/X-Sharp/XSharpInteractive/blob/main/README.md)~~

### Notebooks
1. Download or Clone the repository with the Notebooks.
2. - To clone the repo, you can run VS Code. At start time, in the **welcome page**, click on the *Clone Git Repository...* item
- If you don't see the **welcome page**, press *ctrl* + *shift* + *p* to show the command prompt, type *clone* then select the *Git: Clone* command.
3. Copy/Paste the following URL : https://github.com/X-Sharp/xsharp-notebooks

## How to use it

> Dont forget to look at the [How to start](HowToStart.ipynb) notebook.

After all this, you have a running Visual Studio Code environment for coding with .NET 8, you have the XSharp compiler and Scripting engine installed, ~~you have the XSharp Interactive kernel,~~ and you have finally cloned the Notebooks : You are ready to go !

Open the Folder that contains the Notebooks you are looking for, eg **FirstSteps**.  
Select the Notebook that point to the lesson you are looking for, and follow the instructions the cells.

I hope you will enjoy your journey with **XSharp Interactive** !


| Notebooks | Description| X# Dialect | Level | 
| -------- |--- | ------- |---| 
| [First Steps](./FirstSteps/00-Index.ipynb) | Start learning X# language | Core | Beginner
| [Simple SQL](./SimpleSQL/00-Index.dib) | Using SQLite in your X# Application, and change for MariaDB, PostgreSQL, ... | Core | Intermediate
| [Entity Framework](./EntityFramework/01-01_Introduction.dib) | How to access your DB with an ORM ? Try Entity Framework with X# ! | Core | Intermediate
| [First Steps VFP](./WorkInProgress.ipynb) | Start X# with your VFP background | VFP | Beginner


### License

This repository is licensed under the Apache 2.0.

### Content

The structure and the content of this repository has been inspired by the .NET interactive notebooks for C# and the csharp-101 Notebooks.

These are Copyright (c) .NET Foundation. All rights reserved.

