# 由SpawnKill引出的彩虹六号基础战术内核

## 前言

> 这一篇攻略主要面对的是170级以下100级以上的玩家
> 实际上我就是抛砖引玉，希望有更多想法的玩家可以向我提出意见，我会在这里的Q&A之后根据你们提的意见对整篇攻略做一个优化和补充
>
> 2019-1-10

## Q&A

> <font color=#FF0000>Q:这篇文章太长了，有没有什么导言和总结啊？</font>
> <font color=#0066FF>A:你好，有的
> 对于心情比较急迫的玩家，我推荐只阅读第二点，看一看海岸线和别墅的偷人点就可以了
> 对于有耐心看下去的玩家，我建议从第一点开始看(对于第三点，我推荐先看理论基础和结论再去结合实例观看)
> 总结：游戏对局的过程中目标要明确，要多交换信息</font>
>
> ~~拒绝聋哑，人人有责~~

> <font color=#FF0000>Q:楼主我已经全部看完了，可是为什么我感觉什么都没说呢？</font>
>
> <font color=#0066FF>A:你好，这种情况是存在的 ~~我自己写完了都不知道我写了什么(不是~~ 遇见这种情况，我推荐的是再看一看第三点的对照平面图，思考进攻路径与防守路径的交叉位置，然后再对照实例看一看进攻方的进攻路线，也许会有些收获</font>

> <font color=#FF0000>Q：为什么是100-170级呢？其他等级不行吗？</font>
>
> <font color=#0066FF>A：首先来说下限，100级这个基础实际上不是固定的，只要是对地图有一定了解的玩家，我认为或多或少都能有所收获
> 而上限170级是因为我只有170级![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)，再高等的玩家我个人实力不够，就不做指摘</font>

> <font color=#FF0000>Q：那个平面图是从哪里找来的啊？</font>
>
> <font color=#0066FF>A：从这里[<http://www.r6maps.com/>] <br>和这里[<https://rainbow6.ubisoft.com/siege/en-us/whiteboard/index.aspx>]</font>

> <font color=#FF0000>Q：你说了这么多，你本人的水平如何呢？</font>
>
> <font color=#0066FF>A：本人由于是休闲玩家，水平一般(丑旧)，没有段位，仅仅对于战略布置有些许体会，而写这篇攻略的主要目的是抛砖引玉，共同进步 ~~信息交换~~</font>

## SpawnKill的成功率影响因素分析

