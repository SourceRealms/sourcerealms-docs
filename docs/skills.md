# Skills & Progression

Everyone has **seven personal skills** that level up as you play. Skills are **yours** — they
follow you across nations. Open the panel with `/skills` (Java gets a GUI, Bedrock a chat
readout); check someone else's with `/skills <player>`.

Each skill levels up from XP earned by doing the matching activity. **Every level from 2 up to the
max grants something** — not just a handful of milestones — plus a **luxury item unlock at the max
level** *(default 10)*.

## Only two skills can be active at once

You can only have **two of your seven skills active** at a time, and **only active skills earn XP
or grant their perks** — swap a skill out and its perks pause (your level and progress are kept,
and come right back if you reactivate it later). This forces nations to spread expertise between
their members rather than everyone maxing everything.

Choose your two with `/skills setactive <skill> <skill>`, or click a skill in the `/skills` GUI.
**Choose carefully — this choice is permanent.**

## Perks by level

A few perks are described as "a taste of" a later one — that earlier value is replaced, not added
to, once you reach the level it's building toward. Anything else stacks or stands on its own.

**Mining** → unlocks **Netherite** at mastery

| Lv | Perk |
|---|---|
| 2 | 10% chance to double ore drops (taste of Lv 3) |
| 3 | 25% chance to double ore drops |
| 4 | -15% pickaxe durability loss |
| 5 | +1 bonus XP orb per ore |
| 6 | Ores auto-smelt when mined |
| 7 | -50% fall damage while Mining is active |
| 8 | 10% chance a placed torch isn't consumed |
| 9 | Haste while mining |

**Woodcutting** → unlocks **Shulker Boxes** at mastery

| Lv | Perk |
|---|---|
| 2 | 10% chance to double log drops (taste of Lv 3) |
| 3 | 25% chance to double log drops |
| 4 | -15% axe durability loss |
| 5 | 10% chance a chopped log flies straight to your inventory |
| 6 | Fell whole trees with an axe |
| 7 | +10% axe attack speed while one's held (taste of Lv 9) |
| 8 | 5% chance of one extra log, independent of Lv 3's roll |
| 9 | +20% axe attack speed while one's held |

**Farming** → unlocks **Enchanted Golden Apples** at mastery

