# C# Revit Resources

## Developer Essentials

#### [Revit API Documentation NEW](https://apidocs.co/)
> NEW! / BETA - Documentation for all public classes and members.
> <a href="https://github.com/mitevpi/awesome-bim/blob/master/Revit/C%23/Assets/apidocs.png"><img src="https://github.com/mitevpi/awesome-bim/blob/master/Revit/C%23/Assets/apidocs.png" height="400"></a>

#### [Revit API Documentation](http://www.revitapidocs.com/)
> Documentation for all public classes and members.

#### [2019 My First Revit Plug-in](https://knowledge.autodesk.com/support/revit-products/learn-explore/caas/simplecontent/content/my-first-revit-plug-overview.html)
> Comprehensive tutorial for C# Revit development. This should be one's first stop.

#### [Add-In Manager](https://knowledge.autodesk.com/support/revit-products/getting-started/caas/screencast/Main/Details/f62848c4-66fb-4ccd-8d74-0626e80c42d5.html)
> The add-in manager is used for rebuilding assemblies in Visual Studio and running them live without having to restart the Revit instance. Very useful for saving time when testing. Not a replacement for Visual Studio's native debugger.

## Debugging Options

#### [Visual Studio Native Debug Settings](/../../tree/master/IDE/VisualStudio/Assets/visualstudio_debugsettings.png)
> How to configure project properties to use Visual Studio's integrated debugging.
> <a href="https://github.com/mitevpi/awesome-bim/blob/master/IDE/VisualStudio/Assets/visualstudio_debugsettings.png"><img src="https://github.com/mitevpi/awesome-bim/blob/master/IDE/VisualStudio/Assets/visualstudio_debugsettings.png" height="300"></a>

#### [Visual Studio Debug Native Troubleshooting](/../../tree/master/IDE/VisualStudio/Assets/visualstudio_debug_troubleshooting.png)
> Sometimes debugging inexplicably fails when using the Visual Studio native debugger. This is typically due to assemblies being looked for in the wrong places. We can find the source of the problem using FUSLOGVW.exe which is included with the Windows SDK. It logs assembly binding failures, and lets you find the true source of errors.

#### [Revit Python Shell Debugging](https://github.com/mitevpi/awesome-bim/tree/master/Revit/C%23/Assets/csharp_debug_rps.png)
> Since Revit uses IronPython as opposed to CPython (Python 3.X), we can use the [RevitPythonShell](https://github.com/architecture-building-systems/revitpythonshell) to import .NET compiled assemblies. We can interrogate the public members and/or trigger breakpoints set from within Visual Studio, as long as the Revit instance hosting the Python Shell is also launched through Visual Studio's native debugger.
> <a href="https://github.com/mitevpi/awesome-bim/blob/master/Revit/C%23/Assets/csharp_debug_rps.png"><img src="https://github.com/mitevpi/awesome-bim/blob/master/Revit/C%23/Assets/csharp_debug_rps.png" height="400"></a>

#### [Revit Macro Editor Debugging](https://github.com/mitevpi/awesome-bim/tree/master/Revit/C%23/Assets/csharp_debug_macroeditor.png)
> Normally, Revit will lock a file (.dll) which it has referenced. This makes debugging challenging, as Revit constantly has to be restarted in order to actualize a change in the code. Using the Revit Macro Editor can be a way around this, as the Macro Editor lets you reference a compiled .dll, but it does not lock it - instead it copies it to another location, and overwrites on top of that copy when there are changes. This works best for modular code - class libraries, functions, methods, etc. For full add-in/application debugging, the [Add-In Manager](https://knowledge.autodesk.com/support/revit-products/getting-started/caas/screencast/Main/Details/f62848c4-66fb-4ccd-8d74-0626e80c42d5.html) is optimal.
> > <a href="https://github.com/mitevpi/awesome-bim/tree/master/Revit/C%23/Assets/csharp_debug_macroeditor.png"><img src="https://github.com/mitevpi/awesome-bim/tree/master/Revit/C%23/Assets/csharp_debug_macroeditor.png" height="300"></a>


## Community Resources

#### [Jeremy Tammik](http://thebuildingcoder.typepad.com/blog/2018/06/revit-2019-sdk-and-my-first-plugin-update.html#2)
> Blog full of Revit API examples/tutorials.

#### [Danny Bentley](https://www.youtube.com/channel/UC1Dx-jGyRbvvHzZ8ZyGWF5w/videos?disable_polymer=1)
> Large collection of Revit API videos.

#### [Archi-Lab](http://archi-lab.net/create-your-own-tab-and-buttons-in-revit/)
> Revit API tutorials.



## Code Snippets & Examples

#### [Revit API TutorialBook Snippets](https://github.com/mitevpi/revit-api-snippets)
> Revit API snippets translated from a tutorial book originally in Chinese.

#### [RevitAPI Docs Snippets](http://www.revitapidocs.com/code/)
> Revit API Docs also houses code samples as well as documentation.
