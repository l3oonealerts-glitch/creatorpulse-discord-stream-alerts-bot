# CreatorPulse — Multi-Platform Discord Alert Bot (TikTok, YouTube, Twitch)

[Whop Storefront](https://whop.com/discord-9c93/products) | [Discord Support Community](https://discord.gg/5sBvB5Ngm8) | [Buy Standard ($19.99)](https://whop.com/discord-9c93/creatorpulse-discord-stream-alerts-bot-standard-edition/) | [Buy Pro ($29.99)](https://whop.com/discord-9c93/creatorpulse-pro-multi-platform-alert-bot-tiktok-feed-engine/)

CreatorPulse is an enterprise-grade, self-hosted Discord notification bot suite built specifically for creators, streamers, and community servers. Monitor TikTok LIVE, YouTube, and Twitch simultaneously with ultra-low latency and zero recurring monthly fees.

---

## Architectural Philosophy & Highlights

- 100% One-Time Purchase: Full uncompiled, clean Python source code ownership forever with zero recurring SaaS renewal fees.
- Zero-Cost 24/7 Cloud Support: Ultra-lightweight core memory footprint (~50MB RAM). 100% compatible with Discloud Free Tier ($0/mo), Docker, or Linux VPS.
- Dual-Language System: Instant toggle between English and Thai (/settings language) with clean, full-width responsive alerts.
- Zero API Quota Overhead: Built-in high-speed YouTube XML parser alerts for Live streams, Premieres, and Uploads without consuming Google API quotas.
- Twitch Helix Integration: Automated OAuth2 token refresh protocol ensuring continuous uptime.
- Decoupled Architecture (Pro Edition): The resource-heavy TikTok video scraper is isolated into an automated, serverless GitHub Actions worker, keeping your main bot ultra-light (~50MB) and safe from single-IP restrictions.

---

## Edition Comparison & Technical Matrix

| Technical Specification | Standard Edition ($19.99) | Pro Edition ($29.99) |
|---|---|---|
| YouTube Alerts (Live, Premieres, Uploads) | Yes | Yes |
| Twitch Alerts (Live Streams & Game Info) | Yes | Yes |
| TikTok LIVE Detection (Webcast Polling) | Yes | Yes |
| TikTok Uploaded Videos Feed Engine | Not Included | Yes (Decoupled Cloud Worker) |
| Database Storage Engine | SQLite / Postgres | SQLite / Supabase / Postgres |
| Core Bot 1-Click Launch (start.bat) | Yes (100% Plug & Play) | Yes (Core Bot Only) |
| TikTok Video Engine Setup Required | None | Free 3-Step GitHub Actions Workflow |
| Database Setup Required | Zero Config (Auto SQLite) | Zero Config (Auto SQLite) or Optional Cloud DB |
| 24/7 Free Cloud Support (Discloud / Docker) | Yes | Yes |
| Interactive Visual Manuals (HTML) | Standard (TH/EN) | Standard + Oracle/Supabase (TH/EN) |
| Upgrade Policy | Base Tier | Pay Difference ($10.00) |

---

## Transparent Deployment Workflows

### Standard Edition: True 1-Click Launch
Designed as a turnkey, single-folder solution requiring zero programming knowledge:
1. Extract the downloaded product archive.
2. Double-click start.bat on Windows (or upload to Discloud Free Tier for 24/7 uptime).
3. The setup wizard automatically launches the visual interactive manual in your browser, prompts for your Discord Bot Token on first boot, installs packages in an isolated virtual environment, and starts the bot with automatic SQLite storage.

### Pro Edition: Modular Two-Tier Architecture
Designed for creators who need both live stream alerts and uploaded TikTok clips without overloading their server:
1. Core Bot Launch: Open the bot/ directory and run start.bat (or deploy to Discloud/Docker). The core bot begins monitoring TikTok LIVE, YouTube, and Twitch immediately.
2. TikTok Video Feed Engine: Push the lightweight feed-worker/ directory to your personal GitHub repository, specify your creators in the TIKTOK_USERS variable, and link the generated private RSS feed into Discord using /tiktok feed. Runs 100% free on GitHub Actions cloud infrastructure.
3. Optional Cloud Scaling: Follow the included visual manual (ADVANCED_SETUP_ORACLE_SUPABASE.html) to link managed Supabase PostgreSQL or deploy on a free Oracle Cloud Linux VPS.

---

## Repository Files Overview

This public repository serves as the official specification and documentation hub for CreatorPulse:

- .env.example — Configuration template showing required credentials.
- requirements.txt — Production Python dependencies.
- discloud.config — Standard deployment configuration for 24/7 Discloud free hosting.
- README.md — Complete architectural specification and deployment guidelines.

---

## Commercial Purchase & Instant Delivery

Instant digital download is available through our verified storefronts:

- Standard Edition ($19.99): [Purchase Standard Edition on Whop](https://whop.com/discord-9c93/creatorpulse-discord-stream-alerts-bot-standard-edition/)
- Pro Edition ($29.99): [Purchase Pro Edition on Whop](https://whop.com/discord-9c93/creatorpulse-pro-multi-platform-alert-bot-tiktok-feed-engine/)
- All Products Catalog: [Browse Full Whop Catalog](https://whop.com/discord-9c93/products)
- Official Community Discord: https://discord.gg/5sBvB5Ngm8
- Technical Diagnostics & Business Contact: l3oone.alerts@gmail.com

---

## Terms of Purchase & Transparency Notice

1. Self-Hosted Delivery: This product is distributed as uncompiled, self-hosted Python source code and deployment templates. It is not a hosted multi-tenant SaaS service.
2. Independent Development: CreatorPulse is independently developed by l3oone. It is not affiliated with, endorsed by, or sponsored by Discord, YouTube/Google, Twitch Interactive, or TikTok/ByteDance.
3. Single-IP Safety Quotas: To prevent platform rate-limiting, the system checks channels on a safe 3-minute polling interval. Recommended quotas per bot instance: up to 10 YouTube channels, 10 Twitch streams, and 5 TikTok creators.
4. Support & Maintenance: Technical assistance is provided directly via ticket support on the official Discord community.

CreatorPulse • Crafted by l3oone
