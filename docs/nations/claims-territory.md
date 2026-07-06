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
| Base claim capacity | 10 chunks | 40 chunks |
| Extra claims per member | +5 | +8 |
| Max separate territory clusters ("colonies") | 3 | 10 |

A neutral nation gets a much larger, more scattered builder-friendly allowance in exchange for
never being able to fight. A warlike nation gets a tighter, more contested territorial game.

- **Colonies**: a new claimed chunk that doesn't touch your existing territory starts a new
  "colony." Once you hit your colony cap, new claims must connect to territory you already hold.
- **Minimum distance** *(default: 5 chunks)*: your border must stay at least this many chunks from
  another nation's, for **both** neutral and warlike nations — this buffer always applies.
- **Overworld only**: only overworld chunks can be claimed. The Nether can be explored freely but
  never claimed; the End is disabled entirely (see [World Rules](../world-rules.md)).

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
- **PvP is disabled inside claims** — claims are safe zones… *unless* the two players' nations are
  at war and it's an active battle (see [Declaring War](../war/overview.md)).

When you cross a border you'll see the nation's name (in its colour) and its leader as a title
and/or action-bar message.
