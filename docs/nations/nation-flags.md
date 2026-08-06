# Nation Flags: Why Can't I Declare War?

Every nation is in one of two modes: **SMP** or **Geopolitical** - this is the single biggest fork
in how the server plays for you, and it exists so builders and conquerors can share the same map
without stepping on each other.

## What SMP mode means

An **SMP** nation:

- **Cannot declare war** on anyone.
- **Cannot be attacked** - nobody can declare war on an SMP nation, no matter how tempting their
  land looks.
- **Cannot be pulled into a battle as an ally**, even via a Mutual Defense/Aggression Pact.
- Gets a **much larger claim allowance** and can hold more scattered territory clusters - see
  [Claims & Territory](claims-territory.md).

A **Geopolitical** nation is the opposite: it can declare war, be attacked, and join battles as an
ally - but its claim allowance is smaller and tighter.

!!! info "New nations start Geopolitical"
    Every nation is created in **Geopolitical mode by default**. If you'd rather build peacefully,
    opt in to SMP mode yourself with `/nation mode smp`.

## Checking and changing your mode

| Command | What it does |
|---|---|
| `/nation mode` | Show your nation's current mode and, if you recently changed it, how long until you can change it again. |
| `/nation mode geopolitical` | Switch to Geopolitical mode - you can now declare war and be attacked. |
| `/nation mode smp` | Switch to SMP mode - you're now safe from war, but can't declare it either. |

Both require the **Manage Diplomacy** permission.

## The catches (anti-abuse rules)

- **You can't switch to SMP mode to dodge a war.** If your nation is currently involved in a
  declared, scheduled, or active war, `/nation mode smp` is blocked until it's resolved.
- **A 24-hour cooldown applies in both directions.** You can't flip back and forth to game the
  system - after any mode change, you must wait before changing it again.
- **Switching to Geopolitical mode can be blocked by your claim size.** If your SMP nation is
  holding more territory than the geopolitical cap allows, you'll need to unclaim down to that
  limit before `/nation mode geopolitical` will succeed. See
  [Claims & Territory](claims-territory.md) for the exact numbers.

## So why can't I declare war on that nation?

If `/nation war declare <nation>` is refused, check, in order:

1. **Is your own nation in SMP mode?** Run `/nation mode geopolitical` first.
1. **Is the target nation in SMP mode?** You simply can't attack them - that's the point.
1. Are you already in an unresolved war, or do you have an active treaty/pact with them that blocks
   war? See [Diplomacy](../diplomacy.md).
1. Is the current or next war-session slot fully booked? See [Declaring War](../war/overview.md).
