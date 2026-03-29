# WebViewPackage

![GitHub release (latest by date)](https://img.shields.io/github/v/release/JonaNorman/WebViewPackage)
![GitHub repo size](https://img.shields.io/github/repo-size/JonaNorman/WebViewPackage)
![Vendors](https://img.shields.io/badge/vendors-AOSP_%7C_Google_%7C_Chrome_%7C_Huawei_%7C_Amazon-blue)

[**English**](./README.md) | [**中文文档**](./README_zh.md)

这是一个用于收集和归档各厂商 Android WebView APK 的开源仓库。

由于 Android 系统的碎片化，不同设备上的 WebView 版本和厂商各不相同，这给前端和客户端开发者在做兼容性测试和调试时带来了很大的困难。本项目旨在汇总不同厂商、不同架构、不同 API 级别的 WebView 安装包，方便开发者按需下载进行测试和问题复现。

所有的 WebView APK 均托管在 [Releases](https://github.com/JonaNorman/WebViewPackage/releases) 页面中，并通过不同的 Tag 来区分不同厂商的版本。

> **🛠 机器可读数据源 (JSON Data)**
> 我们提供了一份包含所有 WebView 包元数据的 JSON 文件：[`webview_packages.json`](./webview_packages.json)。你可以通过脚本解析此文件，用于自动下载或更新你的 CI/CD 流程中的依赖。

## 📦 支持的厂商及 Tag 索引

| 厂商 | Tag | 包名 (Package Name) | 说明 |
| :--- | :--- | :--- | :--- |
| **Android (AOSP)** | [`android`](https://github.com/JonaNorman/WebViewPackage/releases/tag/android) | `com.google.android.webview` / `com.android.webview` | Android 官方开源系统 WebView |
| **Google** | [`google`](https://github.com/JonaNorman/WebViewPackage/releases/tag/google) | `com.google.android.webview` | Google 官方提供的 WebView 组件 |
| **Chrome** | [`chrome`](https://github.com/JonaNorman/WebViewPackage/releases/tag/chrome) | `com.android.chrome` | Google Chrome 浏览器 (可作为 WebView Provider) |
| **Huawei (华为)** | [`huawei`](https://github.com/JonaNorman/WebViewPackage/releases/tag/huawei) | `com.huawei.webview` | 华为设备内置的基于 Chromium 的 WebView |
| **Amazon (亚马逊)** | [`amazon`](https://github.com/JonaNorman/WebViewPackage/releases/tag/amazon) | `com.amazon.webview.chromium` | 亚马逊 Fire OS 等设备使用的 WebView |

---

## 📋 详细版本列表

> **说明:** 
> - **GitHub 下载:** 官方 Releases 直链，直接点击架构名称即可下载。
> - **国内加速下载:** 使用 `ghproxy.net` 代理的加速链接，方便国内网络环境下高速下载。

### 🤖 Android WebView
- **Tag:** [`android`](https://github.com/JonaNorman/WebViewPackage/releases/tag/android)

| 版本号 | 最低系统版本 | GitHub 下载 | 国内加速下载 (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 134.0.6998.39 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_x86.apk) |
| 128.0.6613.88 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_x86.apk) |
| 124.0.6367.219| API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_x86.apk) |
| 113.0.5672.136| API 24 (Android 7.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_x86.apk) |

### 🇬 Google WebView
- **Tag:** [`google`](https://github.com/JonaNorman/WebViewPackage/releases/tag/google)

| 版本号 | 最低系统版本 | GitHub 下载 | 国内加速下载 (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 146.0.7680.164| API 32 (Android 12L)| [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_x86.apk) |
| 146.0.7680.164| API 29 (Android 10) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min29_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min29_arm32+64.apk) |
| 143.0.7499.147| API 29 (Android 10) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/143.0.7499.147_min29_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/143.0.7499.147_min29_arm32+64.apk) |
| 133.0.6943.138| API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32.apk) |
| 122.0.6261.64 | API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_x86.apk) |
| 113.0.5672.77 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_x86.apk) |

### 🌐 Chrome WebView
- **Tag:** [`chrome`](https://github.com/JonaNorman/WebViewPackage/releases/tag/chrome)

| 版本号 | 最低系统版本 | GitHub 下载 | 国内加速下载 (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 136.0.7103.125| API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/136.0.7103.125_min26_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/136.0.7103.125_min26_arm32+64.apk) |
| 122.0.6261.64 | API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_x86.apk) |
| 116.0.5845.93 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_x86.apk) |
| 106.0.5249.65 | API 23 (Android 6.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_x86.apk) |

### 🌸 Huawei WebView (华为)
- **Tag:** [`huawei`](https://github.com/JonaNorman/WebViewPackage/releases/tag/huawei)

| 版本号 | 最低系统版本 | GitHub 下载 | 国内加速下载 (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 15.0.4.326 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/15.0.4.326_min24_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/15.0.4.326_min24_arm32+64.apk) |
| 14.0.0.331 | API 29 (Android 10) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/14.0.0.331_min29_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/14.0.0.331_min29_arm32+64.apk) |

### 🛒 Amazon WebView (亚马逊)
- **Tag:** [`amazon`](https://github.com/JonaNorman/WebViewPackage/releases/tag/amazon)

| 版本号 | 最最低系统版本 | GitHub 下载 | 国内加速下载 (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 142-7444 | API 29 (Android 10) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/142-7444_min29_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/142-7444_min29_arm32.apk) |
| 132-6834 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/132-6834_min26_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/132-6834_min26_arm32.apk) |
| 130-6723 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/130-6723_min26_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/130-6723_min26_arm32.apk) |
| 118-5993 | API 24 (Android 7.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/118-5993_min24_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/118-5993_min24_arm32.apk) |

---

## 💡 如何使用

1. 根据你的测试需求，在上方列表中找到对应的厂商、版本和 CPU 架构。
2. 点击表格中的架构名称即可下载对应的 `.apk` 安装包文件（如果访问 GitHub 较慢，请使用“国内加速下载”链接）。
3. 将设备连接到电脑，使用 `adb` 命令将 WebView 安装到测试设备上（如果设备已存在较低版本，可以使用 `-d` 参数降级安装）：
   ```bash
   adb install -r -d <path_to_apk>
   ```
4. 安装完成后：
   - 对于大部分系统，你可以在设备的 **“开发者选项” -> “WebView 实现 (WebView Implementation)”** 中选择刚安装的 WebView 版本。
   - 某些高度定制的系统（或者如需要替换系统级别的核心 WebView 时）可能需要 Root 权限或者采用 Magisk 模块来强制替换。

### 🔄 App 内替换 WebView

如果需要在 App 内部替换或升级 WebView 的实现（而不是在系统全局替换），可以使用 [WebViewUpgrade](https://github.com/JonaNorman/WebViewUpgrade) 这个库。

## 🤝 贡献与反馈

如果你需要其他特定厂商或版本的 WebView，或者在此仓库下载安装包遇到问题，欢迎提交 [Issue](https://github.com/JonaNorman/WebViewPackage/issues) 告知。如果你有其他来源的稳定版 WebView APK，也欢迎通过 PR 补充到本仓库！