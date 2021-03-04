# MAGPIE <small>v0.1</small>

窗口放大镜！

可以将任意窗口全屏显示，支持高级缩放算法，包括 Jinc2、[Anime4K](https://github.com/bloc97/Anime4K)（本项目包含一个hlsl移植）、Lanczos6等。

主要用于游戏窗口的放大显示，适用于那些不支持全屏模式，或者游戏自带的全屏模式会使画面模糊的情况。

本项目还处于早期阶段，欢迎fork和star，欢迎任何形式的贡献。

注意：欲使用本程序你需要一个性能足够的GPU，尤其是使用Anime4K缩放模式时。

## 窗口截图

![image-20210303215055446](img\窗口截图.png)

使用方法：程序启动后，激活要放大的窗口，按下热键即可全屏显示该窗口，再次按下热键将退出全屏。

目前缩放模式仅支持通用（Jinc2+自适应锐化）以及Anime4K（Anime4K+HQBicubic）。（程序内使用json，因此你可以轻松地组合出自己的缩放模式）

## 效果截图

*以下图像均只用于演示目的*

#### 通用模式

源窗口

![通用_源](img\通用_源.png)

放大后

![通用_放大后](img\通用_放大后.png)

#### Anime4K模式

源窗口

![Anime4K_源](img\Anime4K_源.png)

放大后

![Anime4K_放大后](img\Anime4K_放大后.png)

## 已知限制

由于实现的限制，在帧数较低时鼠标将运动迟缓。目前不支持使用自定义鼠标的窗口。

## 开发计划

见 [Milestones](https://github.com/Blinue/Magpie/milestones)

