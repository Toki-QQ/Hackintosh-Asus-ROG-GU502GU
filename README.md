# Hackintosh-Asus-ROG-GU502GU

中文：

这个EFI已经适配 Catalina 10.15.5 19F96 版本。

如果触摸板用不了的话，请修改DSDT里面的GPIO Pin，DSDT路径在 ACPI/patched/DSDT。 至于如何修改，请参照远景上的教程。

如果电量不能显示的话，请给DSDT打上 battery_ASUS_ROG-GU502GU 这个补丁。

睡眠：可以用
因为我只测试2个半小时，是能用触摸板唤醒的，但其他时间我没测试过，可以自行测试。

这个EFI能满足日常使用的了。

Clover内置了一个我自己设计的主题，不喜欢的话可以更换。


English:

This EFI is for Catalina 10.15.5 19F96.

If your Trackpad is disabled, please change GPIO Pin in ACPI/patched/DSDT.
Search "ETPD" in DSDT, you will find a Pin List, change it by following the results what you searched on the Google or Baidu.

If your battery is disabled, please patch battery_ASUS_ROG-GU502GU to DSDT.

Sleep: possible.
I tested it for 2.5 hours, PC can be waked up by Trackpad, but I didn't test for other time.
Please test it by yourself.

This EFI can be satisfying for daily use.

I put a theme into this EFI, which was designed by myself. You can change it in config.plist.
