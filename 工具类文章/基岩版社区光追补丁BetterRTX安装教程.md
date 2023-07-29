基岩版社区光追补丁 Better RTX 运行安装程序闪退的解决方案

这是一篇临时文章，更多的内容补充和格式完善将在未来更新

------

> 官方的 Discord 链接：https://discord.gg/minecraft-rtx-691547840463241267
> 安装程序下载直链：https://ghproxy.com/github.com/ABUCKY0/BetterRTX-Installer/releases/download/v1.0.0/BetterRTX_Installer.ps1


# 前言  
Better RTX 的安装过程中需要运行官方的 PowerShell 安装程序，而这个过程中可能脚本窗口直接闪退，实际上是有报错的，只是一闪而过：![](/betterrtx/info.png)  

那么问题就比较明显了，是系统禁止运行 Powershell 脚本，而具体的解决方案就是调整其执行策略为 RemoteSigned  

# 设置执行策略  
1、使用管理员模式打开 PowerShell  
![](/betterrtx/openinadmin.png)  
2、输入 get-executionpolicy ，回车，以检查目前的执行策略，这时应该显示的是 Restricted  
3、接着输入 set-executionpolicy remotesigned，回车，然后输入Y，回车，这样就设置完成了
![](/betterrtx/set.png)

------
本文贡献者：[壹粥粥粥](https://space.bilibili.com/474001515)（编写、审查）
本文仓库：https://gitee.com/community-tut/minecraft-community-tut/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB%E6%96%87%E7%AB%A0/%E5%9F%BA%E5%B2%A9%E7%89%88%E7%A4%BE%E5%8C%BA%E5%85%89%E8%BF%BD%E8%A1%A5%E4%B8%81BetterRTX%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B.md