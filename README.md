# Minecraft-Traptrix-Adv
蟲惑魔冒險包

一個使用了各種材質和資料包製作的冒險包



## 使用的資料包：
- 使用的資料包和材質包大部份非原創。但是為了確保運行正常，我修改了部份資料包的mcfunction，因此會和原版有差異，並且會提供原版連結。

### traptrix_spawn_1.20.1
自製的核心部件，使主世界會生成落穴，並且能從中找到隨機的蟲惑魔生怪蛋。<br>
使用MobTamer馴服她們，並帶著她們冒險。<br>
#### 功能：
- 對骨弓丟1個銅方塊將其靜音(會消耗)
- 對盔甲架丟pet蛋可以把她們變成裝飾放在地上，對她們丟盔甲架回收蛋
- 對丟失mt.id 的 pet丟木棍，可以讓其重新把5格內的玩家認主。
- 每得到1種蟲惑魔的蛋，就會增加40cost(40*16=640)，用來增加pet的上限

#### 蟲惑魔合成台：
- 所有蟲惑魔腳下的發射器方塊會自動視為「蟲惑魔合成台」，可以把物品放進發射器中進行合成。

#### 隨機裝備：
- 在合成台用１金蘋果＋４銅方塊合成隨機裝備
- 可以通過隨機裝備得到帶有「蟲惑魔」特性的護甲，穿戴這種裝備的玩家不會受到陷阱影響

#### 蟲惑魔弓：
- 發射時25%機會不發射箭，改為放置陷阱。
- 可以在蟲惑魔合成台用弓、金蘋果、藤蔓和蜘蛛眼合成。

| 藤蔓 | 蜘蛛眼 | 藤蔓 |
| :----: | :----: | :----: |
| 藤蔓 | 弓 | 藤蔓 |
| 藤蔓 | 金蘋果 | 藤蔓 |

- 可以通過和升級材料合成進行強化。

| 空 | 材料 | 空 |
| :----: | :----: | :----: |
| 空 | 弓 | 空 |
| 空 | 材料 | 空 |

##### 強化材料及其效果：
- 絆線鉤＝＞放置機率：1-4，每級增加25%機率放置陷阱，提升到４級＝１００％放置陷阱
- 螢石粉＝＞效果等級：1-6
- 紅石粉＝＞緩速等級：1-6，每級增加5秒持續時間
##### 陷阱效果：
- 蜘蛛眼＝＞0傷害：每級給予2傷害
- 毒馬鈴薯＝＞1中毒：給予中毒１，每級增加5秒持續時間
- 凋零骷髏頭＝＞2凋零：給予凋零１，每級增加5秒持續時間
- 火焰彈＝＞3點燃：使生物燃燒，每級給予Fire + 140
- 粉雪桶＝＞4冷凍：使生物冷凍，每級給予TicksFrozen + 140
- 發酵蜘蛛眼＝＞5虛弱：給予虛弱１，每級增加5秒持續時間







<br>
<br>

### MobTamer_For1-20_v1-0-2_en_edit5
修改版的MobTamer，主要是使其適配traptrix_spawn<br>
原版連結：<br>
https://github.com/Keeema-1/MobTamer/wiki/Home_EN

### bck-Super Enchants plus_v2
經修改的增強版Super Enchants<br>
增加了從工具中提取附魔書的功能（會摧毀掉工具）<br>
另外支援MobTamer（使裝備適合tamer pet使用）<br>
原版連結(1.2)：<br>
https://modrinth.com/datapack/super-enchants


## 材質包：（需要OptiFine）

### TraptrixGirl (1.18.2+)v4<br>
提供蟲惑魔材質和音效<br>
需要配合traptrix_spawn才能運作<br>
材質來源：<br>
https://www.minecraftskins.com/profile/4288357/fullviking0

### UnobtrusiveArmors-2-2<br>
使裝備的面積減少
https://modrinth.com/resourcepack/unobtrusive-armor/versions


## 其他可選的資料包：

### Multitool<br>
多用途工具，減少切換工具的時間<br>
https://modrinth.com/datapack/multitool/version/4.1.2

### recipe_shulkerbox<br>
可以用皮革＋箱子合成潜影盒，給玩家用作冒險背包<br>

### ore-detector-datapack<br>
幫助玩家找尋礦物<br>
https://www.planetminecraft.com/data-pack/minecraft-but-i-have-ore-detector/



