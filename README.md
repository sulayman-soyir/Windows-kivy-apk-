关键词说明：
Kivy：kivy是开源Python函式库，用于开发行动应用程序和其它采用自然用户界面的多点触控应用软件。它可以在Android，iOS，Linux，OS X和Windows执行。采用MIT授权条款，Kivy是自由并且开源的软件------摘自《百度百科》

Buildozer：Buildozer是一款旨在轻松打包移动应用程序的工具。 它自动化整个构建过程，下载python-for-android，Android SDK，NDK等先决条件。Buildozer在您的应用程序目录中管理一个名为buildozer.spec的文件，描述您的应用程序要求和设置，如标题，图标，包含的模块等。它将使用规范文件为Android，iOS等创建一个安装包。------译自Buildozer日志网站https://buildozer.readthedocs.io/en/latest/
不幸的是，buildozer工具只工作于linux系统，所以在Windows系统就需要安装linux虚拟环境。我试过ubuntu18.04桌面版，但是可能由于我的系统配置太低，总感觉整个配置过程特别慢而且感觉笨重，在这里推荐使用xubuntu，去官网就可以下载，使用起来相对更加轻便。（如果电脑上已安装ubuntu虚拟机可仍然按照此教程进行配置）

目的：
在Windows系统下的xubuntu虚拟机上安装buildozer工具，以及其他相关工具，将kivy（python）程序打包成可以在手机上安装的apk文件。
