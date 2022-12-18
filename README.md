# IcefrostPeglin
这是一个哥布林弹珠的模组，只需要将所有文件放入游戏源文件内即可使用。

## 更新内容

### 效果
<details>
<summary>详细内容</summary>

* 增加3个效果

  * 护盾：抵挡相同层数的伤害，重新装填时清空层数。

  * 复生：每回合恢复相当于层数的生命，层数减1。

  * 血仇：每回合增加相当于层数的伤害并对自己造成相同层数伤害并清空层数，效果持续一回合。


* 已有效果更改

  * 致盲：生效后层数减半。
</details>

### 机制（必看）

<details>
<summary>详细内容</summary>

* 可以储存弹珠，需要单击右键，跳过弹珠改为长按右键。

  * 弹珠在存储时会有额外的效果

  * 带有重复效果的弹珠在储存后重新射出会有一个显示bug，只要再次储存收回更新一下就没事了，目前只会影响衔尾弹珠。

* 增加休息处，可以回血或升级弹珠

  * 特定遗物可以增加休息处的功能

  * boss战前必有休息处。
  
* 增加药水类型弹珠。
</details>

### 弹珠

<details>
<summary>详细内容</summary>

* 在自定义模式的弹珠选择界面不会显示已有弹珠的修改，但在游戏内会显示。

* 新增弹珠。
  
  * 碎石弹珠 ：会随碰撞变小分裂，分裂出的弹珠在碰撞后消失。
  
  * 激光弹珠 ：多个弹珠互相发射激光，触发沿途的钉子，攻击整排敌人，视作三次攻击。

  * 药水弹珠 ：会在战后奖励和商店出现。固定50金币，不可升级，使用后移除。部分药水弹珠有持续效果，最多同时生效3个。

* 修改9个弹珠

  * 吸血弹珠：治疗量不可超过生命上限的30%/60%。（一级为30%，二/三级为60%）
  
  * 滚石弹珠：当这颗弹珠被射出时，获得2/4/6层护盾。
  
  * 石头：三级时，当这颗弹珠被跳过时，获得5层护盾。
  
  * 方尖弹珠 ：伤害恒为0，这颗弹珠被储存时，射出的石头/滚石弹珠/碎石弹珠会因你的石头/滚石弹珠/碎石弹珠数量而获得护盾。
  
  * 套娃弹珠 ：当这颗弹珠被储存时，你当前弹珠获得分裂1/2层。（二级为1，三级为2）
  
  * 以太弹珠 ：当这颗弹珠被储存时，你当前弹珠掉出版面时刷新。
  
  * 闪电弹珠 ：当这颗弹珠被储存时，你当前弹珠会溅射1/2/3次。
  
  * 血祭弹珠 ：效果最多生效3/6/9次。
  
  * 减震弹珠 ：每个效果最多触发3/6/9次。
</details>  
  
### 遗物

<details>
<summary>详细内容</summary>

* 新增遗物

  * 幸运猫 ：弹珠选择增加1个，有7%%的概率在战斗结束后获得礼物盒。
  
  * 风铃 ：重新装填获得一层绝技。
  
  * 未烬之残烛 ：增加两个休息处。
  
  * 史莱姆精华 ：休息处治疗量变为25%。
  
  * 放大镜 ：弹珠变得更大。
  
  * 巴西果 ：你的弹珠将按等级从低到高排列。

  * 等离子球 ：击中钉子11下后最多溅射7次。
  
  * 聚集的星尘 ：进入休息处时获得牌库内弹珠数量的最大血量并失去5倍该数量的血量，该效果致死时不会生效。
  
  * 秋叶 ：你可以在休息处删除弹珠。
  
  * 无害手环 ：增加两个精英敌人，所有精英敌人的生命值翻倍。
  
  * 古树枝 ：可以在休息处选择2个操作。
  
  * 黄水晶 ：战后可获得的弹珠在原有基础上升一级，获得所需要的金币翻倍。
  
  * 黄金像 ：休息处的操作可以多次进行，需要额外金币。
  
* 新增商店类型遗物

  * 黄金矿工 ：你可以在休息处开采黄金，这会给你带来25-75个金币。
  
  * 铲子 ：你可以在休息处挖掘遗物，最多3次。
  
  * 存钱罐 ：可以在休息处投资十元，每投资十元就在战斗后获得一个金币。
  
  * 哈布林的金币 ：增加两个商店。
  
* 修改遗物

  * 全熟牛排 ：重装获得三层复生。
  
  * 杀戮尖刺 ：重新装填后的第一个弹珠 +2/ +0
  
  * 笨钟 ：重新装填获得一层强劲。
  
  * 炸弹指挥棒 ：炸弹数量增加2个。
  
  * 曲奇饼 ：一个弹珠最多生效10次。
  
  * 精明天平 ：生命值高于50%时每回合获得一层血仇，低于50%时获得一层复生，等于50%时每次重装获得一层圆满。
</details>


# 新机制

## 储存

可以储存弹珠，需要单击右键，跳过弹珠改为长按右键。
部分弹珠在储存后会有显示bug，再次储存就可以解决。

## 休息处

<details>
<summary>行动</summary>

 * 治疗
 
 * 锻造
 
 * 开掘
 
 * 遗忘
 
 * 开采
 
 * 投资
 
</details>
 
一种特殊的房间，允许你进行最上面的两个行动，拥有特定遗物后会有更多选择。
一般情况下，只能行动一次。

## 药水

<details>
<summary>药水种类</summary>

 * 贪婪药水
 
 * 暴击药水
 
 * 狂暴药水
 
 * 复制药水
 
 * 铁甲药水
 
 </details>
 
一种特殊的弹珠，只能使用一次，费用固定为50。
在发射后生效，不会消耗发射次数，一回合可以使用多瓶药水，持续性药水最多同时生效3瓶。
