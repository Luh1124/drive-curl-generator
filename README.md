# 云盘文件下载工具

[English](README_EN.md)

一个纯前端的小工具，用于快速生成 Google Drive 与 OneDrive 的下载命令，支持深色模式与中英文切换。

## 功能特性
- Google Drive：支持直接粘贴分享链接，自动提取文件 ID
- OneDrive：支持粘贴完整 cURL 命令，一键生成下载命令
- 主题跟随系统，支持手动切换
- 中英文界面切换

## 在线预览
- GitHub Pages：`https://<你的用户名>.github.io/<仓库名>/`
- 自定义域名：`https://your-domain.com/`

## 本地使用
1. 直接打开 `app.html`
2. 或用任意静态服务器托管（如 `python -m http.server`）

## 部署到 GitHub Pages
1. 新建仓库并提交代码
2. 仓库设置 → Pages → 选择分支（如 `main`）与根目录
3. 等待部署完成，访问生成的链接

## 使用说明
### Google Drive
1. 粘贴分享链接或文件 ID
2. 输入保存文件名
3. 点击生成命令并复制使用

### OneDrive
1. 打开分享链接 → F12 → Network
2. 点击下载，找到 `download.aspx`
3. 右键请求 → Copy as cURL
4. 粘贴 cURL，生成命令并复制

## 可配置项
- 修改 GitHub 链接：
  - 在 `app.html` 中查找 `https://github.com/yourname/drive-download` 并替换为你的仓库地址

## 许可
MIT
