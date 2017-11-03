# 在模拟器中学习使用 Altizure \(Phantom 3, Inspire 1, M100 等\)

#### 支持机型

* Phantom 3 \(Pro / Adv / 4K / Standard\)
* Inspire 1, Inspire 1 Pro, Inspire 1 Raw
* Matrice 100

#### 支持的操作系统

* Windows

#### 1. 下载安装 DJI PC 模拟器

下载并安装 [模拟器](https://dev.dji.com/downloads/dev/0d63fc06-30a9-4818-9b27-66265f777cdd) 和 [驱动](https://dev.dji.com/downloads/dev/1f3df392-3026-44ed-a9a8-20caa020f6c7)。如果官网链接无法打开，可以 [使用百度网盘下载](http://pan.baidu.com/s/1dF5NjPn)。

打开 **DJI PC 模拟器**，然后点击 **Display Simulator**

![](/assets/pcsimulator_disconnected.png)

#### 2. 连接电脑与无人机

开启无人机的电源，最好不要安装桨叶。用 USB 线连接无人机和电脑。![](/assets/p3_usb.jpg)![](/assets/inspire_usb.jpg)

#### 3. 启动模拟器

输入你所在位置的 **Latitude**（纬度）和 **Longitude**（经度），点击 **Start Simulation **启动模拟器。 如果启动成功， 这个按钮会变成灰色，模拟器里也会显示当前的经纬度。![](/assets/pcsimulator_connected.png)

#### 4. 试用 Altizure

连接手机和遥控，打开 Altizure。在 app 里找到无人机的位置（启动模拟器前输入的经纬度），在附近规划并开始一个新的航点任务。

![](/assets/app_simulating.jpg)

#### 其他技巧

* 这里有 [DJI 官方教程](https://developer.dji.com/mobile-sdk/documentation/application-development-workflow/workflow-testing.html#aircraft-simulator) 介绍如何使用模拟器。
* 模拟器模式下也同样会拍摄照片，请在模拟结束后删除这些照片来释放 SD 卡的储存空间。
* 用鼠标可以拖动模拟器界面变更视角，用鼠标滚轮可以拉近或拉远。
* 右键点击模拟器界面, 点击 **setup**, 选中 **show trace**, 可以显示已飞过的航线。



