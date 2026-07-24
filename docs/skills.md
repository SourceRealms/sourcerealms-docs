# Skills & Progression

Everyone has **five personal skills** that level up as you play. Skills are **yours** — they
follow you across nations. Open the panel with `/skills` (Java gets a GUI, Bedrock a chat
readout); check someone else's with `/skills <player>`.

Each skill levels up from XP earned by doing the matching activity, and unlocks **perks at levels
3, 6, and 9**, plus a **luxury item unlock at the max level** *(default 10)*.

## Only two skills can be active at once

You can only have **two of your five skills active** at a time, and **only active skills earn
XP**. This forces nations to spread expertise between their members rather than everyone maxing
everything.

Choose your two with `/skills setactive <skill> <skill>`, or click a skill in the `/skills` GUI.
**Choose carefully — this choice is permanent.**

| Skill | Lv 3 | Lv 6 | Lv 9 | Mastery (max level) |
|---|---|---|---|---|
| **Mining** | 25% chance to double ore drops | Ores auto-smelt when mined | Haste while mining | Unlocks **Netherite** |
| **Woodcutting** | 25% chance to double log drops | Fell whole trees with an axe | Haste while chopping | Unlocks **Shulker Boxes** |
| **Farming** | 25% chance for extra crop yield | Crops auto-replant | Guaranteed +1 crop yield | Unlocks **Enchanted Golden Apples** |
| **Combat** | 30% less knockback taken | Heal on kill (lifesteal) | 20% less damage taken | Unlocks the **Totem of Undying** |
| **Enchanting** | -1 level cost to enchant | -2 level cost to enchant | Anvil cost reduced by 40% (repairing and combining) | Unlocks **Mending** |

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

Only **survival-mode** actions grant XP, and only for your **two active skills** — everything
below is a no-op while a skill is inactive.

**Mining** — breaking naturally-generated ore/stone. Blocks *you* placed give nothing.

| Block | XP |
|---|---|
| Ancient Debris | 15 |
| Diamond Ore, Emerald Ore | 8 |
| Iron, Gold, Nether Gold, Redstone, Lapis Ore | 4 |
| Coal, Copper, Nether Quartz Ore | 3 |
| Stone, Deepslate, Netherrack, Granite/Diorite/Andesite, Tuff, Cobblestone, Blackstone, End Stone, Basalt, Calcite | 0.5 |

**Woodcutting** — breaking naturally-generated logs. Placed logs give nothing.

- Any log: **3 XP** per block (including each extra log felled by the Tree Feller perk).

**Farming** — harvesting crops.

- Wheat, Carrots, Potatoes, Beetroot, Nether Wart (must be **fully grown**): **3 XP**
- Pumpkin, Melon: **2 XP**

**Combat** — killing mobs or players.

| Kill | XP |
|---|---|
| Player (PvP) | 15 |
| Ender Dragon, Wither | 100 |
| Warden, Elder Guardian, Ravager | 20 |
| Blaze, Witch, Enderman, Piglin Brute, Evoker, Vindicator, Hoglin, Zoglin, Guardian | 6 |
| Any other hostile mob | 4 |
| Passive mobs | 0 |

**Enchanting** — every enchant you apply at a table gives **4× its displayed level cost** in XP
(e.g. a cost-30 enchant gives 120 XP).

In the `/skills` GUI, each skill has its own row: a coloured summary (level + XP bar) and its
milestones — unlocked perks show in the skill's colour, locked ones are white panes with the level
they require. Your two active skills are marked; the rest show as inactive.

## It's a slow grind, on purpose

Skills are meant to be a **long-term** goal, not something maxed in a day or two of casual play.
The XP curve gets steeper every level, and the higher-value actions (rare ores, tough kills,
expensive enchants) are the ones actually worth pursuing if you want to level efficiently.
