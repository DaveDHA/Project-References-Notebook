# Project References Notebook

A Polyglot Notebook for examining project references in a .Net solution.

## Prerequisites

You will need [Visual Studio Code](https://code.visualstudio.com/download) with the [Polyglot Notebooks Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) installed.

## Instructions

1. Under the **Configuration** section, edit the `slnFolder` to the absolute path of the folder containing your solution.  
2. Under the **Configuration** section, edit the `samplePath` to choose a specific project that will be used by the type provider to examine the project XML. Choose a good sample project with a robust project file that at least includes some project references, or the type provider won't be able to parse your projects.
3. Run all cells in the **Configuration** and **Setting Up** sections.
4. In the **Viewing Project Reference Information** section, run the cells you are interested in.  You may need to edit some project names to view projects you are interested in.  Project names are case-sensitive, so you may want to copy-paste from **A list of all projects under the solution folder**.

The diagram under **All Project References in the solution** gets pretty rough for large projects.  Looking at specific projects will likely be must more useful.

If you switch to a different `slnFolder`, it is best to `Restart` the notebook to make sure that the type provider is refreshed.