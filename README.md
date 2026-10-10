# 《弑父者》网页小说

格鲁吉亚作家亚历山大·卡兹别吉长篇小说《弑父者》（მამის მკვლელი / The Patricide, 1882）的全书中文详细译述，纯静态站点，无构建步骤。

## 部署到 GitHub Pages

1. 新建一个仓库，名为 `<你的用户名>.github.io`（或任意项目仓库）。
2. 把本目录下所有文件（`index.html`、`part1.html`、`part2.html`、`part3.html`、`notes.html`）提交到仓库根目录并推送。
3. 若是 `<用户名>.github.io` 仓库，推送后访问 `https://<用户名>.github.io` 即可；
   若是项目仓库，到 Settings → Pages 选择分支（如 `main` / 根目录），稍等片刻访问 `https://<用户名>.github.io/<仓库名>/`。

所有链接均为相对路径，两种托管方式都无需改动。

## 文件

- `index.html` — 扉页：作品背景、人物表、风物词、总目录
- `part1.html` / `part2.html` / `part3.html` — 三部正文（共 36 场）
- `notes.html` — 主题与结构评点、译本信息

功能：明暗主题切换（记忆偏好）、阅读进度条、章节高亮、自动记忆上次阅读位置。
