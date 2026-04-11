# Changelog

All notable changes to this project are documented here. The app is a single file: `index.html`.

## Unreleased

- **Theme:** reverted mint/Blooket-blue experiments; restored the original dark neon site palette.
- **Golden Ticket:** staff-configurable blook (extra pack drop + ticket tier roll for entry value), hidden inventory section, **three** giveaways each with a **single** prize and live top-10 entry boards (`giveawayLeaderboards/{A|B|C}`). No auto winner draw.
- Pack unbox: smaller on-screen pack scale during open animation.
- Discord special pulls: embed uses blook art as **thumbnail only**; message body lists pull line, stars, rarity (title case), and chance.

## Earlier

- Staff Panel: **Discord — special pull alerts** (webhook URL, enable, optional invite, auto rules by rarity rank / max chance).
- Profile: unique blook count vs catalog total; top blooks by rarity; inventory UI tweaks.
- Lazy-load main games section until scroll; various performance and UI adjustments.

See [commit history](https://github.com/brendan00948/games-universe/commits/main/) on `main` for full detail.
