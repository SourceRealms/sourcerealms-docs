# Tax & Upkeep

Two things happen to your nation's money automatically, once a day: **tax** flows in from members,
and **upkeep** is charged for the land you hold. Both run on a single daily cycle.

## Nation tax

A nation can tax its members — a set percentage of each member's gold balance, taken once a day and
paid straight into the [nation bank](bank.md). There's no tax by default; leadership chooses whether
to turn it on.

- Set it with **Nation Menu → Economy → Taxes** (Java) or `/nation tax set <percent>` — anywhere from
  **1% to 100%**. Setting it to **0%** turns tax off.
- It applies to every member's gold balance each day. If you have no gold, you're not taxed.
- The **leader is exempt** by default, and specific members can be exempted too.
- If you're online when tax is taken, you get a chat message telling you how much.

| Command | What it does |
|---|---|
| `/nation tax` | Show your nation's current tax rate and who's exempt. |
| `/nation tax set <percent>` | Set the daily tax rate (0–100%). Needs *Manage Taxes*. |
| `/nation tax exempt <player>` | Stop taxing a member. Needs *Manage Taxes*. |
| `/nation tax unexempt <player>` | Start taxing a member again. Needs *Manage Taxes*. |

On Java you can manage exemptions visually from **Economy → Taxes → Exemptions** — click a member to
toggle them.

## Nation upkeep

Holding land costs money. Every day, your nation pays **upkeep** from its bank based on how much it
has claimed — **5 gold per claimed chunk** *(default)*. You can see your current daily upkeep in the
lore of the gold icon on the **Economy** menu.

- It's paid automatically from the nation bank each day.
- If the bank **can't cover it**, the leader is warned — right away if online, otherwise the next time
  they log in. After **3 days in a row** *(default)* of unpaid upkeep, the nation is **disbanded**.
- Paying resets the countdown. Missed days don't stack up as debt — you just need enough in the bank
  on the day to clear the warning.

Keep the bank topped up (through tax, deposits, [foreign aid](aid.md), or
[war reparations](../war/overview.md#7-the-spoils-reparations)) so upkeep never catches you short —
especially as you claim more territory.
