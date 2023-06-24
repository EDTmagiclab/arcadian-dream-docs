# 弹幕

## 介绍

弹幕游戏（STG）, 又被称为子弹地狱, 是射击游戏的一个子类型，通常有数十到数百个敌弹同屏。东方project是此类游戏中较为著名的例子。

在幻想之梦模组中，弹幕是一个允许您创建子弹图案并在战斗中使用它们的系统。当然，也有敌人使用弹幕来对付你。从某种意义上说，弹幕相当于这个模组的魔法。

## 新手上路

要创造您自己的弹幕, 你需要一些材料. 这些材料的主要来源是模组中的各种敌人。

!!! 提示

    材料的作用可通过标签进行修改


图标  |   材料   | 描述
-----|----------|------------
<img alt="Power Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/power_item.png"/> | P点 | 用于提升弹幕的杀伤力
<img alt="Big Power Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/big_power_item.png"/> | 大型P点 | 用于增加弹幕数量，也用于合成初始弹幕
<img alt="Point Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/point_item.png"/> | 蓝点 | 用于提升弹速
<img alt="Max Point Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/max_point_item.png"/> | 大型蓝点 | 暂无用途
<img alt="Star Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/star_item.png"/> | 星点 | 用于增加子弹的持续时间及合成子弹核心
<img alt="Faith Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/faith_item.png"/> | 信仰点 | 用于修复破损的弹幕
<img alt="Time Orb" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/time_orb.png"/> | 刻符 | 将弹幕冷却时间永久减半

第一步是合成一个子弹核心。每种子弹类型都有一个等效的子弹核心。这些可以在工作台中使用星点制作。

!!! 注意

    每种子弹类型都有自己的基础和最大属性。

图标 | 子弹类型 | 注释
-----|-------------|-----------
![Circle](../images/circle_shot.png) | 小玉 |
![Bubble](../images/bubble_shot.png) | 大玉 | 碰撞箱较大
![Amulet](../images/amulet_shot.png) | 札弹 | 对亡灵生物造成更高的伤害
![Star](../images/star_shot.png) | 星弹 | 无视护甲
![Kunai](../images/kunai_shot.png) | 苦无 | 刺穿敌人
![Pellet](../images/pellet_shot.png) | 点弹 | 密度极高

要将子弹核心变成可用的子弹，您需要一个弹幕工作台

## Danmaku Crafting Table

The Danmaku Crafting Table is a block that allows you to create, repair and modify Shot items.

![Danmaku Crafting Table](../images/danmaku_crafting_table.png)

1. Core
2. Shot
3. Modifier
4. Repair
5. Pattern
6. Color
7. Result

Placing a core in the core slot and a Big Power Item in the modifier slot will result in a Shot item. From there you can place it in the shot slot to repair it using Faith Items in a repair slot or modifying it using other materials and slots.

<figure markdown>
  ![Danmaku Crafting Example](../images/danmaku_crafting_example1.png){width="326"}
  <figcaption>An example of crafting a shot.</figcaption>
</figure>

<figure markdown>
  ![Danmaku Crafting Example](../images/danmaku_crafting_example2.png){width="326"}
  <figcaption>An example of modifying and repairing a shot.</figcaption>
</figure>

## Using Danmaku

After getting your hands on a Shot, you can use it like any other throwable projectile. Keep in mind that the shot's density affects the durability. Shots cannot break, only become unusable until repaired.

There is also a cooldown between shots. Modifying a shot in any way will increase the cooldown, up to a maximum based on the bullet type.

Bullets deal their own type of damage, so they are not affected by things like Projectile Protection. There is a new enchantment called Danmaku Protection that can be applied to armor to reduce the damage taken from bullets.

## Patterns

By default, shots come with the "spread" pattern. This pattern will fire a single bullet in the direction you are looking. If there are multiple bullets in a single shot, they will have divergence applied to them based on the density.

More patterns can be found around the Minecraft world in the form of templates. Once found, a Pattern Template can be crafted into a Bullet Pattern item, which can then be placed in the pattern slot of a Danmaku Crafting Table.

Pattern items can be duplicated using an existing pattern, some materials and a shot.

Icon | Pattern | Location
-----|---------|---------
<img alt="Spread Pattern" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/spread_pattern.png"/> | Spread | Shipwreck
<img alt="Ray Pattern" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/ray_pattern.png"/> | Ray | Pillager Outpost
<img alt="Ring Pattern" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/ring_pattern.png"/> | Ring | Nether Fortress & Abandoned Shrine
<img alt="Arc Pattern" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/arc_pattern.png"/> | Arc | Ancient City
<img alt="Double Pattern" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/double_pattern.png"/> | Double | Mineshaft
<img alt="Triple Pattern" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/triple_pattern.png"/> | Triple | Stronghold

## Cancelling Bullets and Extends

Icon | Item
-----|-----
<img alt="Bomb Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/bomb_item.png"/> | Bomb Item
<img alt="Extend Item" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/extend_item.png"/> | Extend Item
<img alt="Life Fragment" width="16" src="https://raw.githubusercontent.com/Maxmani/arcadian-dream/HEAD/src/main/resources/assets/arcadiandream/textures/item/life_fragment.png"/> | Life Fragment

Bullets that are not your own can be cancelled using a Bomb Item. This removes all nearby bullets and gives you some Star Items in return. Bombs are quite uncommon, so use them wisely.

There is also the Extend Item, which acts as an equipable Totem of Undying. It will cancel bullets similar to a Bomb, but won't give you any Star Items. It also grants temporary invulnerability. It is a rare drop from certain mobs.

Extends can be turned into Life Fragments and vice versa.