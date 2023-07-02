# DDE CFront C++ code for RISC OS DDT friendly

This simple code example shows how to write CFront C++ for RISC OS in a way that is friendly and easy to debug using DDt (DesktopDebugger Tool).

This code has been written to show how to use private members in C++ and how to debug them using DDT debugger.

## How to build the code

Ensure you have a copy of DDE suite installed on your RISC OS system and that RISC OS Desktop Filer has seen it (specifically !SetPaths).

Git clone this repository in a way that can be reached by your RISC OS system, if you do not know how to do this have a look at [this set of videos](https://www.youtube.com/playlist?list=PLEnraaJ9VQfWDl5T4D0P51pG89KRzj0n1) on the matter that can help you to find the best approach for you to use git with your RISC OS.

Then, from your RISC OS system, double click on the file called MkDDE or mkDDEDebug (to generate the "debuggable" executable) have a look at the sources in the subdirectory `c++` and `h`.

For a full description of how the code works (or see the techniques used to debug private member variables) have a look at this video [here](https://youtu.be/H54uwru9G5k)

Enjoy!
