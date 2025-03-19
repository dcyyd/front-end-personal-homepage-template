<h1 align="center">🌟 D.C.Y. 个人主页模板</h1>
<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License">
  <img src="https://img.shields.io/badge/version-2.0.0-green" alt="版本">
  <img src="https://img.shields.io/badge/accessibility-AA-success" alt="无障碍等级">
</p>

## 🚀 项目概览

**现代化的个人数字门户，集成**：

- 📌 多平台入口聚合
- 🎨 响应式视觉设计（支持移动端/桌面端）
- 🔒 企业级安全策略（CSP/SRI/Referrer Policy）
- 📊 技能矩阵可视化展示
- 🌐 SEO 优化（Schema.org 结构化数据）

**在线预览**：[https://dcyyd.github.io/front-end-personal-homepage-template](https://dcyyd.github.io/front-end-personal-homepage-template)

## ✨ 核心特性

| 功能模块     | 技术实现                           | 性能指标              |
| ------------ | ---------------------------------- | --------------------- |
| 星空动态背景 | Canvas + RequestAnimationFrame     | 60FPS 稳定渲染        |
| 技能进度条   | CSS Custom Properties + Transition | GPU 加速动画          |
| 项目卡片     | CSS Grid + Aspect-ratio            | 自适应布局            |
| 社交图标     | FontAwesome 6.5 + SVG Sprites      | 矢量图标（<2KB 加载） |
| 图片懒加载   | Intersection Observer API          | 优化页面加载性能      |

## 🛠️ 技术栈

```bash
# 核心依赖
├── 📦 HTML5 Semantic Tags，用于构建具有语义的页面结构
├── 🎨 CSS3 (Flexbox/Grid/Custom Properties)，实现页面布局和样式设计
└── ⚡ JavaScript (ES6+)，实现页面交互和动态效果

# 增强功能
├── 📈 Google Analytics，通过异步脚本加载跟踪网站数据
├── 🔐 Content Security Policy，保障网站内容安全
└── 🖼️ Lazy Loading (Intersection Observer API)，优化图片加载性能
```

## 📂 项目结构

```bash
front-end-personal-homepage-template/
├── 📁 assets
│   ├── 📁 css        # 样式资源
│   ├── 📁 js         # 脚本模块
│   └── 📁 images     # 项目用到的图片
├── 🔒 robots.txt     # 搜索引擎爬虫协议
├── 📚 .gitignore     # Git版本控制忽略文件
├── 📄 LICENSE        # 开源许可证
├── ❌ 404            # 404页面
├── 📝 README.md      # 项目文档
├── 🗺️ sitemap.xml    # SEO站点地图
└── 📜 index.html     # 单页应用入口
```

## 🎯 最佳实践

1. 资源预加载（使用 `<link rel="preload">`），如预加载 CSS 和 JS 文件，提高页面加载速度。
2. 关键 CSS 内联（首屏优化），减少首屏加载时间。
3. 异步脚本加载（`async/defer`），避免脚本阻塞页面渲染。
4. 响应式图片（`srcset+sizes`），根据设备屏幕大小加载合适的图片。
5. 无障碍访问（ARIA 标签 + 语义化 HTML），提高网站的可访问性。

## 🚀 快速开始

```bash
# 克隆项目
git clone https://github.com/dcyyd/front-end-personal-homepage-template.git
# 进入项目目录
cd front-end-personal-homepage-template
# 启动网页
start index.html 
```

## 📞 技术支持

- 📮 **联系维护者**：[dcyyd_kcug@yeah.net](mailto:dcyyd_kcug@yeah.net)
- 🐙 **GitHub 主页**：[https://github.com/dcyyd](https://github.com/dcyyd)/

## 📜 许可证

```text
MIT License
Copyright (c) 2024 窦长友

授予权限包括但不限于：
✅ 商业用途    ✅ 修改衍生    ✅ 私有部署
✅ 专利使用    ✅ 责任免除    ✅ 版权声明保留
```
