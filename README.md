# AD9959驱动代码工程

## 简介
本仓库提供了一个完整的AD9959驱动程序工程，适用于基于KEIL5和STM32的开发环境。该工程包含了AD9959的多种功能实现，包括单频、PSK、FSK、ASK等模式。

## 功能特点
- **单频模式**：支持AD9959的单频输出功能。
- **PSK模式**：实现相移键控（PSK）功能。
- **FSK模式**：实现频移键控（FSK）功能。
- **ASK模式**：实现幅移键控（ASK）功能。

## 使用说明
1. **环境要求**：
   - KEIL5开发环境
   - STM32系列微控制器

2. **工程结构**：
   - `src/`：包含驱动程序的源代码。
   - `inc/`：包含驱动程序的头文件。
   - `project/`：包含KEIL5工程文件。

3. **编译与烧录**：
   - 打开KEIL5工程文件，编译工程。
   - 将生成的二进制文件烧录到STM32微控制器中。

4. **功能测试**：
   - 通过修改配置文件，选择所需的功能模式（单频、PSK、FSK、ASK）。
   - 运行程序，观察AD9959的输出结果。

## 注意事项
- 请确保STM32与AD9959的硬件连接正确。
- 在修改配置文件时，请仔细阅读注释，确保配置正确。

## 贡献
欢迎提交问题和改进建议，帮助我们完善这个驱动程序工程。

## 许可证
本工程采用MIT许可证，详情请参阅`LICENSE`文件。

## 下载链接

[AD9959驱动代码工程](https://pan.quark.cn/s/72e46a8a4961)