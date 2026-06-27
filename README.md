# 组合数学与信息交叉科学研究团队

这是一个使用 Quarto 制作的中文数学团队主页模板。

## 文件说明

- `_quarto.yml`：网站总设置，包括标题、导航栏、发布网址
- `index.qmd`：首页
- `people.qmd`：团队成员
- `publications.qmd`：论文成果
- `seminars.qmd`：讨论班
- `news.qmd`：新闻动态
- `openings.qmd`：招生招聘
- `resources.qmd`：学术资源
- `styles.css`：页面样式
- `images/`：成员照片与图片资源

## 本地预览

在项目文件夹中运行：

```bash
quarto preview
```

## 生成网页

```bash
quarto render
```

生成后的网页会放在 `docs/` 文件夹中。

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库，例如 `combinatorics-info-group-homepage`
2. 上传本文件夹中的所有文件
3. 在本地运行 `quarto render`，并把生成的 `docs/` 文件夹一起上传
4. 进入 GitHub 仓库的 Settings -> Pages
5. 选择 Source: Deploy from a branch
6. 选择 Branch: main，Folder: /docs

网站通常会发布到：

```text
https://your-username.github.io/combinatorics-info-group-homepage/
```
