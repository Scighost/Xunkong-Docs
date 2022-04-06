---
lang: zh-CN
title: 下载安装
---

# 下载安装

## 环境要求

Windows 10 1809 及以上版本，建议升级到最新版本。

## 下载

通过以下链接下载最新版本：

[线路一](https://file.xunkong.cc/download/desktop/Xunkong.Desktop.Package.zip)

[线路二](https://scighost-generic.pkg.coding.net/xunkong/releases/Xunkong.Desktop.Package.zip)

## 安装

- 解压已下载的安装包
- 找到名为 **Install.ps1** 的文件，右键点击打开菜单
- 点击 **使用 PowerShell 运行**
- 根据提示完成后续操作
- 安装完成后，点击开始菜单的寻空图标启动应用

## 后续

后续的使用教程请浏览[帮助部分](../help/index.md)。

## 可能遇到的问题

#### 无法加载文件 Install.ps1，因为在此系统中禁止执行脚本

以管理员身份运行 PowerShell，输入 `Set-ExecutionPolicy RemoteSigned` ，然后按下回车。

上述语句的作用是允许本地计算机中未签名的脚本运行。

#### 应用安装在哪里

以 MSIX 打包的应用安装在 `C:\Program Files\WindowsApps` 文件夹内。

#### 无法安装msixbundle

安装msixbundler需要Windows 10 1809 及以上版本

> 如何查看windows版本?  

- 打开设置->关于,就可以看到windows版本了
- 打开cmd,输入`winver`即可看到windows版本

![win版本](./img/win.png)

然后,安装[应用安装程序](https://www.microsoft.com/zh-cn/p/%e5%ba%94%e7%94%a8%e5%ae%89%e8%a3%85%e7%a8%8b%e5%ba%8f/9nblggh4nns1#activetab=pivot:overviewtab),安装完成后就可以打开安装包了

![应用商店](./img/appcenter.png)

#### windows app runtime 安装失败

部分用户因为网络问题,windows app runtime下载失败  
需要在微软[官网](https://docs.microsoft.com/zh-cn/windows/apps/windows-app-sdk/downloads)下载runtime
[点击直接下载](https://aka.ms/windowsappsdk/1.0/1.0.1/windowsappruntimeinstall-1.0.1-x64.exe)

![runtime](./img/appsdk.png)
::: tip 提示
推荐使用深色模式，视觉效果更好。
:::
