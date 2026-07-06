# Neutrality: Why Can't I Declare War?

Every nation is either **neutral** (peaceful) or **warlike** — this is the single biggest fork in
how the server plays for you, and it exists so builders and conquerors can share the same map
without stepping on each other.

## What neutral means

A **neutral** nation:

- **Cannot declare war** on anyone.
- **Cannot be attacked** — nobody can declare war on a neutral nation, no matter how tempting their
  land looks.
- **Cannot be pulled into a battle as an ally**, even via a Mutual Defense/Aggression Pact.
- Gets a **much larger claim allowance** and can hold more scattered territory clusters — see
  [Claims & Territory](../nations/claims-territory.md).

A **warlike** nation is the opposite: it can declare war, be attacked, and join battles as an ally
— but its claim allowance is smaller and tighter.

!!! info "New nations start neutral"
    Every nation is created **neutral by default**. You have to deliberately opt in to the war
    game with `/nation neutral off` — nobody is dragged into PvP territory conflict by accident.

## Checking and changing your stance

| Command | What it does |
|---|---|
| `/nation neutral` | Show your nation's current stance and, if you recently changed it, how long until you can change it again. |
| `/nation neutral off` | Become warlike — you can now declare war and be attacked. |
| `/nation neutral on` | Become neutral — you're now safe from war, but can't declare it either. |

Both require the **Manage Diplomacy** permission.

## The catches (anti-abuse rules)

- **You can't go neutral to dodge a war.** If your nation is currently involved in a declared,
  scheduled, or active war, `/nation neutral on` is blocked until it's resolved.
- **A 24-hour cooldown applies in both directions.** You can't flip back and forth to game the
  system — after any neutrality change, you must wait before changing it again.
- **Re-arming (going warlike) can be blocked by your claim size.** If your neutral nation is
  holding more territory than the warlike cap allows, you'll need to unclaim down to that limit
  before `/nation neutral off` will succeed. See
  [Claims & Territory](../nations/claims-territory.md) for the exact numbers.

## So why can't I declare war on that nation?

If `/nation war declare <nation>` is refused, check, in order:

1. **Is your own nation neutral?** Run `/nation neutral off` first.
1. **Is the target nation neutral?** You simply can't attack them — that's the point.
1. Are you already in an unresolved war, or do you have an active treaty/pact with them that blocks
   war? See [Diplomacy](../diplomacy.md).
1. Is the current or next war-session slot fully booked? See [Declaring War](overview.md).
