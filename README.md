# 谷歌拼音输入法/PinyinIME

## 介绍
1. 该源码基于AOSP中android/platform/packages/inputmethods/PinyinIME修改，commit id 为 49aebad1c1cfbbcaa9288ffed5161e79e57c3679，[下载地址]((https://android.googlesource.com/platform/packages/inputmethods/PinyinIME/))
2. 由于官方源码2014年停止更新，无法用AndroidStudio编译工程，该工程修改了部分代码用以实现在 AndroidStudio编译和打包
3. 手机上安装后，需要在 设置-更多设置-输入法 中勾选PinyinIME，才能使用该输入法输入
4. 修改了输入NSS崩溃的问题，修改横屏不能全屏的问题，修改了部分布局，添加了一些注释

![image](https://github.com/WKingdom/PinyinIME/blob/master/screenshot/main.jpg)


