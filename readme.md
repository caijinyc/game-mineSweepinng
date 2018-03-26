# 原生 JavaScript 实现扫雷游戏

学习了这么长时间的 JS，不能光看不练，于是就写了个小游戏练习一下。

如果感兴趣的话可以试试：[Demo](http://caijin.tech/demo/mineSweeping/index.html)

## 效果图
![demo1](https://github.com/CaiJinyc/game-mineSweepinng/blob/master/img/demo1.gif)![demo2](https://github.com/CaiJinyc/game-mineSweepinng/blob/master/img/demo2.png)![demo3](https://github.com/CaiJinyc/game-mineSweepinng/blob/master/img/demo3.png)![demo4](https://github.com/CaiJinyc/game-mineSweepinng/blob/master/img/demo4.png)

## 功能
#### 实现的功能
基本扫雷的功能都实现了，例如：
* 计时
* 选择游戏难度
* 标记地雷（插旗子标记地雷，标记之后不能点击）
* 剩余雷数（总的雷数减去插旗的数量）
* 自动连锁点开（当点开某个区块后，如果该区块的数字为 0，也就是九宫格内没有雷，那么将自动点开九宫格内的所有区块）

还做了点小彩蛋，例如：踩到地雷时，地雷会逐步显示，还有成功扫到所有雷之后，地图逐渐被彩色方块覆盖，然后提示扫雷成功。

#### 没有实现的功能
自定义，问号标记（偷懒了偷懒了，说不定以后会补上呢 *（鬼才会信吧）*）。
