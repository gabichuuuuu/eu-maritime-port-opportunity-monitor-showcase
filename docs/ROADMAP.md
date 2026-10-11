# Public roadmap

This roadmap describes direction, not a promise of release dates.

## Foundations — in place

- private Apify Actor repository with a public-documentation boundary;
- one filter model shared by every official source, with a maritime prefilter;
- qualification that requires a primary maritime signal and excludes known false positives;
- resilient source access with retries, pagination and per-source coverage reporting;
- Spain-first procurement coverage with European TED signals;
- deterministic maritime classification using CPV and multilingual terminology;
- cross-source deduplication and monitor-specific history;
- traceable lifecycle events and official source links;
- incremental scanning per source, with events beyond the run limits deferred rather than dropped.

## In active development

- monitoring the three official source integrations against upstream changes;
- expanding the maritime taxonomy for port equipment, decarbonisation and Portuguese terminology;
- measuring real execution costs of scheduled monitors under pay-per-event pricing;
- preparing a safe, useful public product demonstration with synthetic data.

## Later

- broader European coverage where official interfaces provide reliable signals;
- customer-facing examples based on synthetic or anonymised notices;
- additional export and workflow integrations supported by Apify;
- carefully scoped enrichment if it can remain explainable and cost-controlled.

## Intentionally excluded

Private customer profiles, credentials, tender documents, bid strategy, probability-of-winning scores
and unreleased implementation details remain outside this public repository.
