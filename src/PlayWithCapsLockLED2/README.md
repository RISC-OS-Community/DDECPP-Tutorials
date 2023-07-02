# Playing with CapsLock LED in Acorn/ROOL DDE CFront C++ on RISC OS (DDT friendly version)

This simple code example shows how to use RISC OS SWIs (SysCalls) in DDE CFront C++.

This version of the code is written to be DDT friendly, that is, it can be debugged using the DDT debugger.

## How to build the code

Ensure you have a copy of DDE suite installed on your RISC OS system and that RISC OS Desktop Filer has seen it (specifically !SetPaths).

Git clone this repository in a way that can be reached by your RISC OS system, if you do not know how to do this have a look at [this set of videos](https://www.youtube.com/playlist?list=PLEnraaJ9VQfWDl5T4D0P51pG89KRzj0n1) on the matter that can help you to find the best approach for you to use git with your RISC OS.

Then, from your RISC OS system, double click on the file called MkDDE or have a look at the sources in the subdirectory names `c++`.

For a full description of how the code works have a look at this video [here](https://www.youtube.com/watch?v=bK-Na5LBWtY)

For the full description on how to use this example with DDT have a look at this video [here](https://youtu.be/H54uwru9G5k)

Enjoy!
