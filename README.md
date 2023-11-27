# Pokemon

<p align="center">
  <a href="https://github.com/jiluoQAQ/pokemon"><img src="https://s2.loli.net/2023/11/03/mW1ykVxItGRSqjN.png" width="256" height="256" alt="pokemon"></a>
</p>
<h1 align = "center">Pokemon 0.2</h1>
<h4 align = "center">🚧支持OneBot(QQ)、QQ频道、微信、开黑啦、Telegram的宝可梦小游戏插件🚧</h4>
<div align = "center">
        <a href="https://docs.sayu-bot.com/" target="_blank">安装文档</a> &nbsp; · &nbsp;
        <a href="https://docs.sayu-bot.com/常见问题/">常见问题</a>
</div>


## 丨安装提醒

> **注意：该插件为[早柚核心(gsuid_core)](https://github.com/Genshin-bots/gsuid_core)的扩展，具体安装方式可参考[GenshinUID](https://github.com/KimigaiiWuyi/GenshinUID)**
>
> **如果已经是最新版本的`gsuid_core`, 可以直接对bot发送`core安装插件pokemon`，然后重启core以应用安装**
>
> 如使用命令缺失素材可尝试使用命令`pm下载全部资源`
>
> 支持NoneBot2 & HoshinoBot & ZeroBot & YunzaiBot的宝可梦小游戏插件
>
> 🚧插件目前还在施工中，可以使用，功能快速完善中...🚧
>
> ✨如果有其它的建议欢迎在issues中提出✨

## 丨功能

<details><summary>猜猜我是谁 - 命令: 我是谁</summary><p>
<img src="https://s2.loli.net/2023/11/03/j4J2YMHzRtE5aAb.jpg"/> 
</p></details>

## 丨当前进度

> **宝可梦对战正在制作中**
> 
> 对战相关
> 
> 已完成技能伤害测试
> 
> 全技能70%已覆盖
> 
> 已完成属性克制，天气影响，技能属性提升等对战因素
> 
> 已完成技能释放AI
> 
> 已完成野外训练家宝可梦随机战斗AI
> 
> 正在开始制作城镇系统
>
> 已完成关东地区的设计
>
> 其它精灵的孵化已完成
>
> 玩家对战已完成

## 丨整体目标

地图设置
>设置多个地图，初始诞生地根据选择的初始精灵自动选择
>例：小火龙 关东地区 真新镇
>    菊草叶 成都地区 若叶镇

>每个地区的不同地点有进入要求，暂定为徽章 	已完成
>例：关东地区 1号道路 无徽章要求
>   关东地区 5号道路 要求一个徽章

>城镇地区可以进行打工赚取金钱			已完成
>需求徽章越高的城镇地区打工奖励越高，为徽章要求x5000

>城镇商店都会出售可以重置单条努力值的道具，方便训练家训练精灵

>城镇商店都会出售可以添加对应努力值的道具(精神之羽等)，方便训练家训练精灵
>商店道具随个人徽章数量开放

>去往另外的大地区需要道馆徽章8个
>8个徽章每天只能切换一次大地区
>挑战过4天王每天可以切换5次
>挑战过冠军每天无限制

>每天0点在各个地区的随机野外地点会出现宝可梦大量出现，大量出现在野外探索的遇见概率统一为30%
>大量出现的宝可梦在普通宠——二级神(种族值650以下)随机出现，按照种族值来随机出现的概率
>300以下 	15% 	lv20
>300-399	20%	lv30
>400-499	30%	lv40
>500-599	30%	lv50
>600以上    5%	lv60
>战胜后有10%概率获得对应的初始形态精灵蛋，可孵化

精灵设置
>暂定每个人只能有一只可战斗的同种族精灵，重复获得自动转化为精灵蛋，同种族精灵可以通过消耗同种族精灵蛋进行个体值的重置

>精灵暂时需要手动进行进化指令操作，进化时判断进化条件是否满足（等级/背包的进化道具）
>进化的时候记得同步手持精灵编号

>精灵升级技能学习暂时需要手动确认，替换可学习的等级技能无消耗

>精灵可以使用技能学习机器进行技能学习，学习的时候判断是否可以学习与道具是否充足

>可以设置一队的战斗精灵，暂定最高手持4只，太多怕战斗的时候服务器撑不住

战斗设置
>[野外探索]时触发随机事件，事件类型为寻宝5%，野外训练家20%，野生精灵75%

>寻宝事件：获得道具奖励：技能学习机器40%，进化道具20%

>战胜野外训练家会得到金钱奖励

>战胜精灵会根据野外精灵的等级和种族值得到相应的经验值

>战胜精灵会根据野外精灵的最高种族值得到对应的努力值(50以下>1，50-99>2，100以上>3) 不提示

>战胜野外精灵后有10%的概率获得对应的初始形态精灵蛋，可孵化		未确定

>可以与群友进行切磋，精灵战胜奖励与野外训练家一致，失败者按照训练家等级扣除一定的金钱(暂定)

>战斗目前暂定为自动随机技能战斗，战斗失败后按照剩余的手持精灵进行随机轮换
>只有最后一击的精灵可以获得战胜的对应奖励

>精灵战斗每次最多15回合，15回合后剩余血量高的精灵获胜(防止2只精灵都不带攻击技能进入无限循环卡死服务器)
>此方法获得胜利的获胜精灵只能获得完整的一半奖励

后期工作
>赛事系统设置
>个人承办赛事
>个人可以举办比赛，指令为
>举办个人赛事 赛事名称(作为报名赛事的识别名) 奖励类型(道具/精灵蛋) 奖励名称 报名天数

>个人赛事玩家同意报名费用为5000金币，个人赛事结束后个人举办方会得到总报名费的40%作为承办方资金

>报名时间结束后报名人数达到赛事开始的最低标准(暂定8人)就自动开始比赛，比赛记录留存，可以后期查询
>时间没有到达最低要求就个人赛事举办失败，返还奖励道具和报名费用
>赛事举办成功会扣除道具
>个人赛事只有最后的冠军会得到(道具/精灵蛋) 奖励

>系统举办赛事

>系统会定期举办赛事
>奖励 进化道具、准神，御三家精灵蛋随机
>无需报名费
>系统赛事的举办时间按照人数与报名时间，默认7天报名时间/人数达到64人(最低人数64人，超出7天没有达到也要等达到64人)
>达到开始的最低要求后后台自动开始比赛，比赛记录留存，可以后期查询
>冠军获得准神精灵蛋
>亚军获得御三家精灵蛋
>第三第四获得奖励的道具

## 丨其他

+ 本项目仅供学习使用，请勿用于商业用途
+ [GPL-3.0 License](https://github.com/jiluoQAQ/pokemon/blob/main/LICENSE)
