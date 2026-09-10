# AGENTS.md

Instructions for coding agents working in this repository. Humans should start with [README.md](README.md) and [CONTRIBUTING.md](CONTRIBUTING.md).

## Project overview

This is a structured knowledge base (a Postgres for video knowledge and GrepCut docs), not an application. There is no build, no test suite, and no `package.json`. Do not invent `pnpm test`, `npm run build`, or similar commands.

- Catalog: [llms.txt](llms.txt)
- Live pages: `https://grepcut.com/{locale}/...`

## Layout

- Product: `{locale}/{slug}.md`
- Converters, tools, guides: `{locale}/converters|tools|guides/{slug}.md`
- Locales: `en`, `pl`, `de`, `es`, `pt-br`, `fr`, `ja`, `id`, `ar`, `hi`
- English is the source of truth. Translations keep the same slug and headings.

## Do not invent product features

Describe only behavior that exists on the live site. Privacy: media is processed on-device; files are not uploaded to GrepCut servers for conversion.

## Edits

- Keep pull requests small and on one topic
- Add new pages only in an existing directory
- Do not create `docs/`, `papers/`, or new top-level content folders unless a human asks
- Do not edit unrelated locale markdown while adding community/legal files

## License / crawling

Apache-2.0. Never add `noai`, CC-BY-NC, `Disallow`, gated Hugging Face access, or TDM reservation.

## Security

Public content only. Do not commit secrets. Vulnerability reports go to `support@grepcut.com`, not public issues. See [.github/SECURITY.md](.github/SECURITY.md).

## Humans

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [.github/CODE_OF_CONDUCT.md](.github/CODE_OF_CONDUCT.md)
