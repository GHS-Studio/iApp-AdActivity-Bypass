# iApp-SkipAd

📖 中文说明：[README_zh_cn.md](README_zh_cn.md)

A simple **iApp (Android)** project that demonstrates how to **skip advertisement Activities** by directly jumping to non‑ad Activities.

Many Android apps display splash or interstitial ads using a **separate Ad Activity**.  
This project avoids launching that Ad Activity and enters the main interface directly.

---

## ✨ Key Idea

- Advertisement screens are usually implemented as **independent Activities**
- Instead of starting the Ad Activity, we **redirect to the target Activity**
- Result: **the ad is never shown**

> Skip the Ad Activity → Skip the ad itself.

---

## 🚀 How It Works

1. Analyze the app's startup flow  
2. Identify the **non‑advertisement Activity**
3. Launch that Activity directly
4. Avoid starting the Ad Activity

This method works for:
- Splash ads
- Interstitial ads
- Popup-style ad pages

---

## 📱 Use Case

- Learning Android Activity navigation
- Understanding ad delivery mechanisms
- Demonstrating Activity-level ad bypass techniques

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**.  
Please respect app policies, advertisements, and developer efforts.

---

## 🛠 Tech Stack

- Android
- iApp (visual Android development tool)

---

## 📄 License

MIT License