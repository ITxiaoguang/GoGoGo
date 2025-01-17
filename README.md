<p align="center">
<img src="./docs/LOGO.png" height="80"/>
</p>

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/ZCShou/GoGoGo?logo=github)](https://github.com/ZCShou/GoGoGo/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ZCShou/GoGoGo?logo=github)](https://github.com/ZCShou/GoGoGo/network)
[![license](https://img.shields.io/github/license/ZCShou/GoGoGo)](https://github.com/ZCShou/GoGoGo/blob/master/LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
</div>

<div align="center">
影梭 - 用于 Android 8.0+ 的无需 ROOT 权限的虚拟定位软件。
</div>

##
&emsp;&emsp;影梭是一个基于 Android 调试 API + 百度地图实现的虚拟定位工具，不需要 ROOT 权限，并且同时实现了一个可以自由移动的摇杆。

&emsp;&emsp;项目源码同时上传了 [Gitee](https://gitee.com/zcshou/gogogo) 和 [Github](https://github.com/ZCShou/GoGoGo)，传送门： https://gitee.com/zcshou/gogogo 或 https://github.com/ZCShou/GoGoGo ，鉴于 Github 访问缓慢，大家可以去 Gitee。

下载地址：[发行版](https://gitee.com/zcshou/gogogo/releases/)

## 背景
&emsp;&emsp;之前在玩一款 VR 游戏：一起来捉妖。为了省事，就想有没有可以更改位置的 APP。经过一番摸索发现确实有不少可以修改位置的 APP。但是，绝大多数这种 APP 都是收费的！我比较感兴趣的是这样的技术是如何实现的，因此决定研究研究自己写一个！

现在游戏已经弃坑了，但是技术不能丢，因此开源出来大家一起学习！但是请注意：

1. 该 APP 仅仅是为了学习 Android + 百度地图的实现方法，请勿用于游戏作弊！
2. 该 APP 仅仅是为了学习 Android + 百度地图的实现方法，请勿用于游戏作弊！
3. 该 APP 仅仅是为了学习 Android + 百度地图的实现方法，请勿用于游戏作弊！

重要的事情说三遍！否则后果自负！

## 功能
1. 定位修改
2. 摇杆控制移动
3. 历史记录
4. 位置搜索
5. 直接输入坐标

## 截图
![摇杆类型.jpg](./docs/摇杆类型.jpg)
![位置搜索与记录.jpg](./docs/位置搜索与记录.jpg)
![悬浮窗地图_坐标输入.jpg](./docs/悬浮窗地图_坐标输入.jpg)

## 用法
1. 下载 APK 直接安装
2. 启动软件，赋予相关权限
3. 单击地图位置，然后点击启动按钮

## 文档
&emsp;&emsp;由于本人并不是做移动开发的，很多功能代码写的都比较差。我也第一次写  Android APP，目前还处在学习中。。。此外，就一个简单的 APP，应该也不需要啥文档，开发过程中遇到的一些问题，我一般都会记录在个人博客中，具体参见：https://blog.csdn.net/zcshoucsdn/category_10559121.html

&emsp;&emsp;如果有疑问可以直接搜索 ISSUE 或者 在上面直接提交问题。

## 参考
&emsp;&emsp;由于本人也是个新手，纯属业余瞎搞，因此，在写影梭的过程中，参考了很多网友分享的技术文章、示例代码等。包括但不限于以下列出的几个：
1. https://github.com/Hilaver/MockGPS
2. https://github.com/bxxfighting/together-go
3. https://github.com/P72B/Mocklation

&emsp;&emsp;还有些 CSDN 上的文章，目前不记得地址了，如果您发现其中有直接引用或借鉴您的地方，请与我联系，我会再第一时间进行处理，谢谢！

## FAQ
Q：为何不支持 Android 8.0 以下版本？

A：因为手里没有机器无法进行适配。。。

Q：为何定位不稳定，总是会飘回真实位置？

A：这是是由于实现原理导致的，Android 调试 API 固有的问题。确切的说，应该是手机开启了其他定位方式，例如，基站定位、wifi定位等

Q：是否支持鸿蒙系统？

A：经过部分网友测试，影梭可以在鸿蒙系统上正常运行。

## 如何贡献
1. FORK -> PR
2. 加入影梭开发，共同完善

## 许可证
GPL-3.0 © ZCShou


