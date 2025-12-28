# 个人作品集网站 | Personal Portfolio Website

一个现代化、响应式的个人作品集网站，使用纯 HTML、CSS 和 JavaScript 构建。

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📸 预览

<!-- 在这里添加网站截图 -->
<!-- ![网站预览](./images/preview.png) -->

> **提示**：你可以在完成网站后添加截图到这里

## ✨ 特性

- 📱 **完全响应式** - 适配所有设备（桌面、平板、手机）
- 🎨 **现代化设计** - 使用渐变色和流畅的动画效果
- 🚀 **性能优化** - 快速加载，流畅的用户体验
- ♿ **可访问性** - 遵循 WCAG 标准
- 🎯 **SEO 友好** - 优化的元标签和语义化 HTML
- 🌈 **平滑滚动** - 优雅的页面导航体验
- ⚡ **无依赖** - 纯 HTML/CSS/JS，不需要框架
- 🎭 **动画效果** - 滚动触发的淡入动画

## 📋 功能模块

- **首页** - 醒目的欢迎区域，介绍你的身份
- **关于我** - 个人简介和基本信息
- **技能** - 展示你掌握的技术栈
- **作品集** - 展示你的项目作品
- **联系方式** - 联系表单和社交媒体链接
- **返回顶部** - 便捷的页面导航按钮

## 🚀 快速开始

### 前置要求

- 一个现代化的浏览器（Chrome、Firefox、Safari、Edge）
- （可选）Node.js 和 npm - 如果你想使用开发服务器

### 安装步骤

1. **克隆仓库**

```bash
git clone https://github.com/yourusername/duoduoweb.git
cd duoduoweb
```

2. **添加图片资源**

将你的个人照片和项目截图放入 `images/` 文件夹：
- `profile.jpg` - 个人照片
- `project1.jpg`, `project2.jpg`, `project3.jpg` - 项目截图

> 详细说明请查看 [images/README.md](./images/README.md)

3. **自定义内容**

编辑 `index.html` 文件，替换以下内容：
- 个人姓名和简介
- 技能描述
- 项目信息
- 联系方式和社交媒体链接

4. **运行网站**

**方法 1：直接打开（最简单）**
```bash
# 直接在浏览器中打开 index.html
双击 index.html 文件
```

**方法 2：使用开发服务器（推荐）**
```bash
# 安装依赖
npm install

# 启动开发服务器
npm start
```

然后在浏览器中访问 `http://localhost:3000`

## 📁 项目结构

```
duoduoweb/
├── index.html              # 主 HTML 文件
├── css/
│   └── style.css          # 样式表
├── js/
│   └── main.js            # JavaScript 交互逻辑
├── images/                # 图片资源文件夹
│   ├── README.md          # 图片说明文档
│   ├── profile.jpg        # 个人照片
│   ├── project1.jpg       # 项目1截图
│   ├── project2.jpg       # 项目2截图
│   └── project3.jpg       # 项目3截图
├── projects/              # 项目详情页面（可选）
├── package.json           # 项目配置文件
├── LICENSE                # Apache-2.0 许可证
└── README.md              # 项目说明文档
```

## 🎨 自定义指南

### 修改颜色主题

在 `css/style.css` 文件的顶部找到 CSS 变量：

```css
:root {
    --primary-color: #6366f1;      /* 主色调 */
    --secondary-color: #8b5cf6;    /* 辅助色 */
    --accent-color: #ec4899;       /* 强调色 */
    /* 修改这些值来改变网站配色 */
}
```

### 添加更多项目

在 `index.html` 的项目部分复制粘贴项目卡片代码：

```html
<div class="project-card">
    <div class="project-image">
        <img src="images/your-project.jpg" alt="项目名称">
        <div class="project-overlay">
            <a href="#" class="btn-view">查看详情</a>
        </div>
    </div>
    <div class="project-info">
        <h3>你的项目名称</h3>
        <p>项目描述...</p>
        <div class="project-tags">
            <span class="tag">技术1</span>
            <span class="tag">技术2</span>
        </div>
    </div>
</div>
```

### 修改字体

可以在 `css/style.css` 中引入 Google Fonts：

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

body {
    font-family: 'Poppins', sans-serif;
}
```

## 🔧 技术栈

- **HTML5** - 语义化标签，SEO 优化
- **CSS3** - Flexbox、Grid、动画、渐变
- **JavaScript (ES6+)** - 交互功能、DOM 操作
- **Font Awesome** - 图标库

## 📱 浏览器支持

- ✅ Chrome（推荐）
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

> 支持所有现代浏览器的最新两个版本

## 🚀 部署

### GitHub Pages

1. 将代码推送到 GitHub 仓库
2. 进入仓库的 Settings > Pages
3. 选择 main 分支作为源
4. 保存后等待几分钟
5. 访问 `https://yourusername.github.io/duoduoweb`

### Netlify

1. 在 Netlify 注册账号
2. 点击 "New site from Git"
3. 连接你的 GitHub 仓库
4. 点击 "Deploy site"

### Vercel

1. 在 Vercel 注册账号
2. 导入你的 GitHub 仓库
3. 一键部署

## 📝 待办事项

- [ ] 添加个人照片和项目截图
- [ ] 修改个人信息和简介
- [ ] 更新社交媒体链接
- [ ] 添加真实的项目案例
- [ ] （可选）集成后端表单处理服务
- [ ] （可选）添加深色模式切换
- [ ] （可选）添加多语言支持

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 这个仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📄 许可证

本项目使用 [Apache-2.0](LICENSE) 许可证。

## 👨‍💻 作者

**Querrky125**
- Email: qukun19851125@gmail.com
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 致谢

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Unsplash](https://unsplash.com/) - 高质量图片资源
- 感谢所有开源贡献者

## 💡 灵感来源

如果你觉得这个项目有帮助，欢迎给个 ⭐ Star！

---

**📌 提示**：这是一个学习项目，适合初学者了解 Web 开发的基础知识。随着你技能的提升，可以继续添加更多功能！

## 📚 学习资源

- [MDN Web Docs](https://developer.mozilla.org/) - Web 开发权威文档
- [CSS-Tricks](https://css-tricks.com/) - CSS 技巧和教程
- [JavaScript.info](https://javascript.info/) - 现代 JavaScript 教程
- [W3Schools](https://www.w3schools.com/) - Web 技术教程

## 🐛 常见问题

**Q: 为什么图片不显示？**
A: 确保图片文件放在 `images/` 文件夹中，且文件名与 HTML 中引用的名称一致。

**Q: 如何修改网站配色？**
A: 在 `css/style.css` 文件顶部的 `:root` 选择器中修改 CSS 变量。

**Q: 联系表单如何工作？**
A: 目前表单只有前端验证。要实现实际发送功能，需要集成后端服务（如 FormSpree、Netlify Forms）。

**Q: 可以用于商业项目吗？**
A: 可以！本项目使用 Apache-2.0 许可证，允许商业使用。

---

**开始构建你的精彩作品集吧！** 🎉
