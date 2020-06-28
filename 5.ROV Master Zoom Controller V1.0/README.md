<p align="center">
  <img src="https://zengwangfa.oss-cn-shanghai.aliyuncs.com/rov/sub_master(vector).png"/>
</p>


<p align="center">
  <a href="https://www.altium.com/"><img src="https://img.shields.io/badge/tool-Altuim Designer-brigreen.svg?style=flat-square"></a>
  <a href="https://img.shields.io"><img src="https://img.shields.io/github/repo-size/ROV-Master/rovmaster-hardware?style=flat-square" alt="Size"></a>
</p>




# 1.新增加的特性

- 使用`MCU` STM32F103C8T6 
- 增加`CP2102`  USB转UART模块进行调试
- 使用A4988步进电机驱动模块

  

# 2.说明

[A4988 文件夹](https://github.com/ROV-Master/rovmaster-hardware/tree/master/5.ROV Master Zoom Controller V1.0/A4899) 存放A4988步进电机驱动芯片datasheet、尺寸图



# 3.后续改进的地方

### 3.1 设计缺陷
- A4988驱动器为驱动8~35V步进电机，若为低压步进电机可以使用[DRV8834驱动模块](https://www.pololu.com/product/2134) 

![A4988步进电机励磁序列](https://zengwangfa.oss-cn-shanghai.aliyuncs.com/rov/A4988_sequence_of_excitation.png "A4988步进电机励磁序列")

![变焦镜头步进电机励磁序列](https://zengwangfa.oss-cn-shanghai.aliyuncs.com/rov/focus_camera_sequence_of_excitation.png "变焦镜头步进电机励磁序列")

- 由上图可知，但是由于变焦镜头步进电机节拍表与普通的并不一致，因此此类型的驱动模块并不适用
### 3.2 解决方案
- 因而需要使用最原有方案，利用达林顿管芯片进行驱动(eg.ULN2803、ULN2003驱动芯片)
- ULN2003为7通道达林顿管，但是变焦镜头有2个4相步进电机，因此使用ULN2803驱动芯片（8通道）

