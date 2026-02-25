<p align="center">
  <img src="banner.png" alt="Stratal" width="600" />
</p>

<h3 align="center">A modular framework for Cloudflare Workers</h3>

<p align="center">
  <a href="https://www.npmjs.com/package/stratal"><img src="https://img.shields.io/npm/v/stratal.svg" alt="npm version" /></a>
  <a href="https://github.com/strataljs/stratal/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/stratal.svg" alt="license" /></a>
  <a href="https://github.com/strataljs/stratal/actions/workflows/ci.yml"><img src="https://github.com/strataljs/stratal/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
</p>

---

## What is Stratal?

Stratal is a TypeScript framework for building [Cloudflare Workers](https://workers.cloudflare.com/) applications using a modular, dependency-injection-driven architecture. It brings familiar patterns from frameworks like NestJS to the edge.

## Features

- **Dependency Injection** — Built on [tsyringe](https://github.com/microsoft/tsyringe) with request-scoped and global containers
- **Modular Architecture** — Organize your app into modules with controllers, providers, and lifecycle hooks
- **Type-safe Routing** — [Hono](https://hono.dev)-based routing with automatic OpenAPI schema generation via Zod
- **Queue Consumers** — Declarative handlers for Cloudflare Queue messages
- **Cron Jobs** — Schedule recurring tasks with `@Job()` decorators
- **Guards & Middleware** — Protect routes and intercept requests
- **i18n** — Built-in internationalization support
- **Caching & Storage** — Abstractions for KV, R2, and cache API
- **Email** — Send emails via multiple providers

## Packages

| Package | Description |
|---------|-------------|
| [`stratal`](https://www.npmjs.com/package/stratal) | Core framework |
| [`@stratal/testing`](https://www.npmjs.com/package/@stratal/testing) | Test utilities, mocks, and factories |

## Links

- [Documentation](https://stratal.dev)
- [GitHub Repository](https://github.com/strataljs/stratal)
- [Contributing Guide](https://github.com/strataljs/stratal/blob/main/CONTRIBUTING.md)
- [Examples](https://github.com/strataljs/stratal/tree/main/examples)
