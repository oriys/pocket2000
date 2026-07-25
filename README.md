# POCKET 2000 · 怀旧掌机益智合集

复古 Game Boy 绿屏像素风的益智小游戏合集，八合一。每个游戏都是纯 HTML 单文件，无依赖、无构建，双击即玩。

**▶ 在线游玩：<https://oriys.github.io/pocket2000/>**

![掌机菜单](screenshot.png)

打开就是掌机菜单：方向键选择游戏，Enter 进入，游戏内 Esc 随时回菜单。所有进度保存在浏览器 localStorage。

## 收录游戏

| 游戏 | 类型 | 内容 | 直达 |
|---|---|---|---|
| **推箱子** SOKOBAN | 解谜 | 经典 245 关：原版 50 + 隐藏附加 40 + Microban 155，带地图缩略图选关 | [sokoban.html](https://oriys.github.io/pocket2000/sokoban.html) |
| **华容道** KLOTSKI | 解谜 | 39 局经典开局，全部经 BFS 验证可解，显示公认最优步数 | [klotski.html](https://oriys.github.io/pocket2000/klotski.html) |
| **数字华容道** 15 PUZZLE | 解谜 | 3×3 / 4×4 / 5×5，随机游走打乱保证有解，计步计时 | [fifteen.html](https://oriys.github.io/pocket2000/fifteen.html) |
| **关灯游戏** LIGHTS OUT | 解谜 | 50 关确定性生成、保证可解，显示目标按数 | [lightsout.html](https://oriys.github.io/pocket2000/lightsout.html) |
| **记忆序列** SIMON | 记忆 | 1978 年电子玩具经典：灯序越来越长，凭记忆复现 | [simon.html](https://oriys.github.io/pocket2000/simon.html) |
| **猜数字** 1A2B | 推理 | 文曲星经典：猜 4 位不重复数字，几A几B 收敛真相 | [guess.html](https://oriys.github.io/pocket2000/guess.html) |
| **扫雷** MINES | 推理 | 初/中/高三种规格（9×9 到 30×16/99 雷），首点必安全，支持清算 | [mines.html](https://oriys.github.io/pocket2000/mines.html) |
| **数织** PICROSS | 推理 | 29 幅像素画，全部经求解器验证"仅凭行列数字唯一可解"，完成揭晓图案 | [nonogram.html](https://oriys.github.io/pocket2000/nonogram.html) |

![华容道](screenshot-klotski.png)

## 通用按键

| 按键 | 功能 |
|---|---|
| 方向键 / WASD | 移动 / 滑动 / 光标（Simon 中即四个按键） |
| Z / 空格 | 撤销，或翻开 / 涂格（扫雷、数织） |
| X | 插旗（扫雷）/ 打叉（数织） |
| 数字键 | 输入（1A2B）/ 切换规格难度（数字华容道、扫雷） |
| R | 重开本关 |
| N / P | 下一关 / 上一关 |
| L | 选关面板 |
| F | 浏览器全屏 |
| M | 静音（全部游戏共享） |
| Esc | 返回掌机菜单 |

全部游戏同时支持鼠标 / 触屏操作。

## 技术与致谢

像素画、位图字体、音效（WebAudio 方波）全部由代码生成，无任何外部资源。

- 推箱子原版 90 关：Thinking Rabbit（今林宏行，1982），数据取自 Cornell xsokoban 3.3c，版权归原作者，仅作学习怀旧用途
- Microban 155 关：David W. Skinner，作者允许自由分发
- 华容道 39 局布局数据：[jeantimex/klotski](https://github.com/jeantimex/klotski)（MIT License）
- 数织 29 幅图案为本项目原创，经行列约束传播求解器验证唯一可解
