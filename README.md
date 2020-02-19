# 喷泉轨迹编辑程序Demo

## 简介

 windows 10简单测试，基本的喷泉轨迹编辑功能，未加入球体控制轨迹，仅使用键盘控制轨迹。

 **设定喷泉在三维空间中，坐标系如下图所示：**

![坐标系统](https://github.com/yyyydev/mTraceEdit/raw/master/coordinate_systems_right_handed.png "坐标系")

*图像展示在xy平面。*

 目前设定，暂有三个与喷泉有关的参数：

- X轴：喷泉投影在xz平面，与x轴的夹角*（0-360）*。

- Y轴：喷泉与y轴的夹角*(0-90)*。

- 速度：喷泉中心点，水滴向上的初始速度*(0-1.0)*。

另外，还有重力加速度、喷泉的散开角度等参数未加入设定中。

## 安装

 直接打开运行即可

## 操作说明

### 初始参数

​		点击菜单"编辑->参数"，可以设定喷泉的初始值。

### 1. 记录轨迹

​		点击菜单“动作->录制”,弹出录制时间设定对话框，点击确认开始录制。

控制按键说明：

- W->X轴的值增加。
- A->Y轴的值减小。
- D->Y轴的值增加。
- Q->速度的值减小。
- E->速度的值增加。

*说明：X轴轨迹线为**红色**，Y轴轨迹线为**绿色**，速度轨迹线为**蓝色**。*

### 2.编辑轨迹

#### 打开曲线编辑器

- 点击菜单“编辑->X轴”打开X轴曲线编辑器，通过拖拽黑色的控制点，绘制平滑的轨迹曲线。

- 点击菜单“编辑->Y轴”打开速度曲线编辑器。

- 点击菜单“编辑->速度”打开速度曲线编辑器。

#### 编辑器操作说明

- 通过`鼠标左键拖拽`黑色的控制点，控制曲线的绘制。

- 鼠标右键点击黑色的控制点，删除该控制点。

- 按住`"Ctrl"+鼠标右键`，添加控制点。

- 编辑界面有上下两条虚线，分别对应最大最小值线。

- 通过键盘`"Esc"键`退出编辑界面。
