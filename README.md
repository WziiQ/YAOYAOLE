# 2020年新工科联盟-Xilinx暑期学校（Summer School）项目
# 项目名称：摇摇乐
# 小组成员：张智杰 桑泽田
# 项目概述：
利用板载陀螺仪读取姿态数据，通过ESP32的WIFI联网，进行摇摇乐的实现
# 板卡型号
xc7s15ftgb196-1
# 外设
无
# 项目流程概述：
# 开发板
1.将esp32与fpga通过qspi协议进行通信。  

2.使用vivado进行bit流生成。

3.用tf卡上传到板子上进行烧录。
# Arduion
1.对于开发板进行烧录。

2.编程实现对于陀螺仪原始数据的处理。

3.编写计数器模块进行计数。

4.通过串口监视器查看。
# AWS
1.Iot-core中创建things，策略，进行关联。

2.本地下载证书，进行esp32与aws iot的连接。

3.上传数据至aws。

4.订阅MQTT主题观察数据。
# 仓库目录介绍
# ExecutableFiles
1.bit文件
# Sourcecode
1.esp32完整工程

2.fpga完整工程
# images
1.arduion端示意图

2.aws端示意图

3.系统组成


