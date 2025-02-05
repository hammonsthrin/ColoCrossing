# Cursor：免费 GPT-4 IDE 工具的详细使用指南

## 简介

`Cursor` 是一款基于人工智能技术的**代码生成工具**。它利用先进的**自然语言处理**和**深度学习算法**，根据用户的输入或需求自动生成高质量的代码。无论是初学者还是资深开发者，`Cursor` 都能成为您编程之路上的得力助手。

### 主要特点
- **多语言支持**：支持 `Python`、`Java`、`C#`、`JavaScript` 等多种编程语言。
- **跨平台兼容**：可在 `Mac`、`Windows`、`Linux` 等操作系统中运行。
- **高效生产力**：Cursor 旨在通过 AI 技术显著提升您的编码效率。

> 官网宣称：*"Built to make you extraordinarily productive, Cursor is the best way to code with AI."*  
> 翻译：*"Cursor 旨在提高您的工作效率，是使用 AI 进行编码的最佳方式。"*

![Cursor 工具界面](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/af4ce062146e45f6b966c1d666cccef8~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=fYNIX91IYxy4iWXNGr%2Brj5aKRHQ%3D)

---

## 教程步骤

### 1. 下载与安装
- 打开 [Cursor 官网](https://www.cursor.so)，点击 `Download` 按钮下载对应操作系统的版本。
- 下载完成后，找到 `Cursor Setup 0.40.4 - Build 2409052yfcjagw2-x64.exe` 文件，双击安装。

![下载界面](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/4103c9e84d1a420c8323a63ce51c1496~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=HrzuxkEuKK6YWHOzqSjih6F7ATw%3D)

### 2. 初始化配置

#### 2.1 配置快捷键与 AI 语言
- **Keyboard**：根据您的习惯选择快捷键方案，例如选择 `Jetbrains` 以保持与 Idea 一致。
- **Language for AI**：为 AI 指定非英语语言，例如输入中文。
- **Codebase-wide**：默认设置即可。

![快捷键配置](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/d09f19e6e1104b4593296c741fbbc9a8~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=Z1olRJp1fpdtT9omUw4VAyWeoAg%3D)

#### 2.2 导入 VS Code 扩展
- 如果需要导入 VS Code 扩展，点击 `Use Extensions`；否则选择 `Start from Scratch`。

![扩展导入](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/0f0d9de40024410ea65fda74f86f695a~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=JvpF8tMlIrsmOrNUNznfCZGxA4c%3D)

#### 2.3 数据偏好设置
- **Help improve Cursor**：允许收集使用数据，包括聊天问题和代码片段。
- **Privacy Mode**：启用隐私模式，不存储任何数据。
- 选择后点击 `Continue`。

![数据偏好](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/47dcc008c42a46cdbc2f3cb6d67576ad~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=cI%2FJSLKWLLURmq3wJCcnueNfuac%3D)

#### 2.4 登录/注册
- 登录后可使用 AI 功能，或点击 `Skip for now` 跳过。
- 点击 `Log In`，使用 GitHub 登录。

![登录界面](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/7ec80e0746904383a89815cf2512d8e1~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=1fhgDuWyA52dC7pIYaghlFI0eII%3D)

### 3. 插件安装

#### 3.1 设置中文界面
- 按 `Ctrl + Shift + X` 打开插件市场，搜索并安装 `Chinese (Simplified)` 插件。

![中文插件](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/f082072fc8744f49b4a90c040ea159df~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=lPENBQMO9AeCwK45xVwlG1mXqTM%3D)

#### 3.2 配置 Gitee
- 搜索并安装 `Gitee` 插件，申请一个私人令牌（access token）。
- 按 `F1`，输入 `Gitee`，选择相关命令。

![Gitee 配置](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/98eecd0f20584a54b20f05412c618d5b~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=UPdGpQ1JHtGlJPrIxIuAqScyl90%3D)

### 4. 模型与密钥配置

#### 4.1 选择模型
- 点击右上角设置图标，进入 `Models` 选项，选择模型。

![模型选择](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/8885eeddaa7941c0af46fb9c81a8b70e~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=pvYvtmDuujVIz5Lwt%2BilUqc5jg4%3D)

#### 4.2 配置密钥
- 输入自定义的 KEY 和 URL，点击 `Override OpenAI Base URL`。

![密钥配置](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/325cc0f636aa4ab9ba6fd7d1ae3338a6~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=7OoBqaRLOi2DCELZcKVjsjZNB6I%3D)

#### 4.3 自定义模型
- 点击 `Add model`，输入模型名称。

![自定义模型](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/4a71204423124123939dad516552f791~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=zL1Ar4atRU4MPkoxrY7tlIlssYY%3D)

#### 4.4 测试配置
- 点击 `Verify` 测试，若无提示则配置成功。

![测试配置](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/b74d51f93d2c4e5dbf3a822beaaa9d61~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=gr7Cc3YbtISPVTDLaIIZvkMh%2BMs%3D)

### 5. 使用 Cursor
- 打开提示词面板，开始高效的编程体验。

![使用界面](https://p3-volc-community-sign.byteimg.com/tos-cn-i-tlddhu82om/c9a91caec7784605a7d781e2560e4291~tplv-tlddhu82om-image.image?=&rk3s=8031ce6d&x-expires=1738687069&x-signature=CqG59gZJlyHjrAwRbru3nj0HDjk%3D)

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)