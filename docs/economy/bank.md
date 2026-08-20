# The Nation Bank

Separate from your personal wallet, each nation has a shared **bank**. Open
**Nation Menu → Economy** (Java), or use commands:

| Command | What it does |
|---|---|
| `/nation bank deposit <amount>` | Move money from **your** balance into the bank. Any member with *Bank Deposit* (a default Member permission) can do this. |
| `/nation bank withdraw <amount>` | Move money from the bank to **your** balance. Requires *Bank Withdraw*. |
| `/nation bank send <amount> <nation>` | Send money to another nation's bank - foreign aid. Requires *Foreign Aid* (a separate permission from *Bank Withdraw*, so you can grant one without the other). |
| `/nation bank history` | Show your nation's most recent bank transactions (deposits, withdrawals, aid, tax, war reparations, admin adjustments) - any member can view it, same as the balance. |

The nation bank is shown as **Bank** on `/nation info`, and it's exactly what
[war reparations](../war/overview.md#7-the-spoils-reparations) are paid into and out of. It's also
where [tax](tax-upkeep.md) is collected and where [upkeep](tax-upkeep.md#nation-upkeep) is paid
from each day - so keep it funded.
