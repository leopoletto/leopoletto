# Leonardo Poletto

Senior Software Engineer based in São Paulo, Brazil.

I have 15 years of experience building backend-heavy software with PHP, including seven years with Laravel, much of it working remotely with product teams in the UK and US.

More recently, I've been building product features around LLMs and incorporating AI into my engineering workflow. I tend to use models where interpretation is useful and deterministic code where results need to remain predictable and reproducible.

My work usually sits somewhere between backend engineering, automation, data processing, product development, and investigating systems that do not behave quite as expected.

## AI & Data Projects

### [LaraJobs Analysis](https://github.com/leopoletto/larajobs-analysis)

I turned 699 Laravel job notification emails collected between 2023 and 2026 into a structured dataset.

A Laravel application archives and cleans the original emails before GPT-5 mini extracts 14 structured fields. The pipeline also normalizes skills and salaries and caches results per record, so subsequent runs only process new data.

The complete dataset cost about $2.30 to process.

The project was featured in **Artisan Weekly**.

### [LinkedIn Chrome Extension Probing](https://github.com/leopoletto/linkedin-chrome-extension-probing)

I investigated client-side code used by LinkedIn to check for the presence of Chrome extensions in the browser.

The project reconstructs a dataset of **4,279 extension IDs**, resolves available extensions against the Chrome Web Store, and publishes the scripts, data, and methodology behind the analysis.

The goal of the project is not to infer intent, but to document observable browser behavior and make the findings reproducible.

## Web Research & Tooling

I maintain [leopoletto.dev](https://leopoletto.dev) as an open lab for experiments around browsers, crawlers, web standards, privacy, metadata, and automation.

Some of that work has produced tools and datasets such as:

- [robots.txt parser](https://github.com/leopoletto/robots-txt-parser) — a PHP library for parsing and inspecting robots.txt rules.
- [Chrome privacy extension](https://github.com/leopoletto/chrome-privacy-extension) — experiments around browser requests, tracking behavior, and privacy signals.
- [Font self-hosting tools](https://github.com/leopoletto/font-self-host) — tooling for downloading and self-hosting web fonts.
- [Font metadata analysis](https://github.com/leopoletto/font-lint-python-scripts) — scripts for extracting and analyzing font metadata at scale.

## How I Work

I like systems where the boundaries are explicit.

For AI-backed features, that usually means letting the model handle interpretation while keeping validation, normalization, business rules, and reproducible decisions in code.

For software development, I use **Claude Code, Codex, and Gemini CLI** daily. Specifications, architectural decisions, and repository conventions live alongside the code, and agent-generated changes are reviewed against those constraints before commit.

The same principle applies outside AI: understand the system first, make hidden assumptions visible, and prefer behavior that can be tested and explained.

## Open Source

I've contributed fixes or improvements upstream when my work exposed gaps in the tools I was using, including:

- [PHP.net](https://github.com/php/web-php/pull/777)
- [Google robotstxt](https://github.com/google/robotstxt/pull/78)
- [Spatie Laravel CSP](https://github.com/spatie/laravel-csp/pull/178)
- [Tighten Jigsaw](https://github.com/tighten/jigsaw/pull/686)
- [Google Chrome / Lighthouse](https://github.com/GoogleChrome/lighthouse/pull/16665)

## Background

Before focusing more heavily on AI-backed products, I spent most of my career building and maintaining production web applications.

At **Simple Education**, I went from being the company's only developer to leading a team of four and rebuilding the platform it still sells today as SimpleLab.

At **StudentCrowd** in the UK, I worked on product and platform features involving Laravel, Symfony, Elasticsearch, BigQuery, GrowthBook, SendGrid, and Google Cloud.

For US clients, I've worked on high-traffic Laravel applications, Laravel Vapor, media-processing pipelines, legacy systems, and unfamiliar codebases where understanding the existing constraints was often as important as writing the new code.

## What I'm Interested In

I'm particularly interested in:

- AI-backed product engineering
- LLM extraction and structured outputs
- agent-assisted software development
- backend and distributed systems
- deterministic automation
- data pipelines
- browser and crawler behavior
- developer tooling
- systems that need to evolve without losing predictability

I'm currently open to **AI engineering and senior backend engineering roles**, as well as selected consulting work.

[LinkedIn](https://www.linkedin.com/in/leopoletto/) · [leopoletto.dev](https://leopoletto.dev) · [hello@leopoletto.dev](mailto:hello@leopoletto.dev)
