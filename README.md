# 文陶的个人主页

个人文章、课程笔记和学习资源的静态主页，使用 HTML 与 CSS。

- 主页：https://tauzhao.github.io/wentao-homepage/
- 文章：10 篇旧稿、2 篇网页与网络笔记
- 资源目录：20 个课程、论文、模型与工具链接
- 首页照片：本人在扎龙拍摄的鹤群

## 本地查看

直接用浏览器打开 `index.html`，或在项目目录运行：

```sh
python3 -m http.server 8000
```

随后访问 `http://localhost:8000/`。

## 文件组织

- `index.html`：首页、文章目录和资源链接
- `about.html`：关于本站
- `posts/`：文章页面
- `css/style.css`：公共样式
- `images/`：照片与文章配图

## 修改与发布

GitHub Pages 的发布源为 `main` 分支根目录。提交并推送后，GitHub 会更新网站。

```sh
git status
git add .
git commit -m "Update homepage"
git push origin main
```

添加文章时，在 `posts/` 中保存新的 HTML 文件，并更新首页的文章目录和数量。链接与图片使用相对路径。

原有网页制作提交历史随源码保留。
