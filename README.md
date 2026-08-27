# 原阅

一个以白色为主色调的 Android 阅读器 App，包含：

- 首页每日资讯摘要
- 微博、百度、知乎、哔哩哔哩等平台热搜聚合
- 自定义 RSS 源订阅与管理
- 本地 TXT / EPUB 书籍导入
- Kindle 风格阅读页，支持横向翻页、纵向滚动、纸张主题、字号与行距调节

## 技术栈

- Kotlin
- Jetpack Compose + Material 3
- Room
- DataStore
- OkHttp
- Jsoup

## 环境要求

- Android Studio
- JDK 17
- Android SDK 35
- 最低 Android 8.0（API 26）

## 运行

1. 用 Android Studio 打开本目录。
2. 等待 Gradle 同步完成。
3. 选择模拟器或真机运行 `app`。

本项目没有内置账号系统，所有数据均保存在本地。
