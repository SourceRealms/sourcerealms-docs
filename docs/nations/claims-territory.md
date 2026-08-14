# Claims & Territory

Claims are **per chunk** (a 16×16 column). Stand in a chunk and:

| Command | What it does |
|---|---|
| `/nation claim` | Claim the chunk you're standing in. |
| `/nation unclaim` | Release it. |
| `/nation map` | Show a mini-map of nearby claims. |

Claiming and unclaiming need the **Claim Land** / **Unclaim Land** permissions - Trusted-level by
default (see [Roles & Permissions](roles-permissions.md)).

## Personal plots

A nation-claimed chunk can be handed to one or more specific members as a **personal plot** - within
it, only they (or the nation leader, always) can build, break, open containers, or use doors/levers.
Every other member loses build rights there too, even ones who'd normally be allowed to build
anywhere in the nation's territory. It's meant for two things: a bit of protection against
accidental (or not-so-accidental) griefing between nation-mates, and a real personal space - a house
that's actually yours, even inside shared territory.

Requires the **Manage Plots** permission (not granted to any role by default except the Leader -
a nation must deliberately hand it out, same as any other permission):

| Command | What it does |
|---|---|
| `/nation plot claim <player> [player2] [...]` | Turn the chunk you're standing in into a personal plot for those member(s). |
| `/nation plot release` | Release the current chunk back to plain nation territory. |
| `/nation plot info` | Check who (if anyone) the current chunk is plotted to. |
| `/nation plot list` | List every personal plot in your nation. |

A few things worth knowing:

- Plots are **per chunk** - a bigger house needs the command run once per chunk it covers.
- Targets must already be members of your own nation - you can't hand a plot to an outsider.
- If a plotted member is **kicked or leaves**, their plot access is automatically released - it
  doesn't sit there locked forever.
- If a plotted chunk is **lost in a war**, the plot restriction is wiped along with the ownership
  change - the new owner doesn't inherit someone else's house rule.
- There's no limit on how many chunks a nation can turn into personal plots - that's entirely up to
  whoever holds the Manage Plots permission.

## Rules and limits

- **Claim capacity**: 10 chunks base, +8 per member. Need more room than your member count earns
  you? See the [claim capacity marketplace](#claim-capacity-marketplace) below.
- **Colonies**: a new claimed chunk that doesn't touch your existing territory starts a new
  "colony," capped at **3** separate colonies. Once you hit the cap, new claims must connect to
  territory you already hold.
- **Minimum distance** *(default: 5 chunks)*: your border must stay at least this many chunks from
  another nation's - this buffer always applies.
- **Overworld only**: only overworld chunks can be claimed. The Nether can never be claimed and is
  wiped weekly, so don't rely on it for anything permanent; the End is disabled entirely (see
  [World Rules](../world-rules.md)).

## Claim capacity marketplace

Not every nation actually uses all the claim capacity its member count earns it. Instead of that
headroom just sitting idle, you can sell it - for gold, to any other nation, no diplomacy or
negotiation required.

**This trades capacity, not land.** Selling capacity never gives away or moves any of your actual
claimed chunks - it only adjusts how much *more* either nation can claim going forward.

| Command | What it does |
|---|---|
| `/nation claims sell <amount> <price>` | List some of your unused claim capacity for sale at a flat total price. |
| `/nation claims listings` | Browse every open listing on the server. |
| `/nation claims buy <id>` | Buy a listing outright - pays in full from your nation bank. |
| `/nation claims unlist <id>` | Cancel one of your own listings. |

A few things worth knowing:

- You can only sell capacity you're not currently using (`capacity - claimed chunks`). It's set
  aside the moment you list it, so you can't double-list the same headroom or claim past what
  you're about to sell.
- Payment goes bank to bank, same as sending foreign aid.
- There's no limit today on how much capacity a nation can accumulate by buying.
- Selling capacity permanently lowers your own cap until you buy some back (from anyone, any time)
  - it isn't a loan.

!!! note "No trading mid-war"
    Neither buying nor selling is available while your nation has an unresolved war - same
    reasoning as blocking a leadership transfer mid-war. This moves gold between nation banks, and
    a nation about to lose a war (and its reparations) shouldn't be able to use it to move funds
    out of reach first.

## What claims protect *(all default-on, admin-toggleable)*

Inside your claims, outsiders can't:

- **Break, place, or open containers** (build protection).
- Trigger **explosions**, spread **fire**, or cause **mob griefing** that damages your blocks.
- Harm your **animals, item frames, paintings, or vehicles**.
- Push blocks in with **pistons** or flow **fluids** across your border.
- **Build in the unclaimed wilderness right next to your wall** - placing blocks is blocked within
  1 chunk of any claim that isn't the placer's own, so a trespasser can't just tower or bridge over
  from just outside it.
- **Splash a harmful potion** (poison, wither, weakness, instant damage, etc.) at your animals or
  your members from outside - it just has no effect. Beneficial potions (healing, strength, and so
  on) aren't affected, so sharing a buff with a visiting ally still works fine.
- **Hook you with a fishing rod** and reel you out of your own claim.
- **Place a boat** inside your claim to leave as clutter.

**PvP in your claim is one-directional**: an intruder can't damage anyone standing in your
territory, but a member of your nation can freely fight back against them - a deliberate anti-troll
rule, not a loophole for the intruder. This flips two ways: during an active war battle, both sides
may fight anywhere including inside claims (see [Declaring War](../war/overview.md)); and if a
fight was already underway before either player crossed the border, it keeps going - retreating
into a claim mid-fight doesn't grant safety. Separately, **nation members can never PvP each
other**, in claims or the wilderness alike - friendly fire is always off.

You also can't `/sethome` inside a claim that isn't your own nation's, or within 4 chunks of one.

When you cross a border you'll see the nation's name (in its colour) and its leader as a title
and/or action-bar message.
