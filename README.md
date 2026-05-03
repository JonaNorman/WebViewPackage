# WebViewPackage

![GitHub release (latest by date)](https://img.shields.io/github/v/release/JonaNorman/WebViewPackage)
![GitHub repo size](https://img.shields.io/github/repo-size/JonaNorman/WebViewPackage)
![Vendors](https://img.shields.io/badge/vendors-AOSP_%7C_Google_%7C_Chrome_%7C_Huawei_%7C_Amazon-blue)

[**English**](./README.md) | [**中文文档**](./README_zh.md)

This is an open-source repository dedicated to collecting and archiving Android WebView APKs from various vendors.

Due to Android fragmentation, the versions and vendors of WebViews vary greatly across different devices. This poses significant challenges for front-end and client-side developers during compatibility testing and debugging. This project aims to centralize WebView installation packages across different vendors, architectures, and API levels, making it convenient for developers to download them on-demand for testing and issue reproduction.

All WebView APKs are hosted on the [Releases](https://github.com/JonaNorman/WebViewPackage/releases) page, using different Git tags to differentiate between vendor versions.

> **🛠 Machine-Readable Data (JSON)**
> We provide a JSON file containing metadata for all WebView packages: [`webview_packages.json`](./webview_packages.json). You can parse this file via scripts to automate downloading or updating dependencies in your CI/CD pipelines.

## 📦 Supported Vendors & Tags

| Vendor | Tag | Package Name | Description |
| :--- | :--- | :--- | :--- |
| **Android** | [`android`](https://github.com/JonaNorman/WebViewPackage/releases/tag/android) | `com.android.webview` | Official Android system WebView |
| **Google** | [`google`](https://github.com/JonaNorman/WebViewPackage/releases/tag/google) | `com.google.android.webview` | Official WebView component provided by Google |
| **Chrome** | [`chrome`](https://github.com/JonaNorman/WebViewPackage/releases/tag/chrome) | `com.android.chrome` | Google Chrome Browser (can be used as a WebView Provider) |
| **Huawei** | [`huawei`](https://github.com/JonaNorman/WebViewPackage/releases/tag/huawei) | `com.huawei.webview` | Chromium-based WebView built into Huawei devices |
| **Amazon** | [`amazon`](https://github.com/JonaNorman/WebViewPackage/releases/tag/amazon) | `com.amazon.webview.chromium` | WebView used on Amazon Fire OS and similar devices |

---

## 📋 Detailed Version List

> **Note:** 
> - **GitHub Download:** Official direct links from GitHub Releases. Click the architecture name to download.
> - **China Accelerated:** Accelerated download links proxied via `ghproxy.net` for faster access within mainland China.

### 🤖 Android WebView
- **Tag:** [`android`](https://github.com/JonaNorman/WebViewPackage/releases/tag/android)

| Version | Min SDK | GitHub Download | China Accelerated (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 134.0.6998.39 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/134.0.6998.39_min26_x86.apk) |
| 128.0.6613.88 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/128.0.6613.88_min26_x86.apk) |
| 124.0.6367.219| API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/124.0.6367.219_min26_x86.apk) |
| 113.0.5672.136| API 24 (Android 7.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm32.apk), [arm64](https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm64.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_x86.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm32.apk), [arm64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_arm64.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/android/113.0.5672.136_min24_x86.apk) |

### 🇬 Google WebView
- **Tag:** [`google`](https://github.com/JonaNorman/WebViewPackage/releases/tag/google)

| Version | Min SDK | GitHub Download | China Accelerated (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 146.0.7680.164| API 32 (Android 12L)| [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min32_x86.apk) |
| 146.0.7680.164| API 29 (Android 10) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min29_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/146.0.7680.164_min29_arm32+64.apk) |
| 143.0.7499.147| API 29 (Android 10) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/143.0.7499.147_min29_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/143.0.7499.147_min29_arm32+64.apk) |
| 133.0.6943.138| API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/133.0.6943.138_min26_arm32.apk) |
| 122.0.6261.64 | API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/122.0.6261.64_min26_x86.apk) |
| 119.0.6045.53 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/119.0.6045.53_min24_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/119.0.6045.53_min24_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/119.0.6045.53_min24_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/119.0.6045.53_min24_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/119.0.6045.53_min24_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/119.0.6045.53_min24_x86.apk) |
| 113.0.5672.77 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/google/113.0.5672.77_min24_x86.apk) |

### 🌐 Chrome WebView
- **Tag:** [`chrome`](https://github.com/JonaNorman/WebViewPackage/releases/tag/chrome)

| Version | Min SDK | GitHub Download | China Accelerated (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 136.0.7103.125| API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/136.0.7103.125_min26_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/136.0.7103.125_min26_arm32+64.apk) |
| 122.0.6261.64 | API 26 (Android 8.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/122.0.6261.64_min26_x86.apk) |
| 116.0.5845.93 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/116.0.5845.93_min24_x86.apk) |
| 106.0.5249.65 | API 23 (Android 6.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32+64.apk), [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32.apk), [x86](https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_x86.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32+64.apk), [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_arm32.apk), [x86](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/chrome/106.0.5249.65_min23_x86.apk) |

### 🌸 Huawei WebView
- **Tag:** [`huawei`](https://github.com/JonaNorman/WebViewPackage/releases/tag/huawei)

| Version | Min SDK | GitHub Download | China Accelerated (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 15.0.4.326 | API 24 (Android 7.0) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/15.0.4.326_min24_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/15.0.4.326_min24_arm32+64.apk) |
| 14.0.0.331 | API 29 (Android 10) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/14.0.0.331_min29_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/14.0.0.331_min29_arm32+64.apk) |
| 11.0.6.310 | API 21 (Android 5) | [arm32+64](https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/11.0.6.310_min21_arm32+64.apk) | [arm32+64](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/huawei/11.0.6.310_min21_arm32+64.apk) |

### 🛒 Amazon WebView
- **Tag:** [`amazon`](https://github.com/JonaNorman/WebViewPackage/releases/tag/amazon)

| Version | Min SDK | GitHub Download | China Accelerated (Ghproxy) |
| :--- | :---: | :--- | :--- |
| 142-7444 | API 29 (Android 10) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/142-7444_min29_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/142-7444_min29_arm32.apk) |
| 132-6834 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/132-6834_min26_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/132-6834_min26_arm32.apk) |
| 130-6723 | API 26 (Android 8.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/130-6723_min26_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/130-6723_min26_arm32.apk) |
| 118-5993 | API 24 (Android 7.0) | [arm32](https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/118-5993_min24_arm32.apk) | [arm32](https://ghproxy.net/https://github.com/JonaNorman/WebViewPackage/releases/download/amazon/118-5993_min24_arm32.apk) |

---

## 💡 How to Use

1. Based on your testing needs, locate the corresponding vendor, version, and CPU architecture in the lists above.
2. Click the architecture name in the table to download the corresponding `.apk` installation package. (If accessing GitHub is slow, please use the "China Accelerated" links).
3. Connect your device to your computer and use the `adb` command to install the WebView on your test device (if a lower version already exists on the device, you can use the `-d` parameter to downgrade):
   ```bash
   adb install -r -d <path_to_apk>
   ```
4. After installation:
   - On most systems, you can select the newly installed WebView version in your device's **"Developer Options" -> "WebView Implementation"**.
   - Highly customized systems (or when replacing a core system-level WebView) may require Root access or a Magisk module to force the replacement.

### 🔄 In-App WebView Replacement

If you need to replace or upgrade the WebView implementation directly within your Android application (without affecting the whole system), you can use the [WebViewUpgrade](https://github.com/JonaNorman/WebViewUpgrade) library.

## 🤝 Contribution and Feedback

If you need a specific vendor or version of WebView not listed here, or if you encounter issues downloading packages from this repository, feel free to open an [Issue](https://github.com/JonaNorman/WebViewPackage/issues). If you have stable WebView APKs from other sources, pull requests are very welcome!
