# 家国梦数值模拟器

用于计算已有卡牌的最佳组合的模拟器！

## 使用
1. 下载simulator文件夹，打开其中的simulator.html。（请使用chrome浏览器）
2. 按照自己的数据，修改config.json，或者直接在网页上修改。
3. 点击开始计算。

## 说明
1. 目前模拟器仅支持0-620级建筑模拟，欢迎大家提供620级以上的数据，或自行修改config.json文件内的levelGain变量,此变量为“一星”基础建筑（如木屋等无加成建筑），每10级的基础收益值。如建筑超过一星，需要除以星级加成（2星除2，3星除6，4星除24，5星除120）

2. 后续可能会更新建筑升级花费及最佳升级路线。
3. 由于是暴力穷居，点击开始计算后可能会很慢，请泡碗面慢慢等待。
