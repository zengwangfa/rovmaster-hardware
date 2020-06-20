<div align="center">
  <a href="https://github.com/zengwangfa/rov-master"><img src="https://zengwangfa.oss-cn-shanghai.aliyuncs.com/rov/rovmaster1.jpg" alt=""></a>
  <a href="https://github.com/zengwangfa/rov-master"><h1>Rov-Master</h2></a>
</div>

<div align="center">
  <a href="https://www.altium.com.cn/"><img src="https://img.shields.io/badge/Tool-Altuim%20Designer-orange" alt="Tool"></a>
  <a href="http://wiki.friendlyarm.com/wiki/index.php/NanoPi_NEO_Core/zh"><img src="https://img.shields.io/badge/CPU-H3-brigreen.svg?style=flat-square" alt="Device"></a>
  <a href="https://img.shields.io"><img src="https://img.shields.io/github/repo-size/ROV-Master/rovmaster-hardware?style=flat-square" alt="Size"></a>
</div>

## 1.ROV Master 硬件说明:pencil2:

> 电源供电为DC300V，主板基于NanoPi NEO Core，外部扩展PWM、ADC

| 序号 | 文件夹名 | 用途 |
| :---: | :---: | :---: |
| 1 | ROV Master Interface Board | 接线板，插入主板，用于给PWM设备信号线接入 |
| 2 | ROV Master Mainboard | 主板，主控 |
| 3 | ROV Master Powerboard | 舱内电源板，为设备提供1500W电源输出 |
| 4 | ROV Master Ground Station | 地面站，提供通信转接及高压直流电源 |
| 5 | MP1584 VRM | 低压电源模块，峰值3A |



## 2.ROV Master 硬件进展:family:

- [x] 舱内电路设计
	- [x] 接线板 by [@Ian](https://github.com/zengwangfa)
    - [x] Rov Master主板 by [@Ian](https://github.com/zengwangfa)	
	- [x] 舱内电源板 by [@Ian](https://github.com/Hyf338)

- [ ] 地面站

- [x] 深度传感器
	- [x] MS5837 I2C版本 by [@Ian](https://github.com/zengwangfa)	
	- [x] SPL1301 I2C版本 by [@Ian](https://github.com/zengwangfa)		 
	- [ ] MS5837 UART自带解算版本
	- [ ] SPL1301 UART自带解算版本	

- [ ] 电调
	- [ ] 单向电调
	- [ ] 双向电调
	
- [ ] 9轴模块

- [ ] 水下监控摄像头

- [ ] 探照灯

- [ ] 舵机调试器	
	
- [ ] 稳压电源
	- [ ] AC-DC 稳压电源
	- [x] DC-DC 24V/3A 降压模块
	
	
#### Github下载过慢
- [Github下载过慢解决办法](https://blog.csdn.net/wangshuaiwsws95/article/details/104730741/)
	
#### 参与贡献
- Fork 本仓库
- 新建分支
- 提交
- 新建 Pull Request
- [点击联系我](Mailto:zengwangfa@outlook.com)