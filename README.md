# Awesome opensource with stars

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset=".github/assets/banner-light.png">
    <img alt="banner" src=".github/assets/banner-dark.png">
  </picture>

  <p>
    <br/>
    A collection of <strong>truly open-source resources</strong> &mdash;
    <br/>
    because I'm also tired of projects that aren't really open source.
    <br/><br/>
  </p>

</div>

<p align="center">
  <a href="https://awesome.re" rel="nofollow"><img src="https://awesome.re/badge.svg" alt="Awesome Repository"></a>
  <a href="https://github.com/hadez8877/awesome-opensource/blob/main/LICENSE" rel="nofollow"><img src="https://img.shields.io/github/license/hadez8877/awesome-opensource?color=blue" alt="License"></a>
  <a href="https://github.com/hadez8877/awesome-opensource/blob/main/CONTRIBUTING.md" rel="nofollow"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
</p>

<div align="center">
  <p>
    <a href="README.md">English</a> |
    <a href="README.zh-cn.md">简体中文</a> |
    <a href="README.zh-tw.md">繁體中文</a> |
    <a href="README.es.md">Español</a> |
    <a href="README.br.md">Português (Brasil)</a>
  </p>
</div>

## Contents

| Category        | Description                                                                                                                                                      | Shortcut                       |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| Backend / BaaS  | Tools and platforms for backend services, APIs, authentication, and Backend-as-a-Service like Firebase, Supabase, and frameworks for Node.js and other runtimes. | [Click here](#backend--baas)   |
| CLI Tools       | Command-line utilities for productivity, file management, system monitoring, modern shells, and daily developer workflow automation.                             | [Click here](#cli-tools)       |
| Databases       | Relational, NoSQL, graph, search, vector, and time-series database systems for different use cases and scalability needs.                                        | [Click here](#databases)       |
| DevOps          | Infrastructure as code, Kubernetes orchestration, CI/CD, monitoring, networking, and security for modern cloud deployments.                                      | [Click here](#devops)          |
| Mobile Apps     | Frameworks and applications for cross-platform mobile development, including browsers, productivity, multimedia, and communication.                              | [Click here](#mobile-apps)     |
| Security        | Security tools for containers, networks, endpoints, privacy, reverse engineering, and vulnerability management.                                                  | [Click here](#security)        |
| Self-Hosted     | Software you can host on your own infrastructure, including Git platforms, DNS, media servers, monitoring, and file management.                                  | [Click here](#self-hosted)     |
| Software / SaaS | Complete applications for analytics, automation, communication, documentation, storage, and team productivity.                                                   | [Click here](#software--saas)  |
| Web Development | Frameworks, UI libraries, code editors, design tools, and resources for frontend and fullstack web development.                                                  | [Click here](#web-development) |

## Backend / BaaS

### API & GraphQL

* [tRPC](https://github.com/trpc/trpc) ⭐ 40,544 | 🐛 279 | 🌐 TypeScript | 📅 2026-08-13 - End-to-end typesafe APIs without schemas.
* [PostgREST](https://github.com/PostgREST/postgrest) ⭐ 27,624 | 🐛 390 | 🌐 Haskell | 📅 2026-08-24 - Instantly turns PostgreSQL into a REST API.
* [GraphQL Yoga](https://github.com/dotansimha/graphql-yoga) ⭐ 8,526 | 🐛 159 | 🌐 TypeScript | 📅 2026-08-20 - Modern, lightweight GraphQL server.

### Authentication & Identity

* [Keycloak](https://github.com/keycloak/keycloak) ⭐ 36,391 | 🐛 3,119 | 🌐 Java | 📅 2026-08-25 - Full-featured open source IAM solution (SSO, OAuth2, OIDC, SAML) backed by Red Hat.
* [Authelia](https://github.com/authelia/authelia) ⭐ 28,684 | 🐛 116 | 🌐 Go | 📅 2026-08-25 - Self-hosted multi-factor authentication solution.
* [Ory Kratos](https://github.com/ory/kratos) ⭐ 13,846 | 🐛 224 | 🌐 Go | 📅 2026-07-29 - Security-focused authentication system with a fully open source core.

### Backend as a Service

* [Supabase](https://github.com/supabase/supabase) ⭐ 108,368 | 🐛 1,053 | 🌐 TypeScript | 📅 2026-08-25 - Open source Firebase alternative built on PostgreSQL.
* [PocketBase](https://github.com/pocketbase/pocketbase) ⭐ 60,799 | 🐛 19 | 🌐 Go | 📅 2026-08-24 - Embedded backend with SQLite, auth, and REST API, fully open source.
* [Parse Server](https://github.com/parse-community/parse-server) ⭐ 21,412 | 🐛 553 | 🌐 JavaScript | 📅 2026-08-07 - Mature open source backend with no critical closed features.
* [UnDB](https://github.com/undb-io/undb) ⭐ 2,974 | 🐛 55 | 🌐 TypeScript | 📅 2025-07-13 - Self-hosted no-code database and BaaS (SQLite-based, Airtable-like).

### Frameworks

* [Hono](https://github.com/honojs/hono) ⭐ 31,950 | 🐛 363 | 🌐 TypeScript | 📅 2026-08-24 - Ultrafast framework for modern runtimes (Edge, Bun, Deno, Node).
* [AdonisJS](https://github.com/adonisjs/core) ⭐ 19,101 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-21 - Modern Node.js framework with a TypeScript-first approach.
* [Elysia](https://github.com/elysiajs/elysia) ⭐ 18,959 | 🐛 376 | 🌐 TypeScript | 📅 2026-08-19 - High-performance Bun-first framework with strong typing.
* [Wasp](https://github.com/wasp-lang/wasp) ⭐ 18,707 | 🐛 841 | 🌐 TypeScript | 📅 2026-08-24 - Declarative full-stack framework that generates backend automatically.
* [FeathersJS](https://github.com/feathersjs/feathers) ⭐ 15,267 | 🐛 126 | 🌐 TypeScript | 📅 2026-08-14 - Flexible framework for REST and real-time applications.
* [Midway](https://github.com/midwayjs/midway) ⭐ 7,741 | 🐛 115 | 🌐 TypeScript | 📅 2026-08-24 - Node.js framework with dependency injection inspired by Spring.
* [Moleculer](https://github.com/moleculerjs/moleculer) ⭐ 6,375 | 🐛 74 | 🌐 JavaScript | 📅 2026-08-22 - Fast and powerful microservices framework.
* [LoopBack](https://github.com/loopbackio/loopback-next) ⭐ 5,107 | 🐛 332 | 🌐 TypeScript | 📅 2026-08-24 - Advanced API framework based on OpenAPI.

## CLI Tools

### Developer Tools

* [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 81,609 | 🐛 1,025 | 🌐 Go | 📅 2026-08-21 - Simple terminal UI for Git operations.
* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 67,574 | 🐛 182 | 🌐 Rust | 📅 2026-08-04 - Extremely fast recursive search tool respecting `.gitignore`.
* [bat](https://github.com/sharkdp/bat) ⭐ 60,247 | 🐛 424 | 🌐 Rust | 📅 2026-08-11 - `cat` clone with syntax highlighting and Git integration.
* [lazydocker](https://github.com/jesseduffield/lazydocker) ⭐ 52,600 | 🐛 295 | 🌐 Go | 📅 2026-04-19 - Terminal UI for Docker and container management.
* [fd](https://github.com/sharkdp/fd) ⭐ 44,192 | 🐛 189 | 🌐 Rust | 📅 2026-08-11 - Simple, fast, and user-friendly alternative to `find`.
* [httpie](https://github.com/httpie/cli) ⭐ 38,449 | 🐛 332 | 🌐 Python | 📅 2024-12-17 - Human-friendly command-line HTTP client for APIs and web services.
* [jq](https://github.com/jqlang/jq) ⭐ 35,478 | 🐛 467 | 🌐 C | 📅 2026-08-23 - Lightweight and flexible JSON processor for the terminal.
* [delta](https://github.com/dandavison/delta) ⭐ 31,852 | 🐛 430 | 🌐 Rust | 📅 2026-08-02 - Syntax-highlighting pager for Git and diff outputs.
* [hyperfine](https://github.com/sharkdp/hyperfine) ⭐ 28,727 | 🐛 97 | 🌐 Rust | 📅 2026-04-30 - Command-line benchmarking tool with statistical analysis.
* [yq](https://github.com/mikefarah/yq) ⭐ 15,870 | 🐛 287 | 🌐 Go | 📅 2026-08-20 - Portable YAML, JSON, XML, and TOML processor inspired by jq.
* [xh](https://github.com/ducaale/xh) ⭐ 8,038 | 🐛 38 | 🌐 Rust | 📅 2026-08-23 - Friendly and fast HTTP client designed as an alternative to HTTPie.

### File Management & Navigation

* [fzf](https://github.com/junegunn/fzf) ⭐ 82,640 | 🐛 327 | 🌐 Go | 📅 2026-08-24 - General-purpose fuzzy finder for the command line.
* [yazi](https://github.com/sxyazi/yazi) ⭐ 41,655 | 🐛 65 | 🌐 Rust | 📅 2026-08-24 - Blazing fast terminal file manager written in Rust.
* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 38,819 | 🐛 136 | 🌐 Rust | 📅 2026-08-24 - Smarter `cd` command inspired by z and powered by frecency.
* [nnn](https://github.com/jarun/nnn) ⭐ 21,828 | 🐛 5 | 🌐 C | 📅 2026-08-17 - Lightweight and extremely fast terminal file browser.
* [ranger](https://github.com/ranger/ranger) ⭐ 17,366 | 🐛 899 | 🌐 Python | 📅 2026-08-15 - Console file manager with Vim-style keybindings.
* [broot](https://github.com/Canop/broot) ⭐ 12,909 | 🐛 232 | 🌐 Rust | 📅 2026-08-24 - Interactive directory tree navigator with fuzzy search.

### Package Managers & Runtimes

* [Deno](https://github.com/denoland/deno) ⭐ 108,300 | 🐛 1,529 | 🌐 Rust | 📅 2026-08-25 - Secure JavaScript and TypeScript runtime built with Rust.
* [Bun](https://github.com/oven-sh/bun) ⭐ 95,666 | 🐛 8,463 | 🌐 Rust | 📅 2026-08-25 - Fast JavaScript runtime, package manager, and bundler.
* [Homebrew](https://github.com/Homebrew/brew) ⭐ 49,262 | 🐛 13 | 🌐 Ruby | 📅 2026-08-25 - Popular package manager for macOS and Linux.
* [pnpm](https://github.com/pnpm/pnpm) ⭐ 36,201 | 🐛 2,509 | 🌐 Rust | 📅 2026-08-25 - Fast and disk space-efficient package manager for JavaScript.
* [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,544 | 🐛 152 | 🌐 Go | 📅 2026-08-12 - Extendable version manager supporting multiple runtimes and tools.

### Productivity & Workflow

* [atuin](https://github.com/atuinsh/atuin) ⭐ 31,398 | 🐛 409 | 🌐 Rust | 📅 2026-08-25 - Shell history sync and search engine with encrypted storage.
* [Glow](https://github.com/charmbracelet/glow) ⭐ 27,028 | 🐛 222 | 🌐 Go | 📅 2026-08-16 - Render Markdown files beautifully in the terminal.
* [gum](https://github.com/charmbracelet/gum) ⭐ 24,273 | 🐛 192 | 🌐 Go | 📅 2026-08-20 - Tool for building glamorous shell scripts and terminal workflows.
* [wtfutil](https://github.com/wtfutil/wtf) ⭐ 17,061 | 🐛 102 | 🌐 Go | 📅 2026-08-05 - Personal terminal dashboard for displaying developer information.
* [Taskwarrior](https://github.com/GothenburgBitFactory/taskwarrior) ⭐ 6,016 | 🐛 439 | 🌐 C++ | 📅 2026-08-24 - Powerful CLI task management and productivity tool.

### Shells & Terminal Environments

* [Warp](https://github.com/warpdotdev/Warp) ⭐ 64,502 | 🐛 5,094 | 🌐 Rust | 📅 2026-08-25 - Rust-based modern terminal with AI and collaborative features.
* [tmux](https://github.com/tmux/tmux) ⭐ 48,800 | 🐛 28 | 🌐 C | 📅 2026-08-25 - Terminal multiplexer for managing persistent sessions and panes.
* [Nushell](https://github.com/nushell/nushell) ⭐ 40,330 | 🐛 1,436 | 🌐 Rust | 📅 2026-08-24 - Modern shell built around structured data instead of plain text.
* [Zellij](https://github.com/zellij-org/zellij) ⭐ 35,098 | 🐛 1,873 | 🌐 Rust | 📅 2026-08-24 - Terminal workspace and multiplexer focused on usability and extensibility.
* [Fish Shell](https://github.com/fish-shell/fish-shell) ⭐ 34,058 | 🐛 568 | 🌐 Rust | 📅 2026-08-25 - User-friendly smart shell with autosuggestions and modern defaults.
* [WezTerm](https://github.com/wez/wezterm) ⭐ 28,536 | 🐛 1,823 | 🌐 Rust | 📅 2026-08-24 - GPU-accelerated cross-platform terminal emulator written in Rust.

### System Monitoring & Utilities

* [btop](https://github.com/aristocratos/btop) ⭐ 34,202 | 🐛 528 | 🌐 C++ | 📅 2026-08-23 - Modern and visually rich resource monitor for Linux, macOS, and BSD.
* [bottom](https://github.com/ClementTsang/bottom) ⭐ 13,925 | 🐛 109 | 🌐 Rust | 📅 2026-08-24 - Cross-platform graphical process and system monitor inspired by htop.
* [dust](https://github.com/bootandy/dust) ⭐ 12,178 | 🐛 8 | 🌐 Rust | 📅 2026-08-19 - More intuitive replacement for `du` written in Rust.
* [htop](https://github.com/htop-dev/htop) ⭐ 8,280 | 🐛 353 | 🌐 C | 📅 2026-08-24 - Interactive process viewer and system monitor.
* [dua](https://github.com/Byron/dua-cli) ⭐ 6,171 | 🐛 31 | 🌐 Rust | 📅 2026-08-25 - Fast disk usage analyzer with an interactive terminal UI.
* [procs](https://github.com/dalance/procs) ⭐ 6,142 | 🐛 41 | 🌐 Rust | 📅 2026-08-17 - Modern replacement for `ps` with colored and structured output.

## Databases

### Graph Databases

* [Dgraph](https://github.com/hypermodeinc/dgraph) ⭐ 21,778 | 🐛 96 | 🌐 Go | 📅 2026-08-24 - Distributed graph database with GraphQL-native APIs.

### Key-Value & Cache Databases

* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,167 | 🐛 319 | 🌐 Go | 📅 2026-08-24 - Distributed key-value store used for Kubernetes coordination and service discovery.
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,023 | 🐛 304 | 🌐 C++ | 📅 2026-08-25 - Modern in-memory datastore compatible with Redis and Memcached APIs.
* [Valkey](https://github.com/valkey-io/valkey) ⭐ 26,975 | 🐛 877 | 🌐 C | 📅 2026-08-25 - Community-driven Redis fork focused on fully open-source development.
* [Apache Ignite](https://github.com/apache/ignite) ⭐ 5,077 | 🐛 871 | 🌐 Java | 📅 2026-08-24 - Distributed in-memory database and caching platform.

### NoSQL Databases

* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 26,995 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 - Real-time distributed database with changefeed support.
* [ArangoDB](https://github.com/arangodb/arangodb) ⭐ 14,262 | 🐛 838 | 🌐 C++ | 📅 2026-08-25 - Multi-model database supporting graph, document, and key-value data models.
* [FerretDB](https://github.com/FerretDB/FerretDB) ⭐ 11,054 | 🐛 447 | 🌐 Go | 📅 2026-06-05 - Open-source MongoDB alternative built on PostgreSQL.
* [Cassandra](https://github.com/apache/cassandra) ⭐ 10,081 | 🐛 472 | 🌐 Java | 📅 2026-08-24 - Highly scalable wide-column database built for high availability.
* [CouchDB](https://github.com/apache/couchdb) ⭐ 6,942 | 🐛 368 | 🌐 Erlang | 📅 2026-08-25 - Distributed JSON document database with replication and offline-first capabilities.

### Relational Databases

* [ClickHouse](https://github.com/ClickHouse/ClickHouse) ⭐ 49,434 | 🐛 7,058 | 🌐 C++ | 📅 2026-08-25 - High-performance column-oriented database for analytics and observability.
* [DuckDB](https://github.com/duckdb/duckdb) ⭐ 40,591 | 🐛 820 | 🌐 C++ | 📅 2026-08-25 - In-process analytical database designed for fast OLAP workloads.
* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,464 | 🐛 6,824 | 🌐 Go | 📅 2026-08-25 - Distributed MySQL-compatible database designed for HTAP and cloud-native workloads.
* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,415 | 🐛 8,270 | 🌐 Go | 📅 2026-08-07 - Distributed SQL database focused on scalability and fault tolerance.
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 21,890 | 🐛 0 | 🌐 C | 📅 2026-08-25 - Advanced open-source relational database known for reliability, extensibility, and SQL compliance.
* [LibSQL](https://github.com/tursodatabase/libsql) ⭐ 17,167 | 🐛 449 | 🌐 C | 📅 2026-08-23 - Open-source fork of SQLite focused on distributed and embedded workloads.
* [FoundationDB](https://github.com/apple/foundationdb) ⭐ 16,640 | 🐛 770 | 🌐 C++ | 📅 2026-08-25 - Distributed transactional key-value database designed for strong consistency.
* [YugabyteDB](https://github.com/yugabyte/yugabyte-db) ⭐ 10,496 | 🐛 8,275 | 🌐 C | 📅 2026-08-25 - High-performance distributed PostgreSQL-compatible database for scalable applications.
* [SQLite](https://github.com/sqlite/sqlite) ⭐ 10,333 | 🐛 22 | 🌐 C | 📅 2026-08-24 - Lightweight embedded relational database widely used in applications and mobile devices.
* [RisingWave](https://github.com/risingwavelabs/risingwave) ⭐ 9,285 | 🐛 1,613 | 🌐 Rust | 📅 2026-08-25 - Distributed SQL streaming database compatible with PostgreSQL.
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,136 | 🐛 465 | 🌐 C++ | 📅 2026-08-25 - Community-driven relational database forked from MySQL with strong open-source governance.

### Search & Analytics Engines

* [Meilisearch](https://github.com/meilisearch/meilisearch) ⭐ 59,081 | 🐛 313 | 🌐 Rust | 📅 2026-08-14 - Fast and developer-friendly search engine with typo tolerance.
* [Typesense](https://github.com/typesense/typesense) ⭐ 26,478 | 🐛 873 | 🌐 C++ | 📅 2026-08-18 - Open-source instant search engine focused on simplicity and performance.
* [Sonic](https://github.com/valeriansaliou/sonic) ⭐ 21,319 | 🐛 62 | 🌐 Rust | 📅 2026-08-24 - Lightweight and schema-less search backend optimized for speed.
* [OpenSearch](https://github.com/opensearch-project/OpenSearch) ⭐ 13,577 | 🐛 3,120 | 🌐 Java | 📅 2026-08-24 - Community-driven search and analytics engine forked from Elasticsearch.
* [Manticore Search](https://github.com/manticoresoftware/manticoresearch) ⭐ 11,955 | 🐛 715 | 🌐 C++ | 📅 2026-08-24 - Full-text search engine designed for high-performance indexing and querying.

### Time-Series Databases

* [TDengine](https://github.com/taosdata/TDengine) ⭐ 25,083 | 🐛 449 | 🌐 C | 📅 2026-08-24 - Time-series platform designed for IoT, industrial, and monitoring data.
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,277 | 🐛 935 | 🌐 Java | 📅 2026-08-25 - High-performance time-series database focused on fast SQL analytics.

### Vector Databases

* [Milvus](https://github.com/milvus-io/milvus) ⭐ 45,776 | 🐛 1,324 | 🌐 Go | 📅 2026-08-25 - Scalable vector database built for machine learning embeddings and AI workloads.
* [Qdrant](https://github.com/qdrant/qdrant) ⭐ 34,171 | 🐛 713 | 🌐 Rust | 📅 2026-08-25 - Vector similarity search engine for AI and semantic search applications.
* [SurrealDB](https://github.com/surrealdb/surrealdb) ⭐ 32,926 | 🐛 749 | 🌐 Rust | 📅 2026-08-21 - Multi-model database combining document, graph, and relational features with vector support.
* [Chroma](https://github.com/chroma-core/chroma) ⭐ 29,138 | 🐛 800 | 🌐 Rust | 📅 2026-08-24 - Lightweight embedding database designed for LLM applications.
* [Weaviate](https://github.com/weaviate/weaviate) ⭐ 16,750 | 🐛 687 | 🌐 Go | 📅 2026-08-25 - Open-source vector search engine with GraphQL and AI-native capabilities.
* [LanceDB](https://github.com/lancedb/lancedb) ⭐ 11,264 | 🐛 612 | 🌐 Rust | 📅 2026-08-25 - Embedded vector database optimized for AI applications and local-first workflows.

## DevOps

### Containers & Virtualization

* [Podman](https://github.com/containers/podman) ⭐ 32,682 | 🐛 1,132 | 🌐 Go | 📅 2026-08-24 - Daemonless container engine focused on security and OCI compatibility.
* [containerd](https://github.com/containerd/containerd) ⭐ 21,157 | 🐛 453 | 🌐 Go | 📅 2026-08-25 - High-performance container runtime used by Kubernetes and Docker.
* [Incus](https://github.com/lxc/incus) ⭐ 6,011 | 🐛 41 | 🌐 Go | 📅 2026-08-24 - Modern community-driven container and virtual machine manager forked from LXD.
* [CRI-O](https://github.com/cri-o/cri-o) ⭐ 5,653 | 🐛 139 | 🌐 Go | 📅 2026-08-25 - Kubernetes-native container runtime implementing the CRI standard.
* [LXC](https://github.com/lxc/lxc) ⭐ 5,247 | 🐛 149 | 🌐 C | 📅 2026-08-20 - Lightweight Linux container runtime with low-level system container support.

### Kubernetes & Orchestration

* [Kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 125,165 | 🐛 3,037 | 🌐 Go | 📅 2026-08-21 - The leading open-source container orchestration platform.
* [k3s](https://github.com/k3s-io/k3s) ⭐ 33,809 | 🐛 72 | 🌐 Go | 📅 2026-08-22 - Lightweight Kubernetes distribution optimized for edge and IoT workloads.
* [Helm](https://github.com/helm/helm) ⭐ 30,173 | 🐛 456 | 🌐 Go | 📅 2026-08-24 - Package manager for Kubernetes applications.
* [Rancher](https://github.com/rancher/rancher) ⭐ 25,872 | 🐛 3,344 | 🌐 Go | 📅 2026-08-25 - Kubernetes management platform for multi-cluster operations.
* [Argo CD](https://github.com/argoproj/argo-cd) ⭐ 23,988 | 🐛 4,396 | 🌐 Go | 📅 2026-08-25 - Declarative GitOps continuous delivery tool for Kubernetes.
* [Flux](https://github.com/fluxcd/flux2) ⭐ 8,369 | 🐛 251 | 🌐 Go | 📅 2026-08-09 - GitOps toolkit for keeping Kubernetes clusters in sync with Git repositories.

### CI / CD

* [Jenkins](https://github.com/jenkinsci/jenkins) ⭐ 26,491 | 🐛 3,606 | 🌐 Java | 📅 2026-08-25 - Extensible automation server for CI/CD pipelines.
* [Tekton](https://github.com/tektoncd/pipeline) ⭐ 9,043 | 🐛 566 | 🌐 Go | 📅 2026-08-24 - Kubernetes-native framework for creating CI/CD systems.
* [Concourse](https://github.com/concourse/concourse) ⭐ 7,893 | 🐛 78 | 🌐 Go | 📅 2026-08-24 - Container-based continuous integration system with declarative pipelines.
* [Woodpecker CI](https://github.com/woodpecker-ci/woodpecker) ⭐ 7,742 | 🐛 360 | 🌐 Go | 📅 2026-08-25 - Lightweight and fully open-source CI/CD system inspired by Drone.
* [GoCD](https://github.com/gocd/gocd) ⭐ 7,429 | 🐛 82 | 🌐 Java | 📅 2026-08-22 - Open-source continuous delivery server focused on complex workflows.

### Infrastructure as Code

* [Ansible](https://github.com/ansible/ansible) ⭐ 70,450 | 🐛 842 | 🌐 Python | 📅 2026-08-19 - Agentless automation tool for configuration management and provisioning.
* [OpenTofu](https://github.com/opentofu/opentofu) ⭐ 29,903 | 🐛 324 | 🌐 Go | 📅 2026-08-24 - Community-driven infrastructure as code tool forked from Terraform.
* [Pulumi](https://github.com/pulumi/pulumi) ⭐ 25,605 | 🐛 2,454 | 🌐 Go | 📅 2026-08-25 - Infrastructure as code platform using familiar programming languages.
* [Crossplane](https://github.com/crossplane/crossplane) ⭐ 11,976 | 🐛 187 | 🌐 Go | 📅 2026-08-25 - Kubernetes-based control plane framework for cloud infrastructure.
* [Atlantis](https://github.com/runatlantis/atlantis) ⭐ 9,252 | 🐛 887 | 🌐 Go | 📅 2026-08-24 - GitOps workflow automation for Terraform and OpenTofu projects.

### Monitoring & Observability

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 65,804 | 🐛 918 | 🌐 Go | 📅 2026-08-24 - Monitoring and alerting toolkit designed for reliability and scalability.
* [Jaeger](https://github.com/jaegertracing/jaeger) ⭐ 23,137 | 🐛 568 | 🌐 Go | 📅 2026-08-24 - Distributed tracing platform for monitoring microservices.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,591 | 🐛 779 | 🌐 Go | 📅 2026-08-25 - High-performance time-series database and monitoring stack.
* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector) ⭐ 7,448 | 🐛 703 | 🌐 Go | 📅 2026-08-25 - Open standard and tooling for telemetry data collection.

### Networking & Reverse Proxy

* [Caddy](https://github.com/caddyserver/caddy) ⭐ 75,189 | 🐛 276 | 🌐 Go | 📅 2026-08-25 - Web server with automatic HTTPS and simple configuration.
* [Traefik](https://github.com/traefik/traefik) ⭐ 64,573 | 🐛 916 | 🌐 Go | 📅 2026-08-24 - Modern reverse proxy and ingress controller with automatic service discovery.
* [Nginx](https://github.com/nginx/nginx) ⭐ 31,488 | 🐛 474 | 🌐 C | 📅 2026-08-24 - High-performance web server and reverse proxy.
* [CoreDNS](https://github.com/coredns/coredns) ⭐ 14,273 | 🐛 293 | 🌐 Go | 📅 2026-08-24 - Flexible and extensible DNS server commonly used in Kubernetes.
* [HAProxy](https://github.com/haproxy/haproxy) ⭐ 6,801 | 🐛 381 | 🌐 C | 📅 2026-08-24 - Reliable high-availability load balancer and proxy server.

### Secrets & Security

* [Trivy](https://github.com/aquasecurity/trivy) ⭐ 37,596 | 🐛 255 | 🌐 Go | 📅 2026-08-21 - Security scanner for containers, dependencies, Kubernetes, and IaC.
* [Infisical](https://github.com/Infisical/infisical) ⭐ 28,934 | 🐛 751 | 🌐 TypeScript | 📅 2026-08-25 - Open-source secrets management platform for teams and infrastructure.
* [Falco](https://github.com/falcosecurity/falco) ⭐ 9,300 | 🐛 64 | 🌐 C++ | 📅 2026-08-03 - Runtime security monitoring for containers and Kubernetes.
* [Step CA](https://github.com/smallstep/certificates) ⭐ 8,775 | 🐛 287 | 🌐 Go | 📅 2026-08-24 - Private certificate authority and automated TLS management solution.

## Mobile Apps

### Browsers & Internet

* [Cromite](https://github.com/uazo/cromite) ⭐ 8,107 | 🐛 537 | 🌐 C++ | 📅 2026-08-25 - Privacy-focused Chromium fork with ad blocking.
* [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit) ⭐ 5,429 | 🐛 165 | 🌐 Java | 📅 2026-08-19 - Open-source Reddit client for Android.
* [Firefox for Android](https://github.com/mozilla-mobile/firefox-android) ⚠️ Archived - Open-source mobile browser developed by Mozilla.
* [Fulguris](https://github.com/Slion/Fulguris) ⭐ 818 | 🐛 318 | 🌐 Kotlin | 📅 2026-08-24 - Lightweight privacy-focused Android browser.
* [Mull](https://github.com/Divested-Mobile/Mull-Fenix) ⚠️ Archived - Hardened Firefox fork for Android privacy.

### File Management & Utilities

* [Termux](https://github.com/termux/termux-app) ⭐ 59,740 | 🐛 592 | 🌐 Java | 📅 2026-08-24 - Android terminal emulator and Linux environment.
* [Obtainium](https://github.com/ImranR98/Obtainium) ⭐ 19,235 | 🐛 388 | 🌐 Dart | 📅 2026-08-24 - App updater directly from GitHub and other sources.
* [Material Files](https://github.com/zhanghai/MaterialFiles) ⭐ 8,803 | 🐛 628 | 🌐 Kotlin | 📅 2026-04-06 - Material Design file manager for Android.
* [SD Maid SE](https://github.com/d4rken-org/sdmaid-se) ⭐ 7,358 | 🐛 12 | 🌐 Kotlin | 📅 2026-08-24 - Android system cleaning and maintenance utility.
* [Neo Store](https://github.com/NeoApplications/Neo-Store) ⭐ 4,933 | 🐛 129 | 🌐 Kotlin | 📅 2026-04-25 - Modern F-Droid client for Android.

### Launchers & Customization

* [Lawnchair](https://github.com/LawnchairLauncher/lawnchair) ⭐ 13,389 | 🐛 722 | 🌐 Java | 📅 2026-08-24 - Pixel-inspired customizable Android launcher.
* [Kvaesitso](https://github.com/MM2-0/Kvaesitso) ⭐ 5,038 | 🐛 687 | 🌐 Kotlin | 📅 2026-08-23 - Launcher focused on search and productivity.
* [Neo Launcher](https://github.com/NeoApplications/Neo-Launcher) ⭐ 2,101 | 🐛 134 | 🌐 Java | 📅 2026-08-16 - Fork of Lawnchair with enhanced customization.

### Media & Music

* [Metrolist](https://github.com/MetrolistGroup/Metrolist) ⭐ 12,204 | 🐛 486 | 🌐 Kotlin | 📅 2026-08-24 - Feature-rich YouTube Music client for Android with offline playback, synced lyrics, and Material 3 design.
* [ViMusic](https://github.com/vfsfitvnm/ViMusic) ⚠️ Archived - Lightweight open-source music streaming app for Android.
* [PixelPlayer](https://github.com/theovilardo/PixelPlayer) ⭐ 6,189 | 🐛 526 | 🌐 Kotlin | 📅 2026-08-24 - Privacy-first Android music player built with Material 3.
* [InnerTune](https://github.com/z-huang/InnerTune) ⭐ 6,047 | 🐛 268 | 🌐 Kotlin | 📅 2025-11-13 - Modern YouTube Music client for Android.
* [SpotiFLAC-Mobile](https://github.com/spotiflacapp/SpotiFLAC-Mobile) ⭐ 5,979 | 🐛 89 | 🌐 Dart | 📅 2026-08-25 - Open-source mobile companion for managing personal music libraries.
* [Retro Music](https://github.com/RetroMusicPlayer/RetroMusicPlayer) ⭐ 5,272 | 🐛 367 | 🌐 Kotlin | 📅 2026-08-19 - Stylish Android music player with modern UI.
* [Auxio](https://github.com/OxygenCobalt/Auxio) ⭐ 4,192 | 🐛 203 | 🌐 Kotlin | 📅 2026-08-04 - Local Android music player focused on simplicity and performance.
* [RiMusic](https://github.com/fast4x/RiMusic) ⚠️ Archived - Beautiful Android music player powered by YouTube Music.
* [Gramophone](https://github.com/FoedusProgramme/Gramophone) ⭐ 2,243 | 🐛 290 | 🌐 Kotlin | 📅 2026-08-24 - Material You inspired local music player for Android.
* [Symphony](https://github.com/zyrouge/symphony) ⭐ 1,696 | 🐛 205 | 🌐 Kotlin | 📅 2026-07-20 - Elegant and lightweight Flutter-based music player.
* [Vinyl Music Player](https://github.com/VinylMusicPlayer/VinylMusicPlayer) ⭐ 990 | 🐛 247 | 🌐 Java | 📅 2024-08-18 - Fork of Phonograph with classic Android music player experience.

### Messaging & Communication

* [K-9 Mail](https://github.com/thunderbird/thunderbird-android) ⭐ 13,908 | 🐛 1,057 | 🌐 Kotlin | 📅 2026-08-24 - Open-source email client for Android.
* [FairEmail](https://github.com/M66B/FairEmail) ⭐ 4,581 | 🐛 3 | 🌐 Java | 📅 2026-08-24 - Privacy-oriented email client with extensive customization.
* [Element](https://github.com/element-hq/element-android) ⭐ 3,721 | 🐛 2,210 | 🌐 Kotlin | 📅 2026-08-21 - Matrix-based secure messaging application.
* [Molly](https://github.com/mollyim/mollyim-android) ⭐ 3,664 | 🐛 331 | 🌐 Kotlin | 📅 2026-08-22 - Hardened Signal fork for Android.
* [Session](https://github.com/session-foundation/session-android) ⭐ 869 | 🐛 214 | 🌐 Kotlin | 📅 2026-08-25 - Privacy-focused encrypted messenger without phone numbers.
* [Briar](https://github.com/briar/briar) ⭐ 685 | 🐛 1 | 🌐 Java | 📅 2026-07-13 - Peer-to-peer encrypted messaging app.

### Password Managers & Security

* [Aegis](https://github.com/beemdevelopment/Aegis) ⭐ 12,964 | 🐛 115 | 🌐 Java | 📅 2026-07-16 - Secure two-factor authentication app.
* [Bitwarden](https://github.com/bitwarden/android) ⭐ 9,264 | 🐛 176 | 🌐 Kotlin | 📅 2026-08-25 - Open-source password manager for Android.
* [KeePassDX](https://github.com/Kunzisoft/KeePassDX) ⭐ 7,175 | 🐛 557 | 🌐 Kotlin | 📅 2026-08-23 - KeePass-compatible password manager.
* [Authenticator Pro](https://github.com/jamie-mh/AuthenticatorPro) ⭐ 4,556 | 🐛 80 | 🌐 C# | 📅 2026-08-24 - Two-factor authentication app with backups.
* [Proton Pass](https://github.com/protonpass/android-pass) ⭐ 759 | 🐛 2 | 🌐 Kotlin | 📅 2026-07-28 - Password manager developed by Proton.

### Productivity & Notes

* [Joplin](https://github.com/laurent22/joplin) ⭐ 56,090 | 🐛 622 | 🌐 TypeScript | 📅 2026-08-24 - Note-taking and task management application with sync support.
* [Logseq](https://github.com/logseq/logseq) ⭐ 44,609 | 🐛 958 | 🌐 Clojure | 📅 2026-08-24 - Knowledge management and outlining application.
* [Notesnook](https://github.com/streetwriters/notesnook) ⭐ 14,466 | 🐛 977 | 🌐 TypeScript | 📅 2026-08-25 - Privacy-focused encrypted note-taking app.
* [NoteGen](https://github.com/codexu/note-gen) ⭐ 12,683 | 🐛 111 | 🌐 TypeScript | 📅 2026-08-25 - Local-first Markdown note-taking app with capture, editing, optional sync, and AI-assisted organization.
* [Standard Notes](https://github.com/standardnotes/app) ⭐ 6,601 | 🐛 99 | 🌐 TypeScript | 📅 2026-08-18 - End-to-end encrypted notes application.
* [Markor](https://github.com/gsantner/markor) ⭐ 6,021 | 🐛 183 | 🌐 Java | 📅 2026-08-25 - Markdown editor and note-taking app for Android.
* [Tasks.org](https://github.com/tasks/tasks) ⭐ 5,510 | 🐛 1,173 | 🌐 Kotlin | 📅 2026-08-22 - Open-source task management app for Android.
* [Quillpad](https://github.com/quillpad/quillpad) ⭐ 1,363 | 🐛 294 | 🌐 Kotlin | 📅 2026-08-25 - Minimal Material You note-taking app.

### Video & Streaming

* [NewPipe](https://github.com/TeamNewPipe/NewPipe) ⭐ 39,479 | 🐛 1,447 | 🌐 Java | 📅 2026-08-24 - Lightweight YouTube frontend for Android without Google dependencies.
* [Seal](https://github.com/JunkFood02/Seal) ⭐ 28,441 | 🐛 707 | 🌐 Kotlin | 📅 2026-07-25 - Video and audio downloader powered by yt-dlp.
* [Mihon](https://github.com/mihonapp/mihon) ⭐ 23,102 | 🐛 723 | 🌐 Kotlin | 📅 2026-08-23 - Open-source manga reader for Android.
* [LibreTube](https://github.com/libre-tube/LibreTube) ⭐ 12,547 | 🐛 158 | 🌐 Kotlin | 📅 2026-08-24 - Privacy-focused YouTube client using Piped.
* [Aniyomi](https://github.com/aniyomiorg/aniyomi) ⭐ 7,625 | 🐛 375 | 🌐 Kotlin | 📅 2026-08-19 - Anime streaming and manga reader forked from Mihon.
* [Jellyfin Android](https://github.com/jellyfin/jellyfin-android) ⭐ 2,710 | 🐛 190 | 🌐 Kotlin | 📅 2026-08-24 - Android client for the Jellyfin media server.
* [Grayjay](https://github.com/futo-org/grayjay-android) ⭐ 1,796 | 🐛 958 | 🌐 Kotlin | 📅 2026-08-12 - Unified media platform supporting multiple content sources.

## Security

### Container & Kubernetes Security

* [Kubescape](https://github.com/kubescape/kubescape) ⭐ 11,686 | 🐛 83 | 🌐 Go | 📅 2026-08-25 - Kubernetes security platform for risk analysis and compliance scanning.
* [Kube-bench](https://github.com/aquasecurity/kube-bench) ⭐ 8,151 | 🐛 95 | 🌐 Go | 📅 2026-08-24 - CIS Kubernetes benchmark compliance checker.
* [Kyverno](https://github.com/kyverno/kyverno) ⭐ 8,068 | 🐛 642 | 🌐 Go | 📅 2026-08-25 - Kubernetes-native policy engine for security, governance, and compliance.
* [Kube-hunter](https://github.com/aquasecurity/kube-hunter) ⭐ 5,078 | 🐛 82 | 🌐 Python | 📅 2024-03-19 - Kubernetes penetration testing and security auditing tool.
* [Dockle](https://github.com/goodwithtech/dockle) ⭐ 3,290 | 🐛 53 | 🌐 Go | 📅 2026-08-10 - Container image linter focused on security best practices.
* [Chainguard Images](https://github.com/chainguard-images/images) ⭐ 692 | 🐛 114 | 🌐 HCL | 📅 2026-08-24 - Minimal and hardened container images focused on supply chain security.

### Endpoint & Runtime Security

* [Osquery](https://github.com/osquery/osquery) ⭐ 23,518 | 🐛 624 | 🌐 C++ | 📅 2026-08-19 - Operating system instrumentation framework exposing system data through SQL.
* [Lynis](https://github.com/CISOfy/lynis) ⭐ 16,224 | 🐛 218 | 🌐 Shell | 📅 2026-08-05 - Security auditing and hardening tool for Unix-based systems.
* [Wazero](https://github.com/tetratelabs/wazero) ⭐ 6,341 | 🐛 40 | 🌐 Go | 📅 2026-08-24 - Secure WebAssembly runtime for sandboxed application execution.
* [OpenEDR](https://github.com/ComodoSecurity/openedr) ⭐ 2,715 | 🐛 37 | 🌐 C++ | 📅 2026-05-23 - Endpoint detection and response platform for monitoring and threat analysis.
* [Chkrootkit](https://github.com/Magentron/chkrootkit) ⚠️ Archived - Toolset for detecting rootkits on Unix systems.

### Network Security & Monitoring

* [Wazuh](https://github.com/wazuh/wazuh) ⭐ 16,671 | 🐛 2,972 | 🌐 C++ | 📅 2026-08-25 - Open-source XDR and SIEM platform for threat detection and compliance.
* [CrowdSec](https://github.com/crowdsecurity/crowdsec) ⭐ 14,640 | 🐛 284 | 🌐 Go | 📅 2026-08-24 - Collaborative IPS and threat intelligence platform protecting servers and applications.
* [Zeek](https://github.com/zeek/zeek) ⭐ 7,903 | 🐛 246 | 🌐 C++ | 📅 2026-08-24 - Powerful network analysis framework for monitoring and security visibility.
* [Suricata](https://github.com/OISF/suricata) ⭐ 6,568 | 🐛 98 | 🌐 C | 📅 2026-08-22 - High-performance network IDS, IPS, and network security monitoring engine.
* [Security Onion](https://github.com/Security-Onion-Solutions/securityonion) ⭐ 4,843 | 🐛 81 | 🌐 Shell | 📅 2026-08-25 - Linux distribution for intrusion detection, enterprise security monitoring, and log management.
* [Snort](https://github.com/snort3/snort3) ⭐ 3,407 | 🐛 76 | 🌐 C++ | 📅 2026-04-23 - Widely used open-source intrusion prevention and detection system.

### Privacy & Anonymity

* [OpenSnitch](https://github.com/evilsocket/opensnitch) ⭐ 14,001 | 🐛 185 | 🌐 Python | 📅 2026-07-26 - Application firewall and outbound connection monitor for Linux.
* [Arkenfox user.js](https://github.com/arkenfox/user.js) ⭐ 12,804 | 🐛 19 | 🌐 JavaScript | 📅 2026-08-20 - Hardened Firefox configuration focused on privacy and security.
* [Tor](https://github.com/torproject/tor) ⭐ 5,006 | 🐛 101 | 📅 2024-03-05 - Anonymous overlay network for protecting privacy and resisting surveillance.
* [GrapheneOS](https://github.com/GrapheneOS/platform_manifest) ⭐ 535 | 🐛 1 | 📅 2026-08-13 - Privacy and security-focused Android-based mobile operating system.

### Reverse Engineering & Pentesting

* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) ⭐ 72,766 | 🐛 1,922 | 🌐 Java | 📅 2026-08-24 - Software reverse engineering suite developed by the NSA.
* [Metasploit Framework](https://github.com/rapid7/metasploit-framework) ⭐ 38,868 | 🐛 597 | 🌐 Ruby | 📅 2026-08-24 - Penetration testing framework for security auditing and exploit development.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,258 | 🐛 32 | 🌐 Python | 📅 2026-08-23 - Automated SQL injection and database takeover tool.
* [OWASP ZAP](https://github.com/zaproxy/zaproxy) ⭐ 15,677 | 🐛 859 | 🌐 Java | 📅 2026-08-21 - Open-source web application security scanner maintained by OWASP.
* [Amass](https://github.com/owasp-amass/amass) ⭐ 15,037 | 🐛 237 | 🌐 Go | 📅 2026-07-19 - Attack surface mapping and external asset discovery tool.
* [Nmap](https://github.com/nmap/nmap) ⭐ 13,445 | 🐛 674 | 🌐 C | 📅 2026-08-24 - Network discovery and security auditing utility.
* [Hetty](https://github.com/dstotijn/hetty) ⭐ 12,004 | 🐛 50 | 🌐 Go | 📅 2026-07-21 - Open source proxy that allows you to modify packets.
* [Wireshark](https://github.com/wireshark/wireshark) ⭐ 9,774 | 🐛 2 | 🌐 C | 📅 2026-08-25 - Network protocol analyzer for troubleshooting and packet inspection.
* [Responder](https://github.com/lgandx/Responder) ⭐ 6,554 | 🐛 29 | 🌐 Python | 📅 2026-06-10 - LLMNR, NBT-NS, and MDNS poisoner commonly used in internal network assessments.

### Secrets Management & Encryption

* [HashiCorp Vault](https://github.com/hashicorp/vault) ⭐ 36,164 | 🐛 1,428 | 🌐 Go | 📅 2026-08-24 - Secrets management and encryption platform for protecting sensitive infrastructure data.
* [age](https://github.com/FiloSottile/age) ⭐ 23,311 | 🐛 33 | 🌐 Go | 📅 2026-03-20 - Simple, modern, and secure file encryption tool.
* [SOPS](https://github.com/getsops/sops) ⭐ 22,913 | 🐛 443 | 🌐 Go | 📅 2026-08-24 - Tool for encrypting and managing structured configuration files and secrets.
* [Cryptomator](https://github.com/cryptomator/cryptomator) ⭐ 16,006 | 🐛 284 | 🌐 Java | 📅 2026-08-24 - Client-side encrypted cloud storage solution focused on privacy.
* [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) ⭐ 9,256 | 🐛 69 | 🌐 Go | 📅 2026-08-20 - Kubernetes controller for managing encrypted secrets safely in Git repositories.

### Vulnerability Scanning & Analysis

* [Semgrep](https://github.com/semgrep/semgrep) ⭐ 16,385 | 🐛 899 | 🌐 OCaml | 📅 2026-08-25 - Static analysis tool for finding security issues in source code.
* [Grype](https://github.com/anchore/grype) ⭐ 12,784 | 🐛 412 | 🌐 Go | 📅 2026-08-21 - Vulnerability scanner for container images and filesystems.
* [Clair](https://github.com/quay/clair) ⭐ 11,051 | 🐛 59 | 🌐 Go | 📅 2026-08-24 - Static analysis tool for identifying vulnerabilities in container images.
* [OWASP Dependency-Check](https://github.com/dependency-check/DependencyCheck) ⭐ 7,667 | 🐛 195 | 🌐 Java | 📅 2026-08-25 - Tool for detecting vulnerable dependencies in software projects.
* [Dependency-Track](https://github.com/DependencyTrack/dependency-track) ⭐ 4,139 | 🐛 1,074 | 🌐 Java | 📅 2026-08-24 - Software supply chain security platform for SBOM analysis and vulnerability tracking.
* [OpenSCAP](https://github.com/OpenSCAP/openscap) ⭐ 1,802 | 🐛 61 | 🌐 XSLT | 📅 2026-08-13 - Security compliance and vulnerability scanning framework implementing SCAP standards.

## Self-Hosted

### Developer Platforms & Git Services

* [Gitea](https://github.com/go-gitea/gitea) ⭐ 57,584 | 🐛 2,527 | 🌐 Go | 📅 2026-08-25 - Simple, lightweight, and self-hosted Git service.
* [GitLab CE](https://github.com/gitlabhq/gitlabhq) ⭐ 24,536 | 🐛 37 | 🌐 Ruby | 📅 2026-08-25 - Complete DevOps platform with source control and CI/CD features.
* [Onedev](https://github.com/theonedev/onedev) ⭐ 15,177 | 🐛 0 | 🌐 Java | 📅 2026-08-24 - All-in-one Git server with CI/CD and issue tracking.

### DNS, Networking & Privacy

* [Pi-hole](https://github.com/pi-hole/pi-hole) ⭐ 60,589 | 🐛 38 | 🌐 Shell | 📅 2026-08-22 - Network-wide ad blocker and DNS sinkhole for improving privacy.
* [Headscale](https://github.com/juanfont/headscale) ⭐ 43,153 | 🐛 153 | 🌐 Go | 📅 2026-08-25 - Open-source self-hosted coordination server compatible with Tailscale clients.
* [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) ⭐ 36,345 | 🐛 1,280 | 🌐 TypeScript | 📅 2026-08-21 - Self-hosted DNS server with ad and tracker blocking.
* [NetBird](https://github.com/netbirdio/netbird) ⭐ 28,638 | 🐛 1,576 | 🌐 Go | 📅 2026-08-25 - WireGuard-based secure networking platform for private connectivity.
* [Technitium DNS Server](https://github.com/TechnitiumSoftware/DnsServer) ⭐ 9,584 | 🐛 173 | 🌐 C# | 📅 2026-07-25 - Powerful open-source DNS server with modern protocol support.

### Homelab & Server Management

* [Coolify](https://github.com/coollabsio/coolify) ⭐ 61,008 | 🐛 653 | 🌐 PHP | 📅 2026-08-24 - Open-source self-hostable alternative to Heroku, Netlify, and Vercel.
* [CasaOS](https://github.com/IceWhaleTech/CasaOS) ⭐ 37,127 | 🐛 831 | 🌐 Go | 📅 2025-08-06 - Simple and beginner-friendly home cloud operating system for self-hosted apps.
* [Dokploy](https://github.com/Dokploy/dokploy) ⭐ 36,847 | 🐛 689 | 🌐 TypeScript | 📅 2026-08-25 - Modern self-hosted deployment platform built for Docker and VPS environments.
* [CapRover](https://github.com/caprover/caprover) ⭐ 15,139 | 🐛 178 | 🌐 TypeScript | 📅 2026-08-20 - Lightweight self-hosted PaaS platform for deploying web applications with Docker.
* [Umbrel](https://github.com/getumbrel/umbrel) ⭐ 11,790 | 🐛 448 | 🌐 TypeScript | 📅 2026-07-10 - Personal server platform for running self-hosted applications and services.
* [Cosmos Server](https://github.com/azukaar/Cosmos-Server) ⭐ 6,128 | 🐛 187 | 🌐 JavaScript | 📅 2026-08-24 - Self-hosted portal for managing apps, reverse proxy, and authentication in one interface.
* [YunoHost](https://github.com/YunoHost/yunohost) ⭐ 2,968 | 🐛 103 | 🌐 Python | 📅 2026-08-23 - Debian-based self-hosting platform focused on simplicity and privacy.

### Media Servers & Streaming

* [Jellyfin](https://github.com/jellyfin/jellyfin) ⭐ 56,151 | 🐛 595 | 🌐 C# | 📅 2026-08-24 - Fully open-source media server for movies, TV shows, music, and live TV.
* [Navidrome](https://github.com/navidrome/navidrome) ⭐ 23,102 | 🐛 271 | 🌐 Go | 📅 2026-08-25 - Lightweight self-hosted music streaming server compatible with Subsonic clients.
* [Audiobookshelf](https://github.com/advplyr/audiobookshelf) ⭐ 14,108 | 🐛 1,144 | 🌐 JavaScript | 📅 2026-08-16 - Self-hosted audiobook and podcast server with modern apps and metadata support.
* [Owncast](https://github.com/owncast/owncast) ⭐ 11,470 | 🐛 183 | 🌐 Go | 📅 2026-08-25 - Self-hosted live streaming server with chat and federation support.
* [Tube Archivist](https://github.com/tubearchivist/tubearchivist) ⭐ 8,393 | 🐛 26 | 🌐 Python | 📅 2026-08-23 - Self-hosted YouTube media server and video archiving platform.
* [Azuracast](https://github.com/AzuraCast/AzuraCast) ⭐ 4,008 | 🐛 107 | 🌐 PHP | 📅 2026-08-25 - Web radio management suite for self-hosted internet radio stations.

### Monitoring & Uptime

* [Uptime Kuma](https://github.com/louislam/uptime-kuma) ⭐ 90,584 | 🐛 787 | 🌐 JavaScript | 📅 2026-08-25 - Self-hosted uptime monitoring tool with status pages and notifications.
* [Netdata](https://github.com/netdata/netdata) ⭐ 80,285 | 🐛 390 | 🌐 Go | 📅 2026-08-25 - Real-time infrastructure monitoring and troubleshooting platform.
* [Beszel](https://github.com/henrygd/beszel) ⭐ 24,632 | 🐛 318 | 🌐 Go | 📅 2026-08-24 - Lightweight server monitoring platform with Docker support.
* [Checkmk](https://github.com/Checkmk/checkmk) ⭐ 2,348 | 🐛 56 | 🌐 Python | 📅 2026-08-25 - Comprehensive IT monitoring solution for servers, containers, and networks.

### Password Managers & Authentication

* [Vaultwarden](https://github.com/dani-garcia/vaultwarden) ⭐ 66,157 | 🐛 85 | 🌐 Rust | 📅 2026-08-24 - Lightweight Bitwarden-compatible password manager server written in Rust.
* [Authentik](https://github.com/goauthentik/authentik) ⭐ 25,133 | 🐛 1,062 | 🌐 Python | 📅 2026-08-25 - Self-hosted identity provider and authentication platform.
* [LLDAP](https://github.com/lldap/lldap) ⭐ 6,463 | 🐛 122 | 🌐 Rust | 📅 2026-08-10 - Lightweight LDAP server for small teams and homelab setups.
* [Passbolt](https://github.com/passbolt/passbolt_api) ⭐ 6,089 | 🐛 27 | 🌐 PHP | 📅 2026-08-21 - Open-source password manager designed for team collaboration.
* [Kanidm](https://github.com/kanidm/kanidm) ⭐ 5,284 | 🐛 267 | 🌐 Rust | 📅 2026-08-25 - Modern identity management server focused on security and simplicity.

### Photos & File Management

* [Immich](https://github.com/immich-app/immich) ⭐ 112,588 | 🐛 712 | 🌐 TypeScript | 📅 2026-08-25 - High-performance self-hosted photo and video backup solution inspired by Google Photos.
* [Syncthing](https://github.com/syncthing/syncthing) ⭐ 87,964 | 🐛 376 | 🌐 Go | 📅 2026-08-25 - Decentralized continuous file synchronization application.
* [PhotoPrism](https://github.com/photoprism/photoprism) ⭐ 40,106 | 🐛 457 | 🌐 Go | 📅 2026-08-24 - AI-powered self-hosted photo management application.
* [File Browser](https://github.com/filebrowser/filebrowser) ⭐ 35,931 | 🐛 1 | 🌐 Go | 📅 2026-07-31 - Web-based file manager for managing files on remote servers.
* [Piwigo](https://github.com/Piwigo/Piwigo) ⭐ 3,844 | 🐛 748 | 🌐 PHP | 📅 2026-08-25 - Open-source photo gallery platform with plugin support.

### RSS, Read-It-Later & Knowledge

* [Hoarder](https://github.com/hoarder-app/hoarder) ⭐ 28,590 | 🐛 692 | 🌐 TypeScript | 📅 2026-08-22 - Self-hosted bookmark manager with AI-assisted organization.
* [Karakeep](https://github.com/karakeep-app/karakeep) ⭐ 28,590 | 🐛 692 | 🌐 TypeScript | 📅 2026-08-22 - Modern self-hosted bookmarking and knowledge management platform.
* [FreshRSS](https://github.com/FreshRSS/FreshRSS) ⭐ 15,829 | 🐛 665 | 🌐 PHP | 📅 2026-08-21 - Lightweight and self-hosted RSS feed aggregator.
* [Wallabag](https://github.com/wallabag/wallabag) ⭐ 12,932 | 🐛 762 | 🌐 PHP | 📅 2026-08-24 - Self-hosted read-it-later application for saving web articles.
* [Miniflux](https://github.com/miniflux/v2) ⭐ 9,609 | 🐛 278 | 🌐 Go | 📅 2026-08-24 - Minimalist RSS reader focused on performance and simplicity.

## Software / SaaS

### Analytics & Monitoring

* [Umami](https://github.com/umami-software/umami) ⭐ 38,348 | 🐛 102 | 🌐 TypeScript | 📅 2026-08-25 - Privacy-focused web analytics alternative to Google Analytics.
* [Signoz](https://github.com/SigNoz/signoz) ⭐ 31,931 | 🐛 1,536 | 🌐 TypeScript | 📅 2026-08-25 - Open-source observability platform for metrics, traces, and logs.
* [Plausible Analytics](https://github.com/plausible/analytics) ⭐ 28,739 | 🐛 62 | 🌐 Elixir | 📅 2026-08-25 - Lightweight and privacy-friendly website analytics platform.
* [OpenReplay](https://github.com/openreplay/openreplay) ⭐ 12,565 | 🐛 175 | 🌐 TypeScript | 📅 2026-08-24 - Session replay and product analytics platform for debugging user issues.

### Automation & Internal Tools

* [n8n](https://github.com/n8n-io/n8n) ⭐ 202,334 | 🐛 1,077 | 🌐 TypeScript | 📅 2026-08-25 - Workflow automation platform with self-hosting and extensible integrations.
* [ToolJet](https://github.com/ToolJet/ToolJet) ⭐ 40,758 | 🐛 1,164 | 🌐 JavaScript | 📅 2026-08-25 - Low-code platform for building internal tools and admin panels.
* [Appsmith](https://github.com/appsmithorg/appsmith) ⭐ 40,742 | 🐛 4,474 | 🌐 TypeScript | 📅 2026-08-24 - Open-source framework for creating internal applications rapidly.
* [Budibase](https://github.com/Budibase/budibase) ⭐ 28,242 | 🐛 273 | 🌐 TypeScript | 📅 2026-08-25 - Low-code platform for internal tools, forms, and operational dashboards.

### Communication & Support

* [Chatwoot](https://github.com/chatwoot/chatwoot) ⭐ 36,179 | 🐛 1,350 | 🌐 Ruby | 📅 2026-08-25 - Customer engagement and support platform with live chat and omnichannel inboxes.
* [Formbricks](https://github.com/formbricks/formbricks) ⭐ 12,815 | 🐛 237 | 🌐 TypeScript | 📅 2026-08-25 - Open-source experience management and product feedback platform.
* [Typebot](https://github.com/baptisteArno/typebot.io) ⭐ 10,285 | 🐛 14 | 🌐 TypeScript | 📅 2026-08-24 - Conversational form builder for creating interactive chat-style workflows.
* [Papercups](https://github.com/papercups-io/papercups) ⭐ 6,098 | 🐛 178 | 🌐 Elixir | 📅 2024-02-15 - Open-source live chat and customer messaging platform.

### Documentation & Knowledge Bases

* [Outline](https://github.com/outline/outline) ⭐ 40,313 | 🐛 79 | 🌐 TypeScript | 📅 2026-08-25 - Collaborative team knowledge base and documentation platform.
* [Wiki.js](https://github.com/requarks/wiki) ⭐ 28,792 | 🐛 189 | 🌐 Vue | 📅 2026-08-25 - Powerful and extensible open-source wiki platform.
* [Docs](https://github.com/suitenumerique/docs) ⭐ 16,751 | 🐛 394 | 🌐 Python | 📅 2026-08-24 - Collaborative document editing platform focused on privacy and self-hosting.
* [Documenso](https://github.com/documenso/documenso) ⭐ 14,734 | 🐛 255 | 🌐 TypeScript | 📅 2026-08-25 - Open-source document signing platform as an alternative to DocuSign.

### File Storage & Cloud

* [Nextcloud](https://github.com/nextcloud/server) ⭐ 36,567 | 🐛 3,591 | 🌐 PHP | 📅 2026-08-25 - Self-hosted productivity cloud with file sync, collaboration, and communication tools.
* [Cloudreve](https://github.com/cloudreve/Cloudreve) ⭐ 28,603 | 🐛 154 | 🌐 Go | 📅 2026-08-24 - Self-hosted cloud storage system supporting multiple storage providers.
* [Seafile](https://github.com/haiwen/seafile) ⭐ 15,164 | 🐛 90 | 🌐 C | 📅 2026-08-08 - High-performance open-source file hosting and synchronization platform.
* [Filestash](https://github.com/mickael-kerjean/filestash) ⭐ 14,543 | 🐛 122 | 🌐 Go | 📅 2026-08-25 - Modern web client for managing files across multiple storage backends.

### Productivity & Collaboration

* [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) ⭐ 75,929 | 🐛 1,000 | 🌐 Dart | 📅 2026-08-11 - Open-source workspace and knowledge management platform positioned as an alternative to Notion.
* [AFFiNE](https://github.com/toeverything/AFFiNE) ⭐ 71,859 | 🐛 710 | 🌐 TypeScript | 📅 2026-08-24 - All-in-one collaborative workspace combining docs, whiteboards, and databases.
* [Plane](https://github.com/makeplane/plane) ⭐ 58,084 | 🐛 1,083 | 🌐 TypeScript | 📅 2026-08-24 - Open-source project management and issue tracking platform.
* [Twenty](https://github.com/twentyhq/twenty) ⭐ 55,490 | 🐛 176 | 🌐 TypeScript | 📅 2026-08-25 - Modern open-source CRM platform focused on extensibility and ownership.
* [Focalboard](https://github.com/mattermost/focalboard) ⭐ 26,425 | 🐛 784 | 🌐 TypeScript | 📅 2026-05-18 - Self-hosted project and task management tool inspired by Trello and Notion.
* [Erxes](https://github.com/erxes/erxes) ⭐ 4,072 | 🐛 639 | 🌐 TypeScript | 📅 2026-08-25 - Open-source growth marketing, sales, and customer engagement platform.

## Web Development

### Angular UI libraries

* [Angular Material](https://github.com/angular/components) ⭐ 25,036 | 🐛 1,377 | 🌐 TypeScript | 📅 2026-08-24 - A Material Design component library for Angular maintained by Google.
* [PrimeNG](https://github.com/primefaces/primeng) ⚠️ Archived - A rich Angular UI component library with high performance and extensive customization options.
* [Taiga UI](https://github.com/taiga-family/taiga-ui) ⭐ 4,042 | 🐛 117 | 🌐 TypeScript | 📅 2026-08-24 - A powerful open source Angular UI kit with a large set of components and tools.
* [TailAdmin Angular](https://github.com/TailAdmin/free-angular-tailwind-dashboard) ⭐ 120 | 🐛 3 | 🌐 HTML | 📅 2026-05-23 - An open-source Angular admin dashboard template built with Tailwind CSS.

### Code Editors

* [Visual Studio Code](https://github.com/microsoft/vscode) ⭐ 189,578 | 🐛 20,089 | 🌐 TypeScript | 📅 2026-08-25 - The most widely used open source code editor with a massive extension ecosystem.
* [Neovim](https://github.com/neovim/neovim) ⭐ 101,947 | 🐛 1,861 | 🌐 Vim Script | 📅 2026-08-25 - A highly popular, extensible Vim-based editor focused on performance and modern workflows.
* [Zed](https://github.com/zed-industries/zed) ⭐ 89,172 | 🐛 3,254 | 🌐 Rust | 📅 2026-08-25 - A high-performance collaborative editor gaining rapid adoption.
* [Helix](https://github.com/helix-editor/helix) ⭐ 45,922 | 🐛 1,623 | 🌐 Rust | 📅 2026-08-18 - A fast-growing modal editor with built-in LSP support and modern defaults.
* [VSCodium](https://github.com/VSCodium/vscodium) ⭐ 32,971 | 🐛 137 | 🌐 Shell | 📅 2026-08-12 - A fully open source distribution of VS Code without proprietary components.
* [Eclipse Theia](https://github.com/eclipse-theia/theia) ⭐ 21,653 | 🐛 1,503 | 🌐 TypeScript | 📅 2026-08-25 - A flexible open source IDE platform used in cloud and desktop environments.

### Design Tools

* [Excalidraw](https://github.com/excalidraw/excalidraw) ⭐ 130,442 | 🐛 3,377 | 🌐 TypeScript | 📅 2026-08-22 - Virtual whiteboard for sketching hand-drawn style diagrams with real-time collaboration and infinite canvas.
* [Open Design](https://github.com/nexu-io/open-design) ⭐ 91,185 | 🐛 850 | 🌐 TypeScript | 📅 2026-08-25 - Local-first AI design tool with 19 skills and 71 brand-grade design systems for generating web, mobile, and slide artifacts.
* [open-pencil](https://github.com/open-pencil/open-pencil) ⭐ 7,979 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-25 - AI-native Figma-compatible design editor with headless CLI, MCP server, and design-to-code export.

### Icons

* [Feather Icons](https://github.com/feathericons/feather) ⭐ 25,979 | 🐛 511 | 🌐 JavaScript | 📅 2025-03-11 - Minimal and clean open-source icons.
* [Simple Icons](https://github.com/simple-icons/simple-icons) ⭐ 25,715 | 🐛 940 | 🌐 JavaScript | 📅 2026-08-23 - Brand and logo icons in SVG format.
* [Heroicons](https://github.com/tailwindlabs/heroicons) ⭐ 23,759 | 🐛 4 | 🌐 JavaScript | 📅 2026-05-12 - Official Tailwind CSS icon set (outline & solid).
* [Tabler Icons](https://github.com/tabler/tabler-icons) ⭐ 21,491 | 🐛 108 | 🌐 JavaScript | 📅 2026-08-24 - Large, consistent and actively maintained icon set.
* [Ionicons](https://github.com/ionic-team/ionicons) ⭐ 18,157 | 🐛 86 | 🌐 TypeScript | 📅 2026-07-28 - Icon pack for Ionic and general use.
* [React Icons](https://github.com/react-icons/react-icons) ⭐ 12,621 | 🐛 240 | 🌐 TypeScript | 📅 2026-08-12 - Popular icon packs as React components.
* [css.gg](https://github.com/astrit/css.gg) ⭐ 10,036 | 🐛 45 | 🌐 JavaScript | 📅 2024-08-26 - Open-source CSS and SVG icon system.
* [Remix Icon](https://github.com/Remix-Design/RemixIcon) ⭐ 8,293 | 🐛 600 | 🌐 Less | 📅 2026-04-28 - System-style open-source icon library.
* [Bootstrap Icons](https://github.com/twbs/icons) ⭐ 8,107 | 🐛 482 | 🌐 TypeScript | 📅 2026-08-07 - Official Bootstrap icon library.
* [Lucide Animated](https://github.com/pqoqubbw/icons) ⭐ 7,988 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-22 - Beautifully crafted collection of animated React icons built with Motion and Lucide.
* [Boxicons](https://github.com/atisawd/boxicons) ⭐ 3,183 | 🐛 811 | 🌐 TypeScript | 📅 2026-02-16 - Simple and flexible icon library.

### React UI libraries

* [Ant Design](https://github.com/ant-design/ant-design) ⭐ 99,179 | 🐛 1,089 | 🌐 TypeScript | 📅 2026-08-25 - An enterprise-class design system with robust and consistent React components.
* [Material-UI (MUI)](https://github.com/mui/material-ui) ⭐ 98,923 | 🐛 1,493 | 🌐 JavaScript | 📅 2026-08-25 - A React component library based on Material Design, highly customizable and widely adopted.
* [Chakra UI](https://github.com/chakra-ui/chakra-ui) ⭐ 40,592 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-24 - A modular library focused on accessibility and great developer experience.
* [React Bootstrap](https://github.com/react-bootstrap/react-bootstrap) ⭐ 22,610 | 🐛 235 | 🌐 TypeScript | 📅 2026-08-23 - Bootstrap components rebuilt for React without jQuery dependency.
* [NativeBase](https://github.com/GeekyAnts/NativeBase) ⭐ 20,385 | 🐛 376 | 🌐 TypeScript | 📅 2026-01-31 - A utility-first component system for building consistent UIs across mobile and web.
* [Semantic UI React](https://github.com/Semantic-Org/Semantic-UI-React) ⭐ 13,212 | 🐛 244 | 🌐 JavaScript | 📅 2024-11-22 - The official React integration for Semantic UI with declarative components.
* [PrimeReact](https://github.com/primefaces/primereact) ⚠️ Archived - A comprehensive suite of rich, flexible, and design-agnostic React UI components.

### UI Components

* [shadcn/ui](https://github.com/shadcn-ui/ui) ⭐ 122,038 | 🐛 2,319 | 🌐 TypeScript | 📅 2026-08-24 - Copy-paste open-source UI components for React built on Tailwind CSS.
* [Headless UI](https://github.com/tailwindlabs/headlessui) ⭐ 28,720 | 🐛 109 | 🌐 TypeScript | 📅 2026-04-13 - Fully accessible unstyled UI primitives designed for Tailwind CSS.
* [uiverse](https://github.com/uiverse-io/galaxy) ⭐ 12,164 | 🐛 14 | 🌐 HTML | 📅 2024-09-02 - Community-driven open-source UI elements built with HTML and CSS.
* [Flowbite](https://github.com/themesberg/flowbite) ⭐ 9,324 | 🐛 257 | 🌐 HTML | 📅 2026-06-27 - Open-source UI component library based on Tailwind CSS with interactive elements.
* [LangUI](https://github.com/CommandCodeAI/langui) ⭐ 3,144 | 🐛 6 | 🌐 HTML | 📅 2024-07-10 - Open-source Tailwind CSS components for AI and GPT-style interfaces.
* [8bitcn](https://github.com/TheOrcDev/8bitcn-ui) ⭐ 2,005 | 🐛 16 | 🌐 TypeScript | 📅 2026-08-21 - Retro 8-bit styled open-source UI component library.
* [Dotmatrix](https://github.com/zzzzshawn/matrix) ⭐ 555 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-03 - Reusable dotmatrix-style loading animation components installable via shadcn registry or manual copy.
* [loading-ui](https://github.com/turbostarter/loading-ui) ⭐ 472 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-01 - Beautiful open-source loading states, skeletons, and animated placeholders built for modern React apps with Tailwind CSS.

### Vue UI Libraries

* [Vuetify](https://github.com/vuetifyjs/vuetify) ⭐ 41,033 | 🐛 386 | 🌐 TypeScript | 📅 2026-08-25 - Material Design component framework for Vue with a large ecosystem.
* [Quasar](https://github.com/quasarframework/quasar) ⭐ 27,204 | 🐛 291 | 🌐 JavaScript | 📅 2026-08-24 - Full-featured Vue framework for building SPAs, SSR, mobile and desktop apps.

## Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork this repository and create a new branch: `feat/project-name`
2. Add your entry to the appropriate section in `README.md` following the format below.
3. Push to the branch (`git push origin feat/project-name`)
4. Open a Pull Request with a title like `feat: Project Name` and a brief explanation of why it belongs.

For more information on contributing, please refer to our [Contributing Guidelines](CONTRIBUTING.md).

* ❤️ Thank you for contributing to the project! Your help is greatly appreciated.

<div align="center">

  <h3>Contributors</h3>

  <a href="https://github.com/hadez8877/awesome-opensource/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=hadez8877/awesome-opensource" />
  </a>

</div>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
