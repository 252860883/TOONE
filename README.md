![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/%E6%80%BB%E4%BD%93.png)

## 关于 TO ONE
TO ONE 是参加公司 2018 Hackathon 比赛耗费一个月的闲暇时间完成的比赛项目，很荣幸拿了一等奖。
>TO ONE 是一款独立游戏，以小数的二进制数作为剧情主线展开。玩家从“0”关开始，将面对几十道由不大于 1 的小数组成的递增关卡。在每道关卡中，由当前关卡小数的二进制数铺满游戏宫格，玩家需要通过移动色块将所有的 0 变成 1。最终达到“1”关时既在整个 TO ONE 游戏人生中通关。
#### 体验 TO ONE
* 如果你是PC，来点击：http://www.duhonghui.top/toone/web/  
* 如果你是手机，来扫描下方二维码：
![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/0.png)
* TO ONE 采用 LAYABOX 游戏引擎开发，（悄悄的说，数据直接写缓存了，偷懒没有写后端,哈哈哈哈）
* 项目源码请见：https://github.com/Game-Storm/TOONE_LAYA


## 起源
![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/9.png) 
  
故事的开场，就从这个诡异的结果开始了，哈哈哈哈哈。前端工程师都面临过这个问题吧！术语俗称**精度缺失**。
>计算机内部采取二进制存储。十进制小数转二进制采取“乘2取整”法则，而大部分的小数转二进制会出现无限循环的情况由于计算机的容量有限，只能存储52位,故出现误差。

然后我就想，其实计算机也没有我们想的那么精准嘛！那把这无限的 0 和 1 做成个游戏关卡会是什么样的体验呢？
于是就激发出了 TO ONE 这个游戏。

## 故事主线
>游戏由介于0-1之间的小数递增列组成，通过当前关卡即可解锁下一张数字卡牌。

![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/10.png)
### 0关
>讲述游戏的由来、玩法以及意义。From ZERO To ONE.

![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/2.png)

### 普通关卡
>每个关卡由当前小数的二进制格式0和1铺满宫格，用户需要通过移动色块将宫格转换成全部变成1即通关。游戏玩法非常简单，色块移动到的位置会进行**01置换**。随着关卡的增大，宫格数量也会随之增加，同时会新增一些难度设定。

![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/10.png)
![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/7.png)

### 1关
>通关彩蛋。由游戏引发人生思考，TO ONE 的整个游戏人生其实折射出我们现实世界的真理。同时为系列游戏的概念埋伏笔。

![image](https://github.com/Game-Storm/TOONE_LAYA/blob/master/github/8.png)
