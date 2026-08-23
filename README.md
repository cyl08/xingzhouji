# 行舟记 🗺️ · Xingzhouji — Travel Footprint Map

> 走到哪，点亮哪。一个记录旅行足迹、规划下一站的开源小站。
> Light up every place you've been. An open-source travel footprint map & trip planner.

[中文](#-功能) · [English](#english)

## 📸 截图

![行舟记截图](screenshot.png)

## ✨ 功能

- **点亮足迹**：在地图上标记你去过的地方，自动连成发光路线
- **旅行规划**：城市打卡清单、六项预算、交通/住宿比价、一键导出攻略
- **旅行相册**：照片随足迹保存，点开即看
- **成就系统**：点亮 / 拍照 / 写感想解锁成就，还有隐藏彩蛋
- **足迹海报**：一键生成图片，发朋友圈
- **清欢的信**：走到一定数量，解锁写给 TA 的信

## 🧱 技术栈

- 纯前端，零依赖构建（单文件 `index.html` + `sw.js`）
- [Leaflet](https://leafletjs.com/) + 高德瓦片
- IndexedDB 本地存储足迹（含照片）、localStorage 存规划
- PWA：可离线、可添加到主屏幕

## 🚀 本地运行

直接双击 `index.html` 即可，无需安装任何东西。

## 📁 目录

```
index.html        # 主应用（单文件）
sw.js             # Service Worker（PWA 离线）
manifest.json     # PWA 清单
icon-192.png / icon-512.png
使用指南.html      # 详细使用说明
```

## 📄 License

MIT

---

## English

**Xingzhouji (行舟记)** is an open-source travel footprint map & trip planner.

**Features**

- **Light up footprints** — mark places you've visited, auto-connected into a glowing route
- **Trip planner** — city checklist, six-item budget, transport/lodging price comparison, one-click itinerary export
- **Travel album** — photos saved with each footprint
- **Achievements** — unlock badges by checking in, taking photos, writing notes (plus hidden easter eggs)
- **Footprint poster** — generate a shareable image in one click

**Tech stack**: zero-dependency vanilla front-end (single `index.html` + `sw.js`), [Leaflet](https://leafletjs.com/) with AMap tiles, IndexedDB for offline storage, PWA (offline + add-to-home-screen).

**Run locally**: just open `index.html` — no install, no build step.

**License**: MIT
