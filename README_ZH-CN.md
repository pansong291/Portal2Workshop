# Portal2Workshop
[English](../README.md) | 中文

这个仓库用来储存 Portal2 的创意工坊地图。  
[它们发布在这里。](https://steamcommunity.com/profiles/76561198391583576/myworkshopfiles/?appid=620)  

要编译这些谜题，对于 **.p2c** 文件，你需要安装 [BEE2](https://github.com/BEEmod/BEE2.4/releases) mod，对于 **.vmf** 文件，需要安装 [Portal 2 Authoring Tools](https://developer.valvesoftware.com/wiki/Authoring_Tools/SDK_(Portal_2))。  

- **.p2c** 文件的路径为 _**你的 Steam 安装目录**\\steamapps\\common\\Portal 2\\portal2\\puzzles\\**一串长数字**_
- **.vmf** 文件的路径为 _**你的 Steam 安装目录**\\steamapps\\common\\Portal 2\\portal2\\maps_

如果你想知道如何使用 **Hammer** 制作 Portal2 地图，请阅读[此系列指南](https://steamcommunity.com/sharedfiles/filedetails/?id=2204608925)。

如果你找不到伙伴，也能够通过分屏模式玩双人地图。操作方法：
- 下载你想要的地图文件（**.bsp** 文件）。
- 复制 **.bsp** 文件到地图主目录下（_**你的 Steam 安装目录**\\steamapps\\common\\Portal 2\\portal2\\maps_）
- 启动 Portal2 并选择 "社区实验室"。
- 选择 "新建实验室" 并点击屏幕下边的 "新建"。
- 加载完后，点击左上角的 "文件"。
- 选择 "合作谜题"。
- 点击屏幕上边中间的 "编译并运行谜题"。
- 加载完后，打开控制台（在屏幕暂停时的 "键盘和鼠标" 选项菜单中启用它）并输入 "**changelevel mp_coop_lobby_3**"（**_mp_coop_lobby_3_** 可以替换成你想游玩的地图名。注意，输入的地图名不包含 **_.bsp_** 后缀）
- 按 "**R**" 键切换玩家。

还有：如果你想玩校准课程，你可以再次打开控制台并输入 "**changelevel mp_coop_start**"，现在你知道了如何单人分屏游玩合作地图了。
