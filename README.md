# Portal2Workshop
English | [中文](README_ZH-CN.md)

This repository is used to store the workshop maps of Portal 2.  
[They are published here.](https://steamcommunity.com/profiles/76561198391583576/myworkshopfiles/?appid=620)  

To compile these puzzles, you need to install the [BEE 2](https://github.com/BEEmod/BEE2.4/releases) mod for the **.p2c** files, the [Portal 2 Authoring Tools](https://developer.valvesoftware.com/wiki/Authoring_Tools/SDK_(Portal_2)) for the **.vmf** files.  

- The **.p2c** file's path is _**Your steam installation directory**\\steamapps\\common\\Portal 2\\portal2\\puzzles\\**BigNumber**_
- The **.vmf** file's path is _**Your steam installation directory**\\steamapps\\common\\Portal 2\\portal2\\maps_

If you want to know how to use **Hammer** to make a Portal 2 map, please read [these series of guides](https://steamcommunity.com/sharedfiles/filedetails/?id=2204608925).

It's possible to play the map split-screen if you can't find anyone. To do this;
- Download the map (the **.bsp** file) you want.
- Copy **.bsp** file into the main maps directory (_**Your steam installation directory**\\steamapps\\common\\Portal 2\\portal2\\maps_)
- Start up Portal 2 and go to "Community Test Chambers".
- Select "New Test Chamber" then click "New" at the bottom of your screen.
- Once you load in, click "File" in the top left.
- Select "Cooperative Puzzle".
- Click "Build and Play Puzzle" in the top middle of your screen.
- Once it loads in, open up the console (activate it in the "Keyboard and Mouse" part of the options menu in the pause screen) and type in: "**changelevel mp_coop_lobby_3**" (the **_mp_coop_lobby_3_** can be replaced by any map you want to play. _NB._ The typed map name does not have the **_.bsp_** suffix) Give it a minute to load, and then your set!
- Just press "**R**" to change players!
 
One other thing: If you want to do the Calibration Course, you have to reopen the console and type in: "**changelevel mp_coop_start**" Now you know how to do splitscreen Co-op on Steam with 1 player!
