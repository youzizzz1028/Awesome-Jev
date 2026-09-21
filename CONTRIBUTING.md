# Contributing to Awesome Jev

Thank you for improving the index. Contributions may add a resource, correct metadata, report a broken link, or propose a reproducible evaluation.

## Inclusion criteria

A resource should make a concrete contribution to at least one of these topics:

- Jev or the public System One interface;
- typed or structured decision outputs;
- probability calibration or uncertainty quantification;
- selective prediction, abstention, or learning to defer;
- decision-focused learning;
- model routing, cascading, or confidence-gated automation;
- reproducible evaluation of correctness, calibration, latency, cost, or shift.

## Required metadata

Each pull request should provide:

1. title and stable URL;
2. authors or maintaining organization;
3. year and venue where applicable;
4. evidence label (`A`, `B`, `C`, or `D`);
5. one sentence explaining relevance;
6. access date for vendor documentation and mutable dashboards;
7. disclosure of author affiliation with the resource.

Performance claims require a versioned protocol or should be described as self-reported. Do not use schema validity as evidence of factual correctness. Do not add referral links, scraped copies of copyrighted papers, or unversioned benchmark screenshots.

## Editing the catalog

Update `README.md` and the corresponding machine-readable catalog: use `data/resources.yml` for papers and documentation, and `data/ecosystem.yml` for repositories. Keep entries concise and place them under the narrowest applicable category. Repository entries must distinguish TypeSafe-maintained projects from independent community work. Edit figures in their HTML source and re-export them at the fixed canvas dimensions declared in the file.

For papers, use this README format:

```markdown
- **[A · 2024 · Venue] [Paper title](stable-paper-url)** — one-sentence contribution. `bibtexKey`
```

Use `A` only for an archival peer-reviewed version and `B` for a preprint. Sort papers chronologically within a category, prefer the archival URL over a preprint when both exist, and reuse the exact citation key from `paper/references.bib`. If one paper spans several categories, choose its primary contribution and avoid duplicate entries; mention secondary relevance in the description.
