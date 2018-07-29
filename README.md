# intelliji configuration
This repo contains configuration that I used for intelliji projects.

- [intelliji configuration](#intelliji-configuration)
    - [Code style](#code-style)
    - [Activation of auto-import](#activation-of-auto-import)
    - [Build project automatically](#build-project-automatically)

----
## Code style
To import code style :
-  Open preferences window
-  Go to Editor > Code Style
-  Import the file src/configuration-code_style.xml into the scheme
-  You are now using the tpoi_code_style
-  Click OK to save settings
----
## Activation of auto-import
Default configuration doesn't active auto-import.
To activate : 
-  Open preferences window
-  Go to Editor > General > Auto Import
-  Select "Add unambiguous imports on the fly" and "Optimize imports on the fly (for current project)"
-  Click OK to save settings

![Screenshot](screenshots/auto-import.png)

----
## Build project automatically
Default intelliji configuration doesn't build project automaticaly, to activate : 
-  Open preferences window
-  Go to Build, Execution, Deployement > Compiler
-  Check "Build project automaticaly"
-  Click OK to save settings

![Screenshot](screenshots/build_project_automaticaly.png)