# 云盘文件下载工具

[English](README_EN.md)

一个纯前端的小工具，用于快速生成 Google Drive 与 OneDrive 的下载命令，支持深色模式与中英文切换。

## 功能特性
- Google Drive：支持直接粘贴分享链接，自动提取文件 ID
- OneDrive：支持粘贴完整 cURL 命令，一键生成下载命令
- 主题跟随系统，支持手动切换
- 中英文界面切换

## 在线预览
- GitHub Pages：`https://luh1124.github.io/drive-curl-generator/`

## 本地使用
1. 直接打开 `app.html`
2. 或用任意静态服务器托管（如 `python -m http.server`）

## 部署到 GitHub Pages
1. 新建仓库并提交代码
2. 仓库设置 → Pages → 选择分支（如 `main`）与根目录
3. 等待部署完成，访问生成的链接

## 使用教程
### Google Drive（支持直接粘贴分享链接）
1. 复制分享链接或文件 ID
2. 粘贴到「文件ID或分享链接」
3. 输入保存文件名
4. 点击「生成下载命令」并复制使用

### OneDrive（文字流程）
1. 打开 OneDrive 分享链接
2. 按 `F12` 打开开发者工具，切换到 `Network`/`网络`
3. 点击页面的「下载」
4. 在请求列表中找到 `download.aspx`
5. 右键该请求 → `Copy` → `Copy as cURL`
6. 将完整 cURL 粘贴到输入框，生成命令并复制使用

### OneDrive（图文流程占位）
> 你可以按以下顺序补充截图或录屏：
1. 打开分享链接页面
2. `F12` → `Network`/`网络` 面板
3. 点击下载并出现 `download.aspx`
4. 右键请求复制为 cURL

## 许可
MIT