>相信大家在平时游戏的时候经常会有偷人或者被人偷的习惯
>而影响偷人成功率的因素有哪些，关于这一方面我会说一些自己的理解。
>(以下内容偏理论)
>
>* **有利的地形 **
>
> >在防守方有SpawnKill想法的时候，由于防守方会有45秒的提前准备时间，在进行完封墙等准备活动以后，通常会有10-30秒不等的时间来进行转移
> >所以一般来说就算是ROOK和DOC这样的三甲龟速干员也能够在正式开始之前占领一个有利的地形
> >有利的地形对于SpawnKill来说是必不可少的，一个好的地形可以打进攻方一个措手不及
> >比如
> >
> >**高处的窗户(信息差)**
> >
> ><details><summary>偷主要入口和泳池</summary>
> ><pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-isafZqT3cS1hc-u0.jpg>
> ><br>
> ><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-1lzkZrT3cS1hc-u0.jpg>
> ></pre></details>
> >
> >**阴险的苗人凤(信息差)**
> >
> ><details><summary>偷废墟</summary>
> ><pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-cpn2ZoT3cS1hc-u0.jpg>
> ></pre></details>
> >
> >**趁进攻方不备冲出来对枪**
> >
> ><details><summary>偷泳池和厨房窗口和水烟间平台</summary>
> ><pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-fjdrZwT3cS1hc-u0.jpg>
> ><br>
> ><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-9x0mZzT3cS1hc-u0.jpg>
> ></pre></details>
>
>* **充足的信息**
>
> >由于对局还未正式开始，所以我在这一点所指的信息仅仅是指防守方偷人手的位置以及进攻方的出生点位
> >在这45-65秒的时间内，进攻方的无人机是否存活，是否搜寻到了防守方偷人手的位置，防守方的摄像头是否捕捉到了进攻方的出生点位
> >在没有摄像头的情况下，偷人手是否能够通过声音以及被毁坏的摄像头来判断进攻方的进攻路线
> >以上的信息都会很明显地影响到开局这1分钟出现击杀的概率
> >而刚开局就产生的击杀，会很明显地影响到队伍的胜率，比如：
> >被偷的人心态爆炸退出游戏，进攻方失去了一个信息位； ~~被偷的人感觉失去游戏兴趣，打开手机开始刷NGA~~
> >偷人失败反而暴露位置被围剿失去性命心态爆炸退出游戏，防守方失去了一个信息位
> >(而彩虹六号作为一款极度依赖信息传递和道具交换的战术射击游戏，失去一个干员就相当于失去了2-3个道具，失去了2架无人机~~和一个人肉排雷器~~)
> >(自然而然，开局失去干员的队伍胜率不会很高。)
> 
>* **强大的心脏**
>
>>我相信大家都有这样的经历，正在1v2残局的时候，静步走在过道上瞄着拐角处爆头线，突然脚下一凉，啪的一声把自己吓得枪口乱飘然后被拐角出现的防守方一枪干死
> >在我们偷人的时候，尤其是在我们听见进攻方的脚步越来越近的时候，我们的心跳会加快 ~手会微微颤抖~，这些心理上的变化，会影响到我们筛选信息的能力
> >我这里说的心理变化可能是好的也可能是不好的，但是一般来说是不好的 ~因为你手一抖，枪就瞄不准~
> >当精神高度集中的时候，我们会下意识地忽略一些信息，比如蹲在地上玩手机只露出一个脑袋的干员，比如就在你隔壁的破门声，还有TWITCH在你脚下放贴片的声音等等
> >这些非常重要的信息一旦忽略，我们的偷人行动很可能会失败甚至付出生命的代价
> >所以，有一个强大的心脏是非常重要的，这不仅仅影响到你偷人的成功率，更影响到你对于突发信息的处理程度(比如你被3个人围起来了应该朝哪边突破的问题)
> * **枪法的准度**
>> 对于这一点我之所以放在第四点，不是因为枪法不重要，而是因为我接下来要引出的内容跟枪法关系不是很大
> > 我写这个东西的目的是让更多枪法像我一样菜鸡的人能够从彩虹六号这款游戏里面得到很大的乐趣，所以接下来的内容才是重点
> ~~妈个鸡劳资枪法好还研究这些搞毛啊~~ ![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)

## SpawnKill的点位探索以及其所含的彩虹六号基础战术思想

> 在这一点我会简单地说一下SpawnKill对围攻这两个字的体现
> 然后从SpawnKill引出“拦截”这一概念

