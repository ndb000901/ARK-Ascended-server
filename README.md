# 方舟飞升服务器

# 参考资料

[Server_configuration](https://ark.wiki.gg/wiki/Server_configuration)

[]()


----


# 服务器搭建

## 1. 瓦尔(Valguero)

### 1.1 下载服务器

```bash
steamcmd +force_install_dir D:\ark2\servers\valguero +login anonymous +app_update 2430930 +quit validate
```

### 1.2 启动服务器

```bash

start "valguero" /normal "D:\ark2\servers\valguero\ShooterGame\Binaries\Win64\ArkAscendedServer.exe" Valguero_WP?listen?MultiHome=192.168.43.240?Port=7777?QueryPort=27015?MaxPlayers=10?AllowCrateSpawnsOnTopOfStructures=True -ForceAllowCaveFlyers -clusterid=wuhen-ark -ClusterDirOverride="D:\ark2\cluster" -NoBattlEye -servergamelog -nosteamclient -game -server -log -MinimumTimeBetweenInventoryRetrieval=3600 -automanagedmods -mods=929420,947033,929868,950914,929578,929110,940975,947835,1006355,933447,1005095,932365,928641,940338,928650,1123495,935408,930347,1222937,955623,912902,900062,914844,926259,916922,926956,927131,928501,932822
```

## 2. 灭绝(Extinction_WP)

### 2.1 安装服务器文件

```bash
steamcmd +force_install_dir D:\ark2\servers\extinction +login anonymous +app_update 2430930 +quit validate
```

### 2.2 启动服务器

```bash

start "extinction" /normal "D:\ark2\servers\extinction\ShooterGame\Binaries\Win64\ArkAscendedServer.exe" Extinction_WP?listen?MultiHome=192.168.43.240?Port=7778?QueryPort=27016?MaxPlayers=10?AllowCrateSpawnsOnTopOfStructures=True -ForceAllowCaveFlyers -clusterid=wuhen-ark -ClusterDirOverride="D:\ark2\cluster" -NoBattlEye -servergamelog -nosteamclient -game -server -log -MinimumTimeBetweenInventoryRetrieval=3600 -automanagedmods -mods=929420,947033,929868,950914,929578,929110,940975,947835,1006355,933447,1005095,932365,928641,940338,928650,1123495,935408,930347,1222937,955623,912902,900062,914844,926259,916922,926956,927131,928501
```


# 3. mod

## mod

```
Super Spyglass Plus 929420
Awesome Spyglass!  947033
Admin Panel  929868
Awesome Teleporters!  950914
AP: Death Recovery [Cross-platform]  929578
TG Stacking Mod 10000-90  929110
Cybers Structures QoL+ (Crossplay)  940975
human 947835 (需要强制刷新野生龙)
Chain Link Fence Skins 1006355
Alfa Oceanic Platforms 933447
Custom Cosmetic: Novabeast  1005095 (服务器去掉，客户端安装即可)
Resource Gatherers  932365 (需要配置下，只生产基础资源，不然降低游戏乐趣)
HK cryopod and Cryofridge 928641
RR-Potions 940338
Potions | Gaia Studios 928650
Dino Upgrade Potions! 1123495
Der Dino Finder  935408
Legacy Meat Spoiler 930347
Map Unlocker 1222937
Mining Drill (Cross-Platform)  955623
Additions Ascended: Deinosuchus 912902
Additions Ascended: Ceratosaurus 900062
Additions Ascended: Deinotherium 914844
Additions Ascended: Acrocanthosaurus 926259
Additions Ascended: Helicoprion 916922
Additions Ascended: Archelon 926956
Additions Ascended: Brachiosaurus 927131
Solo Farm Mod 928501
Net Projectile 932822 (有bug)
Net Pro 1019389

```


# 4、配置



# 5.mod配置

## 5.1 Resource Gatherers(932365) 配置


```ini

```
