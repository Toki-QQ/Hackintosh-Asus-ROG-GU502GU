# Hackintosh-Asus-ROG-GU502GU
English:

This EFI is only for Mojave 10.14.6 18G87. I will update after MacOS 10.16 beta.

If your Trackpad is disabled, please change GPIO Pin in ACPI/patched/DSDT.
Search "ETPD" in DSDT, you will find a Pin List, change it by following the results what you searched on the Google or Baidu.

You can display the battery power without charging. You can open the switch in the settings
If your battery is disabled, please patch battery_ASUS_ROG-GU502GU to DSDT.

Sleep: possible.
I tested it 20 minutes, system can be waked up, but I didn't test other time.
Please test it by yourselves.

This EFI can be satisfying for daily use.

I put a theme into this EFI, which was designed by myself. You can change it in config.plist.

中文：

这个EFI只适配 Mojave 10.14.6 18G87 版本，Catalina 10.15版本无法启动，但我会在10.16测试版本之后更新。

如果触摸板用不了的话，请修改DSDT里面的GPIO Pin，DSDT路径在 ACPI/patched/DSDT。 至于如何修改，请参照我教程里面提到的教程。

如果电量不能显示的话，请先拔掉充电线，再到设置里面开启电量显示即可。
如果电量还是不能显示的话，请给DSDT打上 battery_ASUS_ROG-GU502GU 这个补丁。

睡眠：应该可以用
因为我只测试了20分钟睡眠，是能唤醒的，但其他时间我没测试过，可以自行测试。

这个EFI能满足日常使用的了，后续完善难度较高，我尽量吧。

主题内置了一个我自己设计的主题，不喜欢的话可以更换。
