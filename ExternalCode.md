# Run external code ?

In a standard Dotnet Interactive Notebook, you can use the `#!import` magic command, to load an run some code that is stored in a file.

The trouble is that the file must contain code that is known by the original Dotnet Interactive, and the call to the right execution engine is based on the file extension :  
- .cs file will run using the C# engine
- .ps1 file will run using the Powershell engine  
etc

Unfortunatly, XSharp code is stored in a .prg file, that the `#!import` magic command will not recognize.

# Workaround

But ... Dotnet Interactive is able to `#!import` an external Notebook !! :)

So, the solution is to put your external code into a Notebook (either .ipynb or .dib).
In this Notebook, add some code cells. Maybe one cell in csharp script to load the XSharpInteractive engine, then another cell with all your XSharp code.

Then, in your current Notebook you can write :  

    #!import pathToYour/NotebookToImport.dib
And below the ***new*** code that can use the elements you have defined in the *imported* Notebook.

Imagine:  
you can have your classes definitions in some external Notebook, and use it in your current Notebook.
