# 森月集

这是 `https://awaym0.github.io/` 的新版静态博客源文件。

## 定位

公开给朋友看的个人博客，主要记录：

- 科研学习
- 生活随笔
- 各种奇奇怪怪的知识
- 影集

## 怎么更新文章

1. 新建一个英文路径文件夹，例如 `posts/my-new-note/`。
2. 复制 `posts/_template.html` 到新文件夹里，并改名为 `index.html`。
3. 打开新文件夹里的 `index.html`，修改栏目、标题、日期和正文。
4. 在 `index.html` 首页对应分类卡片里更新“最新文章”链接。
5. 在 `archives/index.html` 归档页加一条新文章链接。
6. 把这些文件提交到 GitHub 仓库 `AwayM0/AwayM0.github.io`。

## 文件说明

- `index.html`：首页
- `about/index.html`：关于页
- `archives/index.html`：归档页
- `posts/start/index.html`：示例文章
- `posts/_template.html`：新文章模板
- `assets/site.css`：全站样式
- `.nojekyll`：让 GitHub Pages 按普通静态文件发布

这个版本不依赖 Hexo、Node.js 或 npm。
