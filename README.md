# agent-os

把飞书变成 AI 编程 CLI（Claude Code / Codex）的指挥台。

- 一个话题 = 一个任务
- bot 之间可互相 @ 协作
- cron 定时巡检

## 运行

```bash
pnpm dev     # tsx watch
pnpm start
pnpm build
```

## 约定

- ESM only，Node 22+，pnpm
- 凭证只放 `.env`（已 gitignore），绝不硬编码、绝不提交
