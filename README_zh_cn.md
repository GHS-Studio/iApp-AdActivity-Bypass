# iApp-SkipAd

一个基于 **iApp（安卓）** 的简单示例项目，演示如何通过**直接跳转至非广告 Activity**，从而跳过应用中的广告页面。

很多 Android 应用会将开屏广告或插屏广告放在一个**独立的广告 Activity** 中显示。  
本项目通过**避免启动该广告 Activity**，直接进入主界面，从而实现“跳过广告”的效果。

---

## ✨ 核心思路

- 广告页面通常以 **独立 Activity** 的形式存在
- 不直接启动广告 Activity，而是**跳转到目标 Activity**
- 结果：**广告根本不会被展示**

> 跳过广告 Activity → 跳过广告本身

---

## 🚀 实现方式

1. 分析应用的启动流程  
2. 确定**非广告的目标 Activity**
3. 直接启动该 Activity
4. 避免触发广告 Activity

该方法适用于：
- 开屏广告
- 插屏广告
- 弹窗式广告页面

---

## 📱 适用场景

- 学习 Android Activity 跳转机制
- 研究广告加载与展示流程
- 演示 Activity 层面的广告跳过思路

---

## ⚠️ 免责声明

本项目仅供 **学习与技术研究** 使用。  
请尊重应用的使用条款、广告策略以及开发者的劳动成果。

---

## 🛠 技术栈

- Android
- iApp（可视化安卓开发工具）

---

## 📄 开源协议

MIT License

Copyright (c) 2026 VernaWatson (GuLi)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.