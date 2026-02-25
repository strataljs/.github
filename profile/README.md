<p align="center">
  <img src="banner.png" alt="Stratal" width="600" />
</p>

<h3 align="center">A modular Cloudflare Workers framework with automatic OpenAPI documentation, dependency injection, queue consumers, cron jobs, and type-safe configuration.</h3>

<p align="center">
  <a href="https://www.npmjs.com/package/stratal"><img src="https://img.shields.io/npm/v/stratal.svg" alt="npm version" /></a>
  <a href="https://github.com/strataljs/stratal/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/stratal.svg" alt="license" /></a>
  <a href="https://github.com/strataljs/stratal/actions/workflows/ci.yml"><img src="https://github.com/strataljs/stratal/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
</p>

---

## What is Stratal?

Stratal is a TypeScript framework for building [Cloudflare Workers](https://workers.cloudflare.com/) applications with automatic OpenAPI documentation, modular architecture, and dependency injection. Define your Zod schemas once and get a full OpenAPI 3.0 spec with interactive docs — while using familiar patterns from frameworks like NestJS at the edge.

## Features

- **OpenAPI Documentation** — Define Zod schemas once and get a full OpenAPI 3.0 spec with Scalar docs UI, auto-derived HTTP methods and status codes, error schemas, and security definitions
- **Dependency Injection** — Two-tier DI container (global + request-scoped) powered by tsyringe with Symbol-based tokens
- **Modular Architecture** — NestJS-style `@Module()` decorator pattern with lifecycle hooks, dynamic modules, and middleware configuration
- **Hono Routing** — Convention-based RESTful controllers with `@Controller` and `@Route` decorators, auto-mapped to HTTP methods
- **Queue Consumers** — Typed Cloudflare Queue consumers with message-type filtering
- **Cron Jobs** — Scheduled tasks via Cloudflare Workers cron triggers
- **Storage** — S3-compatible file storage with presigned URLs and TUS upload support
- **Email** — Resend and SMTP providers with React Email template support
- **Internationalization** — Type-safe i18n with locale detection from request headers
- **Guards & Middleware** — Route protection with guard decorators and per-module middleware configuration

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
