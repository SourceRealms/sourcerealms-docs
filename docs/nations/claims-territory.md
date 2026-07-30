# Claims & Territory

Claims are **per chunk** (a 16×16 column). Stand in a chunk and:

| Command | What it does |
|---|---|
| `/nation claim` | Claim the chunk you're standing in. |
| `/nation unclaim` | Release it. |
| `/nation map` | Show a mini-map of nearby claims. |

Claiming and unclaiming need the **Claim Land** / **Unclaim Land** permissions — officer-level by
default (see [Roles & Permissions](roles-permissions.md)).

## Rules and limits

Your ruleset depends on whether your nation is **neutral or warlike** — see
[Neutrality](../war/neutrality.md) for what that status actually means. The two get genuinely
different claim allowances:

| | **Warlike** | **Neutral** |
|---|---|---|
| Base claim capacity | 10 chunks | 25 chunks |
| Extra claims per member | +5 | +5 |
| Max separate territory clusters ("colonies") | 3 | 5 |

A neutral nation gets a much larger, more scattered builder-friendly allowance in exchange for
never being able to fight. A warlike nation gets a tighter, more contested territorial game.

- **Colonies**: a new claimed chunk that doesn't touch your existing territory starts a new
  "colony." Once you hit your colony cap, new claims must connect to territory you already hold.
- **Minimum distance** *(default: 5 chunks)*: your border must stay at least this many chunks from
  another nation's, for **both** neutral and warlike nations — this buffer always applies.
- **Overworld only**: only overworld chunks can be claimed. The Nether can never be claimed and is
  wiped weekly, so don't rely on it for anything permanent; the End is disabled entirely (see
  [World Rules](../world-rules.md)).

!!! note "Re-arming has a catch"
    If your neutral nation has claimed more land than the **warlike** cap allows, you can't just
    flip `/nation neutral off` — you'll need to unclaim down to the warlike limit first. This stops
    a nation hoarding a huge neutral-sized territory and then instantly becoming un-conquerable
    warlike land.

## What claims protect *(all default-on, admin-toggleable)*

Inside your claims, outsiders can't:

- **Break, place, or open containers** (build protection).
- Trigger **explosions**, spread **fire**, or cause **mob griefing** that damages your blocks.
- Harm your **animals, item frames, paintings, or vehicles**.
- Push blocks in with **pistons** or flow **fluids** across your border.
- **Build in the unclaimed wilderness right next to your wall** — placing blocks is blocked within
  1 chunk of any claim that isn't the placer's own, so a trespasser can't just tower or bridge over
  from just outside it.
- **Splash a harmful potion** (poison, wither, weakness, instant damage, etc.) at your animals or
  your members from outside — it just has no effect. Beneficial potions (healing, strength, and so
  on) aren't affected, so sharing a buff with a visiting ally still works fine.
- **Hook you with a fishing rod** and reel you out of your own claim.
- **Place a boat** inside your claim to leave as clutter.

**PvP in your claim is one-directional**: an intruder can't damage anyone standing in your
territory, but a member of your nation can freely fight back against them — a deliberate anti-troll
rule, not a loophole for the intruder. This flips two ways: during an active war battle, both sides
may fight anywhere including inside claims (see [Declaring War](../war/overview.md)); and if a
fight was already underway before either player crossed the border, it keeps going — retreating
into a claim mid-fight doesn't grant safety. Separately, **nation members can never PvP each
other**, in claims or the wilderness alike — friendly fire is always off.

You also can't `/sethome` inside a claim that isn't your own nation's, or within 4 chunks of one.

When you cross a border you'll see the nation's name (in its colour) and its leader as a title
and/or action-bar message.
