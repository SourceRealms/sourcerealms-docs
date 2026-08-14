# FAQ & Troubleshooting

### How do I create a nation?

`/nation create <name>`. See [Creating & Joining](nations/creating-joining.md).

### Why can't I declare war?

Usually one of: the current or next war-session slot is fully booked, your nation (or the target)
is already in an unresolved war, or you have a treaty blocking it - see
[Declaring War](war/overview.md).

### Why don't piglins drop gold?

On purpose. Gold is the server's currency, so every mob-drop and trade source of it has been
removed - piglins, zombified piglins, piglin bartering, and every villager/wandering-trader trade.
Mining and natural chest loot are the only ways to get gold. See [World Rules](world-rules.md).

### Why can't I make netherite gear?

Netherite (ingots, blocks, scrap, and any netherite gear) is locked behind **mastering the Mining
skill** - reaching its max level. Until then it's unobtainable through **any** path: crafting,
smithing, fishing, trading, or looting it from a chest. The only exception is being handed one by a
player who has already mastered Mining. See [Skills & Progression](skills.md).

### What is this server about?

Source Realms is a geopolitics SMP: found or join a nation, claim territory, build an economy,
and compete for land through diplomacy and scheduled war. See the [Home page](index.md) for the
full pitch.

### How do I manage my nation's member permissions?

Permissions live on **roles** (Leader/Trusted/Member by default, plus any custom roles you make).
Open **Nation Menu → Nation Management → Members & Permissions**, or use `/nation role ...` and
`/nation perms ...`. Full breakdown: [Roles & Permissions](nations/roles-permissions.md).

---

### I typed `/nation` and got a text menu instead of the GUI. Why?

The inventory GUI opens for **Java** players who are **in a nation**. Bedrock players and players
without a nation get the chat menu instead - that's expected, and every feature is reachable that
way.

### I can't claim here.

You may be too close to another nation *(default: 5 chunks)*, at your colony cap, over your claim
capacity (invite more members, or sell some via the [claim capacity marketplace](nations/claims-territory.md#claim-capacity-marketplace)),
or in a non-overworld world. See [Claims & Territory](nations/claims-territory.md).

### Someone said they invited me but I can't join.

Invites expire after **10 minutes** *(default)*. Ask them to `/nation invite` you again, then run
`/nation accept`.

### Why is my war "awaiting approval"?

All wars need an admin to approve them before they go live - see
[Declaring War](war/overview.md#3-admin-review). Once approved, you'll get a warning timer before
the battle, and it's announced in `#nations-news` on Discord.

### Can I fight in someone's claim?

Only the owners can start it - a claim is a one-way safe zone. A member of the owning nation can
freely hit an intruder standing in their territory, but the intruder can never hit back. That flips
during an active war battle between the two nations (both sides may fight anywhere inside the
battlefield), and a fight already underway before either player crossed the border keeps going -
retreating into a claim mid-fight doesn't grant safety.

### Why is PvP/war declaration disabled everywhere right now?

Staff can toggle a server-wide **grace period** (e.g. during launch week or to defuse a situation)
that turns off PvP and blocks new war declarations completely, everywhere - overriding even an active
battle's normal rules. It's announced in chat the moment it's turned on or off, so if combat suddenly
stops working, check chat for that message.

### I can't break into a base during a battle - why?

As an attacker, the defenders' **existing** structure inside the contested territory is locked to you
- walls, floors, and the ground can't be broken by hand, so there's no tunnelling under a base to
bypass its defences. To get in, blast through: **explosions and TNT still destroy everything** in the
battlefield. You can also freely **place** blocks (to bridge, pillar, or take cover), and anything
placed after the battle started can be broken again. (Defenders, meanwhile, can break their own land
freely - it's their base.) Full breakdown:
[Declaring War](war/overview.md#building-and-breaking-during-a-battle).

### My ally is at war - how do I help?

Wait for the **⚔ Call to Arms** message after their war is approved and click `[Reinforce]`, or run
`/nation war reinforce <ally>`. Remember: a Mutual Defense Pact only lets you join a *defense*; a
Mutual Aggression Pact lets you join attacks too. See [Allies & Call to Arms](war/allies.md).

### I deposited gold but some nuggets stayed behind.

That's intentional - there are no fractions. Fewer than 9 nuggets can't make a whole gold, so
they're left in your inventory. See [Gold Currency](economy/gold.md).

### How do I earn skill XP faster?

Do the activity in **survival mode** on natural blocks/mobs. Blocks you placed yourself and
creative-mode actions don't count. Perks unlock at levels 3/6/9, and the luxury item unlocks at
the max level. See [Skills & Progression](skills.md).

### What happens to my stuff if my nation loses a war?

If the attacker wins, they capture the contested territory and take a share *(default 50%)* of
your nation bank and of online members' personal balances. Personal *items* aren't taken by the
system (though normal battle deaths still follow the server's usual death rules).

### A battle was happening and the server restarted.

Live battles aren't saved across restarts, so the war is cancelled - nobody wins or loses.

---

*Anything not covered here - ask an admin or in Discord, and it should get added.*
