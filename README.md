﻿# Super-Fighter<br>
超级战机 重制版 1.1<br>
作者：X_Jun<br>
本作品仅用于学习用途，不允许用于商业用途。<br>


【更新内容】<br>
重置版 V1.1         2018/1/8<br>
-添加XBox手柄支持<br>

重制版 V1.0         2017/9/30<br>
-初步完成最终关（第七关）<br>
-音频调整<br>    

重制版 Beta V0.9    2017/9/28<br>
-完成了第六关（困难第三关）<br>
-修复了WARNING不会被暂停及BLAST3音量不受调整的问题<br>
-调整了某些BOSS的行动逻辑<br>

重制版 Beta V0.8    2017/9/6<br>
-完成了第五关（困难第二关）<br>

重制版 Beta V0.7     2017/9/5<br>
-完成了第四关（困难第一关）<br>
-现在录像不会录制人工退出的部分了<br>

重制版 Beta V0.6     2017/8/31<br>
-增加了全屏(缺背景中，有好的背景可以推荐给我)<br>

重制版 Beta V0.5     2017/8/30<br>
-增加了录像回放功能，每局游戏默认都会产生录像，且存放在Replay文件夹中。<br>
 播放需要在游戏内选择录像回放并打开里面的文件。<br>

重制版 Beta V0.4     2017/8/29<br>
-完成了第三关的布局<br>
-文本编辑器更新<br>
-添加了新的敌机子弹，实装在第三关BOSS上<br>
-修复了玩家死亡后仍进行碰撞检测的问题<br>

重制版 Beta V0.3     2017/8/27<br>
-完成了第二关的布局<br>
-重新调整了敌机的参数，第一关的布局<br>
-修复了碰撞测试的bug<br>
-对音频播放改进，可以调节音量了<br>
-文本编辑器更新<br>


重制版 Beta V0.2     2017/8/18<br>
-增加了反制型追踪弹和倍率系统，并且对第一关飞机布局重新设置<br>
-提供了两种初始机型<br>
-完成了第一关的布局<br>
-增加了真实的本地排行榜<br>
-可以使用文本编辑器来自定义飞机数据和关卡布局<br>
////////////////////////////////////////////////////////////<br>
////////////////////////////////////////////////////////////<br>
原版 版本V0.50       2016/6/2<br>
-完成第三关制作<br>
-修正bug<br>
-添加非自动排行榜，要修改排行榜请拿通关截图分数给作者<br>
-删减选项<br>
-降低三个BOSS部分弹幕的密集程度<br>


原版 版本V0.30       2016/5/20<br>
-完成第二关制作<br>
-注意己方飞机会与敌机发生碰撞<br>
-受伤后无敌时间两秒并且清屏<br>
-修正一堆bug<br>


原版 版本V0.25       2016/5/17<br>
-将火力三发射角度扩大2度<br>
-未完工的第二关<br>
-现可以选择开始的关卡有 1、1BOSS和2<br>


原版 版本V0.14       2016/5/16<br>
-修复重新开始新游戏的一些bug<br>


原版 版本V0.13       2016/5/15<br>
-Boss1第4攻击阶段的弹幕密度调整宽松1度<br>
-更换背景<br>


原版 版本V0.10       2016/5/14<br>
-完成第一关制作<br>
-目前飞机只有散射型<br>

//////////////////////////////////////////////////////////<br>

【基本参数】<br>
分辨率：750x900<br>
运行环境：Windows 7以上，安装了DirectX11运行库且含有VS2017运行库<br>

【控制】<br>
鼠标点击选项（鼠标移动至选项时会变色）<br>
↑：上/XBox 左摇杆 或 十字按钮↑<br>
↓：下/XBox 左摇杆 或 十字按钮↓<br>
←：左/XBox 左摇杆 或 十字按钮←<br>
→：右/XBox 左摇杆 或 十字按钮→<br>
Z：攻击/XBox 按钮X<br>
X：大招/XBox 按钮A<br>
ESC：暂停<br>
F2：暂停后按返回主界面<br>
Enter：暂停后按继续游戏<br>

