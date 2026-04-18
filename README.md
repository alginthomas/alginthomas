<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0d1117&height=160&section=header&text=algin%20thomas&fontSize=56&fontColor=00ADD8&fontAlignY=50&desc=backend%20%E2%80%A2%20data%20%E2%80%A2%20design%20%E2%80%A2%20agentic%20tooling&descAlignY=75&descSize=14&descColor=8b949e" width="100%"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=1200&color=00ADD8&center=true&vCenter=true&width=680&height=36&lines=%24+whoami;builds+in+Go%2C+thinks+in+Postgres%2C+designs+in+Figma.;ships+with+Claude+Code.;prompt+discipline+%3E+prompt+creativity." />

<br><br>

<a href="https://github.com/alginthomas"><img src="https://img.shields.io/badge/-@alginthomas-0d1117?style=flat-square&logo=github&logoColor=c9d1d9&labelColor=0d1117" /></a>
<a href="mailto:alginthomas.work@gmail.com"><img src="https://img.shields.io/badge/-alginthomas.work%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=c9d1d9&labelColor=0d1117" /></a>
<img src="https://komarev.com/ghpvc/?username=alginthomas&label=views&color=00ADD8&style=flat-square&labelColor=0d1117" />

</div>

<br>

```go
// ~/whoami — what you'd find if you greeted the terminal

package main

type Engineer struct {
    Focus      []string
    DailyTools []string
    Principles []string
}

var me = Engineer{
    Focus: []string{
        "backend systems in Go",
        "Postgres that outlives the code above it",
        "design systems wired from Figma to production",
        "agentic developer tooling with Claude Code",
    },
    DailyTools: []string{"Go", "Postgres", "TypeScript", "Figma", "Claude Code"},
    Principles: []string{
        "strong types at the edge, dumb code in the middle, honest SQL at the core",
        "a schema is a contract; a migration is a promise",
        "design tokens are code — treat them like it",
        "if a prompt isn't versioned, it's not engineering",
    },
}
```

<br>

## &nbsp;·&nbsp; stack

<table>
<tr>
  <td valign="top" width="50%">

### Backend &mdash; Go

```txt
net/http + chi     routing w/o ceremony
sqlc               typed queries, no ORM
pgx                connection pool, ctx-aware
slog               structured logging everywhere
golangci-lint      non-negotiable in CI
go test -race      the only acceptable test run
```

  </td>
  <td valign="top" width="50%">

### Data &mdash; Postgres

```txt
goose              schema-first migrations
EXPLAIN ANALYZE    before every index
jsonb              where it earns its keep
row-level security app-level authz is a smell
pgvector           embeddings, fast recall
logical replication  zero-downtime cutovers
```

  </td>
</tr>
<tr>
  <td valign="top" width="50%">

### Design &mdash; Figma

```txt
variables          single source of truth
auto-layout        components that respect reality
Code Connect       Figma ↔ prop parity
variants           mirror component state
dev mode           the handoff contract
tokens → CSS vars  no hand-translated hex
```

  </td>
  <td valign="top" width="50%">

### AI &mdash; Claude Code

```txt
claude code        pair programmer, daily driver
subagents          parallel work, bounded context
MCP servers        domain-specific tools, wired in
slash commands     repeatable workflows as code
hooks              guardrails, never afterthoughts
prompts as code    reviewed, versioned, tested
```

  </td>
</tr>
</table>

<br>

## &nbsp;·&nbsp; now

<table>
<tr>
<td width="50%" valign="top">

**shipping**

Postgres-backed dashboards with deep hierarchical drill-downs — rendered in React, backed by a Go API that does the heavy aggregation in SQL, not in application code.

</td>
<td width="50%" valign="top">

**refining**

A Figma → React pipeline where variables become typed design tokens, and Code Connect keeps the mapping honest. No more designer–engineer translation loss.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**exploring**

Custom MCP servers that teach Claude Code a codebase's grammar — domain models, schema conventions, review patterns — so it operates as a member of the team, not a tourist.

</td>
<td width="50%" valign="top">

**reading**

*Designing Data-Intensive Applications* — Kleppmann. Again. Every read surfaces a mistake I've already made in production.

</td>
</tr>
</table>

<br>

## &nbsp;·&nbsp; contribution graph

<div align="center">

<img src="https://raw.githubusercontent.com/alginthomas/alginthomas/output/pacman-contribution-graph.svg" alt="Pac-Man chasing through my contribution graph" />

<sub><i>regenerated every 12h via GitHub Actions</i></sub>

</div>

<br>

<div align="center">
  <sub>designed and shipped by <a href="https://github.com/alginthomas"><b>@alginthomas</b></a> &nbsp;·&nbsp; <code>v2026.04</code></sub>
</div>
