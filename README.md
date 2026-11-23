# 论文阅读笔记

这是一个用于整理机器学习与大语言模型论文阅读笔记的静态网站。

## 本地预览

直接用浏览器打开 `index.html`。

## GitHub Pages 部署

1. 将本目录中的文件上传到 GitHub 仓库根目录。
2. 仓库设为 **Public**。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，点击 Save。
6. 等待 GitHub Actions 完成部署，访问 `https://<username>.github.io/<repository>/`。

## 文件结构

- `index.html`：论文阅读笔记首页。
- `deepseek-v2.html`：DeepSeek-V2 详细研读笔记。

## 新增论文笔记

将新文章 HTML 放在仓库根目录，然后在 `index.html` 的“全部笔记”区域新增一张卡片，并将卡片链接指向对应 HTML 文件。
