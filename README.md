# R720hackinsh
# 请注意本项目仅支持10.15.7版本。其他版本不保证可用
# 已将本机三码抹除，如要使用请先生成3码再使用
联想拯救者R720黑苹果clover配置  
我的型号是17年拯救者r720，I57300hq，10502g，螃蟹网卡  
除自带网卡、蓝牙和独显不能使用外，其他一切正常  
触摸板驱动使用voodoops2系列。白果手势均可使用  
本项目主要来自[jonny-china](https://github.com/Jonny-china/R720-15IKBN-Hackintosh/tree/10.15)的配置在此基础上完善了睡眠和数字小键盘。  
如果睡眠不正常，请执行以下命令sudo pmset -a hibernatemode 0和sudo pmset -b hibernatemode 0。如果要使用USB网卡或者无线鼠标接收器请使用hackintool将对应的USB端口设置为内建即internal。

如果发现关于本机—系统报告—电源，里面有很多计划事件，可以尝试关闭屏幕使用时间和删除自带的提醒事项APP，然后执行sudo pmset schedule cancelall
