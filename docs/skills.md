# Skills & Progression

Everyone has **five personal skills** that level up as you play. Skills are **yours** — they
follow you across nations. Open the panel with `/skills` (Java gets a GUI, Bedrock a chat
readout); check someone else's with `/skills <player>`.

Each skill levels up from XP earned by doing the matching activity, and unlocks **perks at levels
3, 6, and 9**, plus a **luxury item unlock at the max level** *(default 10)*.

| Skill | Lv 3 | Lv 6 | Lv 9 | Mastery (max level) |
|---|---|---|---|---|
| **Mining** | 25% chance to double ore drops | Ores auto-smelt when mined | Haste while mining | Unlocks **Netherite** |
| **Woodcutting** | 25% chance to double log drops | Fell whole trees with an axe | Haste while chopping | Unlocks **Shulker Boxes** |
| **Farming** | 25% chance for extra crop yield | Crops auto-replant | Guaranteed +1 crop yield | Unlocks **Enchanted Golden Apples** |
| **Combat** | +2 melee damage | Heal on kill (lifesteal) | +4 melee damage | Unlocks the **Totem of Undying** |
| **Enchanting** | Refund +1 XP level | Refund +2 XP levels | Refund +3 XP levels + lapis | Unlocks **Mending** |

## Luxury gating: why can't I get that item?

Those five "luxury" items are **completely unobtainable** until you **master** the matching
skill — reach its max level. This isn't just a crafting block: until you're maxed, you can't get
one **any** way — not by crafting, smithing, fishing it up, trading for it, picking one up off the
ground, or taking it out of a loot chest. Items you already legitimately own are never taken away —
only new acquisition is blocked.

- **Netherite** (ingots, blocks, scrap, and any netherite gear) → mastered **Mining**.
- **Shulker Boxes** (any recipe, any colour) → mastered **Woodcutting**.
- **Enchanted Golden Apple** → mastered **Farming**.
- **Totem of Undying** → mastered **Combat**.
- **Anything enchanted with (or carrying a book with) Mending** → mastered **Enchanting**.

### Crafting a shulker box

Alongside the vanilla recipe (2 shulker shells + a chest), there's a server-specific alternate
recipe:

```
Diamond      Purple Dye   Diamond
Purple Dye   Chest        Purple Dye
Emerald      Purple Dye   Emerald
```

Either recipe produces a shulker box — and either one is blocked the same way until Woodcutting is
maxed.

## How XP is earned (and what doesn't count)

- Only **survival-mode** actions grant XP.
- **Mining** & **Woodcutting**: breaking naturally-generated ore/logs. Blocks *you* placed give
  nothing.
- **Farming**: harvesting **fully-grown** crops.
- **Combat**: killing mobs and players (tougher enemies award more XP).
- **Enchanting**: enchanting items at a table.

In the `/skills` GUI, each skill has its own row: a coloured summary (level + XP bar) and its
milestones — unlocked perks show in the skill's colour, locked ones are dark grey with the level
they require.
