# App 技术支持 & 隐私政策站点

GitHub Pages 静态站，托管所有 App 的技术支持页 + 隐私政策。

## 目录结构
```
.
├── index.md            技术支持主页（列出所有 App）
├── _config.yml         GitHub Pages 主题
└── translens/
    └── privacy.md      TransLens 隐私政策
```

## 新增一个 App
1. 新建目录 `appname/`
2. 放入 `appname/privacy.md`（开头加 front matter：`---\ntitle: ...\n---`）
3. 在 `index.md` 的 Apps 区加一段链接

## 开启 GitHub Pages
1. 把本目录推到一个 GitHub 仓库（例如 `support`）
2. 仓库 Settings → Pages → Source 选 `main` 分支 `/ (root)`
3. 等 1-2 分钟，访问：
   - 支持页：`https://xiezhanglin666-del.github.io/support/`
   - TransLens 隐私：`https://xiezhanglin666-del.github.io/support/translens/privacy`
