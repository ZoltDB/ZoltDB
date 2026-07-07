<p align="center">
  <a href="https://zoltdb.com">
    <img src="assets/zolt-logo-blue.svg" alt="Zolt" width="72" />
  </a>
</p>

<h1 align="center">Zolt</h1>

<p align="center">
  <strong>A modern database client built for speed, safety, and serious SQL work.</strong>
</p>

<p align="center">
  Native desktop app for macOS, Windows, and Linux. Built in Rust on GPUI.
  No Electron. No WebView. No browser engine in your database client.
</p>

<p align="center">
  <a href="https://zoltdb.com"><strong>Website</strong></a>
  ·
  <a href="https://github.com/ZoltDB/ZoltDB/releases/latest"><strong>Latest release</strong></a>
  ·
  <a href="https://github.com/ZoltDB/ZoltDB/issues"><strong>Issues</strong></a>
  ·
  <a href="https://zoltdb.com/download"><strong>Download</strong></a>
</p>

<p align="center">
  <a href="https://zoltdb.com">
    <img src="https://zoltdb.com/og-image.png" alt="Zolt database client preview" width="960" />
  </a>
</p>

<p align="center">
  <img alt="Status: pre-alpha" src="https://img.shields.io/badge/status-pre--alpha-5865f2" />
  <img alt="Rust native" src="https://img.shields.io/badge/Rust-native-f46623" />
  <img alt="GPUI" src="https://img.shields.io/badge/UI-GPUI-111827" />
  <img alt="Platforms" src="https://img.shields.io/badge/macOS%20%7C%20Windows%20%7C%20Linux-desktop-2563eb" />
  <img alt="AI" src="https://img.shields.io/badge/AI-BYOK-059669" />
</p>

## Why Zolt

Database work should feel instant, private, and hard to mess up.

Zolt is a new database client for developers and teams who want the polish of a
native desktop app, the speed of a GPU-rendered interface, and the safety rails
needed for real production data.

| You want | Zolt is built for |
| --- | --- |
| A client that feels fast on every desktop OS | Rust + GPUI, direct native rendering, no embedded browser |
| Big result sets without UI jank | Streaming result sets and a virtualized native grid |
| AI help without giving Zolt your keys | Bring your own provider, local model, CLI tool, or MCP server |
| Safer production changes | Risk signals, read-only modes, confirmations, transactions, and local audit history |
| Team sharing without leaking secrets | End-to-end encrypted shared connections and shared query docs |
| A cleaner TablePlus / Beekeeper / DBeaver alternative | Cross-platform design with database-management workflows first |

## What Zolt is aiming to ship

- Fast query workspace with explicit run modes, cancellation, params, and
  multi-result support.
- Native result grid designed for large datasets, keyboard workflows, and
  responsive scrolling.
- Schema browser with typed introspection for tables, columns, indexes,
  constraints, routines, triggers, grants, and ownership.
- Safe table editing with staged changes, review, commit, rollback, and
  dialect-aware SQL.
- Connection workflows for real setups: SSH, TLS, import, diagnostics, and
  environment labeling.
- BYOK AI for text-to-SQL, explain, optimize, and agent-style database work.
- Team edition foundations: encrypted sharing, RBAC, audit log, SSO, and SCIM.

## Engines

Zolt targets the databases most teams touch every week:

| SQL | NoSQL / cache |
| --- | --- |
| PostgreSQL | Redis |
| MySQL | MongoDB |
| SQLite | More after beta |

## Privacy and security posture

- Your database passwords belong in your OS keychain, not in plaintext config.
- Zolt does not need to proxy your queries, schemas, prompts, responses, or AI
  provider keys.
- AI is bring-your-own-key. Your provider bills you directly.
- Team sync is designed around opaque ciphertext: the server should not be able
  to read shared connection blobs or shared query documents.
- License validation is separate from telemetry. Zolt is built to avoid query
  and schema analytics.

## Current status

Zolt is in pre-alpha. Public builds, checksums, and update metadata are shipped
through GitHub Releases in this repository.

This repository is also the public place for:

- Bug reports
- Feature requests
- Beta feedback
- Release downloads

Open an issue here:
[github.com/ZoltDB/ZoltDB/issues](https://github.com/ZoltDB/ZoltDB/issues)

## Download

Latest release:
[github.com/ZoltDB/ZoltDB/releases/latest](https://github.com/ZoltDB/ZoltDB/releases/latest)

Product site:
[zoltdb.com](https://zoltdb.com)

## Repository note

This public repository currently hosts Zolt release downloads and public issue
tracking. The application source code is not published here.
