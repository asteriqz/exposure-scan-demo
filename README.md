# exposure-scan — worker fleet dashboard

Live demo: **https://asteriqz.github.io/exposure-scan-demo/**

Animated view of a four-stage scanning fleet: `resolve` → `fetch` → `verdict`,
each stage its own worker pool, every worker reporting what it is doing.

## Synthetic data

**Every business name, domain, address and version in this demo is invented.**
Domains use the RFC 2606 reserved `.example` TLD so they can never resolve.

The real tool runs against real targets and its output is kept in a private
repository, because publishing which local businesses are running unpatched
software is neither useful nor fair to them.

The verdict mix here mirrors the measured yield of a real 60-target run:
most third-party sites publish nothing about their runtime, which is why
`NO_PHP` and `HIDDEN` dominate.
