# Contributing

Thanks for improving awesome-token2cash! Please follow the conventions below so reviews stay fast.

## Adding an entry

Use this exact format:

```markdown
- [Name](https://github.com/user/repo) STAR `count` `lang` `license` — description
```

| Field | Rule |
|---|---|
| `Name` | Repository name, capitalized as in GitHub. |
| `url` | Direct link to the GitHub repository. |
| `STAR` | Literal text `STAR` (badge placeholder; maintainers will humanize). |
| `count` | Star count, e.g. `1.2k`. |
| `lang` | Primary language, e.g. `Python` or `-`. |
| `license` | License, e.g. `MIT`. |
| `description` | One concise sentence of what it does. |

Add the entry to the correct section and sort each list in descending order by star count.

## Inclusion criteria

- Must be a real, publicly accessible GitHub repository.
- In scope: projects that apply multi-agent systems or LLMs to stock analysis, trading, financial learning, sentiment analysis, datasets, or related papers.
- Out of scope: pure crypto projects without LLM relevance; traditional quant libraries that do not use LLMs or agents.

## Adding a new language

1. Copy the latest `README.md` (English source) to `README.<lang>.md`.
2. Translate the content.
3. Add the new language to the switcher line at the top of **every** existing `README*.md` file.

## PR checklist

- [ ] Repository exists and is public (verified via `gh api repos/<owner>/<repo>`).
- [ ] Star count is humanized (e.g. `12.5k`, not `12500`).
- [ ] Entries are sorted by star count in descending order.
- [ ] New section anchors use lowercase, hyphenated names (`#-my-section`).

---

## 简体中文 (Simplified Chinese)

# 贡献指南

感谢你对 awesome-token2cash 的贡献！请遵循以下约定，加速审阅。

## 添加条目

使用如下精确格式：

```markdown
- [Name](https://github.com/user/repo) STAR `count` `lang` `license` — description
```

| 字段 | 规则 |
|---|---|
| `Name` | GitHub 仓库名称，按原大小写。 |
| `url` | GitHub 仓库直接链接。 |
| `STAR` | 固定文本 `STAR`（徽章占位符，由维护者统一规范化）。 |
| `count` | Star 数量，如 `1.2k`。 |
| `lang` | 主要语言，如 `Python` 或 `-`。 |
| `license` | 许可证，如 `MIT`。 |
| `description` | 一句话说明项目作用。 |

将条目加入对应分类，并在分类内按 Star 数降序排列。

## 收录标准

- 必须是真实、公开可访问的 GitHub 仓库。
- 范围：将多智能体系统或 LLM 应用于股票分析、交易、金融学习、情感分析、数据集或相关论文的项目。
- 排除：与 LLM 无关的纯加密项目；未使用 LLM 或 Agent 的传统量化库。

## 新增语言翻译

1. 复制最新的 `README.md`（英文源文件）为 `README.<lang>.md`。
2. 翻译内容。
3. 在**每个**已有的 `README*.md` 顶部语言切换行中添加新语言。

## PR 检查清单

- [ ] 仓库存在且公开（通过 `gh api repos/<owner>/<repo>` 验证）。
- [ ] Star 数已规范化（如 `12.5k`，而非 `12500`）。
- [ ] 条目已按 Star 数降序排列。
- [ ] 新增锚点使用小写、连字符格式（`#-my-section`）。