【机种选择】
你可以操控的机型有两种：散射型和集火型<br>
散射型               集火型<br>
火力：较强           火力：较弱<br>
射速：较慢           射速：较快<br>
机动性：较弱         机动性：较强<br>
最大倍率：12x        最大倍率：16x<br>
追踪弹容量：8        追踪弹容量：12<br>
大招：超密集弹幕     大招：疯狂追踪弹<br>



【护盾】<br>
当战机吃到'S'标记的道具时，如果当前没有护盾，则获得3个护盾。若当
前护盾没满，则获得1个护盾。若当前护盾已满(3个)，获得30000分。1个
护盾可以阻挡一次攻击，当受到伤害时，立即相除当前弹幕。

【大招】<br>
当战机吃到'B'标记的道具时，如果当前大招数未满，获得1个大招。若大
招已满(5个)，获得30000分。使用大招在三秒钟内无敌，并且这段时间内
清除敌方的所有弹幕。

【火力】<br>
一个战机有三个火力等级。默认情况下火力等级为1，当战机吃到'P'标记
的道具时，若火力等级未满，增加一个火力等级；否则获得30000分。火力
决定子弹的数目。

【反制型追踪弹】<br>
当敌人的子弹与你的飞机擦肩而过的时候，会自动触发反制型追踪弹。
它将会追踪屏幕早期出现的敌人。但注意不要过于依赖它，因为追踪弹
在短期是有限的，每5秒钟会补充满一次追踪弹。

【倍率系统】<br>
倍率系统可以让你普通子弹和反制型追踪弹击中敌人的时候，享受当前
倍率得分的加成。反制型追踪弹击中敌方飞机的时候，当前倍率加1，但
不能超过当前机种的最大倍率。每当连续3秒时间内没有反制型追踪弹击
中敌机，当前倍率会减半。当你使用大招的时候，以及死亡重生时，当
前倍率都会强制归为1。

【奖励】<br>
当战机在当前游戏内获得100W/200W/300W/500W/800W分时，系统会自动赠
送一条命给你。努力赚取分数来保证自己的存活时间吧！

【最终得分统计】<br>
在完成一关后，影响最终得分的因素有：当前剩余生命数、护盾数、炸弹
数、当前关卡内是否死亡，以及最终击败BOSS时的倍率。奖励分的计算公
式为：
总分 = 当前分 + ((生命数+护盾数+炸弹数)*1000 + 无死亡奖励10000) * 最终倍率 

【排行榜】<br>
当你完成所有关卡/当前硬币所有生命用光时，若分数超过排行榜最后一位，
你可以选择自己的昵称(3个字符)保存成绩。

【选择关卡】<br>
一个关卡分为普通模式和BOSS模式。在BOSS模式下，你将会直接来到当前关
卡的BOSS战，系统会送你一个'P'和一个'S'。

【游戏UI布局】<br>
![image](https://github.com/MKXJun/Super-Fighter/blob/master/pic.png)

左下角的信息若不想显示可以在设置界面中关掉调试信息。<br>


【游戏中暂停】<br>
在游戏时按Esc键可以暂停

【文本编辑器】<br>
更多文本编辑器的内容请到Data文件夹中打开README.txt查阅。

【录像回放】<br>
选择录像回放后，会弹出文件选择框。来到游戏根目录然后找到Replay文件夹，
选择你的一个录像后就会自动播放。若当前币的生命耗光，按回车续币后会继续
播放。当然也可以按Esc退出。
注意：游戏录像的播放可能会有误差。

【全屏】<br>
按ALT+回车可以全屏/窗口化，你也可以在设置中进行修改。




文档修订于 2017年9月30日<br>
By X_Jun<br>
