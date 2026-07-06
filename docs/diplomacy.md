# Diplomacy

Manage relations through **Nation Menu → Diplomacy** (Java), or the `/nation treaty` commands. All
diplomacy actions require the **Manage Diplomacy** permission. Two nations can hold **one**
relation at a time.

## Relation types

| Relation | Meaning | Blocks war? | Breaking it |
|---|---|---|---|
| **Alliance** | Close partnership. | Yes | Starts a war cooldown *(default 24h)* before you may attack each other. |
| **Non-Aggression Pact (NAP)** | "We won't fight." | Yes | Breaks instantly, no cooldown. |
| **Mutual Defense Pact (MDP)** | Defensive alliance — allies can join your **defense**. | Yes | War cooldown on break. |
| **Mutual Aggression Pact (MAP)** | Offensive + defensive — allies can join your **attacks and defenses**. | Yes | War cooldown on break. |
| **Enemy** | A public hostile marker, declared unilaterally. | No | Clear it any time with `treaty break` — no cooldown. |

Marking someone an **Enemy** doesn't affect war rules at all (it's purely a public "we don't like
them" marker) — war is still gated entirely by neutrality, treaties, and the session schedule. See
[Declaring War](war/overview.md).

## Making and managing treaties

| Command | What it does |
|---|---|
| `/nation treaty propose alliance\|nap\|defense\|aggression <nation>` | Offer a treaty. |
| `/nation treaty accept <nation>` | Accept an incoming offer. |
| `/nation treaty deny <nation>` | Decline an incoming offer. |
| `/nation treaty cancel <nation>` | Withdraw your own outgoing offer. |
| `/nation treaty break <nation>` | End an active treaty (or clear an enemy marker). |
| `/nation treaty enemy <nation>` | Mark another nation as an enemy — no consent needed. |
| `/nation treaty list` | See your current relations. |

You can also review signed pacts and pending proposals in **Nation Menu → Library → Documents**,
where clicking a document lets you accept, deny, cancel, or break it directly.
