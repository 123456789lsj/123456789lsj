# 个人网站

一个现代化的响应式个人网站模板，使用HTML5、CSS3和JavaScript构建。

## 功能特点

- 📱 **响应式设计**：适配各种屏幕尺寸
- 🎨 **现代化UI**：简洁美观的设计风格
- ⚡ **流畅动画**：平滑的过渡和动画效果
- 📋 **完整模块**：首页、关于我、技能、项目、联系
- 🔧 **交互功能**：导航栏滚动效果、菜单切换、表单提交
- 📧 **联系表单**：模拟表单提交功能

## 项目结构

```
个人博客/
├── index.html          # 主HTML文件
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # JavaScript文件
├── images/             # 图片目录
└── README.md           # 项目说明
```

## 如何使用

1. **克隆或下载项目**
2. 在浏览器中打开 `index.html` 文件
3. 根据需要修改内容和样式

## 自定义内容

### 修改个人信息
- 编辑 `index.html` 文件中的个人信息、技能和项目内容
- 修改 `home` 部分的姓名和职业描述
- 更新 `about` 部分的个人介绍和联系方式

### 添加图片

1. 将图片文件放入 `images/` 目录
2. 更新HTML文件中的图片路径：

```html
<!-- 个人照片 -->
<img src="images/profile.jpg" alt="个人照片">

<!-- 项目图片 -->
<img src="images/project1.jpg" alt="项目1">
```

#### 占位图片

如果没有实际图片，可以使用以下占位图片服务：

- [Unsplash](https://source.unsplash.com/)
- [Placeholder.com](https://placeholder.com/)
- [Lorem Picsum](https://picsum.photos/)

示例：
```html
<img src="https://picsum.photos/id/1005/300/300" alt="个人照片">
<img src="https://source.unsplash.com/random/800x400/?ecommerce" alt="项目1">
```

### 修改样式

编辑 `css/style.css` 文件来自定义颜色、字体和布局：

- 修改 `:root` 中的CSS变量（如果有的话）
- 调整各部分的样式类
- 更改响应式断点

### 添加新功能

在 `js/main.js` 文件中添加新的交互功能：

- 添加新的事件监听器
- 实现新的动画效果
- 集成第三方API

## 技术栈

- **HTML5**：语义化标签
- **CSS3**：Flexbox、Grid、动画
- **JavaScript**：ES6+ 特性
- **Font Awesome**：图标库

## 浏览器支持

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 许可证

MIT License

## 贡献

欢迎提交Issue和Pull Request！

## 更新日志

### v1.0.0 (2024-01-08)
- 初始版本发布
- 实现基础功能和响应式设计

---

如有任何问题，请随时联系我！