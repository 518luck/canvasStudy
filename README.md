# Canvas 绘图项目集合

这个仓库包含了一系列使用 HTML5 Canvas API 创建的绘图项目和示例。

## 项目结构

```
canvas/
├── canvasJS创建.html       # Canvas基础创建示例
├── canvas圆弧.html         # 绘制圆弧的示例
├── canvas折线.html         # 绘制折线的示例
├── canvas标签.html         # Canvas文本标签示例
├── canvas椭圆.html         # 绘制椭圆的示例
├── canvas渐变.html         # 渐变效果示例
├── canvas渐变折线 copy.html # 带渐变效果的折线示例
├── canvas直线.html         # 绘制直线的示例
├── canvas笑脸.html         # 绘制笑脸的示例
├── canvas自动填充.html      # 自动填充示例
├── gomoku/                # 五子棋游戏
│   └── index.html         # 五子棋游戏主文件
└── images/                # 图片资源
    └── canvas_create_pattern.png
```

## 主要项目

### 五子棋游戏 (gomoku)

一个基于 Canvas 的五子棋游戏实现，包含以下功能：

- 15x15 棋盘绘制
- 黑白棋子交替落子
- 坐标校准和网格对齐
- 胜负判断（五子连珠检测）
- 棋子绘制（带渐变效果）

### Canvas 绘图示例

多种基础绘图示例，展示了 Canvas API 的各种功能：

- 基本图形绘制（直线、折线、圆弧、椭圆等）
- 渐变效果应用
- 文本标签添加
- 自动填充功能

## 如何使用

1. 直接在浏览器中打开 HTML 文件即可运行对应示例
2. 对于五子棋游戏，点击棋盘落子，黑白双方交替进行
3. 当一方形成五子连珠时，游戏结束并提示获胜方

## 技术栈

- HTML5 Canvas API
- JavaScript
- CSS

## 扩展建议

1. 为五子棋添加回退功能
2. 实现 AI 对手
3. 添加游戏计时功能
4. 保存和加载游戏状态
