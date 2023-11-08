# learn_STM32F103C8T6

和江协科技学STM32F103C8T6

## Tips

* 文件最后一行必须为空行，否则会报`Xxxx\xxx.c(xx): warning:  #1-D: last line of file ends without a newline`警告。
* LED引脚区分：长引脚为正极，短引脚为负极。
* 第一次Download前，需要点击魔术棒，选择`Debug`，选择`ST-Link Debugger`右侧的`Settings`，选择`Flash Download`，选中`Reset and Run`。
* 在使用keil软件Debug时，如果不能实时刷新寄存器的值，那么有可能是因为之前关闭了菜单栏中`View`选项菜单下的`Periodic Window Update`选项框，选中后即可，或在Debug模式下选中`Toolbox`中的`Update Windows`即可。

## 相关链接

[STM32入门教程-2023版 细致讲解 中文字幕](https://www.bilibili.com/video/BV1th411z7sn/?vd_source=02dc2e4505cf6f69ca1869dda5e28eb2)
