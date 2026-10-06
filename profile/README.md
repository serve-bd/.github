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
curl -fsSL https://serve.bd/cli.sh | sh
serve login https://serve.example.com
serve deploy
```

## What you get

- **Apps** from Git, a Docker image, a Dockerfile, a Compose file or any folder.
- **Databases:** PostgreSQL, MySQL, MariaDB, MongoDB, Redis, Valkey and ClickHouse, with scheduled backups to S3, read replicas and connection pooling.
- **One-click services** from a catalog of hundreds of open source apps.
- **Deploys** with zero downtime, health checks, rollbacks and pull request previews.
- **Domains and HTTPS** through nginx, Caddy or Traefik, with certificates that renew themselves, and Cloudflare Tunnels for servers without a public IP.
- **Access control:** a login wall for your team or invited guests, HTTP Basic Auth and IP rules.
- **Monitoring:** logs, metrics, uptime checks, alerts to Slack, Discord, email and more, and public status pages.
- **Many servers** joined over a private network, teams with roles, an API and a CLI.

## Repositories

| Repo | What it is |
| --- | --- |
| [serve](https://github.com/serve-bd/serve) | The dashboard, the worker and the CLI |
| [serve.bd](https://github.com/serve-bd/serve.bd) | The website and docs at [serve.bd](https://serve.bd) |
