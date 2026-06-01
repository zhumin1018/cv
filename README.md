# 朱敏个人简历与作品集网站

这是一个可部署到 GitHub Pages 的静态个人网站，包含：

- 关于我
- 实习经历
- 作品集

## 内容结构

- `index.html`：网页内容，包括个人介绍、经历、新闻稿件概览、作品集分组和视频网盘链接。
- `styles.css`：页面样式，主色调为浅绿色，支持移动端自适应。
- `assets/profile.jpg`：个人头像。
- `assets/portfolio/`：作品集图片素材。

## 后续编辑

- 修改个人信息：编辑 `index.html` 首屏和关于我区域。
- 新增作品图片：把图片放入 `assets/portfolio/`，再在对应作品区复制一个 `<figure><img ... /></figure>`。
- 修改视频作品链接：编辑 `index.html` 中“视频制作作品集”区域的百度网盘链接与提取码。

## GitHub Pages

推送到 GitHub 后，工作流会自动发布站点。仓库 Pages 来源选择 GitHub Actions 即可。
