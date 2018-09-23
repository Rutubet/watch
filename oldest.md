<a href="index.md">back</a>

### 2018-06-21(Beat0.0.1a & cap)
* 通过更新cap来增加代码可读性
* 把形状统一归为MPShape类

### 2018-06-22(Beat0.0.1b & cap)
* 把按钮优化了一下，增加代码可读性

### 2018-06-30(Beta0.0.1c & cap)
* 增加3个按钮，一个在右边，两个分别在上右和上左。
* 更新的同时发现cap的缺陷并更新
* 由于未知原因，MPShape创建的Shape很奇葩

### 2018-7-1(Beta0.0.1d & cap)
* 设置upRightBtn关闭Watch
* 修复2018-6-30发现的bug，其实质为MPButton类的public void setBounds(int x, int y)方法出错。
* 优化MPShape类，不会有那么多重复的点了

### 2018-7-3(Beta0.0.1e & cap)
* 在cap中添加NixieTube类，起到数码管的功能
* 时间日期相关更新为java8的时间日期
* 可能会加重CPU的负担从而引发卡顿

### 2018-7-11(Beta0.0.1f)
* 更新了按钮的一个开场动画
* 设置按钮已更新
* 整理了一下代码
* 更新了自动吸附

### 2018-7-12(Beta0.0.1g)
* 更新了界面一开始缓慢从上到下展开的一个开场动画

### 2018-8-5(Beat0.0.1h & cap)
* 在cap中更新了轻量级的布局管理器，现在不需要手动居中了，自动居中
* 运用在watch中的数码管的位置.
* 但只支持从上到下.

### 2018-8-7(Beat0.0.1i & cap)
* 增加了downLeftBtn和downRightBtn，就是左下角和右下角两个按钮，但是并没用实际作用
* 在liren.mp.style中加入一个类MPSegment作为分割线
* 在主界面增加了分割线.
* 拖动窗口只能在上分割线的上面，或者是下分割线的下面.

### 2018-8-15(wav)
* 更新了几个wav文件,打算用于watch<br/>
* [500Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/500Hz.wav)<br/>
* [600Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/600Hz.wav)<br/>
* [700Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/700Hz.wav)<br/>
* [800Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/800Hz.wav)<br/>
* [900Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/900Hz.wav)<br/>
* [1000Hz.wav](https://github.com/Rutubet/watch/raw/master/wavs/1000Hz.wav)<br/>
* [ringing.wav](https://github.com/Rutubet/watch/raw/master/wavs/ringing.wav)<br/>

### 2018-8-16(cap)
* cap更新了liren.math包，使得创建的坐标系可以缩放移动，函数可以正常绘制
  > 得出经验,for循环千万不要用float或double,因为它们运算不准确，即使是那么一点点.更不要去用BigDecimal.

### 2018-8-18(Beta0.0.1j & cap)
* 更新了数码管的一个构造方法，使其代码变得更加简洁.
* 更新了星期显示，在秒的后面

### 2018-8-19(Beta0.0.1k)
* 整理代码，将MainCanvas长度缩短.
* 尝试面板拖拽,成功，但无自动吸附
* 添加数码管的底色，但在背景为黑色时不明显

### 2018-8-20(Beta0.0.1l)
* 添加设置窗口(UI是java自带的)
* 有本地保存功能.
* 修复了设置按钮不上下对齐的bug.
* 增加恢复至默认设置功能
 > 设置是否总在最前，是否使用24小时进制，是否绘制数字的底色，自动保存当退出时窗口的位置，并在下次打开时还原窗口的位置

### 2018-8-21(Beta0.0.1m)
* 修复3个与设置有关的bug
* 修复了与按钮交互整个主界面会闪烁的问题.

### 2018-8-22(Beta0.0.1n)
* 只有左键才能拖动，右键才能滑动
* 添加在主界面内按Ctrl+c可以复制当前时间，比如
  > 2018-08-22T19:39:59.834
* 测试计时功能，但还未实际运用


### 2018-8-23(Beta0.0.2)
* 按Q暂时查看时间
* 按E转到计时面板
* 在计时面板中按R可以开始计时/暂停计时/清零
* 按W到上一个面板
* 按S到下一个面板

### 2018-8-27(cap)
* 增加了类AbstractSystem来使坐标系更人性化
* 修改了Function类和RectangularCoordinateSystem类使其更人性化

### 2018-8-30(Beta0.0.2 & cap)
* 修改了原星期三010000010000010为000010000101000
* 测试了变色功能，实质为XOR mode

### 2018-8-31 (Beta0.0.2 & cap)
 * 修改了类AbstractSystem来使坐标系更人性化
 * 修改了Function类和RectangularCoordinateSystem类使其更人性化
 * 删除了AbstractAnimation类
 * 改IndependentAnimation类为Animation类
 * 增加了AnimationManager类管理Animation

### 2018-9-1 (Beta0.0.2 & cap)
 * 增加了liren.jar包，里面增加Jar类，用以运行Jar
 * 使用了Lanucher类简化Main类
 * 现在会自动更新了 
 * 更新完成后点击鼠标右键进入正常界面
 * 使用了Apache的FileUtils下载文件

### 2018-9-2 (Beta0.0.2a)
* 现在如果Watch没有焦点，那边框会变黑，有焦点时正常显示边框，
 > PS:只有在有焦点时才能进行正常的键盘操作
* 新增Icons类来管理图标
* 新增函数按钮，但无实际功能

### 2018-9-6 (Beta0.0.2b)
* 自动更新完毕之后，过5秒会自动切换到正常界面

### 2018-9-7 (cap)
* 新增InterpolationAnimation类
* 新增Vector2D类

<a href="index.md">back</a>
