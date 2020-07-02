<div align="center">
  <a href="https://github.com/zengwangfa/rov-master"><img src="https://zengwangfa.oss-cn-shanghai.aliyuncs.com/rov/rovmaster(vector)1.png" alt=""></a>
  <a href="https://github.com/ROV-Master/rovmaster-hardware"><h1>ROV-Master</h2></a>
</div>

<div align="center">
  <a href="https://www.altium.com.cn/"><img src="https://img.shields.io/badge/Tool-Altuim%20Designer-orange" alt="Tool"></a>
  <a href="http://wiki.friendlyarm.com/wiki/index.php/NanoPi_NEO_Core/zh"><img src="https://img.shields.io/badge/CPU-Allwinner H3-brigreen.svg?style=flat-square" alt="Device"></a>
  <a href="https://img.shields.io"><img src="https://img.shields.io/github/repo-size/ROV-Master/rovmaster-hardware?style=flat-square" alt="Size"></a>
</div>

## 1.ROV Master 硬件说明:pencil2:

> 电源供电为DC300V，主板基于NanoPi NEO Core，外部扩展PWM、ADC，采用电力载波/光纤与[地面站](https://github.com/ROV-Master/rovmaster-hardware)进行通信.

| 序号 | 文件夹名 | 用途 |
| :---: | :---: | :---: |
| 1 | [ROV Master Interface Board](https://github.com/ROV-Master/rovmaster-hardware/tree/master/1.ROV%20Master%20Interface%20Board%20%20V2.0) | 接线板，插入主板，用于给PWM设备信号线接入 |
| 2 | [ROV Master          Mainboard](https://github.com/ROV-Master/rovmaster-hardware/tree/master/2.ROV%20Master%20Mainboard%20V3.0) | 主板，主控 |
| 3 | [ROV Master        Powerboard](https://github.com/ROV-Master/rovmaster-hardware/tree/master/3.ROV%20Master%20%20Powerboard%20%20V1.0) | 舱内电源板，为设备提供1500W电源输出 |
| 4 | [ROV Master   Ground Station](https://github.com/ROV-Master/rovmaster-hardware/tree/master/4.ROV%20Master%20Ground%20Station%20V1.0) | 地面站，提供通信转接及高压直流电源 |
| 5 | [ROV Master Zoom Controller](https://github.com/ROV-Master/rovmaster-hardware/tree/master/5.ROV%20Master%20Zoom%20Controller%20V3.0) | 变焦镜头控制板 |
| 6 | MP1584 VRM（Voltage Regulator Module） | 低压电源模块，4.5~28V输入，峰值3A，额定1.5A |
| 7 | [lib](https://github.com/ROV-Master/rovmaster-hardware/tree/master/lib) | Altium Designer 封装库 |

![舱内装配图](https://zengwangfa.oss-cn-shanghai.aliyuncs.com/rov/Chamber_structure1.jpg "舱内装配图")


## 2.ROV Master 硬件进展:family:

- [x] 舱内电路设计
	- [x] 接线板 by [@Ian](https://github.com/zengwangfa)
	- [x] ROV Master主板 by [@Ian](https://github.com/zengwangfa)	
	- [x] 舱内电源板 by [@Hyf](https://github.com/Hyf338)
- [x] 地面站 by [@Ian](https://github.com/zengwangfa)	

---

- [ ] 配件
	- [x] 变焦镜头控制板 by [@Ian](https://github.com/zengwangfa)	
	- [x] 深度传感器
		- [x] MS5837 I2C版本 by [@Ian](https://github.com/zengwangfa)	
		- [x] SPL1301 I2C版本 by [@Ian](https://github.com/zengwangfa)		 
	- [ ] MS5837 UART自带解算版本
	- [ ] 电调
		- [ ] 单向电调
		- [ ] 双向电调
	- [ ] 9轴模块
	- [ ] 水下监控摄像头
	- [ ] 探照灯
	- [ ] 舵机调试器	
	- [x] DC-DC 24V/3A 降压模块
	
	
#### Github下载过慢
- [Github下载过慢解决办法](https://blog.csdn.net/wangshuaiwsws95/article/details/104730741/)
	
#### 参与贡献
- Fork 本仓库
- 新建分支
- 提交
- 新建 Pull Request
- [点击联系我](Mailto:zengwangfa@outlook.com)