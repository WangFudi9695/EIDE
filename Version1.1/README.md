新版本暂时不发出来吧，有点问题（执行包读取不出来），现在先发一个稳定版1.1

更新日志

*版本0.9（Arica）发布时间2019/9/23 21:27
就是我之前提交的版本，这个版本的特点就是只能解析一层代码，如果代码层数过多，比如使用嵌套代码，就会解析不出来，同时对各方面支持还比较差，经常卡顿和报错，这里我用了递归等数学方法在版本Birth中解决。就是因为一些莫名其妙的问题重写了多次代码。
*版本1.0（Birth） 发布时间2019/10/1 20:15
这是一个相对正式的版本，可以解决大多数会遇到的代码，不管是几层，也修复了IDE中的部分卡顿和频繁报错问题，同时优化了程序的解析代码，优化了执行包的目录结构，删除了一些不必要的文件，保证程序运行稳定，在编写之后我也单独写了一个调用手册，提供给有需要的用户使用，用于开放IDE。
此外，对主代码中一些字符处理也在执行包中继续修改，进一步的增强通用性，最后开放了一些新函数。
*版本1.1(Birth) 发布时间2019/10/7 23:10
对版本1.0进行了界面的改进，收到反馈说界面做得有些粗糙，所以我升级了界面库到版本2，但是界面库的升级导致我原来的代码失效，又重新写了一遍界面代码，改用VS2015编译器，然后改进了操作逻辑，优化了卡顿现象和数组越界。增加了部分编译器编译提示。


*版本1.2(Birth) 发布时间 2020/1/23 22:54
这次时间跨度有些大，且代码修改量十分巨大（几乎就是将三分之一的代码进行修改），但是我仍然觉得这只是一个小修改，这个原理其实就如某些软件的更新日志一样“提升稳定性”，虽然我增加功能可以让人赏心悦目，但是我并不喜欢华而不实。我也不敢说我的代码就是最稳定最高效的，但是要知道的事情是，一个软件的功能更新或者修复，背后都是有巨大的代码工程做支撑的。
好了，现在说说更新了什么：首先我更新了界面库，版本好像太新了，Windows 10 1903，我的虚拟机都没有达到这个要求，界面有些细节进行了调整，同时对编译器进行调整，然后更新了目录结构，删除了执行包中无用的冗杂数据，最后封装成了自解压包，然后录制了快速入门教程并且更新了API手册和说明文档。
*版本1.3(Birth) 发布时间 2020/2/2
整理源码，进行开源。准备提交到GitHub上。然后重新录制使用教程（有一些细节没有注意），同时更新了说明文档和API调用手册，把格式重构了。