# ff14-treasure-bookkeeper
挖宝会计不请自来v0.1 适配国服5.58
https://bbs.tggfl.com/topic/127

nga不知道为什么被隐藏了 重新排个版发萨雷安.jpg 

%(#ff0000)[部分功能有使用鲶鱼精邮差实现!]

======功能介绍======
没啥可介绍的 它会自己算出挖宝开箱子吃了多少系统金然后发出来
~~我觉得这个功能早就应该有了但是为啥是我自己写出来的~~
提供了小队成员也可以使用的查询功能(可选)
提供了G10转盘没roll点的自动提醒功能(可选)


======食用方法======
- 导入并设置鲶鱼精邮差(参考版内鲶鱼精邮差相关内容)
- ACT高级触发器导入即可(参考版内高级触发器相关内容)
- 请保证基础功能全部勾选
- 可选功能按实际情况酌情开启

======指令一览======
1. 开始挖宝时的金币重置(建议写在宏里并放在**不**经常按的位置):
    ps.只有老板才需要的功能 如果打工的话在进招募的时候会自动重置   %(#ff0000)[重置操作不可逆!操作需谨慎]
```/e 金币重置```
2. 挖宝时的实时查询(建议写在宏里并放在经常按的位置):
```/e 挖宝查询```
```/e 挖宝统计```
3. (可选功能)队友也可以用的挖宝查询(发在小队频道就可以):
```/p 挖宝查询```
```/p 挖宝统计```

======注意事项======
1.鲶鱼精端口默认2019 如果需要更改的话在xml文件里ctrl+H自行替换 ~~懒得改了~~
2.渣技术力 处于勉强可用的状态  出现问题/有新需求可以邮箱联系 %(#00ffe1)[CV-2@qq.com] 或本帖下回复
3.目前只记录G10(运河/转盘) G10绿图 莫古力图 G12  ~~别的没挖过不知道别问我~~


更新日志
2021-04-08 01:40
更新G12转盘
2021-09-04 04:57
1.小队查询指令修改
2.显示的金币数字使用逗号分隔 增加可读性(感谢板内 a553469159 提的PR!)
3.增加部分文本的发送间隔 ~~一直<se.1>真的好吵~~
4.将进队重置的关键词改为里塔提恩强攻战
2022-01-25 05:17
继续增加部分文本的发送间隔 并修改提示音
