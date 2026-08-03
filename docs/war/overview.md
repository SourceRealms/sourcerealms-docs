# Declaring War

War is how territory changes hands. It's a deliberate, scheduled event tied to a fixed weekly
session - not an instant free-for-all - and it only happens between two **warlike** nations (see
[Neutrality](neutrality.md) if you're not sure what that means for you).

## 1. Declare - any time

```
/nation war declare <nation>
```

Requires the **Manage Diplomacy** permission. You **contest one territory** - one connected
cluster of the enemy's claims. If they have several separate territories, you'll be asked to pick
which one to contest (by number).

You can't declare war if:

- Either nation is **neutral**.
- Your nation is already in an unresolved war (win, lose, or resolve it first).
- The target nation is already in an unresolved war.
- You have an active treaty or a recent alliance-break cooldown with them - see
  [Diplomacy](../diplomacy.md).

You can declare **at any time** - there's no need to wait for a specific day. Your war is
automatically slotted into the **next available weekly session**.

## 2. The weekly war session

All battles happen at a **fixed weekly slot: Friday, 20:00–02:00 (UK time)**. Only **one war** can
be scheduled per session, and at most **two upcoming sessions** can be booked at once. When you
declare:

- If the next Friday's slot is free, your war is proposed for it.
- If it's already taken, you're bumped to the Friday after.
- If **both** upcoming Fridays are already booked, your declaration is rejected outright with a
  message to wait or contact an admin - it isn't queued indefinitely.

Any time this wiki (or Discord) mentions a battle time, it's shown as a **dynamic timestamp** that
displays correctly in your own timezone.

## 3. Admin review

A declared war doesn't go live immediately - it's marked **pending** until an admin reviews it (via
an in-game command or a Discord button). This is announced in the server's `#nations-admin` Discord
channel. You'll see your war listed as *pending admin approval* until then.

- **If approved**, your war is confirmed for its session slot, and it's publicly announced in the
  `#nations-news` Discord channel with a countdown timestamp. That post is kept **up to date through
  the whole war** - it updates when the battle begins, when it's won (naming the winner), and if it's
  cancelled. Online members of **both** nations also get an in-game chat message right away; anyone
  offline at that moment gets the same message the next time they log in (as long as the battle
  hasn't already happened by then).
- **If denied**, the war is cancelled before it ever goes public, and your reserved slot frees up
  for someone else.

## 4. Changed your mind? Cancel it

```
/nation war cancel <nation>
```

Only the **attacker** can call off a war, any time before the battle starts, and it requires
*Manage Diplomacy*. If the war had already been publicly announced, cancelling it updates the
`#nations-news` post to a cancellation notice, so nobody shows up to a battle that isn't happening.

## 5. Reminders before the battle

As the battle approaches, both nations' online members get in-game **reminders at 4, 2, and 1 hours
before it starts** *(configurable)*, and a final **"battle begun" announcement** the moment it
kicks off. Anyone offline when a reminder fires is caught up the next time they log in. The first
reminder is also when [allies can answer the call to arms](allies.md).

## 6. Ready up

The battle doesn't start the instant the session slot arrives. Once it does, each nation's **leader**
gets a **30-minute ready-up window** to confirm with:

```
/nation war ready
```

If **both** leaders ready up, the battle starts immediately - no need to wait out the clock. If the
window runs out first, the battle starts automatically regardless of who's readied up.

## 7. The battle

Once the battle actually starts (either because both sides readied up, or the window ran out),
everyone online on both sides is teleported to a **battlefield** around the contested territory:

- Attackers spawn just outside the territory; defenders spawn at its centre.
- You **can't leave the battlefield** - reaching the edge bounces you back rather than teleporting
  you away.
- **PvP is on** between the two sides.
- **Elimination decides it.** When a player dies (or logs out) they're out, and become a free-flying
  spectator (still confined to the battlefield). A side **wins when the entire enemy roster is
  eliminated**.
- A nation whose land is at stake can concede with `/nation war surrender <nation>` (or
  `/nation surrender <nation>`).

### Watching a battle you're not fighting in

Anyone - not just the two nations involved - can watch an ongoing battle:

```
/nation spectate
```

Run it once to be dropped in above the battlefield in spectator mode (you can't be seen or hit, and
can't affect anything); run it again to return to exactly where - and how - you were before. Like a
real participant, you **can't leave the battlefield** while spectating, so it's watch-until-you're-
done rather than a quick peek. You can't spectate a war your own nation is actively fighting in -
you're either a combatant or an onlooker, not both.

### Building and breaking during a battle

The battlefield has two zones, and they play differently:

- **Outside the territory** (the ring where attackers spawn): a free-for-all. Build, break, and place
  whatever you like - it's open ground. This is where you'd set up siege positions.
- **Inside the contested territory:** it's the defenders' land, so the two sides play by different
  rules. **Defenders can build and break their own base freely** - dig in, reroute, wall off, do
  whatever it takes to hold. **Attackers can't break the base by hand:** blocks that were already
  there when the battle started - walls, floors, the ground itself - are locked to them, so there's no
  tunnelling under a castle to pop up in the throne room. Both sides can freely **place** blocks
  (bridge a wall, pillar up, box up for cover), and **any block placed after the battle began can be
  broken again** by either side.

So how does an attacker actually get in? You go **through the wall, not under it**: **explosions still
tear through everything inside the battlefield**, so TNT (and siege equipment) will blast open
pre-built defences that hand-mining can't touch. Solid walls are worth building - they force attackers
to spend explosives instead of quietly digging in.

If you're building defences ahead of a war, note that [obsidian isn't TNT-proof](../world-rules.md#obsidian-isnt-tnt-proof-anymore)
here - it holds up to repeated blasts rather than blocking them outright.

### The war cannon

For heavier siege work, attackers can build a **war cannon** - a deployable structure that lobs primed
TNT over a wall.

**Craft it** in a crafting table. Reading left-to-right, top-to-bottom:

```
Gunpowder   Iron Block   Gunpowder
Iron Block     TNT       Iron Block
Gunpowder   Iron Block   Gunpowder
```

That gives you a **War Cannon** item. Then, during a battle:

1. **Deploy** - hold the cannon and right-click the ground where you want it. The cannon rises in
   front of you, its barrel pointing the way you're facing. You can only place cannons **as an
   attacker, in the buffer zone** outside the contested territory - not inside the enemy's claim - and
   a battle is limited to **5 active cannons** at once.
2. **Load** - right-click the **breech** (the solid block at the back, under the trigger) to open it,
   and drop in **TNT**. It only accepts TNT.
3. **Fire** - hit the **trigger button** on the back of the cannon. It launches a primed TNT charge
   down-range, then needs about **10 seconds to prime** before it can fire again.

A cannon is only as good as its barrel: if the **barrel** or the **trigger** gets broken (or blown
up), the cannon is **wrecked** and becomes an inert pile of blocks - you'll need a fresh one.

## 8. The spoils (reparations)

If the **attacker wins**, they:

- **Capture the contested territory** - those chunks become the attacker's claims.
- **Seize reparations** *(default 50%)* - that percentage of the defender's **nation bank**, plus
  the same percentage of every **online** losing member's personal balance, transfers to the
  winner's bank.

If the **defender wins**, they keep their land and nothing is transferred.

## Things that end a war early

- **Surrender** - the opponent wins outright.
- **No-show** - if a side has nobody online when the battle starts, the war is cancelled.
- **Admin action or a disband** - the battle is torn down.
- **Server restart mid-battle** - the battle is cancelled; battle state isn't saved across restarts.

Check your current war any time with `/nation war list`, or details with
`/nation war info <nation>`.
