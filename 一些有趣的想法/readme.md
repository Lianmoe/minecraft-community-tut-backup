# 一些想法

## 有用的小程序
### MinecraftTree系统
* 用于可视化分析整合包，并合理的构建MOD之间的相互依赖关系
---

## 启动器类
### 客户端
* 简易MC启动器————功能实现：
1. 扁平化设计
2. 支持多系统(可选):WIN/LINUX 
3. 支持导入/导出整合包(多种启动器)
4. N2N联机(考虑接入happynet)
5. 日志在线的抓取和分析系统
6. JAVA的高级启动参数自动设置
7. 接入某些汉化资源，可以实现在线汉化


### 服务端
* 简易MC开服器————功能实现：
1. 扁平化设计
2. 支持多系统(可选):WIN/LINUX
2. 在线选择服务器类型
3. 插件和MOD的选择性安装，并附加一定的建议
4. 远程服务(付费)
5. 日志在线的抓取和分析系统

---
## MOD&插件 类型
* lianmoelogs----通用的日志抓取上传分析工具
1. 实现自动获取崩溃日志，并上传
2. 如果存在有难以解决的问题有人工服务
3. 可以获取当前游戏下所有的结构(mods,plugs,server)