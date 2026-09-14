# 棋乐五棋 (Happy-Chess)

一个零依赖的离线五棋（Five-in-a-Row / Gomoku 风格变体）网页小游戏，纯 HTML + CSS + 原生 JavaScript，单文件即可运行。

## 玩法
- 打开 `index.html` 即可游玩，无需任何后端或安装。
- 支持本地双人对战与多种棋种切换。
- 全部游戏状态保存在浏览器中（`localStorage`），关闭后下次打开继续。

## 运行方式
1. 直接双击 `index.html` 在浏览器中打开。
2. 或运行任意静态服务器，例如：
   ```bash
   python -m http.server 8787
   ```
   然后访问 `http://localhost:8787/`。

## 在线版
[WorkBuddy Sites](https://qile-chess.app.workbuddy.host/)

## 文件
- `index.html` — 游戏全部内容（HTML / CSS / JS 全部内联）。

## 许可
MIT