# Leonardo Poletto

Senior PHP and Laravel engineer based in São Paulo, Brazil.

I have 15 years of experience building backend-heavy software with PHP, including seven years with Laravel, much of it working remotely with product teams in the UK and US.

My work usually sits somewhere between backend engineering, integrations, automation, data processing, and investigating systems that do not behave quite as expected. More recently, I've been building LLM-backed features inside Laravel applications and using AI throughout my engineering workflow.

## Background

At **Simple Education**, I went from being the company's only developer to leading a team of four and rebuilding its LMS from CakePHP to Laravel and Vue.js. The company still sells the platform today as SimpleLab.

At **StudentCrowd** in the UK, I worked on product and platform features involving Laravel, Symfony, Elasticsearch, BigQuery, GrowthBook, SendGrid, and Google Cloud.

For US clients, I've worked on high-traffic Laravel applications, Laravel Vapor, media-processing pipelines, legacy systems, and unfamiliar codebases where understanding the existing constraints was often as important as writing the new code.

## PHP & Laravel Projects

### [robots.txt parser](https://github.com/leopoletto/robots-txt-parser)

A PHP library, published on Packagist, for parsing and auditing robots.txt from a URL, a file, or a string, including the robots `<meta>` tags and `X-Robots-Tag` headers that govern indexing alongside it.

The [robots.txt validator](https://robots.leopoletto.dev/) is built on this library: check any site's robots.txt for mistakes, get a score out of 100 with every finding explained, and see how it ranks against other sites.

### LaraJobs Analysis ([code](https://github.com/leopoletto/larajobs-market-analysis) · [write-up](https://leopoletto.dev/blog/larajobs-market-analysis/))

I turned 699 Laravel job notification emails collected between 2023 and 2026 into a structured dataset.

A Laravel application archives and cleans the original emails before GPT-5 mini extracts 14 structured fields. The pipeline also normalizes skills and salaries and caches results per record, so subsequent runs only process new data.

The complete dataset cost about $2.30 to process. The project was featured in **Artisan Weekly**.

## How I Work

I like systems where the boundaries are explicit.

For AI-backed features, that usually means letting the model handle interpretation while keeping validation, normalization, business rules, and reproducible decisions in code.

For software development, I use **Claude Code, Codex, and Gemini CLI** daily. Specifications, architectural decisions, and repository conventions live alongside the code, and agent-generated changes are reviewed against those constraints before commit.

The same principle applies outside AI: understand the system first, make hidden assumptions visible, and prefer behavior that can be tested and explained.

## Research & Tooling

I maintain [leopoletto.dev](https://leopoletto.dev) as an open lab for experiments around browsers, crawlers, web standards, privacy, metadata, and automation. Some of that work has produced tools and datasets such as:

- [LinkedIn Chrome extension probing](https://github.com/leopoletto/linkedin-chrome-extension-probing) — reconstructs the 4,279 extension IDs LinkedIn checks for in the browser and publishes the scripts, data, and methodology. It documents observable browser behavior rather than inferring intent.
- [Chrome privacy extension](https://github.com/leopoletto/chrome-privacy-extension) — experiments around browser requests, tracking behavior, and privacy signals.
- [Font self-hosting tools](https://github.com/leopoletto/font-self-host) — tooling for downloading and self-hosting web fonts.
- [Font metadata analysis](https://github.com/leopoletto/font-lint-python-scripts) — scripts for extracting and analyzing font metadata at scale.

## Open Source

I've contributed fixes or improvements upstream when my work exposed gaps in the tools I was using, including:

- [PHP.net](https://github.com/php/web-php/pull/777)
- [Google robotstxt](https://github.com/google/robotstxt/pull/78)
- [Spatie Laravel CSP](https://github.com/spatie/laravel-csp/pull/178)
- [Tighten Jigsaw](https://github.com/tighten/jigsaw/pull/686)
- [Google Chrome / Lighthouse](https://github.com/GoogleChrome/lighthouse/pull/16665)

## What I'm Looking For

I'm open to **senior Laravel and PHP backend roles**, especially on teams adding AI-backed features to their products, as well as selected consulting work.

The work I enjoy most:

- backend systems, integrations, and data pipelines
- LLM extraction and structured outputs inside Laravel apps
- deterministic automation and developer tooling
- browser and crawler behavior

[LinkedIn](https://www.linkedin.com/in/leopoletto/) · [leopoletto.dev](https://leopoletto.dev) · [hello@leopoletto.dev](mailto:hello@leopoletto.dev)