## 说明
此为Watch和cap的更新计划列表及更新日志,本界面的样式并非本人所作，我只是写结构.

### 2018-06-21(Beat0.0.1a & cap)
通过更新cap来增加代码可读性
把形状统一归为MPShape类

### 2018-06-21(Beat0.0.1b & cap)
把按钮优化了一下，增加代码可读性

### 2018-06-30(Beta0.0.1c & cap)
增加3个按钮，一个在右边，两个分别在上右和上左。
更新的同时发现cap的缺陷并更新
由于未知原因，MPShape创建的Shape很奇葩

### 2018-7-1(Beta0.0.1d & cap)
设置upRightBtn关闭Watch
修复2018-6-30发现的bug，其实质为MPButton类的public void setBounds(int x, int y)方法出错。
优化MPShape类，不会有那么多重复的点了

### 2018-7-3(Beta0.0.1e & cap)
在cap中添加NixieTube类，起到数码管的功能
时间日期相关更新为java8的时间日期
可能会加重CPU的负担从而引发卡顿

### 2018-7-11(Beta0.0.1f)
更新了按钮的一个开场动画
设置按钮已更新
整理了一下代码
更新了自动吸附

### 2018-7-12(Beta0.0.1g)
更新了界面一开始缓慢从上到下展开的一个开场动画

### 2018-8-5(Beat0.0.1h & cap)
在cap中更新了轻量级的布局管理器，现在不需要手动居中了，自动居中
运用在watch中的数码管的位置.
但只支持从上到下.

### 2018-8-7(Beat0.0.1i & cap)
增加了downLeftBtn和downRightBtn，就是左下角和右下角两个按钮，但是并没用实际作用
在liren.mp.style中加入一个类MPSegment作为分割线
在主界面增加了分割线.
拖动窗口只能在上分割线的上面，或者是下分割线的下面.
![picture](/imgs/2018.8.7.png)

### 2018-8-15(wav)
更新了几个wav文件,先下载再打开,打算用于watch
[500Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/500Hz.wav)
[600Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/600Hz.wav)
[700Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/700Hz.wav)
[800Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/800Hz.wav)
[900Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/900Hz.wav)
[1000Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/1000Hz.wav)
[ringing.wav](https://github.com/Rutubet/watch/raw/master/wavs/ringing.wav)

### 2018-8-16(cap)
* cap更新了liren.math包，使得创建的坐标系可以缩放移动，函数可以正常绘制
  > 得出经验,for循环千万不要用float或double,因为它们运算不准确，即使是那么一点点.更不要去用BigDecimal.
