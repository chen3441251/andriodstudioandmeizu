# andriodstudioandmeizu
修复魅族与模拟器无法共存androidstudio问题

1.在C:\用户\<你的用户名>\.android\adb_usb.ini文件，在第二行加“0x2a45”，如果没有这个文件，添加一个，把这一行复制进去。

2.把手机usb模式设置成MTP模式

3.重新启动 ADB
