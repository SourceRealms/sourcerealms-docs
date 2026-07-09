# Skills & Progression

Everyone has **five personal skills** that level up as you play. Skills are **yours** — they
follow you across nations. Open the panel with `/skills` (Java gets a GUI, Bedrock a chat
readout); check someone else's with `/skills <player>`.

Each skill levels up from XP earned by doing the matching activity, and unlocks **perks at levels
3, 6, and 9**, plus a **luxury item unlock at the max level** *(default 10)*.

## Only two skills can be active at once

You can only have **two of your five skills active** at a time, and **only active skills earn
XP** — the other three sit frozen until you swap. This forces nations to spread expertise between
their members rather than everyone maxing everything.

Choose your two with `/skills setactive <skill> <skill>`, or click a skill in the `/skills` GUI.
**The choice is permanent** — the only way to change an active skill is a **Skill Reset Token**.
Right-click the token (Java opens a small reset menu; Bedrock is asked in chat which skill to drop),
then pick the replacement with `/skills activate <skill>` or another GUI click. Switching a skill
off **never** wipes the levels, perks, or luxury access you already earned in it — it only pauses
further XP.

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
one **any** way — not by crafting, smithing, fishing it up, trading for it, or taking it out of a
loot chest. The one exception is a **gift from a player who has mastered the skill**: if a master
drops one for you, you can pick it up. Items you already legitimately own are never taken away.

- **Netherite** (ingots, blocks, scrap, and any netherite gear) → mastered **Mining**.
- **Shulker Boxes** (any colour) → mastered **Woodcutting**.
- **Enchanted Golden Apple** → mastered **Farming**.
- **Totem of Undying** → mastered **Combat**.
- **Anything enchanted with (or carrying a book with) Mending** → mastered **Enchanting**.

### Crafting a shulker box

Shulker boxes are made with this recipe:

```
Diamond      Purple Dye   Diamond
Purple Dye   Chest        Purple Dye
Emerald      Purple Dye   Emerald
```

### Crafting an Enchanted Golden Apple

Enchanted Golden Apples are made with this recipe:

```
Diamond      Gold Block   Diamond
Gold Block   Apple        Gold Block
Diamond      Gold Block   Diamond
```

Both recipes still require you to have **mastered** the gating skill (Woodcutting for shulker
boxes, Farming for enchanted golden apples) before they'll craft.

## How XP is earned (and what doesn't count)

- Only **survival-mode** actions grant XP.
- **Mining** & **Woodcutting**: breaking naturally-generated ore/logs. Blocks *you* placed give
  nothing.
- **Farming**: harvesting **fully-grown** crops.
- **Combat**: killing mobs and players (tougher enemies award more XP).
- **Enchanting**: enchanting items at a table.

In the `/skills` GUI, each skill has its own row: a coloured summary (level + XP bar) and its
milestones — unlocked perks show in the skill's colour, locked ones are white panes with the level
they require. Your two active skills are marked; the rest show as inactive.
