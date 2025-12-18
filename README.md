# 🌊 Memory Zen

![Status](https://img.shields.io/badge/Status-v9.4-success) ![Size](https://img.shields.io/badge/Size-%3C10kb-green) ![License](https://img.shields.io/badge/License-MIT-blue)

**[English](#-english) | [中文说明](#-中文说明)**

---

<div id="-english"></div>

## 🇬🇧 English

### Introduction
**Memory Zen** is a meditative, generative memory card game built entirely with **Vanilla HTML, CSS, and JavaScript**. 
Unlike traditional web games, it uses **Zero Image Assets**. Every visual element—from the rotating galaxy to the breathing tides—is rendered in real-time using code (CSS Gradients, Box-Shadow Particles, and SVG Data URIs).

### 🎮 Play Now
👉 **[Click Here to Start the Game](https://yyhh-cloud.github.io/memory-zen/)**

### ✨ Key Features (v9.4)
* **🎨 4 Generative Themes**:
    * **🍬 Candy**: High-speed, fluid warm gradients.
    * **🌌 Galaxy**: A rotating nebula with 200+ JS-generated random star particles.
    * **🔮 Mirage**: Holographic, high-saturation floating light blobs with glassmorphism.
    * **🌊 Tides**: A breathing, vertical gradient simulating ocean rhythms.
* **⚡ Zero External Requests**: No `.jpg` or `.png` files. Fast loading, instant play.
* **📱 Perfect Aspect Ratio**: Uses modern CSS `aspect-ratio: 1/1` to ensure cards remain perfectly square on any device.
* **🛠️ Classic UI**: Optimized "Smart Capsule" headers and native-feel dropdown buttons for maximum compatibility and aesthetics.
* **🌐 Bilingual**: Instant switch between English and Chinese.

### 🛠️ Tech Stack
* **Core**: HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Rendering**: CSS Conic/Radial Gradients, Box-Shadow Particles, SVG Data URIs.
* **Animation**: Hardware-accelerated CSS Keyframes (`will-change`, `transform`).
* **Layout**: CSS Grid + Flexbox with `clamp()` responsive typography.

### 🚀 How to Run
No `npm install`. No build steps. Just pure web standards.
1. Clone the repo: `git clone https://github.com/yyhh-cloud/memory-zen.git`
2. Open `index.html` in any browser.

---

<div id="-中文说明"></div>

## 🇨🇳 中文说明

### 项目简介
**Memory Zen (禅意翻牌)** 是一款**零素材、生成式**的网页记忆游戏。
本项目最大的特色在于**“纯代码绘制”**。我们没有使用一张外部图片，所有的视觉效果——包括旋转的银河、流动的光斑、呼吸的潮汐——完全由 CSS 算法和 JS 粒子系统实时渲染而成。

### 🎮 在线试玩
👉 **[点击这里开始游戏](https://yyhh-cloud.github.io/memory-zen/)**

### ✨ 核心亮点 (v9.4)
* **🎨 四大生成式主题**：
    * **🍬 糖果 (Candy)**：极速流动的暖色撞色渐变。
    * **🌌 银河 (Galaxy)**：底层螺旋星云 + 顶层 JS 实时生成的 200 颗随机粒子星星。
    * **🔮 幻境 (Mirage)**：全息风格的彩色光斑，配合高斯模糊渲染梦境感。
    * **🌊 潮汐 (Tides)**：模拟呼吸节奏的垂直海浪渐变。
* **⚡ 极致性能**：无任何图片请求，秒开，显卡硬件加速动画。
* **📱 完美适配**：利用 `aspect-ratio` 技术，强制锁定卡牌为正方形，拒绝变形。
* **🧘 交互美学**：白瓷质感按钮，配合顶部“灵动胶囊”状态栏，极简且优雅。

### 🛠️ 技术栈
* **核心**：原生 HTML5, CSS3, JavaScript (ES6+)。
* **渲染**：CSS 圆锥/径向渐变 (Conic/Radial Gradients), 阴影粒子技术 (Box-Shadow Particles)。
* **动画**：高性能 CSS 关键帧动画。
* **数据**：LocalStorage 记录最佳成绩。

### 🚀 本地运行
无需 Node.js，无需构建工具。
1. 克隆仓库：`git clone https://github.com/yyhh-cloud/memory-zen.git`
2. 双击 `index.html` 即可直接运行。

---

## 📄 License
MIT License. Feel free to fork and learn!
