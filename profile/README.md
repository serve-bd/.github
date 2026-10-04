<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/serve-bd/serve/main/docs/images/logo-dark.svg">
  <img src="https://raw.githubusercontent.com/serve-bd/serve/main/docs/images/logo-light.svg" alt="Serve" width="72" height="72">
</picture>

### Deploy apps, databases and services on your own servers.

Push to deploy, get a domain with HTTPS and manage it all from one dashboard. Open source.

[Website](https://serve.bd) · [Docs](https://serve.bd/docs/) · [Releases](https://github.com/serve-bd/serve/releases) · [CLI](https://serve.bd/docs/cli/)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/serve-bd/serve/main/docs/images/overview-dark.png">
  <img src="https://raw.githubusercontent.com/serve-bd/serve/main/docs/images/overview-light.png" alt="The Serve dashboard" width="100%">
</picture>

</div>

## Install

On a Linux server with 2 GB of RAM or more:

```bash
curl -fsSL https://serve.bd/install.sh | bash
```

Then deploy any folder from your computer with the `serve` CLI:

```bash
curl -fsSL https://raw.githubusercontent.com/serve-bd/serve/main/install-cli.sh | sh
serve login https://your-serve-dashboard
serve deploy
```

## What you get

- **Apps** from Git, a Docker image, a Dockerfile, a Compose file or any folder.
- **Databases:** PostgreSQL, MySQL, MariaDB, MongoDB, Redis, Valkey and ClickHouse, with backups.
- **One-click services** from a catalog of templates.
- **Deploys** with zero downtime, health checks, rollbacks and pull request previews.
- **Domains and HTTPS** with certificates that renew themselves.
- **Many servers**, teams, roles and an API.

## Repositories

| Repo | What it is |
| --- | --- |
| [serve](https://github.com/serve-bd/serve) | The dashboard, the worker and the CLI |
| [serve.bd](https://github.com/serve-bd/serve.bd) | The website and docs at [serve.bd](https://serve.bd) |
