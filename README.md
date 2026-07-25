# 推箱子 · SOKO-BAN 2000

复古 Game Boy 绿屏像素风的经典推箱子（Sokoban / 仓库番），纯 HTML 单文件，无依赖、无构建，双击即玩。

**▶ 在线游玩：<https://oriys.github.io/box/>**

![游戏截图](screenshot.png)

## 操作

| 按键 | 功能 |
|---|---|
| 方向键 / WASD | 移动 |
| Z（或 U / 退格） | 撤销一步 |
| R | 重开本关 |
| N / P | 下一关 / 上一关 |
| L 或 Esc | 选关面板（带每关地图缩略图） |
| F | 浏览器全屏 |
| M | 静音 |

触屏设备可以在棋盘上滑动来移动。过关进度与每关最佳步数自动保存在浏览器 localStorage 中。

## 关卡（共 245 关）

| 套题 | 数量 | 来源 |
|---|---|---|
| 原版经典 | 50 | Thinking Rabbit（今林宏行，1982），数据取自 Cornell xsokoban 3.3c |
| 隐藏附加 | 40 | xsokoban 附带的第 51–90 关 |
| Microban | 155 | David W. Skinner 作品，新手友好，作者允许自由分发 |

像素画、音效（WebAudio 方波）、位图字体均由代码生成，无任何外部资源。

原版 90 关的版权归 Thinking Rabbit 所有，本仓库仅作个人学习与怀旧用途。
