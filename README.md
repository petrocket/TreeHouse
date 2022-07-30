
Source installation information for modders
-------------------------------------------
This code follows the Minecraft Forge installation methodology. It will apply
some small patches to the vanilla MCP source code, giving you and it access 
to some of the data and functions you need to build a successful mod.

Note also that the patches are built against "un-renamed" MCP source code (aka
SRG Names) - this means that you will not be able to read them directly against
normal code.

Setup Process:
==============================

1. Install 64bit OpenJDK 17 from Microsoft https://docs.microsoft.com/en-us/java/openjdk/download - make sure to select the option to add to PATH and set the JAVA_HOME environment variable
1. Install Visual Studio Code https://code.visualstudio.com/download
1. Clone this repository `git clone https://github.com/petrocket/treehouse`
1. Open Visual Studio Code and install the Extension Pack for Java
1. In Visual Studio Code, open the folder where you cloned this repository
1. After a bit VS Code will finish opening the Java project - it downloads dependencies
1. Open a bash terminal in VS Code and run `./gradelw genVSCodeRuns` which will create VS Code run and debug settings so you can run and debug the client or server

Additional Resources: 
=========================
Community Documentation: https://mcforge.readthedocs.io/en/latest/gettingstarted/  
LexManos' Install Video: https://www.youtube.com/watch?v=8VEdtQLuLO0  
Forge Forum: https://forums.minecraftforge.net/  
Forge Discord: https://discord.gg/UvedJ9m  
