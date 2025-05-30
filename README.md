# 3D IO Shooter Game

一个基于浏览器的 3D 多人在线射击游戏。

## 🎮 项目简介

这是一个使用现代 Web 技术开发的 3D IO 类射击游戏，玩家可以在浏览器中直接进行游戏，无需下载客户端。

## 🚀 功能特性

- 🎯 第一/第三人称射击视角
- 🌍 3D 游戏世界
- 👥 多人在线对战
- 🏆 实时排行榜
- 🎨 精美的 3D 图形效果
- 📱 支持多平台（PC、移动设备）

## 🛠️ 技术栈

- **前端框架**: 原生 JavaScript / TypeScript
- **3D 引擎**: Three.js / Babylon.js
- **网络通信**: WebSocket / Socket.io
- **部署平台**: Firebase Hosting
- **CI/CD**: GitHub Actions
- **版本控制**: Git

## 📦 安装与运行

### 前置要求

- Node.js (v18.0.0 或更高版本)
- npm 或 yarn
- Firebase CLI

### 本地开发

1. 克隆项目
```bash
git clone https://github.com/lishuceo/3d-io-shooter-game.git
cd 3d-io-shooter-game
```

2. 安装依赖（如果有 package.json）
```bash
npm install
```

3. 启动开发服务器
```bash
# 如果使用简单的 HTTP 服务器
npx http-server src -p 8080

# 或者使用 Python
python -m http.server 8080 --directory src
```

4. 打开浏览器访问 `http://localhost:8080`

## 🚀 部署

项目使用 GitHub Actions 自动部署到 Firebase Hosting。

### 自动部署

当代码推送到 `main` 分支时，会自动触发部署流程。

### 手动部署

```bash
firebase deploy --only hosting
```

## 🎮 游戏操作

- **移动**: W/A/S/D 或方向键
- **射击**: 鼠标左键
- **瞄准**: 鼠标右键
- **跳跃**: 空格键
- **切换武器**: 1/2/3 数字键
- **重新加载**: R 键

## 📁 项目结构 