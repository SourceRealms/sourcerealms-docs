# Getting Started

When you first join, you're scattered to a random, unclaimed spot on the overworld surface (never
a cave, never inside anyone's territory) rather than a fixed spawn hub — so you'll want to get your
bearings before anything else.

## The three commands you need to know

| Command | What it does |
|---|---|
| **`/nation`** (aliases `/nations`, `/n`) | Java players **in a nation** get a clickable menu hub. Everyone else gets the help list. |
| **`/skills`** | Your personal progression panel — five skills that level up as you play. |
| **`/gold`** | Check your wallet balance and convert physical gold into currency. |

Everything else branches off `/nation ...` (nation management, claims, diplomacy, war), `/skills`
(progression), and `/gold` (money).

Not sure where to start? Run **`/help`** any time for a quick overview of Nations, Skills, World
Rules, RTP, Voting, and the Server Store, all in one menu.

## Getting around

- **`/rtp`** (alias `/wild`) — teleports you to a random, unclaimed, safe surface spot. Useful for
  finding a fresh place to settle. Has a short cooldown between uses.
- **`/map`** — opens the live web map showing every nation's territory, at
  [map.source-realms.com](https://map.source-realms.com).

## What to do first

1. **Decide: found your own nation, or join an existing one?**
     - Founding: `/nation create <name>` — see [Creating & Joining](nations/creating-joining.md).
     - Joining: ask an existing nation's leader/officer for `/nation invite <you>`, then run
       `/nation accept`.
2. **New nations start warlike by default** — you can declare and be drawn into war right away. If
   you just want to build peacefully, opt in to neutral status with `/nation neutral on`: you can't
   be attacked and can't attack, so you can ignore war entirely. See [Neutrality](war/neutrality.md).
3. **Claim some land**: stand in a chunk and run `/nation claim` (needs the *Claim Land*
   permission — officers have it by default). See [Claims & Territory](nations/claims-territory.md).
4. **Set your capital**: `/nation capital set <name>` gives your nation a named home point everyone
   can teleport back to with `/nation capital`.

From there, `/nation info` always shows your nation's current state — description, government,
ideology, capital, bank, claims, members, and whether you're neutral or warlike.