> 首先我们来看一下几个海岸线常见的偷人点位
>
> <details><summary>废墟进攻示意图</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-hed1XhZ4tT3cS1ag-p0.png>
> </pre></details>
>
> <details><summary>偷废墟</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-9c5mZpT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-k1w8ZoT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-cso5ZkT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-7qe1ZtT3cS1hc-u0.jpg>
> </pre></details>
>
> <details><summary>泳池进攻示意图</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-kb9XhZ4rT3cS1a6-ou.png>
> </pre></details>
>
> <details><summary>偷泳池</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-1lzkZrT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-fjdrZwT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-2r8gZvT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-8hpnZyT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-9x0mZzT3cS1hc-u0.jpg>
> </pre></details>
>
> <details><summary>主要入口进攻示意图</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-g3ygXhZ4oT3cS18q-ow.png>
> </pre></details>
>
> <details><summary>偷主要入口</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-dhp2ZlT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-6u9vZoT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-dpaZqT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-35w1ZtT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-isafZqT3cS1hc-u0.jpg>
> </pre></details>
>
> 可以很明显的看得出来，海岸线的三个出生点位都可以被防守方进行围攻
> 而这个围攻的基础是什么呢？
> 答案已经非常明显了，就是进攻方的出生点位是固定的的，而防守方的位置是不可知的
> 简单的来说，就是防守方利用位置上的已知信息差距对进攻方的进攻路线进行预瞄，在进攻方毫无防备的情况下
> 极有可能被防守方的偷人手伤害甚至击杀 这一点很重要，要考
> 而进攻方降低被SpawnKill的几率的办法也很明了，就是“保小车”，无人机作为进攻方在前1分钟之内(甚至整局)唯一的信息来源，在前期的进攻路线选择
> 以及战术制定上无疑是十分重要的。
> 在进攻方的出生进攻路线完全已知的情况下，要减小防守与进攻方的信息差距，只能靠小车在建筑旁边转悠，这样才能够避免伤亡。
> 从这里，我们可以引出彩虹六号最基础的战术思想：以信息交换与信息压制为基础进行围攻行动。
> 这个东西我放下一点讲，这一点首先先讲标题的SpawnKill的点位探索。
> 至于道具交换与道具压制，由于个人水平有限，就不作展开了 ~~懒~~
>
> **我以别墅为例，进行偷人点位的模拟(以下点位仅有部分经过实战检验) **
>
> <details><summary>别墅1F拦截示意图</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-3zdbZ2sT3cS1hc-u0.jpg>
> </pre></details>
>
> <details><summary>1F对应偷人点位示意</summary>
> <pre>
> <b>偷主要入口</b>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-hfrhZ14T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-4e7fZyT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-bxnvZsT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-ep0fZ15T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-a2roZtT3cS1hc-u0.jpg>
> <br>
> <br>
> <b>偷废墟</b>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-8l9bZ11T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-gefZwT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-647tZtT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-f6grZ1eT3cS1hc-u0.jpg>
> <br>
> <b>偷喷水池</b>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-bdq1Z1aT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-kahbZuT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-26vzZwT3cS1hc-u0.jpg>
> </pre></details>
>
> <details><summary>别墅2F拦截示意图</summary>
> <pre><img src=https://img.nga.178.com/attachments/mon_201901/10/goQ5-6lx5Z2sT3cS1hc-u0.jpg>
> </pre></details>
>
> <details><summary>2F对应偷人点位示意</summary>
> <pre><b>偷主要入口</b>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-88p8Z13T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-clsjZwT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-hoh4Z11T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-kxwxZzT3cS1hc-u0.jpg>
> <br>
> <br>
> <b>偷废墟</b>
> 首先先看几张废墟预瞄的点
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-jq3lZ1fT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-1wd1Z19T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-jbohZ1aT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-egz9ZzT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-4m8mZ1gT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-1l5lZ13T3cS1hc-u0.jpg>
> <br>
> 然后再来看偷废墟的点
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-7bqmZzT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-4gssZtT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-b3q6Z16T3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-g4rrZ1bT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-l195Z1aT3cS1hc-u0.jpg>
> <br>
> <b>偷喷水池</b>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-jcbaZ1fT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-fdhmZ1fT3cS1hc-u0.jpg>
> <br>
> <img src=https://img.nga.178.com/attachments/mon_201901/11/goQ5-3mhoZ12T3cS1hc-u0.jpg>
> </pre></details>
>
> 这些图片非常直接，可能看不出什么
> 所以我会讲一下我是怎么找这些点的（当然这些点肯定不是我最先发现的，我只是讲一下思路）
> 其实很简单，你找个别墅的平面图，然后把进攻方的点位一标，把进攻路线标出来
> 然后从防守方的各个外部窗口开始连线，连到进攻方的进攻路线上，一个未经实践的偷人点位就出现了
> 然后再进游戏跑一圈，能用的点记下来，接下来就是实战了
>
> 而SpawnKill这一行为实际上就是防守方对于进攻方的出生点进行围攻的行为
> 而这个进攻路线与防守方到进攻路线的连线，正好是一个拦截关系，这个拦截关系就是我接下来要讲的彩虹六号的基础的战术开发思路
> 接下来我们回到海岸线来分析一局比赛

## 以围攻为基础的基本战术开发思想

> 这一点我会举例(没有特意选过材，可能材料不是特别好)![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)
> 简单讲一讲在围攻行动中，拦截与被拦截关系不断变化的过程对于游戏进程的影响
> 然后是简单的对海岸线各个炸弹点位的防守布置分析
> 由于本人水平有限，所以在分析过程中很可能会出现一些错误，希望有发现的玩家能够帮我指出

