# F18-Shifter-FOR-Simrace

## 注意事项 | Caution
**本项目禁止商用**。任何将本项目用于商业用途的行为均属违法，本人将保留追究法律责任的权利。
This project is **NOT FOR COMMERCIAL USE**. Any commercial use of this project is illegal, and I reserve the right to pursue legal liability.

## 项目介绍 | Project Introduction
这是一个帮助你打造适用于模拟赛车的宝马F18挂挡杆的项目，无需高额成本、无需丰富电子开发经验，即可轻松获得模拟赛车挂挡的真实乐趣。
This is a project that helps you build a BMW F18 shifter for sim racing. You can easily get the real fun of sim racing shifting without high cost or rich electronic development experience.

## 硬件设备 | Hardware
1. Arduino Leonardo R3 开发板 (Arduino Leonardo R3 Development Board)
2. BMW Shifter F18 9296904-01 (Original BMW F18 Shifter, Part No.: 9296904-01)
3. MCP2515 TJA1050 SPI CAN模块 (MCP2515 TJA1050 SPI CAN Module)
4. 12V PowerAdapter（2A）电源适配器 (12V Power Adapter, 2A Output)
5. Wires 连接线束 (Connecting Wire Harness)

## 软件设备 | Software
1. Arduino IDE 开发程序 (Arduino IDE Development Software, download link: https://www.arduino.cc/en/software)
2. 此仓库的代码 | Code in this Project (Directly download the code files in this repository for use)

## 许可协议 | License
本项目采用 [CC BY-NC-ND 4.0](LICENSE) 许可协议，即署名-非商业性使用-禁止演绎 4.0 国际许可协议，使用前请务必阅读完整许可条款。
This project is licensed under the [CC BY-NC-ND 4.0](LICENSE) (Attribution-NonCommercial-NoDerivs 4.0 International License). Please be sure to read the complete license terms before use.

## 简单使用说明 | Simple Usage Guide
1. 按照硬件清单准备所有设备，参照常规电路连接规范，完成挂挡杆、CAN模块与Arduino开发板的接线；
   Prepare all devices according to the hardware list, and complete the wiring of the shifter, CAN module and Arduino development board in accordance with conventional circuit connection specifications;
2. 下载并安装Arduino IDE，在IDE中导入本仓库的代码文件；
   Download and install Arduino IDE, and import the code files of this repository into the IDE;
3. 将Arduino开发板通过USB连接电脑，在IDE中选择对应开发板型号与端口，完成代码烧录；
   Connect the Arduino development board to the computer via USB, select the corresponding development board model and port in the IDE, and complete the code burning;
4. 烧录完成后，连接12V电源适配器，即可将挂挡杆作为游戏控制器接入模拟赛车游戏使用。
   After the burning is completed, connect the 12V power adapter, and the shifter can be used as a game controller to connect to the sim racing game.