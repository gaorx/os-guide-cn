# 从零开始制作一个操作系统！

这只是我个人的学习项目，欢迎 fork 这个仓库。

2022 年更新，内容有所修改，原始仓库在[这里](https://github.com/cfenollosa/os-tutorial)。

## 特点

- 理论很少，不需要很深的理论基础。是的，这是一个很大的特点 - Google 就是你最好的理论导师。
- 教程很简短，你只需要花费少量时间就可以读完。

## ⚠️ 注意

请自行修改 Makefile 文件！

## 📒 备注

`x86_64-elf-gcc` 需要添加`-m32`参数，`i386-elf-gcc`已经废弃。

## 目录

[01、前期准备](https://github.com/gaorx/os-guide-cn/blob/main/01.%E7%8E%AF%E5%A2%83%E5%87%86%E5%A4%87)

[02、引导扇区](https://github.com/gaorx/os-guide-cn/blob/main/02.%E5%BC%95%E5%AF%BC%E6%89%87%E5%8C%BA)

[03、引导打印](https://github.com/gaorx/os-guide-cn/blob/main/03.%E5%BC%95%E5%AF%BC%E6%89%93%E5%8D%B0)

[04、引导内存](https://github.com/gaorx/os-guide-cn/blob/main/04.%E5%BC%95%E5%AF%BC%E5%86%85%E5%AD%98)

[05、引导栈](https://github.com/gaorx/os-guide-cn/blob/main/05.%E5%BC%95%E5%AF%BC%E6%A0%88)

[06、函数和字符串](https://github.com/gaorx/os-guide-cn/tree/main/06.%E5%87%BD%E6%95%B0%E5%92%8C%E5%AD%97%E7%AC%A6%E4%B8%B2)

[07、引导段](https://github.com/gaorx/os-guide-cn/tree/main/07.%E5%BC%95%E5%AF%BC%E6%AE%B5)

[08、引导扇区磁盘](https://github.com/gaorx/os-guide-cn/blob/main/08.%E5%BC%95%E5%AF%BC%E6%89%87%E5%8C%BA%E7%A3%81%E7%9B%98)

[09、32 位打印](https://github.com/gaorx/os-guide-cn/tree/main/09.32%E4%BD%8D%E6%89%93%E5%8D%B0)

[10、32 位 GDT](https://github.com/gaorx/os-guide-cn/tree/main/10.32%E4%BD%8D-gdt)

[11、32 位输入](https://github.com/gaorx/os-guide-cn/tree/main/11.32%E4%BD%8D%E8%BE%93%E5%85%A5)

[12、内核交叉编译器](https://github.com/gaorx/os-guide-cn/tree/main/12.%E5%86%85%E6%A0%B8%E4%BA%A4%E5%8F%89%E7%BC%96%E8%AF%91%E5%99%A8)

[13、内核 - C](https://github.com/gaorx/os-guide-cn/tree/main/13.%E5%86%85%E6%A0%B8-C)

[14、内核准系统](https://github.com/gaorx/os-guide-cn/tree/main/14.%E5%86%85%E6%A0%B8%E5%87%86%E7%B3%BB%E7%BB%9F)

[15、检查点](https://github.com/gaorx/os-guide-cn/tree/main/15.%E6%A3%80%E6%9F%A5%E7%82%B9)

[16、视频端口](https://github.com/gaorx/os-guide-cn/tree/main/16.%E8%A7%86%E9%A2%91%E7%AB%AF%E5%8F%A3)

[17、视频驱动程序](https://github.com/gaorx/os-guide-cn/tree/main/17.%E8%A7%86%E9%A2%91%E9%A9%B1%E5%8A%A8%E7%A8%8B%E5%BA%8F)

[18、视频滚动](https://github.com/gaorx/os-guide-cn/tree/main/18.%E8%A7%86%E9%A2%91%E6%BB%9A%E5%8A%A8)

[19、中断](https://github.com/gaorx/os-guide-cn/tree/main/19.%E4%B8%AD%E6%96%AD)

[20、中断 - irqs](https://github.com/gaorx/os-guide-cn/tree/main/20.%E4%B8%AD%E6%96%AD-irqs)

[21、中断定时器](https://github.com/gaorx/os-guide-cn/tree/main/21.%E4%B8%AD%E6%96%AD%E5%AE%9A%E6%97%B6%E5%99%A8)

[22、Shell](https://github.com/gaorx/os-guide-cn/tree/main/22.shell)

[23、malloc](https://github.com/gaorx/os-guide-cn/tree/main/23.malloc)

[24、Fixes](https://github.com/gaorx/os-guide-cn/tree/main/24.fixes)

[25、el-capitan](https://github.com/gaorx/os-guide-cn/tree/main/25.el-capitan)

## 有用的教程

[The little book about OS development](https://littleosbook.github.io/)

[Roll your own toy UNIX-clone OS](https://web.archive.org/web/20160412174753/http://www.jamesmolloy.co.uk/tutorial_html/index.html)
