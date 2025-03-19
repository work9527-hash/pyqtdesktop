# Todo
- 启动页面(pyinstaller splash)
- 检查更新&一键安装、一键卸载
- 实现pybuilder一键构建
- 和设备通过usb 串口COM通信
- 

# 技术栈
- QT Designer + 模板
- PyQt5
> pip install pyqt5

使用工具
- pybuilder 构建目录结构
- pyinstaller
- Advanced  Installer

 


# 设备设计
- 设备内部各基板通过CAN通信

- 设备外部通讯接口
    - RS232
    - RS485
    - USB（cdc）
    - EtherNET
    - EtherCAT

- 外观尺寸要符合客户的安装尺寸
- 功率部分输入输出接口要与客户要求一致（避免返工 降低效率
- 设备内部功率回路要符合《电气安全距离要求》（仿真 提前规避
- 

