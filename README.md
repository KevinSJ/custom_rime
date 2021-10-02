RIME and TRIME config
---
此repo用于存放个人使用的Rime和Trime(同文输入法)配置文件

日常使用小鹤双拼作为输入方案，同时辅以自定义同文输入法中的自定义主题

### 使用方法
将此repo的所有文件复制到Rime程序文件夹, 不同平台位置不同, 在此不在赘述
复制完成后，需要重新部署。

Android 上的同文输入法在选择部署之后会崩溃，这可能是因为词库过大的关系无法在手机上正常编译的关系(大约32Mb)。

我个人的解决方案是在PC上编译完成后，将build文件夹的词库相关bin文件直接复制到手机的build文件夹中。

已在Windows 7 和 Linux 系统中测试相关输入法方案，均成功。

### 参考资料及感谢
https://github.com/rime -- rime是最好用的输入法引擎，没有之一
https://github.com/osfans/trime -- 同文输入法，开启安卓上使用rime的可能性
https://github.com/fkxxyz/rime-cloverpinyin -- 大部分词库从此处得来
https://placeless.net/blog/rime-squirrel-customization-2021 -- 参考部分双拼配置
https://github.com/cxcn/danjing -- 单静主题, 用于安卓上的同文输入法

