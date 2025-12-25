# Watermark Tool - 在线水印工具

一个基于React的在线水印工具，支持为图片添加文字或图片水印。

## 🌟 功能特性

- 📝 **文字水印** - 支持添加自定义文字水印
- 🖼️ **图片水印** - 支持添加图片作为水印
- 🎨 **样式自定义** - 可调整字体、颜色、大小、透明度等
- 📱 **响应式设计** - 适配各种设备屏幕
- ⚡ **实时预览** - 即时查看水印效果
- 💾 **一键下载** - 快速保存带水印的图片

## 🚀 快速开始

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

## 🚀 部署

### GitHub Pages 自动部署

本项目配置了GitHub Actions自动部署工作流。每次推送到`main`分支时，会自动执行以下步骤：

1. **构建应用** - 运行 `npm run build` 生成生产版本
2. **部署到GitHub Pages** - 自动将`dist`目录部署到GitHub Pages

**访问地址**: https://cherry-min.github.io/react-watermark-tool/

### 本地预览生产版本

```bash
npm run build
npm run preview
```

## 🛠️ 技术栈

- **React** - 前端框架
- **Vite** - 构建工具
- **TypeScript** - 类型安全
- **Tailwind CSS** - 样式框架

## 📁 项目结构

```
watermark/
├── src/
│   ├── components/         # React组件
│   │   ├── ImageWatermark.tsx
│   │   └── ui/            # UI组件
│   ├── lib/               # 工具函数
│   ├── assets/            # 静态资源
│   └── main.tsx           # 应用入口
├── public/                # 静态资源
├── dist/                  # 构建输出目录（自动部署到GitHub Pages）
├── .github/workflows/     # GitHub Actions工作流
├── LICENSE               # MIT许可证
└── README.md             # 项目文档
```

## 📝 使用说明

1. 上传需要添加水印的图片
2. 选择水印类型（文字或图片）
3. 自定义水印样式
4. 调整水印位置和大小
5. 点击下载保存结果

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进这个项目。

## 📝 许可证

本项目采用 [MIT License](LICENSE) 开源许可证。

## 📧 联系方式

如有问题或建议，欢迎通过以下方式联系：
- 提交Issue
- 发送邮件

---

⭐ 如果这个项目对你有帮助，请给个Star支持一下！
