# Portal2Workshop
This repository is used to store the workshop maps of Portal2.

The **p2c** file's path is _**Your steam installation directory**\\steamapps\\common\\Portal 2\\portal2\\puzzles\\**Big number**_

To compile these puzzles, you need to install [the BEE mod](https://github.com/BEEmod/BEE2.4/releases).

It's possible to play the map split-screen if you can't find anyone. To do this;
- Download the map (the **bsp** file) you want.
- Copy **bsp** file into the main maps directory (_**Your steam installation directory**\\steamapps\\common\\Portal 2\\portal2\\maps_)
- Start up Portal 2
- Find a button that you can easily use to switch players (I use z)
- Type in the console: `BindToggle z in_forceuser` and press enter. Obviously the z could be changed in the bind command if you want to use other keys.
- Then type in the console `ss_map xxx.bsp` (_xxx.bsp_ is the file name of the map)
- Once the map is loaded; type in the console `sv_cheats 1`
- Now you're good to go; pressing z will let you change which player you are controlling.

Other ways:  
The first thing you do is go to "Community Test Chambers".  
Then, go to "Create Test Chambers".  
Then, select "New Test Chamber" then click "New" at the bottom of your screen.  
Once you load in, click "File" in the top left.  
Then, select "Cooperative Puzzle".  
From there, click "Build and Play Puzzle" in the top middle of your screen.  
Once it loads in, open up the console (activate it in the "Keyboard and Mouse" part of the options menu in the pause screen) and type in: "changelevel mp_coop_lobby_3" Give it a minute to load, and then your set!  
Just press "R" to change players!  
One other thing: If you want to do the Calibration Course, you have to reopen the console and type in: "changelevel mp_coop_start" Now you know how to do splitscreen Co-op on Steam with 1 player!
