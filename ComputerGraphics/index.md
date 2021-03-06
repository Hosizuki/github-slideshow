# 计算机图形学

## 环境搭建

### 本地模式
- Edge：直接运行
- Chrome：`chrome --allow-file-access-from-files`

### 服务器模式
- Python2：`python -m SimpleHTTPServer`
- Python3：`python -m http.server`

## My Platform
> 本程序仅为展示各种变换及渲染效果，物体可移动旋转删除，是为创造模式。娱乐模式参见OnlyMyCube，物体基本锁定，不可随意移动。

![效果图](http://m.qpic.cn/psc?/V11as4g42Pug3I/I4FpFoYXzdFm.OkebEsY*lJYietdUjRnW4Hj0WEA2ehW0u1XLm2jODItMitatOjB2Erf*bPju9SJ0UcsXUcs3TWpG*syrD.WGXN69oYvqNU!/b)

### 键盘控制
* V/Y/T/B/F/H：物体移动（前后上下左右）
* W/S/A/D：光源移动（上下左右）
* I/K/J/L：相机移动（前后左右）
* P：改变视角模式
* Q：改变光照模式
* Del：删除物体
* 空格：开始/暂停渲染

### 鼠标控制
* 物体选定：出现选取标志
	* 左键拖动：移动物体
	* 滚轮滚动：改变大小
	* 右键拖动：旋转物体
	* 双击：加锁（锁定地面）/解锁
* 默认选定：相机
	* 左键拖动：相机平移
	* 滚轮滚动：调节远近
	* 右键拖动：相机旋转
	* 双击：开始/停止自动旋转

### 渲染模式
* 宝贝球：纯色
* 老虎：带明暗
* 萝莉：带纹理
* 手机：明暗+纹理
* 新科娘（不建议加载）：明暗+纹理

### 在线演示

[demo](https://hosizuki.github.io/github-slideshow/ComputerGraphics/MyPlatform/MyPlatform.html)

## Only My Cube

![效果图](http://m.qpic.cn/psc?/V11as4g42Pug3I/I4FpFoYXzdFm.OkebEsY*qA0UtuIMaeAK7Mz.o2byv1*fJ3fJWxafTDYVZkeJ*Zk*VJ9m2L.qNJt*Nks1ItgN8YoWNgPK0nv5v7s*OGn0C0!/b)

### 键盘控制
* B：控制转向
* P：转换视角模式 正交/透视（不建议使用）
* F5：刷新重新游戏
* Z：增加游戏难度
* X：减小游戏难度
* Delete：删除选中物体（把碰撞检测方块删了就是无敌模式，不建议使用）
* 自动模式：按A键进入
* 空格：开始/暂停
* 左键单击：选择物体

### 鼠标控制
* 左键（触屏）单击：选择物体/开始/转向

### 在线演示

[demo](https://hosizuki.github.io/github-slideshow/ComputerGraphics/OnlyMyCube/OnlyMyCube.html)
