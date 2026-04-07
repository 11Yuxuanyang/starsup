# Starsup

The GitHub playbook for builders who want traffic, citations, and stars.

把一个 GitHub 仓库做成搜索和 AI 都更容易理解、引用、推荐的答案页。

`Starsup` is an open-source playbook for turning a repository into a discoverable product surface. It packages the stack that drives star growth through repository discovery:

- positioning the README around real questions
- adding `llms.txt`, `AGENTS.md`, and citation metadata
- publishing GitHub Pages landing pages for keyword discovery
- tightening repo description, topics, homepage, and link structure
- making the project easier for AI systems to quote, route, and revisit

[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](./LICENSE)

Documentation site:

- https://11yuxuanyang.github.io/starsup/

## What Drives Stars
Repository star growth starts with discoverability through problem keywords instead of brand recall alone.

If someone asks:

- how to optimize a GitHub README for AI citation
- how to make a repo easier for ChatGPT or search systems to understand
- how to structure `llms.txt`, `AGENTS.md`, GitHub Pages, and metadata
- how to turn a repo into a star-worthy landing page

your repository should have an answer page waiting for that query.

## What This Project Gives You

This repo ships four layers:

| Layer | What it gives you |
|------|--------------------|
| `README.md` | a homepage structure built for both humans and keyword discovery |
| `docs/` | GitHub Pages landing pages for problem-driven discovery |
| `templates/` | reusable templates for `README`, `llms.txt`, `AGENTS.md`, and `CITATION.cff` |
| `checklists/` | execution checklists for launch, indexing, and 14-day follow-through |

## The Core Idea

Most repositories read like storage. Repos that spread read like answers.

The difference usually comes down to:

- whether the title matches a real search intent
- whether the README directly answers the user's problem
- whether there are dedicated pages for concrete keyword clusters
- whether AI systems can find a clean machine-readable entry point
- whether outside pages link back with meaningful anchor text

## What Problems This Helps Solve

- Your repo is public, but nobody finds it unless you send the link
- Your README explains the project, but does not answer the user's query
- AI tools can browse the repo, yet still fail to understand what it is for
- You have a good project, but no discoverability architecture around it
- You want more stars, but the repo has no reason to be remembered or cited

## Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/11Yuxuanyang/starsup.git
cd starsup
```

### 2. Start with the templates

- [`templates/README-geo-template.md`](./templates/README-geo-template.md)
- [`templates/llms.txt`](./templates/llms.txt)
- [`templates/AGENTS.md`](./templates/AGENTS.md)
- [`templates/CITATION.cff`](./templates/CITATION.cff)

### 3. Run the checklist

- [`checklists/repo-geo-launch-checklist.md`](./checklists/repo-geo-launch-checklist.md)
- [`checklists/14-day-discovery-loop.md`](./checklists/14-day-discovery-loop.md)

### 4. Read the docs site

- [GitHub GEO for stars](./docs/github-geo-for-stars.html)
- [How to make a repo AI-citation-ready](./docs/ai-citation-ready-repo.html)
- [README, llms.txt, AGENTS.md, Pages](./docs/github-readme-llms-pages.html)
- [Repository GEO checklist](./docs/repository-geo-checklist.html)

## Why This Can Lead to Stars

Stars are downstream of discovery and trust.

A repository gets starred when:

- the right people can find it
- they understand what it does in seconds
- the page feels complete enough to reuse
- the project looks like it will still matter after the tab closes

This repo focuses on the discoverability layer that feeds that loop.

## Chinese Summary

这个项目解决的是一个很具体的问题：很多 GitHub 项目本身不差，差在首页、结构和外部入口没有设计好。结果就是：

- 人搜不到
- AI 看不懂
- 被看到了也记不住
- 内容不错，星标起不来

`Starsup` 做的事，就是把这层“高 star 仓库背后的可发现性工程”拆出来，做成一套公开模板和执行清单。

## Repository Structure

```text
checklists/
├── repo-geo-launch-checklist.md
└── 14-day-discovery-loop.md

docs/
├── index.html
├── github-geo-for-stars.html
├── ai-citation-ready-repo.html
├── github-readme-llms-pages.html
├── repository-geo-checklist.html
├── llms.txt
├── robots.txt
├── sitemap.xml
└── styles.css

templates/
├── README-geo-template.md
├── llms.txt
├── AGENTS.md
└── CITATION.cff
```

## Topics This Repository Covers

- GitHub star growth
- repository discoverability
- AI citation readiness
- GitHub stars
- README optimization
- `llms.txt`
- `AGENTS.md`
- GitHub Pages
- repository metadata

## License

MIT. See [LICENSE](./LICENSE).