>> **理论基础**
>>
>> 我们先回到第一点来看一下影响SpawnKill成功率的几个因素
>> 1)有利的地形 2)充足的信息 3)强大的心脏 4)枪口的准度
>> 在这里我们假设选手水平一致，也就是心理素质水平一样和枪法一样
>> 我们来分析一下地形和信息(以下内容仅局限于炸弹局)
>>
>> 首先是地形
>> 我们玩R6的人都知道，R6与其他射击游戏不同的地方就是其在地形方面的较高的自由度
>> 在一个固定框架之内，所有人都可以围绕点甚至在需要的情况下对远离点的位置进行地形改造
>> 地形改造的方式有许多，现在我们知道的有
>> 直接改造：使用加固墙，使用机动护盾，使用霰弹枪开墙，用近战攻击在墙上敲洞，用远程武器(步枪冲锋枪)在远处开洞
>> Ash，Hibana，Thermite，Maverick的开墙行为，Mira的单向镜
>> 间接改造：Lesion的蛊，Kapkan的绊雷，Nomad的气爆锤，Ela的震荡雷，Frost的陷阱
>>
>> 而地形改造的目的有下：
>> 为获得信息创造条件
>> 获得创造击杀的前置条件(开对枪口等)
>> 创造截断路径
>> 阻止敌方获得信息(加固墙等)
>> 还有总的大目标：阻止敌方获得胜利
>>
>> 很明显，信息作为改造地形的原动力之一，其重要程度是无可质疑的
>> 再分析一下信息
>> 信息的来源有下：
>> 直接来源：干员视线中的注意力集中点和动态物体
>> 间接来源：听觉和道具反馈
>> 信息的作用有下：
>> 提供敌方干员位置
>> 提供敌方道具剩余量
>> 还有最重要的一点：暴露敌方的战术意图
>>
>> 通过以上分析，我们可以知道，在信息差优势的一方可以获得暂时性的主动权
>> 占据主动权就意味着优势方可以利用主动权去创造更大的信息差距或者去创造一个击杀从而向比赛胜利更进一步
>> 因为对于被动的一方，他们对优势方的行动要做出反应需要一定的时间，而这点时间，就是我所说的主动权
>> 而对于主动权的一个基本的运用，就是我之前有提到的，拦截与被拦截关系
>> 当敌方走位偏向分散时，占领信息优势的一方，可以利用其信息优势，对敌方的目标干员进行拦截，比如埋伏在敌方干员的撤退路径上，等待友方利用道具等令敌方干员强制位移然后取得击杀
>>
>> 接下来我通过一场比赛来分析拦截与被拦截关系的运动对于这场比赛胜负的影响
>

