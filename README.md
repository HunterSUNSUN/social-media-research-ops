# Social Media Research Ops

A reusable Codex Skill for turning real social-platform browsing into competitor intelligence, platform-specific strategy, publishable content ideas, and structured Obsidian notes.

It is designed for research across X/Twitter, Xiaohongshu, TikTok, Reddit, and adjacent creator communities. The workflow emphasizes observed posts, comment demand, repeated patterns, and explicit separation between evidence and inference.

## What It Does

- Builds a research map across direct competitors, adjacent accounts, and demand communities.
- Captures representative posts, hooks, formats, engagement signals, and comment questions.
- Analyzes each platform independently before producing cross-platform conclusions.
- Converts findings into positioning, content pillars, post ideas, reply strategy, and next research steps.
- Produces navigable Obsidian notes, daily reports, and durable project memory.
- Uses read-only browsing rules to avoid accidental likes, follows, comments, posts, or account changes.

## Platform Focus

| Platform | Primary research lens |
| --- | --- |
| X/Twitter | Model launches, workflow tests, benchmarks, threads, and credibility-building conversations |
| Xiaohongshu | Search intent, save-worthy tutorials, tool selection, pricing, and comment demand |
| TikTok | First-second hooks, visual proof, comparisons, saves, shares, and pinned details |
| Reddit | Community rules, candid demand, objections, and transparent comparisons |

## Install

Clone the repository, then copy the Skill directory into your Codex skills folder.

```powershell
git clone https://github.com/HunterSUNSUN/social-media-research-ops.git
Copy-Item `
  -Recurse `
  -Force `
  .\social-media-research-ops\social-media-research-ops `
  "$env:USERPROFILE\.codex\skills\social-media-research-ops"
```

Restart Codex after installation if the Skill does not appear immediately.

## Use

Reference the Skill directly in a request:

```text
Use $social-media-research-ops to analyze competitor accounts for an AI video product
across X and Xiaohongshu, then write the findings into my Obsidian vault.
```

Other example requests:

```text
Research how fast-growing creator-tool accounts structure their first 30 posts.
```

```text
Study the comments under high-performing Xiaohongshu AI video tutorials and turn
the recurring questions into ten save-worthy post ideas.
```

```text
Compare the platform logic of X, TikTok, and Reddit for this product category.
Clearly separate observed evidence from strategic inference.
```

## Workflow

1. Define the product, audience, regions, platforms, and desired outputs.
2. Build samples from competitors, adjacent accounts, and demand communities.
3. Read representative posts and comments rather than relying on generic marketing theory.
4. Infer platform logic separately for each network.
5. Convert findings into positioning, content pillars, post ideas, and reply strategy.
6. Store substantial findings in a navigable Obsidian structure.
7. Record the next research breakpoint so another session can continue cleanly.

## Repository Structure

```text
.
|-- README.md
|-- LICENSE
`-- social-media-research-ops/
    |-- SKILL.md
    |-- agents/
    |   `-- openai.yaml
    `-- references/
        `-- templates.md
```

## Design Principles

- Real platform evidence over abstract growth advice.
- Repeated patterns over one viral example.
- Comments and search intent as first-class research data.
- Platform-specific conclusions before cross-platform generalization.
- Read-only account behavior unless the user explicitly authorizes publishing actions.
- Durable notes that another research session can resume without reconstructing context.

## Visual Showcase

The repository includes a five-page, 1080 × 1440 Xiaohongshu carousel introducing the Skill:

- [Open the interactive HTML](showcase/index.html)
- [Browse the exported PNG pages](showcase/exports)

![Social Media Research Ops carousel cover](showcase/exports/social-media-research-ops-1.png)

## 中文说明

这是一个面向 Codex 的社媒研究与运营 Skill，用于把真实平台浏览转化为可复用的方法论和执行方案。它覆盖竞品账号分层、帖子与评论区拆解、平台推流逻辑判断、内容定位、选题生成，以及 Obsidian 分类沉淀。

它尤其适合 AI 工具、创作者工具、SaaS 产品和需要跨平台冷启动研究的团队。研究过程中默认只读浏览，不会主动点赞、关注、评论、发帖或修改账号设置。

## License

[MIT](LICENSE)
