# joystick:bit
[English](README.md) 中文版

joystick:bit为   [深圳市易创空间科技有限公司](www.emakefun.com)出品的针对micro:bit开发的无线可编程手柄，支持micro:bit V1 V2

![image](imgs/joystickbit.jpg)

## 特点

- 左右双摇杆

- 手柄扩展microbit A，B按键

- 左右可编程独立按键

- 板子蜂鸣器和震动电机

- 2节7号电池供电

- 1个PH2.0-4Pin i2c接口 

  

## 图像化编程块说明
   - 《游戏手柄摇杆获取 左/右侧 x/y轴 的值》:该模块用于获取手柄左或者右摇杆x轴或者y轴方向的坐标值，其获取的值为数值类型，其值可以通过‘显示数字’模块显示在micro:bit板上
   - 《游戏手柄震动频率 （）》 :该模块用于调试游戏手柄上震动电机的震动频率，其值为0时震动电机停止震动。
   - 《按键 L/R/左摇杆按键/右摇杆按键 是否是 按下/释放 状态》 :该模块用于判断游戏手柄左右按键和摇杆中心按键是否按下或者释放，是返回ture,否返回false，作用于判断模块（如果...则执行...）
   - 《游戏手柄按键 L/R/左摇杆按键/右摇杆按键 是否被按下》 :该模块用于判断手柄上按钮是否按下，是返回ture,否返回false。
   - 《游戏手柄按键 L/R/左摇杆按键/右摇杆按键 是否被释放》 :该模块用于判断手柄按键是否未按住，是返回ture,否返回false。

   ![image](imgs/1.jpg)
  

### 摇杆图形化块

- 获取游戏手柄摇杆x/y轴值（获取左/右侧x/y轴的值并将其数值通过显示灯管灯显示出来）

   ![image](imgs/11.jpg)

   ![image](imgs/12.jpg)


### 独立按键编程图形块

- 按键 L/R/左摇杆按键/右摇杆按键 是否是 按下/释放 状态
- 下面模块是对按键状态进行一个判断：当你按了按键L，则显示字符串"Hello"

   ![image](imgs/21.jpg)

   ![image](imgs/22.jpg)

- 同理，下面两个模块也是对按键的按下或者未按进行一个判断，为真则显示字符串"Hello"

   ![image](imgs/23.jpg)

   ![image](imgs/24.jpg)


### 震动电机编程图形块



- 配合按键使用


### python支持



## 开源许可
MIT
