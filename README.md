# Gemini-CLI 终极使用教程网站

一个现代化、响应式的 Gemini-CLI 使用教程网站，包含完整的安装指南、命令详解和高级技巧。

## 特性

- 🎨 现代化 UI 设计，响应式布局
- 📱 移动端友好
- 🚀 静态网站，易于部署
- 💻 代码高亮和复制功能
- 🔍 目录导航和锚点链接
- 🌙 平滑滚动和动画效果

## 技术栈

- HTML5 语义化标签
- CSS3 自定义属性和 Grid 布局
- JavaScript 交互功能
- Prism.js 代码高亮
- Google Fonts 字体优化

## 本地运行

```bash
# 克隆项目
git clone <repository-url>

# 进入项目目录
cd gemini-cli-tutorial

# 启动本地服务器（需要安装 live-server 或类似工具）
npx live-server

# 或者直接在浏览器中打开 index.html
```

## 部署

### GitHub Pages 部署

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 `main` 分支的 `root` 目录作为源

### Cloudflare Pages 部署

1. 登录 Cloudflare Dashboard
2. 选择 Pages 服务
3. 连接 GitHub 仓库
4. 设置构建配置：
   - 构建命令：`npm run build`（如果需要构建）或留空
   - 发布目录：`/`（根目录）
5. 点击部署

## 自定义

### 修改内容

- 编辑 `index.html` 文件以修改教程内容
- 更新 `styles.css` 以调整样式
- 修改 `script.js` 以添加或修改交互功能

### 主题定制

网站使用 CSS 自定义属性定义颜色主题，可以在 `styles.css` 中修改以下变量：

```css
:root {
    --bg-primary: #0f172a;
    --bg-secondary: #1e293b;
    --accent-primary: #3b82f6;
    /* 更多颜色变量... */
}
```

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个教程网站。