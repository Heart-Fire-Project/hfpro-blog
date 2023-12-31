---
title: "午夜灵魂：开发者日志 #1"
date: 2023-09-15
tags: 
- 开发者日志
- 更新日志
- 午夜灵魂
categories: 
- 开发者日志
---

# 序言

经过上次测试后，我们发现了一些影响地图体验的问题，在最新的版本中，我们新增和移除了部分内容，从而使对局更加具有对抗性。

# 灵魂宝物系统

经过开发组内部讨论，我们认为**柜子**机制虽然能起到躲藏效果，但大多数情况下，此机制会拖慢游戏进度，因此，我们新增了一种类似于**道具**的新系统，地图中会在随机点位刷新**淡灰色潜影盒**外形的灵魂宝物箱，灵魂方玩家可以通过**保持蹲下**从而获取灵魂宝物，而灵魂守卫者玩家则可以通过**保持蹲下**来移除此灵魂宝物箱并高亮距离自身最远的玩家，同时获得短暂的加速效果。

| 地图名称 | 刷新数量 |
| -------- | -------- |
| 聚光圣殿 | 12       |
| 镇灵塔楼 | 6        |
| 山间湖谷 | 32       |

# 随机点位

为解决背点、守点和游戏过于枯燥问题，我们为每张地图增加了更多的灵魂碎片点位，现在每张地图会刷新**多于**需要收集数量的灵魂碎片。

# 新大厅

新大厅的建造流程已完成！只需要等技术组完成新大厅的适配应该就可以发布了……

# 排位模式

> 此特性将不会在下次更新中添加。

游玩人数大于 5 人时，将会随机选择部分玩家旁观，随后开启一场自主选择天赋、技能，投票选择地图的对局，双方可**投票禁用**对方的1个天赋、技能。

# 新天赋、技能

针对新的**灵魂宝物系统**，我们为双方都添加了全新的天赋和技能。

| 类型 | 名称     | 效果                                 | 阵营         | 冷却时间 | 持续时间   | 备注                                                         |
| ---- | -------- | ------------------------------------ | ------------ | -------- | ---------- | ------------------------------------------------------------ |
| 天赋 | 开锁能手 | 加快开启灵魂宝物箱的速度。           | 灵魂方       | 无       |            |                                                              |
| 技能 | 隔空取物 | 直接开启一个随机的灵魂宝物箱。       | 灵魂方       | 80 秒    |            | 可随机到被诅咒的灵魂宝物箱。                                 |
| 天赋 | 舍近求远 | 高亮距离最远的玩家。                 | 灵魂守卫者方 | 60 秒    | 5 秒       | 在场上只剩下最后两个玩家时无效。                             |
| 技能 | 恶灵诅咒 | 为一个随机的灵魂宝物箱增加诅咒效果。 | 灵魂守卫者方 | 120 秒   | 直至被开启 | 灵魂方：开启被诅咒的灵魂宝物箱后自身赋予发光、缓慢效果。<br />灵魂守卫者方：开启被诅咒的灵魂宝物箱后高亮全体玩家。 |

# 总结

我们优化了地图并增加了一些新内容，不出意外的话，新版本将于10月上旬发布在MCBBS、心火计划博客，欢迎下载游玩！
