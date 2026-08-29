# Contributing

Thank you for helping improve **Awesome Agentic Embodied Systems**. Contributions may add work, correct metadata or links, improve placement and chronology, or sharpen a short section-level explanation.

Please keep changes focused. The public source of truth is [`README.md`](README.md); the repository does not require a separate paper database or per-paper note.

## Before Adding a Work

1. Read the target README section and its short introduction.
2. Search the title, short name, arXiv ID, project name, repository URL, and common aliases across the full README.
3. Verify the canonical title and earliest public release using a primary source.
4. Confirm that the work helps readers understand an agentic embodied system, an enabling capability, a historical step, an evaluation problem, or a clearly transferable agent concept.
5. Choose one primary section by asking: _What is the main reason a reader of this section would care about this work?_
6. Insert it from older to newer using the earliest verifiable public paper, report, repository, or project release.

When relevance is plausible but the best placement is uncertain, describe the ambiguity in the pull request. Do not duplicate the full entry across sections.

## Entry Formats

Use a concise short name, the official full title, and only links that exist.

### arXiv

```markdown
- **Short Name**: "Full Paper Title". [![arXiv](https://img.shields.io/badge/arXiv-YYMM.NNNNN-b31b1b.svg)](https://arxiv.org/abs/YYMM.NNNNN) [![Website](https://img.shields.io/badge/Website-Link-blue)](PROJECT_URL) [![Code](https://img.shields.io/badge/Code-GitHub-green)](CODE_URL)
```

### OpenReview

```markdown
- **Short Name**: "Full Paper Title". [![OpenReview](https://img.shields.io/badge/OpenReview-Paper-8E44AD.svg)](OPENREVIEW_FORUM_URL) [![Code](https://img.shields.io/badge/Code-GitHub-green)](CODE_URL)
```

### Other Paper or Technical Report

```markdown
- **Short Name**: "Full Title". [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](OFFICIAL_PAPER_URL) [![Website](https://img.shields.io/badge/Website-Link-blue)](PROJECT_URL)
```

### Non-Paper Resource

```markdown
- **Resource Name**: One concise description. [![Website](https://img.shields.io/badge/Website-Link-blue)](URL)
```

Remove badges for resources that do not exist. Do not leave template URLs or empty links in a submitted entry.

## Link and Badge Conventions

- Prefer an arXiv abstract page over a direct PDF.
- Prefer the canonical OpenReview forum page over a PDF or group page.
- Prefer official publication, project, code, dataset, and video links.
- Use a generic paper badge for a DOI, official proceedings page, or substantial technical report without arXiv or OpenReview.
- Use red (`b31b1b`) for papers, purple (`8E44AD`) for OpenReview, blue for websites, and green for code.
- Do not infer a code release, project page, venue, date, or identifier from a search snippet.
- Check that every link resolves to the intended work, not merely to a workshop index or lab homepage.

## Editorial Style

- Keep most entries to one line.
- Add one short explanatory phrase only when it clarifies relevance, transfer, or an unusual resource type.
- Do not add author lists, affiliations, task-level metrics, model sizes, dense tags, scores, or mini-reviews by default.
- Use cautious historical language such as `an early example` or `a representative transition` unless a priority claim has been established carefully.
- Distinguish a paper's claims from repository interpretation.
- Treat project pages and technical reports as valuable sources without presenting them as peer-reviewed papers.
- Preserve existing Markdown, heading, and badge style; avoid unrelated reformatting.

## Scope Guide

Work may be relevant through physical robots, simulation, virtual worlds, mixed environments, policy development, autonomous experimentation, or fleet operation. No single feature—an LLM, a physical robot, online learning, long-term memory, end-to-end control, open-source code, or the word `agentic`—is mandatory.

Usually exclude only:

- work with no meaningful embodied or agentic connection;
- accidental duplicates or minor revisions already represented by an entry;
- promotional material without accessible technical substance;
- unverifiable titles or links;
- tangential work that weakens section coherence without adding a useful bridge.

Foundation models and cross-domain agent papers should be selective. For a non-embodied paper, the pull request should be able to state its embodied lesson in one sentence.

## Pull Request Checklist

- [ ] I searched titles, aliases, identifiers, and URLs for duplicates.
- [ ] I verified the official title and useful links with primary sources.
- [ ] The entry has one primary home and a clear connection to the section.
- [ ] The entry is in chronological order by earliest public release.
- [ ] Every badge corresponds to a resource that actually exists.
- [ ] I used an arXiv abstract page or canonical OpenReview forum when available.
- [ ] I did not add unsupported priority, autonomy, generality, or publication claims.
- [ ] I did not reformat or delete unrelated content.
- [ ] I previewed the Markdown and checked heading anchors if the structure changed.

## Corrections and Larger Curation Changes

Small factual corrections can go directly into a focused pull request with the supporting primary link.

For a section split, merge, rename, or substantial synthesis rewrite, explain:

- what is difficult to discover or understand in the current organization;
- which works move and why;
- how duplicate primary homes are avoided;
- whether the table of contents or reading paths must change.

The goal is broad discovery, light verification, thoughtful organization, concise entries, and selective synthesis.

## License

By contributing, you agree that your contribution is licensed under the repository's [BSD 3-Clause License](LICENSE).
