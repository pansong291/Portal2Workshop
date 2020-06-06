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
