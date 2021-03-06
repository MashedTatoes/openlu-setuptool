# openlu-setuptool
Tool to help with setup of [OpenLU](https://github.com/MashedTatoes/OpenLU)  
Credit to [lcdr](https://github.com/lcdr) for making their [Lego Universe utils](https://github.com/lcdr/utils)

## Pre-requisties:
* Python 3.7
* [OpenLU](https://github.com/MashedTatoes/OpenLU)
* [Lego Universe unpacked client](https://docs.google.com/document/d/1XmHXWuUQqzUIOcv6SVVjaNBm4bFg9lnW4Pk1pllimEg/edit) (humanoid/lcdr’s unpacked client reccomended):
* [MySql](https://dev.mysql.com/downloads/mysql/) 
     * *Only if actually using MySql for your database, otherwise use sqlite, which has no pre requisite*



### Use
* Uses no external libaries so only Python 3.7 is needed
* In root directory:
    * `python __main__.py`
    * Follow the steps 
      * *very* intuitive, I know
* *OSX/Linux* 
   * Go to OpenLU.DBContext, open up command line and type
        * `dotnet ef migrations add Initial --context BaseContext`
        * `dotnet ef database update --context BaseContext`
* *Windows*
    * Go to OpenLU.DBContext, open up command line and run initial.bat
