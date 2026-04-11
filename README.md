# games-universe

- **Landing page:** **`index.html`** — short intro and hero art for **https://gamesuniverse.org**
- **Full app (dashboard):** **`dashboard.html`** — games, shop, inventory, missions, chat, staff, etc.

## Published site (source)

- **Branch:** `main` on GitHub  
- **Landing:** https://github.com/brendan00948/games-universe/blob/main/index.html  
- **Dashboard app:** https://github.com/brendan00948/games-universe/blob/main/dashboard.html  
- **Raw dashboard (copy/paste / host):** https://raw.githubusercontent.com/brendan00948/games-universe/main/dashboard.html  

The commit at the tip of `main` is the published version; see **Commits** on GitHub for the exact SHA.

### Hero image on the landing page

Add your collage as **`assets/landing-hero.png`** in the repo (same path on the live site). Until that file exists, the page falls back to **`assets/landing-hero.svg`**.

## Staff: Discord pull alerts

Configure in the **Staff Panel → Rarity & site → Discord — special pull alerts**:

- Webhook URL, enable/disable, optional server invite link  
- Optional **auto rules**: minimum rarity rank (from your rarity order list) and/or maximum listed drop chance %  
- Per-blook and per-rarity **Discord announce** toggles in the pack blook editor and rarity appearance editor  

Settings are stored in Firestore under **`siteConfig/settings`** (e.g. `discordAnnounceWebhookUrl`, `discordAnnounceEnabled`, `discordAnnounceMinRarityIdx`, `discordAnnounceMaxChancePct`).
