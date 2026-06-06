# 金融作战室网页报告

本仓库用于通过 GitHub Pages 托管和渲染生成的金融作战室 HTML 报告。

## 目录

- `public/index.html`：网页入口。
- `public/`：所有静态资源、音频、图片和原始 JSON 数据。
- `.github/workflows/pages.yml`：GitHub Pages Actions 部署工作流。

## 发布方式

1. 在 GitHub 新建仓库，并把本地仓库推送到 `main`。
2. 进入仓库 `Settings -> Pages`。
3. 将 Build and deployment 的 Source 设为 `GitHub Actions`。
4. 推送后等待 Actions 完成部署。

预期 Pages 地址：

https://randomnamec.github.io/daily-finance-war-room-pages-test/

## 本地校验

资源校验：通过
