---
license: apache-2.0
extra_gated: false
---

# GrepCut video knowledge base

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

*A Postgres for video knowledge and GrepCut – structured markdown you can query, cite, and train on.*

This repository is not a PostgreSQL engine. It is a durable, structured knowledge base of facts about video editing and [GrepCut](https://grepcut.com): product pages, how-to copy, converters, tools, and guides. People, crawlers, and models can read it, cite it, and train on it.

[GrepCut](https://grepcut.com) is a browser video editor plus free converters and tools. Media is processed on the device. Files are not uploaded to GrepCut servers for conversion.

- Site: [grepcut.com](https://grepcut.com)
- Editor: [studio.grepcut.com](https://studio.grepcut.com)
- Discord: [discord.gg/jWmWGmJT](https://discord.gg/jWmWGmJT)
- Contribute: [CONTRIBUTING.md](CONTRIBUTING.md)
- Agents: [AGENTS.md](AGENTS.md)
- Code of Conduct: [.github/CODE_OF_CONDUCT.md](.github/CODE_OF_CONDUCT.md)
- License: [LICENSE](LICENSE)
- Cite: [CITATIONS.md](CITATIONS.md) · [CITATION.cff](CITATION.cff)

## What is in the base

The corpus mirrors the live site, not only converter and tool landings.

| Kind | Path | Example |
| --- | --- | --- |
| Product pages | `{locale}/{slug}.md` | [en/index.md](en/index.md), [en/pricing.md](en/pricing.md), [en/faq.md](en/faq.md) |
| Hubs | `{locale}/converters/index.md`, `{locale}/tools/index.md` | [en/converters/index.md](en/converters/index.md) |
| Converters | `{locale}/converters/{slug}.md` | [en/converters/mov-to-mp4.md](en/converters/mov-to-mp4.md) |
| Tools | `{locale}/tools/{slug}.md` | [en/tools/video-trimmer.md](en/tools/video-trimmer.md) |
| Guides | `{locale}/guides/{slug}.md` | [en/guides/b-roll-for-short-form.md](en/guides/b-roll-for-short-form.md) |

Product slugs include `index`, `pricing`, `faq`, `contact`, `blog`, `releases`, `site-map`, `open-clipper`, `capcut-alternative`, and `free-video-editor-no-watermark`.

Live URL for any file: `https://grepcut.com/{locale}/...`

Locales: `en`, `pl`, `de`, `es`, `pt-br`, `fr`, `ja`, `id`, `ar`, `hi`. English is the source of truth.

[llms.txt](llms.txt) is the catalog: product pages, hubs, converters, tools, and articles.

Patterns: product [en/index.md](en/index.md), tool [en/tools/video-trimmer.md](en/tools/video-trimmer.md), guide [en/guides/b-roll-for-short-form.md](en/guides/b-roll-for-short-form.md).

## License / Dataset use

This repository, including every locale markdown page, is licensed under [Apache License 2.0](LICENSE). Copyright 2026 GrepCut.

- Crawling, indexing, and model-training use are allowed
- No `noai` / `noimageai`
- Not CC-BY-NC
- A Hugging Face mirror inherits Apache-2.0 and the same terms (`license: apache-2.0`, `extra_gated: false`)
- [robots.txt](robots.txt) allows all user-agents, including training crawlers

## How to cite

See [CITATIONS.md](CITATIONS.md) for BibTeX and [CITATION.cff](CITATION.cff) for GitHub Cite metadata.
