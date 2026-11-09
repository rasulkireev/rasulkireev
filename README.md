I'm a Senior Growth Engineer at [Readwise](https://readwise.io/) and an independent product builder at [LVTD](https://github.com/LVTD-LLC). I work mostly with Python, Django, PostgreSQL, Rust, and Go—usually where agents, data, and production systems meet.

### What I'm building

#### AI agent tools

Tools that give agents data, a place to test, a second opinion, and useful references.

| Project | What agents can do | Under the hood |
| --- | --- | --- |
| [Rowset](https://github.com/LVTD-LLC/rowset) | Create, query, update, and export structured datasets through MCP, REST, or a CLI, with scoped keys and persistent dataset instructions | Python, Django, FastMCP, Go, Postgres |
| [PGSandbox](https://github.com/LVTD-LLC/pgsandbox) | Test SQL and migrations against disposable Postgres databases, with scoped roles, TTLs, and bounded results | Rust, MCP, Tokio, Postgres |
| [ShipRust](https://shiprust.com) | Generate and download Rust SaaS projects through MCP or REST, with auth, billing, background jobs, and agent-readable docs | Rust, Axum, Maud, Postgres, MCP |
| [Djass](https://djass.dev) | Choose modules, generate a Django SaaS repo, and download it through MCP, CLI, or API, with instructions for the agent that builds next | Python, Django, Postgres, MCP, Go CLI |
| [nitpick](https://github.com/LVTD-LLC/nitpick) | Review a diff with relevant repo context, get structured findings, and iterate using severity-based exit codes or background review hooks | Rust, OpenRouter, local models, agent hooks |
| [TastefulKit](https://github.com/LVTD-LLC/tastefulkit) | Search real design references and retrieve screenshots and DESIGN.md guides through MCP or the API | Python, Django, MCP, design search |
| [CiteGuild](https://github.com/LVTD-LLC/citeguild) | Find relevant member articles for a draft through MCP, CLI, or a versioned API, with excerpts and source links to verify | Python, Django, FastMCP, Postgres |
| [BrowseAwesome](https://github.com/LVTD-LLC/browse-awesome) | Discover open-source dependencies across awesome lists through public read-only MCP tools, using repository metadata and search filters | Python, Django, FastMCP, GitHub ingestion |

Installable agent integrations: [Rowset](https://github.com/LVTD-LLC/rowset-skills) · [nitpick](https://github.com/LVTD-LLC/nitpick-skills) · [TastefulKit](https://github.com/LVTD-LLC/tastefulkit-skills) · [CiteGuild](https://github.com/LVTD-LLC/citeguild-skills)

#### Developer communities & discovery

| Project | What it does | Under the hood |
| --- | --- | --- |
| [Built with Django](https://github.com/LVTD-LLC/builtwithdjango) | Showcases products built by the Django community | Django, Postgres, community submissions |
| [Built with Rust](https://github.com/LVTD-LLC/builtwithrust) | Helps people discover Rust apps and tools; serves cached pages from a single binary and exposes an admin API for agents | Rust, Axum, Maud, SQLite |
| [Built with Bend](https://github.com/LVTD-LLC/built-with-bend) | Collects human-reviewed Bend projects, with public submissions, source links, and a weekly newsletter | Python, Django, Postgres, curator API |

#### Website maintenance

| Project | What it does | Under the hood |
| --- | --- | --- |
| [Staleaway](https://github.com/LVTD-LLC/staleaway) | Turns a sitemap into scheduled page-review reminders so website content gets revisited | Django, Postgres, Django Q2, Redis, email |

### How I work

- **Product first.** I care about the user and the outcome, not just the implementation.
- **Own the unglamorous parts.** Data integrity, queues, retries, monitoring, migrations, and documentation are part of the product.
- **Build for humans and agents.** Good tools expose explicit contracts, bounded actions, and useful evidence.
- **Write things down.** Clear issues, pull requests, runbooks, and technical notes make remote teams faster.

### Current interests

`agent-native software` · `developer tools` · `data systems` · `Django` · `Rust` · `MCP` · `self-hosting`

### Elsewhere

[Website](https://rasulkireev.com) · [Writing](https://rasulkireev.com/articles/) · [X](https://x.com/rasulkireev) · [LinkedIn](https://www.linkedin.com/in/rasul-kireev/) · [Email](mailto:me@rasulkireev.com)

<sub>If you're exploring the repositories, start with Rowset, PGSandbox, and nitpick. They best represent what I'm working on now.</sub>
