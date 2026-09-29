# portfolio-github-pages

这是 GitHub Pages 备用发布目录。

- `index.html` 是 GitHub Pages 入口文件。
- 资源路径必须使用相对路径，例如 `portfolio/photos/...`，不要使用 `/portfolio/...`。
- 作品集详情页保留清晰资源，优先保证面试查看质量。
- 原始工作文件保留在上一级目录，这里只放 GitHub Pages 需要发布的文件。
- 不放 `node_modules`、PDF、旧版 HTML、临时文件或设计源文件。

## 发布资源约定

- `portfolio/` 按主站引用路径保存图片；项目子目录使用英文项目名，例如 `keeta/`。
- Keeta 当前详情使用 `portfolio/projects-20260922/keeta/1.png` 到 `33.png` 的 3840px 高清无损切片，来源为 `D:/dsktop/作品集拼接最新/keeta.pdf`。保留旧资源；不发布 `qa-*`、manifest、验证脚本或中断生成的草稿。
- 发布前校验所有本地资源引用，并验证所有项目的点击放大、还原和双向滚动。
- 删除不再使用的资源须先征得用户同意。

- 拼多多项目使用 `portfolio/projects-20260929/pinduoduo/1.png` 到 `5.png`，3840px 无损切片；不发布源 PDF、cover、manifest 或 QA 文件。

## Automatic Website Publishing

- User authorization (2026-09-29): after requested website changes pass verification, commit and push the relevant site changes to the existing GitHub Pages release automatically, then verify the live version. No repeat confirmation is needed for this website publication. Other destructive operations remain subject to confirmation.

## Xiaohongshu Project

- `portfolio/projects-20260929/xiaohongshu/` stores numbered 3840px lossless PNG slices from `D:/dsktop/杨岱江 - 福州大学-27届小红书体验设计测试13859951216.pdf`. Keep `cover.png` and `manifest.json` local only; publish referenced numbered PNGs. Helpers and visual QA belong in `tmp/pdfs/qa-portfolio-*`; retain previous assets.
