<p align="center">
  <img src="../doc/pictures/SubMaster-logo.jpg"/>
</p>


<p align="center">
  <a href="https://www.altium.com/"><img src="https://img.shields.io/badge/tool-Altuim Designer-brigreen.svg?style=flat-square"></a>
  <a href="https://img.shields.io"><img src="https://img.shields.io/github/repo-size/ROV-Master/rovmaster-hardware?style=flat-square" alt="Size"></a>
</p>




# 1.新增加的特性

- 增加PWM端光耦隔离
- 电源输入为高压直流输入(DC300V)
- 稳压电源后端3.3V、5.0V增加TVS管(在稳压模块异常时保护后端电路)

# 2.说明

- `MainBoard.step`文件为PCB 3D视图文件
- `电源接口及电流采样`文件夹为之前原理图备份


# 3.后续可改进的地方

- 放置请勿触摸图标
- 增加DC310V测试点
- 蜂鸣器`BEEP(C0)`引脚加一个1K下拉引脚
- 地之间隔离的磁珠可以并联一个103电容(用于吸收杂波)
- TVS管标称电压(VRWM)应略大于工作电压，TVS的钳制电压(VCL)尽量大