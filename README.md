# 中国学术地图

这是一个静态网页地图项目，入口文件为 `index.html`，通过 GitHub Pages 发布。

当前线上地址：

```text
https://huangjz-bamboo.github.io/china-intellectual-map/
```

## 版本文件

- `index.html`: 当前公网入口，使用 `files/china-intellectual-map-offline.html` 的离线版内容。
- `china-intellectual-map.html`: 初始版本备份。
- `files/china-intellectual-map-offline.html`: 2026-06-10 新增离线版。
- `files/china-intellectual-map-satellite.html`: 2026-06-10 新增卫星版。

## 本地预览

直接用浏览器打开 `index.html` 即可预览。

## GitHub Pages 发布

1. 将本目录推送到 GitHub 仓库。
2. 在仓库页面进入 `Settings` -> `Pages`。
3. 在 `Build and deployment` 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. 保存后等待 GitHub Pages 构建完成。

发布地址通常为：

```text
https://<your-github-username>.github.io/<repository-name>/
```
