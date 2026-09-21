# syutoi.com

Syutoi 官方网站的第一版静态占位页。

## 特点

- 纯 HTML / CSS / JavaScript
- 无构建工具、无运行时依赖
- 响应式布局
- 自动适配系统浅色 / 深色模式
- 基础 SEO / Open Graph
- 自带 favicon、404、robots.txt、sitemap.xml
- 可直接部署到 GitHub Pages、Cloudflare Pages、Netlify、Vercel、Nginx/Caddy 等静态托管

## 本地预览

进入项目目录后：

```bash
python3 -m http.server 8080
```

然后访问：

```text
http://localhost:8080
```

## 目录

```text
.
├── index.html
├── 404.html
├── CNAME
├── robots.txt
├── sitemap.xml
└── assets
    ├── css
    │   └── style.css
    ├── images
    │   ├── favicon.svg
    │   └── syutoi-logo.png
    └── js
        └── main.js
```

## GitHub Pages

仓库推送到 GitHub 后，可在 **Settings → Pages** 中选择从分支部署。项目根目录已提供 `CNAME`：

```text
syutoi.com
```

随后按 GitHub Pages 提示配置域名 DNS 即可。

## Cloudflare Pages

不需要构建命令：

- Framework preset: `None`
- Build command: 留空
- Build output directory: `/`

部署后在 Custom domains 中添加 `syutoi.com`。

## 后续建议

这一版定位为“品牌占位页”。等 `hexo-theme-syutoi` 发布后，再逐步加入：

- Projects / Products
- GitHub 链接
- Theme Demo
- About
- Blog / Journal
- Syutoi Cat 品牌动画与状态插画
