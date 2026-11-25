# 陈泉的博客

静态博客，首页包含精选文章和分类筛选，正文页包含完整文章和延伸阅读。正文来自 [chenquan.me 旧站](https://chenquan.me/)，首版收录六篇。

## 本地预览

在仓库根目录运行 `python3 -m http.server 8765`，然后打开 http://localhost:8765/。

## GitHub Pages

在仓库的 **Settings → Pages** 中选择 **Deploy from a branch**，发布 `main` 分支的 `/ (root)`。页面使用相对路径，支持 GitHub Pages 的项目子路径，无需构建。

## 更新文章

在 `posts/<slug>/index.html` 新增正文，参考已有文章的结构。在 `index.html` 中新增带 `data-topic` 的文章条目。公共样式位于 `assets/site.css`。

首页的乌镇照片来自原文。其余两张封面来自 [Unsplash](https://unsplash.com/)（[电路板](https://images.unsplash.com/photo-1518770660439-4636190af475)和[代码](https://images.unsplash.com/photo-1515879218367-8466d910aaa4)）。
