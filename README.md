# 📦 Weekly Digest — 每周总结 & 每周五小工具

每周自动产出的两个固定栏目,周一 09:00 / 周五 17:00 自动生成、自动提交、自动同步四站
(GitHub / Gitee / AtomGit / 极狐GitLab)。

## 🗓 每周总结(每周一 09:00 推送)

| 周次 | 总结 | 亮点 |
|---|---|---|
| 2026-W39 | [查看](SUMMARY/2026-W39.md) | 首期 |
| 2026-W40 | [查看](SUMMARY/2026-W40.md) | 语言知识体系库上线 |

- 内容:上周 arXiv 命中论文、GitHub 提交汇总、工作台数据、待办提醒
- 模板见 `_templates/weekly-summary.md`

## 🛠 每周五小工具(每周五 17:00 推送)

| 周次 | 工具 | 说明 |
|---|---|---|
| 2026-W39 | [Token 速算器](MINI-TOOLS/2026-W39-token-estimator/) | LLM 文本 Token 与费用估算(零依赖纯静态 HTML) |

- 内容:每周一个实用单文件小工具(优先纯静态 HTML,零依赖)
- 每个工具独立目录 `MINI-TOOLS/2026-Wxx-名称/`,内含 `index.html` 或脚本 + 简短说明

## 🔄 自动化

- 生成与提交:本地 Hermes cron(周一 09:00 / 周五 17:00)
- 四站同步:`G:\code\github\workbench\mirror_push.py`(每日任务内自动执行)
