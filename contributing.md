# Contribution Guidelines

Thanks for helping make Awesome Poker useful.

This project follows the [Awesome list guidelines](https://github.com/sindresorhus/awesome/blob/main/awesome.md). Contributions are welcome when they improve the list's quality, accuracy, or coverage.

## What Belongs Here

Add resources that are useful to poker developers, researchers, operators, serious students, or tool builders.

Good entries usually fit at least one of these categories:

- Open-source poker software.
- Hand evaluators, equity calculators, engines, simulators, parsers, or solvers.
- Research papers, datasets, benchmarks, or reproducible experiments.
- Rules, standards, formats, and other durable references.
- High-quality learning resources with lasting technical value.

## Quality Bar

Before proposing a resource, check that it is:

- Relevant to poker.
- Publicly accessible.
- Documented well enough for a reader to use or evaluate.
- Maintained, or historically important enough to belong in a separate historical section.
- Described neutrally, without marketing copy.

Please do not add:

- Affiliate links, referral links, or promotional landing pages.
- Thin content, listicles, or SEO pages.
- Bulk-generated submissions that have not been individually reviewed by a maintainer.
- Abandoned, archived, deprecated, or undocumented projects in the main list.
- Closed-source commercial tools unless they are important references for the wider community.
- Resources that encourage cheating, collusion, fraud, unauthorized scraping, or terms-of-service abuse.

## Entry Format

Use this format:

```md
- [Name](https://example.com) - Short objective description ending with a period.
```

Descriptions should be concise, factual, and title-neutral. Do not start descriptions with "A list of", "Awesome", or marketing claims.

Mark closed-source commercial tools with `(Commercial)` at the start of the description:

```md
- [Name](https://example.com) - (Commercial) Short objective description ending with a period.
```

## Category Guide

Awesome Poker is organized by artifact type first: library, engine, solver, paper, dataset, tool, format, asset, or community. This keeps each resource on one obvious shelf as the list grows.

The target architecture is:

- **Libraries & Toolkits** - Importable code: hand evaluation, equity, ranges, combinatorics, and general poker toolkits.
- **Game Engines & Platforms** - Table logic, betting engines, server frameworks, and playable open-source clients/platforms.
- **Solvers** - Runnable software that computes strategies, including GTO/postflop solvers and CFR implementations.
- **AI, Game Theory & Research** - Papers, landmark systems, research frameworks, algorithms, and academic work.
- **Hand Histories, Formats & Standards** - Parsers, converters, hand-history formats, PHH, and site/de-facto formats.
- **Datasets & Corpora** - Poker hand corpora, benchmark logs, released research datasets, and competition data.
- **Tracking & Analysis** - Trackers, HUDs, session analysis, range/equity/ICM analysis tools.
- **Competitions & Benchmarks** - Competitions and benchmark ecosystems where poker software is tested.
- **Fairness, RNG & Security** - Shuffle protocols, RNG references, provably fair systems, mental poker, and operator trust material.
- **Client & UI Assets** - Card decks, SVG assets, table UI assets, and frontend resources for poker clients.
- **Rules, Math & References** - Tournament rules, probability tables, poker math references, and durable rule sources.
- **Learning & Education** - Durable technical learning, such as university courses, CFR tutorials, and bot-building guides.
- **Communities & Research Groups** - Academic groups, serious forums, and builder/research communities.
- **Related Lists** - Other curated lists that overlap with poker software, AI, or research.

Only publish a section in the README once it has enough genuinely recommendable entries to avoid looking abandoned. Empty target sections belong in issues or maintainer notes until they are ready.

The README intentionally omits `Related Lists` from the table of contents because `awesome-lint` treats that section specially.

Locked taxonomy decisions:

- Variants such as Omaha, Stud, Draw, short-deck, and mixed games belong in descriptions unless variant-specific resources become numerous enough to need structure.
- Libraries are organized function-first; split by language only after a section is large enough.
- Category-defining commercial tools are allowed when useful to the wider community, but must be marked `(Commercial)`.
- Keep the list builder/research/operator-first. Avoid affiliate-heavy training content and generic coaching resources.

## Pull Requests

For each pull request:

- Add one resource per commit when practical.
- Explain why the resource belongs here.
- Confirm that the link works.
- Confirm that the project is not archived or deprecated, unless it is being added to a historical section.
- Run `npx awesome-lint` before submitting when possible.

PokerWorks maintains this list as a community resource. Inclusion is based on relevance, quality, usefulness, and maintenance, not affiliation.

Every accepted entry requires human maintainer review. Maintainers should verify the link, section fit, description, maintenance signal, and safety posture before merging.
