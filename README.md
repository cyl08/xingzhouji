# 行舟记 🗺️ · Xingzhouji — Travel Footprint Map

> 走到哪，点亮哪。一个会陪你记住每一段旅程的足迹地图。
> Light up every place you've been — a warm travel-footprint map that also plans your next stop.

![License: MIT](https://img.shields.io/badge/license-MIT-blue?logo=github)
![Vanilla JS](https://img.shields.io/badge/stack-vanilla%20JS-yellow)
![Zero deps](https://img.shields.io/badge/dependencies-0-brightgreen)
![PWA-ready](https://img.shields.io/badge/PWA-ready-blueviolet)
![GitHub stars](https://img.shields.io/github/stars/cyl08/xingzhouji)
[中文](#-核心亮点) · [English](#english)

## 📸 截图

![行舟记截图](screenshot.png)

## ✨ 核心亮点（为什么不一样）

它不是一个冷冰冰的「地图标记工具」，而是一个**有温度、会陪你的足迹小站**：

- 💌 **清欢的信** —— 点亮到 5 个、10 个足迹，会解锁一封一封写给你的信。不是提示文案，是真的懂你、安慰你的信。
- 🥚 **隐藏成就彩蛋** —— 除了「点亮 / 拍照 / 写感想」的常规成就，还有深夜、清晨、黄昏点亮才会触发的隐藏成就，等你亲手撞见。
- ✨ **秘密词彩蛋** —— 在感想里写下「清欢」「此心光明」「知行合一」，会触发专属彩蛋。
- 🖼 **足迹海报** —— 一键把走过的路生成一张可下载的海报，直接发朋友圈。
- 📊 **足迹统计** —— 足迹数、城市数、照片数、感想数、年度足迹分布，一张图看全你的旅程。

## 🎯 功能

### 记录
- **点亮足迹**：在地图上标记你去过的地方，自动连成一条发光的路线
- **旅行相册**：照片随足迹保存，点开即看、可放大
- **感想与秘密词**：每个足迹写一段感想，藏着彩蛋

### 规划下一站
- **旅行规划**：城市打卡清单、六项预算、交通/住宿比价（自动标出「最便宜」）、一键导出攻略
- **🤖 智能推荐打卡点**：输入城市，自动推荐该城市值得去的地方（内置 40+ 热门城市，未收录的城市会联网搜索兜底）

### 展示
- **足迹海报**：生成图片下载
- **足迹统计**：数据总览 + 年度回顾
- **成就系统**：16+ 成就，含隐藏彩蛋

### 体验
- **🌙 深色主题**：一键切换夜间模式，地图自动变暗色，护眼又好看
- **离线可用**：PWA，可加到桌面，断网也能看自己的足迹（照片存本地 IndexedDB）

## 🧱 技术栈

- 纯前端，零依赖构建（单文件 `index.html` + `sw.js`，无框架无打包）
- [Leaflet](https://leafletjs.com/) + 高德瓦片
- IndexedDB 本地存储足迹（含照片）、localStorage 存规划与设置
- 原生 CSS/SVG 图表、Canvas 生成海报
- PWA：可离线、可添加到主屏幕

## 🚀 快速开始

直接双击 `index.html` 即可，无需安装任何东西、无需构建。

在线体验：https://cyl08.github.io/xingzhouji/

## 📁 目录

```
index.html        # 主应用（单文件）
sw.js             # Service Worker（PWA 离线）
manifest.json     # PWA 清单
icon-192.png / icon-512.png
使用指南.html      # 详细使用说明
screenshot.png    # 截图
```

## 📄 License

MIT

---

## English

**Xingzhouji (行舟记)** is an open-source travel-footprint map & trip planner — with a warm twist: it writes you letters, unlocks hidden achievements, and hides easter eggs.

**Highlights**

- 💌 **Letters from Qinghuan** — unlock heartfelt letters at 5 and 10 footprints
- 🥚 **Hidden achievement easter eggs** — time-of-day based achievements (late night, dawn, dusk)
- ✨ **Secret-word easter eggs** — writing certain words in a note triggers a surprise
- 🖼 **Footprint poster** — generate a shareable image in one click
- 📊 **Footprint stats** — totals, cities, photos, and year-by-year breakdown

**Features**

- **Light up footprints** — mark places you've visited, auto-connected into a glowing route
- **Travel album** — photos saved with each footprint
- **Trip planner** — city checklist, six-item budget, transport/lodging price comparison, one-click itinerary export
- **🤖 Smart recommendations** — auto-suggests places for 40+ cities, with web-search fallback
- **🌙 Dark mode** — night theme with an auto-darkened map
- **Offline PWA** — add to home screen, works offline

**Tech stack**: zero-dependency vanilla front-end (single `index.html` + `sw.js`), [Leaflet](https://leafletjs.com/) with AMap tiles, IndexedDB for offline storage, native CSS/SVG charts, PWA.

**Run locally**: just open `index.html` — no install, no build step.

**Live demo**: https://cyl08.github.io/xingzhouji/

**License**: MIT
## Get in touch

Questions, bug reports, or just want to say hi? I'd genuinely like to hear from you.

- **Found a bug or have an idea?** → [open an issue](../../issues)
- **Email** → `2495297174@qq.com`
- **Try the hosted version** (no setup required) → https://mochiway.com/mochi/

I'm a student developer building small, private-by-default web apps — the kind where your data never leaves your own device. If this one is useful to you, I'd love to know what you're using it for.

*If you'd rather not self-host, there's also a one-time-purchase version — same app, no setup, and it helps me keep building.*
