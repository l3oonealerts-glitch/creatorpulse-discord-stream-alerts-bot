# CreatorPulse — Multi-Platform Discord Alert Bot (TikTok, YouTube, Twitch)

[Whop Storefront](https://whop.com/discord-9c93/products) | [Discord Support Community](https://discord.gg/5sBvB5Ngm8) | [Buy Standard ($19.99)](https://whop.com/discord-9c93/creatorpulse-discord-stream-alerts-bot-standard-edition/) | [Buy Pro ($29.99)](https://whop.com/discord-9c93/creatorpulse-pro-multi-platform-alert-bot-tiktok-feed-engine/)

CreatorPulse is an enterprise-grade, self-hosted Discord notification bot suite built specifically for creators, streamers, and community servers. Monitor TikTok LIVE, YouTube, and Twitch simultaneously with ultra-low latency and zero recurring monthly fees.

---

## Architecture & System Highlights

- 100% One-Time Purchase: Uncompiled, clean Python source code ownership forever with zero recurring SaaS fees.
- True 1-Click Launch: Pre-configured start.bat setup wizard for Windows — automatically creates an isolated virtual environment (venv), installs dependencies, and boots the bot in under 60 seconds.
- Zero-Cost 24/7 Cloud Support: Ultra-lightweight memory footprint (~50MB RAM). 100% compatible with Discloud Free Tier ($0/mo), Docker, or Linux VPS.
- Dual-Language System: Instant toggle between English and Thai (/settings language) with clean, full-width responsive alerts.
- Dual Database Engine: Automatic local SQLite out-of-the-box or seamless remote PostgreSQL / Supabase cloud integration.
- Zero API Quota Overhead: Built-in high-speed YouTube XML parser alerts for Live streams, Premieres, and Uploads without consuming Google API quotas.
- Twitch Helix Integration: Automated OAuth2 token refresh protocol ensuring continuous uptime.

---

## Edition Comparison

| Feature | Standard Edition ($19.99) | Pro Edition ($29.99) |
|---|---|---|
| YouTube Alerts (Live, Premieres, Uploads) | Yes | Yes |
| Twitch Alerts (Live Streams & Game Info) | Yes | Yes |
| TikTok LIVE Detection (Webcast Polling) | Yes | Yes |
| TikTok Video Uploads Feed Engine | No | Yes (Isolated GitHub Action) |
| Database Storage Engine | SQLite / Postgres | SQLite / Supabase / Postgres |
| 1-Click Windows Setup (start.bat) | Yes | Yes |
| 24/7 Free Cloud Config (Discloud / Docker) | Yes | Yes |
| Step-by-Step Interactive Visual Manuals | Standard (TH/EN) | Standard + Oracle/Supabase (TH/EN) |
| Upgrade Policy | Base Tier | Pay difference ($10.00) |

---

## Quick Start Overview

### Method 1: Windows PC (1-Click Local Launch)
1. Extract the downloaded product archive.
2. Double-click start.bat.
3. The setup wizard launches the visual interactive manual in your browser, prompts for your Discord Bot Token on first boot, installs packages in an isolated virtual environment, and starts the bot.

### Method 2: 24/7 Free Cloud (Discloud)
1. Insert your Discord Bot Token into .env.
2. Upload the archive to your Discloud Dashboard.
3. The bot stays online 24/7 consuming only ~50MB RAM without keeping your personal computer running.

---

## Commercial Purchase & Instant Delivery

Instant digital download is available through our verified storefronts:

- Standard Edition ($19.99): [Purchase Standard Edition on Whop](https://whop.com/discord-9c93/creatorpulse-discord-stream-alerts-bot-standard-edition/)
- Pro Edition ($29.99): [Purchase Pro Edition on Whop](https://whop.com/discord-9c93/creatorpulse-pro-multi-platform-alert-bot-tiktok-feed-engine/)
- All Products Catalog: [Browse Full Whop Catalog](https://whop.com/discord-9c93/products)
- BuiltByBit Marketplace: [BuiltByBit Store](https://builtbybit.com) (Currently awaiting approval)
- Official Community Discord: https://discord.gg/5sBvB5Ngm8
- Technical Diagnostics & Business Contact: l3oone.alerts@gmail.com

---

## Repository Files Overview

This public repository serves as the official specification and documentation hub for CreatorPulse:

- .env.example — Configuration template showing required credentials.
- requirements.txt — Production Python dependencies.
- discloud.config — Standard deployment configuration for 24/7 Discloud free hosting.
- README.md — Complete architectural specification and deployment guidelines.

---

## Terms of Purchase & Disclaimer

1. Self-Hosted Delivery: This product is distributed as uncompiled, self-hosted Python source code and deployment templates. It is not a hosted multi-tenant SaaS service.
2. Independent Development: CreatorPulse is independently developed by l3oone. It is not affiliated with, endorsed by, or sponsored by Discord, YouTube/Google, Twitch Interactive, or TikTok/ByteDance.
3. Single-IP Safety Quotas: To prevent platform rate-limiting, the system checks channels on a safe 3-minute polling interval. Recommended quotas per bot instance: up to 10 YouTube channels, 10 Twitch streams, and 5 TikTok creators.
4. Support & Maintenance: Technical assistance is provided directly via ticket support on the official Discord community.

CreatorPulse • Crafted by l3oone
