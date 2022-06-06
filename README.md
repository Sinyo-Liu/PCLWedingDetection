# PCLWeldingDetection![](./pic/logo.png)
2022毕业设计-点云焊接轨迹检测平台

#### 介绍
点云焊接轨迹检测及可视化平台-帮助文档

#### 开发架构说明
Qt5 + PointCloud-Library + VTK8.2 + OpenCV3

#### 适用平台
Windows10

#### 焊接轨迹提取操作流程

1.  导入点云文件。
2.  选中左侧数据树中将要进行焊焊接轨迹店提取的点云。
3.  菜单栏的模型中，选择目标点云所对应的模型。
4.  在弹出的下采样窗体中，输入下采样的维度(毫米mm)。
5.  点击确定，进行焊接轨迹店提取，等待结果；点击取消，关闭下采样窗体。
6.  焊接轨迹店提取结果主动显示与中间，左侧数据中以"_Welding"结尾的点云为焊接轨迹点。
7.  选中生成的焊接轨迹点云，选择菜单栏中保存按钮，保存。

#### 下采样

1.  选中数据树中想要进行下采样的点云
2.  鼠标移动至菜单栏中的“采样”
3.  点击“VoxelGrid”
4.  在弹出的窗体中输入下采样尺寸
5.  点击确定执行
6.  等待左侧数据树中产生以“_downsample”结尾的点云，即为下采样结果

#### 点云显示组件使用方法

将鼠标移至中间的点云显示模块，按键及鼠标操作如下：

1.  R键:重置点云至中心位置
2.  G键:显示/隐藏点云尺寸网格
3.  Ctrl + 鼠标左键：旋转点云
4.  Shift + 鼠标左键：平移点云
5.  鼠标滚轮/右键：拉近/放远点云
        
        
        
        


#### 点云颜色、大小更改组件

1.  选中数据树中点云，并保持显示模式(非灰色)
2.  向左或向右移动滑条，至所需颜色或尺寸值
注意：改变下一个点云前滑条位置保持不变
