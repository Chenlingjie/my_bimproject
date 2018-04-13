# EMSD机电工程署（Electrical & Mechanical Services Department） 
> Building Information Modelling for Asset Management (BIM-AM) Standards and Guidelines  
Version 1.0  
Nov 2017

## 目录  
1. 简介   
  1.1 概述和目标  
  1.2 建造BIM模型的切换程序  
  1.3 参考软件  
  1.4 参考标准和规范
2. 编码和编号系统  
  2.1 区码  
  2.2 建筑代码  
  2.3 学科代码  
  2.4 E＆M 系统与路由的名称及代码  
  2.5 E＆M 设备代码  
  2.6 E&M 设备编号系统  
3. 建模标准  
  3.1 模型管理  
  3.2 命名  
    3.2.1 模型命名  
    3.2.2 族命名  
  3.3 模型设置  
    3.3.1 单位和符号  
    3.3.2 位置和地理协调  
    3.3.3 工作共享和工作集  
    3.3.4 多专业协作  
  3.4 浏览器组织  
  3.5 E&M 建模系统设置  
    3.5.1 风管系统  
    3.5.2 管道系统  
    3.5.3 电缆桥架  
    3.5.4 E&M 建模路由与设备  
  3.6 样式管理  
    3.6.1 线型  
    3.6.2 线条样式  
    3.6.3 线宽  
    3.6.4 E&M 系统颜色编码  
  3.7 可维护性  
4. E&M 资产信息  
  4.1 所有系统设备的通用参数  
  4.2 不同E＆M系统的专有参数  
    4.2.1 电梯和自动扶梯  
    4.2.2 LV Switchboard  
    4.2.3 低压配电盘  
    4.2.4 HVAC系统  
    4.2.5 锅炉系统  
    4.2.6 过滤装置  
    4.2.7 FS安装  
    4.2.8 持续电力供应  
    4.2.9 防盗报警器  
    4.2.10 雷达和导航系统  
    4.2.11 微波链路系统  
    4.2.12 定时和显示系统  
    4.2.13 音频视频系统  
    4.2.14 音频电子安装  
    4.2.15 无线电电子装置  
    4.2.16 闭路电视系统  
    4.2.17 广播接收  
    4.2.18 灯光  
    4.2.19 配电  
  4.3 资产信息要求  
  4.4 COBie  
    4.4.1 COBie介绍  
    4.4.2 EMSD COBie  
    4.4.3 EMSD MEP的COBie属性  
    4.4.4 COBie Revit插件  
5. BIM-AM系统与其他系统的交互  
  5.1 建筑管理系统（BMS）/中央控制和监视系统（CCMS）/实时定位系统（RTLS）/物联网（IoT）设备/远程无线电（LoRA）网络的界面  
  5.2 将移动BIM-AM系统与RFID阅读器集成  
    5.2.1 RFID阅读器  
    5.2.2 无源RFID标签  
  5.3 与CCTV系统/相机连接  
  
附录A - 建筑规范  
附录B - 资产信息要求  
附录C - Revit的COBie扩展 

----



## Contents
1. Introduction  
  1.1 Overview and Objectives  
  1.2 Handover Procedure of As-built BIM Model  
  1.3 Reference Software  
  1.4 Reference Standards and Specifications
2. Coding and Numbering System  
  2.1 District Code  
  2.2 Building Code  
  2.3 Discipline Code  
  2.4 Names and Codes of E&M Systems and Routing  
  2.5 E&M Equipment Code  
  2.6 E&M Equipment Numbering System  
3. Modelling Standard  
  3.1 Model Management  
  3.2 Naming Conversion  
    3.2.1 Model Naming  
    3.2.2 Family Naming  
  3.3 Model set up  
    3.3.1 Unit and Symbol  
    3.3.2 Location and Geo-Coordination  
    3.3.3 Worksharing and Worksets  
    3.3.4 Cross-Disciplinary Model Coordination  
  3.4 Browser Organization  
  3.5 E&M System setup and modelling  
    3.5.1 Duct System  
    3.5.2 Pipe System  
    3.5.3 Cable Tray  
    3.5.4 Modelling E&M routing and equipment  
  3.6 Presentation Style  
    3.6.1 Line Styles  
    3.6.2 Line Pattern  
    3.6.3 Line Weight  
    3.6.4 E&M Systems Colour Coding  
  3.7 Maintainability  
4. E&M Asset Information  
  4.1 Common Parameters for Equipment of All Systems  
  4.2 Equipment Specific Parameters for Different E&M Systems  
    4.2.1 Lift and Escalator  
    4.2.2 LV Switchboard  
    4.2.3 Emergency Generator  
    4.2.4 HVAC Systems  
    4.2.5 Boiler System  
    4.2.6 Filtration Plant  
    4.2.7 FS Installation  
    4.2.8 Uninterrupted Power Supply  
    4.2.9 Burglar Alarm  
    4.2.10 Radar and Navigation System  
    4.2.11 Microwave Link System  
    4.2.12 Timing & Display System  
    4.2.13 Audio Video System  
    4.2.14 Audio Electronics Installation  
    4.2.15 Radio Electronics Installation  
    4.2.16 Closed Circuit TV System  
    4.2.17 Broadcast Reception  
    4.2.18 Lighting  
    4.2.19 Electrical Distribution  
  4.3 Asset Information Requirement  
  4.4 COBie  
    4.4.1 Introduction of COBie  
    4.4.2 EMSD COBie  
    4.4.3 COBie for EMSD MEP attributes  
    4.4.4 COBie Revit Add-in  
5. Interfacing/Integrating BIM-AM System with other systems  
  5.1 Interfacing with Building Management System (BMS) / Central Control and Monitoring System (CCMS) / Real Time Location System (RTLS) / Internet-of-Things (IoT) devices / Long Range Radio (LoRA) network  
  5.2 Integrating Mobile BIM-AM System with RFID Reader  
    5.2.1 RFID Readers  
    5.2.2 Passive RFID Tags  
  5.3 Interfacing with CCTV system/camera  
  
Appendix A - Building Code  
Appendix B – Asset Information Requirement  
Appendix C – COBie Extension for Revit 
 


