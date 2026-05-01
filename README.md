# LIONSTUDIO

**WEB** — n8n 自动发布的研究趋势站点与数据仓库（GitHub Pages + 结构化数据）。

| 路径 | 说明 |
|------|------|
| `docs/` | **GitHub Pages**：`index.html` 为站点首页（工作流每次覆盖）；`.nojekyll` 禁用 Jekyll |
| `data/` | 中文 CSV（各期一条，`communication-trends-zh-*.csv`） |
| `database/csv/` | 英文列 CSV（`communication-trends-en-*.csv`，原始分析友好） |
| `database/snapshots/` | **原始数据库**：JSON 快照（`snapshot-YYYY-MM-DD.json`，含 `articles`、主题、简报等） |
| `reports/` | 中文 PDF 简报 |
| `dashboard/` | 预留 |

- **仓库**：<https://github.com/asbaniaworld-ui/LIONSTUDIO>  
- **建议站点**：<https://asbaniaworld-ui.github.io/LIONSTUDIO/>（Settings → Pages → `main` + **`/docs`**）

工作流：`Communication Research Trends Tracker[02].json`  
环境变量：`GITHUB_TOKEN`、`GH_PAGES_REPO=asbaniaworld-ui/LIONSTUDIO`、可选 `GH_PAGES_BRANCH=main`

本地说明另见 **`GitHub清理并重新上传.txt`**。
