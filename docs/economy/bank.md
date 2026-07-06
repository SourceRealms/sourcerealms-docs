# The Nation Bank

Separate from your personal wallet, each nation has a shared **bank**. Open
**Nation Menu → Economy** (Java), or use commands:

| Command | What it does |
|---|---|
| `/nation bank deposit <amount>` | Move money from **your** balance into the bank. Any member with *Bank Deposit* (a default Member permission) can do this. |
| `/nation bank withdraw <amount>` | Move money from the bank to **your** balance. Requires *Bank Withdraw*. |
| `/nation bank send <amount> <nation>` | Send money to another nation's bank — foreign aid. |

The nation bank is shown as **Bank** on `/nation info`, and it's exactly what
[war reparations](../war/overview.md#7-the-spoils-reparations) are paid into and out of.

!!! note "Taxes"
    A tax system is shown in the Economy menu for permission-holders but isn't built yet — it's
    planned for a future update.