>> **实例分析**
>>
>> 这一场比赛是里约S8 8进4 NORA-RENGO对阵ROGUE的一场比赛，地图是海岸线
>> (这场比赛是我随便找的，对于双方的实力理解不是特别深刻，我在这里着重于拦截与被拦截关系的运动对比赛走向的影响而不去分析选手的硬实力) 甚至海岸线这张图都是随心定的 ![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)
>>
>> [[Nora-Rengo vs. Rogue](https://www.bilibili.com/video/av36694227/?p=3)]
>>
>> 首先我们来看BAN人
>> GLAZ  LION  VALKRYIE  ECHO
>> 除了常年小黑屋的LION以外，这一次坐上BAN位的都是信息获取位
>> VALK和ECHO能依靠黑眼和无人机获取到大量的信息
>> 而GLAZ可以在极远处获取敌方的运动方向甚至造成击杀
>> (给极远处举两个例子：一是废墟上的平台，距离撞球桌有30m，二是水烟间窗户正对的帆布，距离撞球桌40m左右，而一般的室内对枪距离是5-15m)
>>
>> 接下来分析一下开局的战术布置
>>
>> <details>
>> <summary>1F的战术布置</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-9z7zXbZ32T3cS1hc-u0.jpg>
>> </pre>
>> </details>
>>
>> <details>
>> <summary>2F的战术布置</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-cooiXdZ3kT3cS1hc-u0.jpg>
>> 撞球桌与水烟间之间有一块黑镜我没有标出来
>> </pre>
>> </details>
>> 干员的位置分布：
>>
>> 除MIRA和ALIBI在红酒吧外
>> 剩余干员均在2L
>>
>> 开局1分钟以后，我们来看一下双方的战术布置
>>
>> <details>
>> ><summary>干员分布</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-b5lmXaZ2tT3cS1hc-u0.jpg>
>> </pre>
>> </details>
>> 通过对进攻方站位的分析，我们可以发现，进攻方的节奏很快，在队长的信息支持下，3个强势干员迅速清点，把远点位的几个房间肃清然后开始推进，目标也很明确，就是点位楼上的水烟间和撞球桌
>> 而防守方也获取了ASH的位置信息
>>
>> 然后来看一张1分40秒的干员站位
>>
>> <details>
>> <summary>干员分布</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-e84gXcZ38T3cS1hc-u0.jpg>
>> </pre>
>> </details>
>> 我们对ASH和LESION进行分析
>> 首先，ASH在前一分钟占领了VIP室并且暴露了自己的位置，LESION在获取ASH的位置信息以后架住了ASH的必经之路，也就是VIP的门(这里是LESION拦截ASH)
>> 而这时，我提一下，由于龙鳞板在水烟间卡住了小车洞，而另一边脚气的小车只探到了撞球间的龙鳞板就停止了，所以LESION的站位是没有被进攻方发现的
>> 所以这里产生了一定的信息差距，如果在这里LESION的枪不马的话，很明显进攻方将会失去一个突破手(3个闪光2个小车还有一发榴弹)
>> 但LESION枪马了，所以我们来分析一下这里的局势，LESION位置暴露，而由于JAGER开枪了，JAGER位置暴露，龙鳞板回点，而ZOFIA准备炸开龙鳞板，脚气已经卡住通道
>> 所以LESION想要撤回点内必然要付出极大的代价(这里是ZOFIA和脚气拦截LESION)，LESION已然是瓮中之鳖
>>
>> 本来剧本是这样写的![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)
>>
>> 但是这时出现了一个问题，由于MIRA，龙鳞板，ALIBI的点位未知，此时时间所剩颇多，所以进攻方选择继续肃清剩余房间，LESION又活了下来
>> 这时ZOFIA炸开龙鳞板，LESION反身架住ZOFIA的位置，交战双方除了LESION以外，又进入搜集信息的状态。(龙鳞板又回到了二楼黑镜处，ALIBI跑到了中央大厅处，而脚气选择往1L中央大厅走)
>>
>> 接下来是第一个击杀 ZOFIA击杀ALIBI
>> 这个我就不放图了，直接说好了，这里是因为枪盾在办公室外玩车，车进入了蓝酒吧以后发现了蓝酒吧被开了一个洞(有个喷开的洞当然要去看看)，而刚刚进入中央大厅的AILBI的位置自然也就被小车发现了
>> 位置被发现后，ZOFIA迅速做出行动，两点一线，跳到中央平台上，利用先手优势收掉了ALIBI的人头。
>>
>> 接下来是第二个击杀 JAGER击杀ASH
>>
>> <details>
>> <summary>JAGER击杀ASH</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-2diuXiZ4zT3cS1hc-u0.png>
>> </pre>
>> </details>
>> 这个地方实际上就是ASH死在了刚刚被LESION击中的位置
>> 很明显，由于LESION的报点，ASH的位置暴露在了整个防守方的视野中，在ASH未做出下一个行动前，防守方所有人都必然默认ASH仍然在VIP室内
>> 所以JAGER在之前探知到通道没有人架枪后，选择直接架住整个通道，获取了通道的控制权，如此以来，ASH探头自然就被JAGER击杀了
>> 而ASH死亡以后，原本在进攻方战略中需要控制的通道也就空了出来，我们可以发现进攻方的战略发生了转移，重心由水烟间和撞球桌变为了撞球桌
>>
>> 接下来是第三，四个击杀 龙鳞板击杀ZOFIA 脚气击杀LESION
>> 龙鳞板在黑镜后抓住了探头的ZOFIA，而ZOFIA死亡以后，原本处于进攻方战略内的撞球桌也不得不放弃(有个黑镜，2L只有CAPTIAO)
>> 龙鳞板的位置暴露
>> 但是这个地方LESION有一个动作，他走出了撞球桌房间然后跳进中央大厅里，被此处从主大厅架红酒吧大门的脚气收掉了(白给)
>>
>> <details>
>> <summary>给一张脚气的第一视角</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-aaa7XmZ60T3cS1hc-u0.png>
>> </pre>
>> </details>
>> 而后JAGER受伤了，我们分析一下此处JAGER受伤
>> 首先，JAGER在二楼收掉ASH以后选择往一楼回防(时间剩余1分钟)
>> 而LESION被击杀以后，脚气射击到了红酒吧吧台的棱镜，暴露了自己的位置，JAGER选择从办公室通过想去击杀脚气，但是办公室中有一个卡点的枪盾
>> JAGER一露头就被枪盾击中(这里实际上是枪盾拦截到了JAGER，保护了脚气的安全)
>> 但是，办公室走不通还可以从厨房外的通道走，所以JAGER选择离开办公室反从红酒吧架住厨房外通道
>> 接下来就是第五个击杀 JAGER击杀脚气
>> 果不其然，脚气从此处通过，被JAGER爆了头，同时，JAGER的位置也暴露了
>>
>> 接下来比赛只剩22秒，而黑镜获取了在办公室的枪盾和队长的信息
>> 此时就是硬对枪时间了，拦截与被拦截关系的运动也就到此为止
>> 实际上拦截与被拦截关系的运动是信息差距所导致的，而当进攻防守双方的信息完全互相暴露时，双方拥有对等的信息，关系运动也就停止了
>> 而这场比赛离结束也就不远了。
>>
>> 以上是这一场比赛的一个流程陈述(夹杂一些拦截与被拦截关系运动的分析)
>> 接下来我从整个地图的角度来分析
>>
>> 首先是一张前一分钟占领区域的分析图
>>
>> <details>
>> <summary>占领区域分析</summary>
>> <pre>
>> <img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-dke6Z2aT3cS1hc-u0.jpg>
>> </pre>
>> </details>
>> 很明显，进攻方在这一场选择的战术是层层推进，通过不断的肃清各个房间从而压制防守方的运动空间
>> 最后通过道具往点内强行突破
>> 实际上现在大部分的比赛用的都是这种思路的战术，这种思路就是围攻。 挂绳在窗户上贴贴片然后突破那个叫突袭 ![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)
>> 而防守方在这一场选择的战术是扩大防守范围，拖延进攻方时间，然后当大部分进攻方位置暴露后，由点内自由人往点外寻找机会突破
>> (这一场防守方唯一的自由人是ALIBI，还白给了)
>>
>> 虽然这一场是进攻方胜利了，但是从战术实行程度的角度上来分析，防守方对于战术的实行显然更好
>> 我们来看，防守方扩大防守范围到2L撞球桌和水烟间，通过3个干员的相互配合防止进攻方迅速攻下二楼从而对点内进行垂直打击
>> 而整场比赛下来，进攻方除了ZOFIA的尸体，没有一个干员进了水烟间和撞球桌
>> 若非是LESION和MIRA的错误走位导致白给，防守方不可能输掉这场比赛。
>
>好，实例分析完了(10场比赛要全部写出来实在是太长了 ~~我懒~~ )，现在我们回到标题，来说一说以围攻为基础的基本战术开发思想
>首先回顾一下理论基础：为了获取胜利，我们需要比对方拥有更多的信息，为了获取或者阻止对方获取信息，我们需要改造一定的地形，然后分散人员的布置
>以此为思路，我来简单的分析一下海岸线各个炸弹点的防守布置和进攻布置
>首先是厨房点
>
><details>
><summary>1F厨房和维修入口</summary>
><pre>
><img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-crkiXbZ34T3cS1hc-u0.jpg>
></pre>
></details>
>
>我们现在对蓝色箭头进行拦截
>拦截的方式有：防守红酒吧，防守二楼VIP室，防守二楼顶层房间
>而防守不住了我们需要有退路
>比如防守红酒吧的可以提前将红酒吧与蓝酒吧的墙喷开从蓝酒吧撤离
>防守2LVIP室的由于在VIP室内没有撤离路线可以提前将VIP室的外墙炸开而在撞球间防守
>防守二楼顶层房间的可以提前将HATCH炸开从HATCH逃离等
>这个思路实际上就是战术布置的思路，同样地，我们分析另外的3个点
>
><details>
><summary>1F红蓝酒吧</summary>
><pre>
><img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-89geXbZ37T3cS1hc-u0.jpg>
></pre>
></details>
>
>首先对蓝箭头进行拦截
>我们发现，可以在办公室，撞球间水烟间，VIP室顶层房间和电影院进行防守
>同样地，我们思考每个房间的撤离路线
>办公室可以提前将蓝酒吧的墙炸开从蓝酒吧撤离到中央庭院，或者从机房撤离
>撞球间水烟间可以联通然后将HATCH炸开从HATCH撤离或者从北方楼梯撤离
>VIP室顶层房间电影院可以联通然后提前将HATCH炸开从HATCH撤离或者从南方楼梯撤离
>而有一些蓝箭头是无法进行直接拦截的，那么我们考虑将蓝箭头所指向的墙面加固，阻止蓝箭头的直接枪线
>这样，整个炸弹点的布置就有了一个大概的雏形
>
><details>
><summary>2F电影院和顶层房间</summary>
><pre>
><img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-9zlcXbZ35T3cS1hc-u0.jpg>
></pre>
></details>
>
><details>
><summary>2L水烟和撞球间</summary>
><pre>
><img src=https://img.nga.178.com/attachments/mon_201901/12/goQ5-fzadXbZ36T3cS1hc-u0.jpg>
></pre>
></details>
>
>剩下的这两个点也大同小异了，用同样的思路可以分析出类似的战术布置，这就是最基础的战术布置了
>关于进攻方的战术布置，实际上也是对箭头的拦截，只不过得在地图上分析“红箭头”的指向，对射出红箭头的房间进行加强打击，压制防守方的活动空间，最终通过道具来决定胜负。
>
>但是有一点，我们对于异常重要的房间可以进行额外的战术布置
>我们通过分析以后发现，VIP室对于四个炸弹点来说都是一个非常重要的地方，许多的蓝箭头都从它或者它附近射出，那么我们可以针对这个房间进行更多的战术布置
>比如：垂直方向的战术布置，PLUSE的垂直C4，VALK的垂直C4等，水平方向的战术布置，加固周围墙面，增多周围防守人员，往这个房间增添道具等
>这就是一般的额外布置思路了
>在布置战术的过程中，我们需要注意的一点就是，你在点外布置越多的干员和道具，那么点内就会越空虚，当进攻方发现点内空虚时，很可能会进行突袭行动，突袭行动一旦成功，攻防互换，防守方的结局就基本固定了
>
>但是，在日常的休闲游戏中，我们并不是整个队伍的指挥官，更多地是扮演一名干员，对自己下命令，自行决定防守方向，这个时候，我们该怎么做呢？
>这就是我要讲的最后一点：学会分析队友站位和整体局势，避免无目的的漫游





## 分析局势，避免错误行动

>在这一点我会说一些日常休闲局中，玩家常见的错误行动，然后分析如何避免这些行动
>再分析如何建立一个在路人局的进攻思路，这里要注意，这个进攻思路不是不变的，因为在路人局中，经常会出现一些意外，我们需要根据当前情况去制定战略
>比如队友猝死导致一些本应处于控制的区域被放空，或者是队友的突袭行动过于成功，点内被清空而敌方的打野干员没有反应等等
>
>首先，我要说一个在路人局中经常被忽略的信息：队友的位置
>由于在R6中，队友的走位我们是可以透视看见的，所以，根据队友的走位，我们可以很明确地判断出，队友走过的房间有没有人(当然有时会翻车)
>这就是一个非常重要的信息，在队友是自闭玩家的情况下，队友的走位就是你唯一可以得到的，来自队友的信息。
>所以在正常对局时，一定要特别注意队友的走位，这是你分析当前局势的基础
>那么如何分析当前局势呢？
>首先最重要的是时间，当前对局还剩多少时间是非常重要的，这影响到你是否有足够的时间来完成接下来的行动
>其次是双方人数对比，优势方可以控制更多的区域，可以获取更多的信息，在各司其职的情况下，优势是非常巨大的而劣势方此时要小心行动，尽量不要暴露自身位置，通过拦截敌方走位拉回人数差距
>或者拖延时间(对于防守方)，而对于进攻方来说，此时最重要的就是集中力量进行突破，争取拉回人数差距
>再次就是分析队友站位，判断出安全区和危险区，这样进攻或者拦截的路线才能逐渐明确，自己才能有一个相对清晰的目标，对于整场比赛才有更大的把握
>
>说完了分析局势，我们再来看一下错误行动
>
>错误行动一：在没有与队友沟通过的情况下直接架与点直接相连的门和窗户
>首先我说一下这个行动为什么错误(这是基于基本战术是围攻而不是突袭的情况下)
>一个团队只有5个干员，但与点直接相连的门和窗户却不止一个
>在没有与队友沟通过的情况下，很可能会出现一个团队内2-5个人同时围着点架的情况，而且在团队水平较低的情况下，还会出现2-3个人同时架一个门/窗户的情况，这就造成了干员资源的极大浪费
>这就意味着，信息来源完全不足(没人玩车和探点)
>而且对于防守方来说，当进攻方干员集中于一个或同一方向的门窗时，自由人可以肆无忌惮地转移点位从而对进攻方造成极大的打击
>通常情况下，在架点干员的位置没有暴露的时候，一个干员就能很好地架住一个门/窗/通道
>而此时，其它干员就可以使用小车或者道具来清理剩余房间，这样可以加快清扫进程，节省时间
>也可以反身架住背后的通道防止自由人摸屁股
>这里要注意的是，进行垂直进攻时，建议2-3个干员抱团，防止被摸屁股
>
>错误行动二：在毫无信息的情况下往房间内冲刺
>这个行为的危险程度非常高，危险程度仅次于往敌方干员脸上冲刺试图刀人
>在未探车的情况下，你不知道房间内敌方干员在此房间内的布置，比如防守方是否在房间内放了道具，是否放了防守干员
>进攻方是否放了阔剑等等
>对于这种行为，我的建议是，有车探车，有摄像头看摄像头，啥都没有听声音
>总而言之，在进入房间之前一定要先获取一定的信息，否则非常容易白给
>
>错误行动三：目标不明确
>目标不明确会导致许多的错误行为
>比如：
>进攻方浪费时间在一些无法进攻的点位，举个例子，在黑镜前试图与黑镜后的干员对枪(又不扔闪又不扔烟，就干看着)
>防守方窝在点内而没有明确的卡点意识(比如枪口瞄地，反应迟缓)
>过拐角的时候不瞄爆头线，确定房间有人的时候不提前开镜等
>关于这一点，我的建议是如果你对这个图的一般进攻路线不理解(对图不熟悉)，那就跟着队友走，帮助队友卡点
>如果熟悉地图，那就去夺取重要房间的所有权，压制敌方的行动空间，为突破做准备
>
>错误行为四：不报点或者报点不明确
>这是我们在游戏中经常出现的错误行为
>不报点自然就不用说了，是自闭玩家的日常，不过这也无可厚非，因为报不报点是别人的自由
>但是对于报点不明确这个行为，对于整个队伍来说，危害是非常大的
>比如，ASH和另一边的大锤同时往门里冲，你拿小车探点发现ASH进门右边有个人，于是你报点，右边右边！而另一边的大锤接受了错误信息，被处于他的方向的左边的人打死了![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)
>这又能怪谁呢
>还有报点说我这有人我这有人！
>不是，不是开黑我哪知道你是谁你在哪，我能怎么办啊![哭笑](https://img4.nga.178.com/ngabbs/post/smile/ac15.png)
>求求你用用Z键罢