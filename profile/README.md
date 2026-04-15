<div align="center">

<br />

# Mdigitalcn

<div align="center">

[Mdigitalcn](https://github.com/mdigitalcn) [Website](https://mdigitalcn.dev) [NPM](https://www.npmjs.com/org/mdigitalcn)

</div>
</div>

Most UI libraries stop at primitives. You still wire up auth pages, dashboard layouts, settings flows, CRM views — all from scratch, every time.

Mdigitalcn gives you the full stack of UI. Components compose into widgets. Widgets compose into pages. Pages snap into layouts. Templates give you a running app in one command.

Everything is accessed through one entry point: the CLI.

## Start here

```bash
npm install -g @mdigitalcn/cli
```

```bash
# Scaffold a new project
mdigitalcn init

# Start from a full starter template
mdigitalcn init --name my-app --template vite/dashboard

# Add anything from the registry into an existing project
mdigitalcn add button login-form dashboard-page sidebar-layout auth
```

The CLI scaffolds projects, pulls from the registry, and wires up configs. You do not install packages manually — `mdigitalcn add` handles everything.

## How it composes

```
cli  ──  scaffold + registry gateway
          |
          templates   10 project starters (Vite · Next.js)
          pages       34 full pages (dashboard, auth, ecommerce, kanban)
          layouts     17 layout shells (sidebar, topnav, docs, wizard)
          modules     cross-cutting logic (auth provider, guard, session)
          widgets     47 composite widgets (auth, charts, CRM, HRM, stats)
          uikit       80+ base components (buttons, tables, modals, forms)
          utils       FP utilities and React hooks
```

## Packages

| Repository | What | |
|---|---|---|
| [`cli`](https://github.com/mdigitalcn/cli) | Rust CLI — scaffold projects, add from any registry | [![crates.io](https://img.shields.io/crates/v/mdigitalcn-cli?color=0070f3)](https://crates.io/crates/mdigitalcn-cli) |
| [`uikit`](https://github.com/mdigitalcn/uikit) | 80+ base components — buttons, tables, modals, pickers, forms, trees | [![npm](https://img.shields.io/npm/v/@mdigitalcn/uikit?color=0070f3)](https://www.npmjs.com/package/@mdigitalcn/uikit) |
| [`widgets`](https://github.com/mdigitalcn/widgets) | 47 composite widgets — auth, charts, CRM, HRM, ERP, marketing, stats | |
| [`pages`](https://github.com/mdigitalcn/pages) | 34 full pages — dashboards, settings, auth, ecommerce, messaging, kanban | |
| [`layouts`](https://github.com/mdigitalcn/layouts) | 17 layout shells — sidebar, topnav, docs, wizard, auth, landing | |
| [`modules`](https://github.com/mdigitalcn/modules) | Cross-cutting — auth provider, auth guard, session monitor | |
| [`utils`](https://github.com/mdigitalcn/utils) | FP utilities and React hooks — array, string, validation, promises | [![npm](https://img.shields.io/npm/v/@mdigitalcn/utils?color=0070f3)](https://www.npmjs.com/package/@mdigitalcn/utils) |
| [`templates`](https://github.com/mdigitalcn/templates) | 10 project starters — Vite and Next.js (SaaS, dashboard, blog, docs, commerce) | |
