# Zenth Status Server

**Zenth Status Server** is a real-time, open-source service monitoring platform designed as part of the Zenth Cloud ecosystem by Sky Genesis Enterprise. It provides both internal and public-facing insights into the health, availability, and performance of Zenth services and infrastructure.

## 📡 Features

- ✅ Public-facing status page (https://status.zenthcloud.com)
- ✅ Real-time health checks and uptime monitoring
- ✅ Internal metrics API and webhook integration
- ✅ Incident reporting and scheduled maintenance tracking
- ✅ Custom service groups and component hierarchy
- ✅ Compatible with Zenth API (`api-server`)
- ✅ Supports integration with Prometheus, Grafana, or custom agents
- ✅ Optional alert system (email, webhook, SIP message, etc.)

## 📦 Part of the Zenth Cloud Stack

Zenth Status Server provides visibility across the entire cloud platform:

- `api-server` – Pulls service states and metrics
- `mail-server`, `sip-server` – Individual service monitoring
- `dns-server`, `vpn-server`, `firewall-server` – Network health
- `panel-server` – Admin view for incident declaration
- External clients – Access public status of subscribed services

## 🛠️ Technology

- Web UI built with modern JavaScript (Svelte/React-based)
- API written in Go or Node.js
- Backed by lightweight database (SQLite/PostgreSQL)
- Optional push gateway for custom probe agents
- Easily deployable via Docker, Proxmox, or standalone

## 📖 Documentation

Setup, configuration, API endpoints, and customization guides are available in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

This project is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. Please see the `LICENSE` file for details.

---

For bug reports, contributions, or feature requests, visit the official repo: [github.com/zenthcloud](https://github.com/zenthcloud).
