# 图片格式转换器 · Image Converter

免费在线批量图片格式转换工具，支持 WebP / PNG / JPG 输出。**100% 浏览器本地处理**，不上传服务器，保护隐私安全。

## ✨ 功能

- 🔄 **WebP / PNG / JPG** 三种输出格式
- 🌓 **暗黑/亮白** 双主题可切换，偏好自动保存
- 📁 批量拖拽文件或文件夹上传
- 🎚️ 无损 / 高质量 / 自定义 三种转换模式
- 📏 智能体积限制（二分搜索最优质量，确保不超过目标 KB）
- 🔍 原图 vs 转换后对比预览
- 📦 批量下载（自动打包 ZIP）
- 🌌 Three.js 动态粒子背景
- 🖱️ 自定义光效光标

## 🚀 部署

纯静态 HTML，扔到任何静态托管即可：

```bash
# GitHub Pages
git push origin main  # 设置 Pages source 为 main 分支

# 本地预览
python -m http.server 8080
# 或直接用浏览器打开 index.html
```

## 📋 支持格式

| 输入 | 输出 |
|------|------|
| PNG、JPG、GIF、BMP、TIFF、WebP | WebP、PNG、JPG |

## 🔒 隐私

所有图片在浏览器本地通过 Canvas API 处理，**绝不会上传到任何服务器**。断网也能用。

## 📄 License

MIT
