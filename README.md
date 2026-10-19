<p align="center">
  <img src="assets/orbit-hero.png" alt="Orbit — Your servers. Your little universe. Our astronaut waves hello." width="1200">
</p>

<p align="center">
  <strong>A home for your applications, databases and servers.</strong><br>
  Orbit turns your own Linux servers into a cloud you can manage from one friendly console.
</p>

<p align="center">
  <a href="https://orbit.getcortexlabs.com">Documentation</a> ·
  <a href="https://orbit.getcortexlabs.com/guide/install">Get started</a> ·
  <a href="https://github.com/getcortexlabs/orbit-releases/releases/latest">Latest release</a> ·
  <a href="https://orbit.getcortexlabs.com/pt-BR/">Português</a>
</p>

---

## A little less infrastructure. A little more building.

Connect a repository, deploy an application and give it an HTTPS address. Add a database beside it. Follow builds, logs and resource usage without leaving the console. Start with one server and connect more as you grow.

| Bring your code | Make room for your data | Run it on your terms |
| --- | --- | --- |
| GitHub, GitLab and Bitbucket repositories, Dockerfiles and container images. | Managed PostgreSQL, MySQL, MongoDB and Redis, with application connections and backups to external storage. | Your servers, across providers. Resource previews, instance placement and a managed private network for your fleet. |

- **From commit to HTTPS.** Automatic builds, custom domains, TLS certificates, health checks and deployment rollback.
- **A place to try things.** Production and staging environments, GitHub pull request previews, workers and scheduled jobs.
- **See what is happening.** Live operation progress, logs, metrics and failures explained with their evidence.
- **Grow deliberately.** Spread application instances across compatible servers and check capacity before applying changes. See [server setup and availability](https://orbit.getcortexlabs.com/guide/servers).
- **Keep a way back.** Database backups, restore workflows and signed updates with preflight checks and recovery instructions.

The console speaks **English and Brazilian Portuguese**, with light and dark themes. The astronaut comes along for the ride.

## Get into Orbit

Start with a clean Linux server and run:

```sh
curl -fsSL https://github.com/getcortexlabs/orbit-releases/releases/latest/download/install.sh | sudo sh
```

The installer checks the machine, downloads the matching binary, verifies its checksum and sets up the runtime. When it finishes, it prints your console address and a one-time token to create the administrator.

**Before you start:** use a supported Ubuntu or Debian release, an x86_64 or ARM64 CPU, at least **2 vCPUs, 2 GB RAM and 20 GB free disk**, and root access. Give builds more memory when they need it. Check the [supported systems, ports and installation guide](https://orbit.getcortexlabs.com/guide/install#requirements) for the complete requirements.

1. Open your console and create the administrator.
2. Connect a Git provider or choose a container image.
3. Deploy your first application and open its HTTPS address.
4. Add a database and [configure external backups](https://orbit.getcortexlabs.com/guide/backups).

Orbit runs on your infrastructure. Under the console, K3s, BuildKit, Traefik and cert-manager handle scheduling, builds, routing and certificates.

## Downloads and updates

This is Orbit's **public distribution repository**: installers, release binaries and release notes. Application source code is not hosted here.

| Download | What it contains |
| --- | --- |
| [Linux x86_64 / amd64](https://github.com/getcortexlabs/orbit-releases/releases/latest/download/orbit-linux-amd64.tar.gz) | Orbit, the embedded console, the agent and the systemd service. |
| [Linux ARM64](https://github.com/getcortexlabs/orbit-releases/releases/latest/download/orbit-linux-arm64.tar.gz) | The same package for ARM64 servers. |
| [Installer](https://github.com/getcortexlabs/orbit-releases/releases/latest/download/install.sh) | Detects the server architecture and installs Orbit. |
| [Checksums](https://github.com/getcortexlabs/orbit-releases/releases/latest/download/SHA256SUMS) · [Signature](https://github.com/getcortexlabs/orbit-releases/releases/latest/download/SHA256SUMS.sig) | SHA-256 checksums and their Ed25519 signature. |

Already running Orbit? Open **Settings → Orbit updates** to review the release and its preflight checks. Console updates verify the signature against Orbit's pinned release key and back up Orbit's metadata before applying the update. The shell installer verifies archive checksums. Read the [update and recovery guide](https://orbit.getcortexlabs.com/guide/updates) before updating an existing installation.

Every version has its own [release notes and downloads](https://github.com/getcortexlabs/orbit-releases/releases).

## Find your way around

- [Your first installation](https://orbit.getcortexlabs.com/guide/install)
- [Applications and deployments](https://orbit.getcortexlabs.com/guide/applications)
- [Databases](https://orbit.getcortexlabs.com/guide/databases)
- [Servers and your fleet](https://orbit.getcortexlabs.com/guide/servers)
- [Backups and recovery](https://orbit.getcortexlabs.com/guide/backups)
- [Operating Orbit](https://orbit.getcortexlabs.com/guide/operating)

<p align="center">
  Made by <a href="https://github.com/getcortexlabs">Cortex Labs</a>.<br>
  <sub>Your servers. Your cloud. A friendly face in mission control.</sub>
</p>