| Lv | Perk |
|---|---|
| 2 | 5% chance of a bonus crop yield (taste of Lv 9) |
| 3 | +25% hunger/saturation from farmed food |
| 4 | 15% chance bonemeal isn't consumed |
| 5 | +1 bonus XP orb per harvest |
| 6 | Crops auto-replant (doesn't apply to Pumpkin/Melon) |
| 7 | 10% chance a hand-replanted crop instantly grows a stage |
| 8 | 5% chance eating a farmed food clears a negative effect |
| 9 | Guaranteed +1 crop yield |

**Combat** → unlocks the **Totem of Undying** at mastery

| Lv | Perk |
|---|---|
| 2 | 5% less knockback taken (taste of Lv 3) |
| 3 | 30% less knockback taken |
| 4 | 5% chance to fully negate knockback |
| 5 | -50% shield durability loss while blocking |
| 6 | Heal on kill (lifesteal) |
| 7 | More healing on kill (replaces Lv 6's amount) |
| 8 | 5% chance to fully negate a melee hit |
| 9 | 20% less damage taken |

**Enchanting** → unlocks **Mending** at mastery

| Lv | Perk |
|---|---|
| 2 | 10% chance to refund the lapis spent |
| 3 | -1 level cost to enchant |
| 4 | 5% chance of double Enchanting XP |
| 5 | Anvil use now grants Enchanting XP (previously none) |
| 6 | -2 level cost to enchant |
| 7 | -10% anvil level cost (taste of Lv 9) |
| 8 | 5% chance of 1 extra level off an anvil operation |
| 9 | Anvil cost reduced by 40% (repairing and combining) |

**Fishing** → unlocks the **Trident** at mastery

| Lv | Perk |
|---|---|
| 2 | 5% chance of a bonus catch (taste of Lv 3) |
| 3 | 25% chance of a bonus catch |
| 4 | -10% bite time (taste of Lv 9) |
| 5 | +1 bonus XP orb per catch |
| 6 | Junk catches re-rolled toward fish/treasure |
| 7 | 5% chance the rod takes no durability damage |
| 8 | +10% extra bonus-catch chance while it's raining |
| 9 | Faster bite time, plus a rare chance at a [legendary catch](#legendary-catches) |

**Alchemy** → unlocks **Strength II Potions** at mastery

| Lv | Perk |
|---|---|
| 2 | 5% chance a brew yields an extra potion |
| 3 | -1 brewing-stand fuel cost |
| 4 | -10% brewing time (taste of Lv 9) |
| 5 | +5% duration on potions you drink directly |
| 6 | Splash potions +15% effect duration |
| 7 | Splash potions +5% more (stacks with Lv 6) |
| 8 | 5% chance a drunk potion isn't consumed |
| 9 | -40% brewing time |

## Luxury gating: why can't I get that item?

Those seven "luxury" items are **completely unobtainable** until you **master** the matching
skill — reach its max level **and** currently have that skill active. This isn't just a crafting
block: until then, you can't get one **any** way — not by crafting, smithing, fishing it up,
trading for it, or taking it out of a loot chest. The one exception is a **gift from a player who
has mastered the skill**: if a master drops one for you, you can pick it up. Items you already
legitimately own are never taken away — but if you swap a mastered skill out, you won't be able to
obtain a *new* one of its luxury until you swap it back in.

- **Netherite** (ingots, blocks, scrap, and any netherite gear) → mastered **Mining**.
- **Shulker Boxes** (any colour) → mastered **Woodcutting**.
- **Enchanted Golden Apple** → mastered **Farming**.
- **Totem of Undying** → mastered **Combat**.
- **Anything enchanted with (or carrying a book with) Mending** → mastered **Enchanting**.
- **Trident** → mastered **Fishing**.
- **Strength II Potions** (regular, splash, or lingering) → mastered **Alchemy**. A master's splash
  potions still buff whoever they hit, even a non-master ally — the gate only blocks *holding or
  drinking* one directly, not being splashed by a master's.

### Crafting a shulker box

Shulker boxes are made with this recipe:

```
Diamond           Phantom Membrane   Diamond
Phantom Membrane  Chest              Phantom Membrane
Emerald           Phantom Membrane   Emerald
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

- Wheat, Carrots, Potatoes, Beetroot, Nether Wart, Cocoa (must be **fully grown**): **3 XP**
- Pumpkin, Melon: **2 XP**
- Sugar Cane: **2 XP** (cane you planted yourself gives nothing — no wait time otherwise, unlike
  other crops)

Cocoa is harvested the same way as wheat/carrots — break the pod, then replant beans on the log —
not by right-clicking it.

At level 3, eating **Bread, Cookie, Carrot, Golden Carrot, Potato, Baked Potato, Beetroot,
Beetroot Soup, Pumpkin Pie, Melon Slice, Sweet Berries, Glow Berries, or Mushroom Stew** restores
25% more hunger and saturation than normal.

**Combat** — killing mobs or players. (The Ender Dragon isn't listed — it only exists in the End,
which is disabled server-wide, see [World Rules](world-rules.md).)

| Kill | XP |
|---|---|
| Player (PvP) | 15 |
| Wither | 100 |
| Warden, Elder Guardian, Ravager | 20 |
| Blaze, Witch, Enderman, Piglin Brute, Evoker, Vindicator, Hoglin, Zoglin, Guardian | 6 |
| Any other hostile mob | 4 |
| Passive mobs | 0 |

Killing the **same player** more than **3 times within 10 minutes** stops earning Combat XP (and
lifesteal) for further kills of them specifically — it resets once that long passes without killing
them again. This only limits repeat kills of one specific person; fighting different opponents is
unaffected. It exists so two players can't just repeatedly kill each other to farm XP.

**Enchanting** — every enchant you apply at a table gives **4× its displayed level cost** in XP
(e.g. a cost-30 enchant gives 120 XP).

**Fishing** — landing a catch.

| Catch | XP |
|---|---|
| Treasure (bow, enchanted book, name tag, saddle, nautilus shell) | 8 |
| Fish (cod, salmon, pufferfish, tropical fish) | 3 |
| Junk (string, bones, leather, sticks, etc.) | 1 |

### Legendary catches

Once Fishing is active at **level 9**, every catch has a small chance (1%) to instead be one of
three curated legendary weapons — a separate, repeatable reward from the one-time Trident unlock at
mastery:

- **Ocean's Wrath** (netherite sword) — Sharpness VIII, Fire Aspect III
- **Storm Breaker** (netherite axe) — Sharpness VIII, Sweeping Edge III, Knockback III
- **Athena's Spear** (netherite spear) — Sharpness VIII, Looting IV

Each pushes at least one enchant past its normal vanilla cap (Sharpness maxes at V, Fire Aspect and
Knockback at II, Looting at III) — unmistakable at a glance. The axe's Sweeping Edge is a second
tell, since vanilla doesn't allow that enchant on an axe at all. None of this is producible through
any normal enchanting table or anvil path. The spear still gets a spear's usual Lunge dash — that's
not a legendary-only bonus, every spear can do it.
Being netherite would normally require mastering Mining first, but a legendary catch bypasses that
gate entirely — it's exempt regardless of your Mining level, the same way a live gift from a master
is. The catch is a genuine power spike, but a temporary one: it comes with only **10% of its normal
durability**, and it can never be repaired, renamed, or combined at an anvil — once it wears out,
it's gone for good.

**Alchemy** — completing a brew at a brewing stand. (Lingering potions need Dragon's Breath, which
only comes from the End — disabled server-wide, see [World Rules](world-rules.md) — so they aren't a
route to XP here.)

| Potion | XP |
|---|---|
| Tier-2 potion (e.g. Strength II, Poison II) | 5 |
| Any other real potion | 2 |

In the `/skills` GUI, each skill has its own row: a coloured summary (level + XP bar), two "Perks"
panes listing levels 2-5 and 6-9 (hover to see which ones you've unlocked), and mastery on the end.
Your two active skills are marked; the rest show as inactive. With seven skills to show, the panel
is two pages — use the Next/Back arrows at the bottom.

## It's a slow grind, on purpose

Skills are meant to be a **long-term** goal, not something maxed in a day or two of casual play.
The XP curve gets steeper every level, and the higher-value actions (rare ores, tough kills,
expensive enchants) are the ones actually worth pursuing if you want to level efficiently.

On top of that curve, every skill needs **4x** the XP shown in the tables above to actually level
up, **except Alchemy, which needs 2x**. The numbers in the tables are still the right ones to
compare actions against each other — they're just not the raw amount that lands on your bar.
