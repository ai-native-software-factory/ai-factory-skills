# Visual Companion 参考指南

本文件供 Brainstorming 流程中 BA 使用。

## 何时使用

每个问题独立决定——用户看图比读文字理解得更好时用浏览器。

### 用浏览器（视觉内容）
- 线框图和模型
- 布局对比（A/B/C/D 并列）
- 架构图和流程图
- 用户旅程图
- 竞品界面截图对比
- 配色/字体方案展示

### 用终端（文本内容）
- 需求问题
- 概念选择
- 权衡列表
- 范围决策
- 优先级讨论

## 如何使用 Browser 工具

1. 用 `browser_navigate` 打开或创建可视化页面
2. 用 `browser_snapshot` 检查当前状态
3. 用 `browser_type` / `browser_click` 交互
4. 用 `browser_vision` 确认视觉效果

## 本地 HTML 方案

最简单的方案：创建单个 `~/visual-companion.html`，每次讨论更新其内容。

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <style>
    body { font-family: system-ui; padding: 2rem; max-width: 900px; margin: 0 auto; }
    .wireframe { border: 1px solid #ccc; padding: 1rem; margin: 1rem 0; }
    .section { margin-bottom: 2rem; }
    h3 { color: #333; }
  </style>
</head>
<body>
  <!-- 内容由 Brainstorming 流程动态更新 -->
</body>
</html>
```

## 常用可视化模板

### 竞品对比表

```html
<table>
  <tr><th>功能</th><th>产品A</th><th>产品B</th><th>我们</th></tr>
  <tr><td>功能1</td><td>✅</td><td>❌</td><td>规划中</td></tr>
</table>
```

### 用户旅程图

```html
<div style="display:flex; gap:1rem;">
  <div>认知 →</div>
  <div>考虑 →</div>
  <div>使用 →</div>
  <div>留存</div>
</div>
```

### 线框模板

```html
<div class="wireframe">
  <div style="background:#f5f5f5;padding:0.5rem;">[Header]</div>
  <div style="min-height:200px;">[Main Content]</div>
  <div>[Footer]</div>
</div>
```
