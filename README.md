# io · 原神主题页面

2022 年创建的前端练习作品：一个原神主题的静态页面，仓库里还保留了 GitHub Pages 的自动部署工作流。

## ⚠️ 当前状态

仓库中**只提交了 `index.html`**，而页面引用的 `js/index.js`、`css/index.css` 和 `image/` 图片目录并未上传。因此直接打开页面时，样式和交互会缺失。这是一个未完成的历史作品，保留在此作为记录。

## 页面结构

- `index.html` —— 主页面，标题「原神」，用 jQuery 1.8.3（CDN）做交互
- `.github/workflows/static.yml` —— GitHub Pages 静态站点部署工作流
- `.github/workflows/jekyll-docker.yml` —— Jekyll 构建工作流

## 如何补全

如果你想把它跑起来，需要补齐以下文件并在 `index.html` 同目录下放置：

```
io/
├── index.html
├── css/index.css
├── js/index.js
└── image/          # index.html 中引用的图片
```

补齐后直接双击 `index.html` 即可预览；推送到 main 分支后，GitHub Pages 工作流会自动部署到 `https://yunhm-520.github.io/io/`。

## 技术栈

HTML · CSS · jQuery

## 说明

早期前端练习，代码较旧（jQuery 1.8.3），仅供学习参考。
