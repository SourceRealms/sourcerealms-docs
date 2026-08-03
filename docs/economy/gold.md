# Gold Currency

The server currency is **gold** (symbol **g**). **1 gold ingot = 1g.** Your balance lives in the
server economy; gold items are the physical form of that money.

## Converting gold ↔ balance

Use `/gold` to move between physical gold and your currency balance:

| Command | What it does |
|---|---|
| `/gold` | Show your balance. |
| `/gold deposit <amount>` | Turn that much gold into currency. |
| `/gold deposit all` | Deposit **all** the gold you're carrying. |
| `/gold withdraw <amount>` | Take that much currency out as physical gold. |
| `/gold withdraw all` | Withdraw your whole (whole-number) balance. |

### Conversion rates

- **1 gold nugget = 1⁄9 g**
- **1 gold ingot = 1 g**
- **1 gold block = 9 g**

**No fractions, ever.** When you `deposit all`, leftover nuggets that don't make a whole gold
(fewer than 9) stay in your inventory. If you deposit a specific amount and a block has to be
broken to make change, you get the difference back as ingots. Withdrawals are handed to you as the
most compact mix of blocks and ingots (overflow drops at your feet if your inventory is full).

!!! note "Only plain gold counts"
    A renamed or otherwise special gold item is never consumed or accepted by `/gold`.

## Where gold actually comes from

Because gold is the whole server's currency, it's deliberately kept **scarce and hard to farm**.
The only intended sources are:

- **Mining** - digging up gold ore yourself.
- **Natural chest loot** - dungeons, ruins, and other generated structures.

Gold is **never** obtainable from mob drops, villager or wandering-trader trades, or piglin
bartering - see [World Rules](../world-rules.md) for the full reasoning.
