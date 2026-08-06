# World Rules

A few server-wide rules sit outside the nation/claim/war systems. These apply to everyone,
regardless of nation or mode.

## The End is disabled

You cannot travel to the End at all - stepping into an End portal simply does nothing. This is a
deliberate server-wide decision, not a bug.

## The Nether is small, temporary, and unclaimable

The Nether has a **worldborder 5,000 blocks wide** (2,500 blocks from spawn in any direction), and it
can't be **claimed** by any nation - only overworld chunks count toward a nation's territory.

It's also **wiped and regenerated every week**, at **Monday 01:00 (UK time)**. Anything you build there
will be gone afterward, so don't treat it as permanent - think of it as a resource run, not a place to
settle. If you're still in the Nether when the reset happens, you're automatically teleported to your
nation's capital (or the overworld spawn if you don't have one), and the whole server gets a heads-up
in chat.

## Why don't mobs drop gold?

Gold is the server's currency (see [Gold Currency](economy/gold.md)), so it's kept deliberately
scarce to stop it being trivially farmed. Specifically:

- **No mob ever drops gold** - nuggets, ingots, or blocks - on death. This includes zombified
  piglins (which normally have a small chance to drop a gold nugget) and piglins (which normally
  drop the gold ingot they're holding when killed).
- **Piglin bartering never returns gold.** Bartering with a piglin can still get you all its other
  usual loot - just never gold nuggets back.
- **No villager or wandering-trader trade ever hands out gold**, in either direction.

The only intended sources of gold left are **mining it yourself** and **natural chest loot** - both
untouched by these restrictions.

## Ocean monuments don't have gold

Normally an ocean monument's vault rooms are full of gold blocks - on this server those have been
stripped out, so raiding a monument won't hand you a stack of free currency.

## Gold can't be stored outside your own territory - or in an ender chest

Gold ingots, blocks, nuggets, and raw gold/raw gold blocks can't be put into a chest, barrel, shulker box, furnace, hopper,
dropper, or dispenser sitting on **unclaimed land**. Trying to place gold into one there fails -
the container has to be inside a claim. This also catches a shulker box (or bundle) that already
has gold inside it - you can't launder gold past the rule by hiding it a container deep.

**Ender chests are off-limits for gold entirely, everywhere** - claimed or not. Ender chest contents
follow you no matter where you are and can never be raided, so allowing gold in there would make
claimed-vs-unclaimed meaningless and hand out a permanently un-seizable stash.

This exists because gold is currency (see [Gold Currency](economy/gold.md)): without it, a member
could sit on a pile of gold to dodge their nation's [tax](economy/tax-upkeep.md), or a nation could
stash its gold outside its own borders right before losing a war to keep it out of
[reparations](war/overview.md#7-the-spoils-reparations) (which only take from the nation bank and
online members' balances). Keeping gold storage inside claimed, raidable territory means it's always
inside *someone's* jurisdiction - taxable, and fair game if that land is conquered.

It doesn't stop you from hiding gold - a chest behind a secret door on unclaimed land is still just
as hidden as one in a claim. It only stops using unclaimed land (or an ender chest) as an untouchable
vault.

## Obsidian isn't TNT-proof anymore

Obsidian is normally immune to TNT - here, it isn't. It takes **5 separate TNT explosions** to break
one obsidian block, so it's a real (if temporary) defensive material rather than a hard wall. To check
how much punishment a block has already taken, **left-click it with a potato** in hand - it'll tell
you how many hits it has left. This works anywhere on the server, not just during wars.

Leave a damaged block alone for **5 minutes** and it starts **healing 1 hit every minute** until it's
back to full health - so a wall that survives an initial assault will recover if the attackers don't
keep the pressure up.

## Combat item rules

To keep PvP fair and skill-based, a handful of items are banned, cooldown-gated, or capped. These
apply to **everyone**, everywhere on the server.

**Banned / disabled outright:**

- **Respawn anchors** - can't be placed or charged (no anchor-bombing).
- **End crystals** - can't be placed (no crystal PvP).
- **Elytra** - gliding is disabled; you can't fly.
- **Tipped arrows** - can't be fired from a bow or crossbow.
- **Cart PvP** - fighting from inside a minecart is banned. TNT minecarts are still fine to use for
  traps - it's just for PvP that it's banned.

**Cooldowns & costs:**

- **Mace** - there's a **10-second cooldown** between mace hits.
- **Spears** - each **lunge** costs **4 hunger bars**, so you can't spam it - a couple of lunges in a
  row will run your hunger out. Normal melee swings are unaffected.
- **Ender pearls** - there's a **5-second cooldown** between throws.
- **Trident Riptide** - there's a **5-second cooldown** between dashes.

**Carry limits** *(you can't hold more than this; any excess is dropped at your feet)*:

| Item | Max you can carry |
|---|---|
| Ender pearls | 32 (2 stacks) |
| Wind charges | 64 (1 stack) - and they **can't be crafted** |
| Enchanted golden apples | 5 |
| Totems of undying | 3 |
| Cobwebs | 64 (1 stack) - counted even if stashed inside a shulker box or bundle |
| Experience bottles | 64 (1 stack) |
| Slow Falling potions | 3 (regular, splash, and lingering all count together) |

## TPA is limited to your own nation

`/tpa` and `/tpahere` only work between members of the **same nation** - you can't teleport-request
your way to a rival (or any other) nation's territory. This keeps travel between nations meaningful
and pushes infrastructure - roads, portals, boats - to actually be built rather than skipped with a
teleport. A player with no nation can't TPA to anyone, including other nationless players.

## Difficulty

The server runs on **Hard** difficulty.
