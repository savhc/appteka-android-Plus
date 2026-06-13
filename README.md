<p align="center">
  <img src="app/src/main/ic_launcher-web.png" alt="Appteka Logo" width="120" height="120">
</p>
<h1 align="center">Appteka Plus</h1>
<p align="center">
  <strong>Appteka 复刻修改版 — 开源 Android 应用商店</strong>
</p>
<p align="center">
  <a href="https://appteka.store"><img src="https://img.shields.io/badge/dynamic/json?color=32A304&label=Appteka&query=%24.newer.ver_name&url=https%3A%2F%2Fappteka.store%2F%2Fapi%2F1%2Fupdate%3Fbuild%3D1" alt="Appteka"></a>
  <a href="LICENSE.txt"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" alt="License: GPL v3"></a>
  <img src="https://img.shields.io/badge/API-21%2B-brightgreen.svg" alt="API 21+">
  <img src="https://img.shields.io/badge/Kotlin-1.9-purple.svg" alt="Kotlin">
</p>
Appteka Plus 是基于 Appteka 源代码复刻的修改增强版，一个免费开源的 Android 应用商店。在此发现、下载并分享应用，与全球开发者社区实时交流。
预览
<p align="center">
  <img src="art/main.jpg" alt="商店" width="200">
  <img src="art/app.jpg" alt="应用详情" width="200">
  <img src="art/profile.jpg" alt="个人中心" width="200">
  <img src="art/topics.jpg" alt="讨论区" width="200">
</p>
功能
浏览与下载 — 海量免费 Android 应用
上传应用 — 向社区分享你的作品
APK 提取 — 提取已安装应用（含系统应用）的 APK
实时聊天 — 与其他用户讨论应用与游戏
用户档案 — 追踪上传、下载与活动记录
评分与评论 — 为应用打分并阅读社区反馈
收藏夹 — 保存应用以便稍后查看
深色主题 — 完整支持暗色模式
无需 Root — 任何 Android 设备均可使用
下载
<a href="https://github.com/你的用户名/appteka-android-plus/releases">
或在 Releases 页面获取最新 APK。
技术栈
表格
类别	技术
语言	Kotlin
UI	Material Design 3, AndroidX
架构	MVP, Clean Architecture
依赖注入	Dagger 2
响应式	RxJava 3, RxKotlin, RxRelay
网络	Retrofit 3, OkHttp 5
图片加载	Simple Image Loader
列表	Konveyor
构建	Gradle, ProGuard
架构
项目遵循 Clean Architecture 与 MVP 模式：
Activity/Fragment — 路由层，实现导航接口
Presenter — 表现层，与框架解耦便于测试
View — 纯 UI 渲染，无业务逻辑
Interactor — 业务逻辑层，仓库模式与数据缓存
Converter — 各层间的数据映射
ResourceProvider — 为框架无关层提供 Android 资源访问
构建
环境要求
Android Studio Ladybug 或更新版本
JDK 17
Android SDK API 35
构建与运行
bash
# 克隆仓库
git clone https://github.com/你的用户名/appteka-android-plus.git
cd appteka-android-plus

# 构建 Debug APK
./gradlew assembleDebug

# 构建 Release APK（需配置签名）
./gradlew assembleRelease
APK 生成路径：app/build/outputs/apk/
本地化
Appteka Plus 支持 9 种语言：
表格
语言	代码
英语	en（默认）
俄语	ru
阿拉伯语	ar
中文	zh
波斯语	fa
印地语	hi
库尔德语	ku
葡萄牙语（巴西）	pt-rBR
越南语	vi
欢迎参与翻译贡献！
参与贡献
欢迎提交：
通过 Issues 报告缺陷与功能建议
提交 Pull Request 改进代码
协助翻译与文档完善
安全声明
所有上传应用均通过内置杀毒系统自动扫描（集成 三款独立杀毒引擎）。
Appteka 是社区驱动的应用交换平台，用户可自由上传应用。Appteka 团队不对用户生成内容负责。 尽管已部署安全扫描与内容审核，安装前请自行核实来源、查阅评分与评论。
服务条款
DMCA 政策
联系方式与捐赠
许可证
plain
Copyright (C) 2016-2026 Appteka

本程序为自由软件：你可以根据自由软件基金会发布的
GNU 通用公共许可证（第 3 版或更新版本）重新分发和/或修改它。

本程序分发时希望它有用，但**不提供任何担保**；
甚至不包含对适销性或特定用途适用性的默示担保。
详情请参阅 GNU 通用公共许可证。
完整许可证文本见 LICENSE.txt。
<p align="center">
  🌙 由 Appteka Plus 团队夜以继日开发
</p>
