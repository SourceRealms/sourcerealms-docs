# Command Reference

## Nation basics

| Command | Description |
|---|---|
| `/nation` · `/nations` · `/n` | Open your Nation Menu (Java, in a nation) or show help |
| `/nation help [page]` | List commands |
| `/nation create <name>` | Create a nation |
| `/nation invite <player>` | Invite a player |
| `/nation accept` / `/nation deny` | Accept / decline an invite |
| `/nation kick <player>` | Remove a member |
| `/nation leave` | Leave your nation |
| `/nation transfer <player>` → `confirm` | Hand off leadership (not while at war) |
| `/nation disband` → `confirm` | Delete your nation |
| `/nation info [name]` | Nation details |
| `/nation list [page]` | All nations |

## Land & capital

| Command | Description |
|---|---|
| `/nation claim` / `/nation unclaim` | Claim / release the current chunk |
| `/nation map` | Nearby-claims mini-map |
| `/nation capital set <name>` | Set & name your capital here |
| `/nation capital` | Teleport to your capital |
| `/nation plot claim <player> [...]` | Turn the current chunk into a personal plot for those member(s) |
| `/nation plot release` | Release the current chunk back to plain nation territory |
| `/nation plot info` | Check who the current chunk is plotted to |
| `/nation plot list` | List every personal plot in your nation |

## Roles & permissions

| Command | Description |
|---|---|
| `/nation roles` | List roles |
| `/nation role create/delete/set/title ...` | Manage roles |
| `/nation perms ...` | View / toggle role permissions |

## Identity

| Command | Description |
|---|---|
| `/nation color <colour>` | Set nation colour |
| `/nation description [text]` | Set/clear description |
| `/nation government [text]` | Set/clear government |
| `/nation ideology [text]` | Set/clear ideology |
| `/nation rename <name>` / `/nation tag <tag>` | Rename / retag |
| `/nation announce <message>` | Broadcast to members |
| `/nation banner set/clear` · `/nation banner` | Manage / get the nation banner |

## Chat

| Command | Description |
|---|---|
| `/nc <message>` | Message your nation privately |
| `/ac <message>` | Message your nation + allies privately |

## Nation Mode & War

| Command | Description |
|---|---|
| `/nation war declare <nation>` | Declare war (contest a territory) |
| `/nation war cancel <nation>` | Call off a war before the battle starts (attacker only) |
| `/nation war reinforce <ally>` | Answer an ally's call to arms |
| `/nation war list` / `/nation war info <nation>` | Your war / war details (shows the war ID) |
| `/nation war adjust <id> <hours>` | Shift a pending/scheduled war's battle time (see [War](../war/overview.md#adjusting-the-battle-time)) |
| `/nation war surrender <nation>` · `/nation surrender <nation>` | Surrender a battle |

## Diplomacy

| Command | Description |
|---|---|
| `/nation treaty propose alliance\|nap\|defense\|aggression <nation>` | Offer a treaty |
| `/nation treaty accept/deny/cancel/break <nation>` | Manage treaties |
| `/nation treaty enemy <nation>` | Mark an enemy |
| `/nation treaty list` | Your relations |

## Economy

| Command | Description |
|---|---|
| `/gold` | Show your balance |
| `/gold deposit <amount\|all>` | Gold items → currency |
| `/gold withdraw <amount\|all>` | Currency → gold items |
| `/nation bank deposit <amount>` | Your balance → nation bank |
| `/nation bank withdraw <amount>` | Nation bank → your balance |
| `/nation bank send <amount> <nation>` | Send money to another nation (aid) |
| `/nation bank history` | Your nation's most recent bank transactions |
| `/nation tax` | Show your nation's tax rate and exemptions |
| `/nation tax set <percent>` | Set the daily member tax (*Manage Taxes*) |
| `/nation tax exempt <player>` | Exempt a member from tax (*Manage Taxes*) |
| `/nation tax unexempt <player>` | Remove a member's exemption (*Manage Taxes*) |
| `/nation chest` | Open your nation's shared community chest (any member, no permission needed) |
| `/bounty <target> <killer> <amount>` | Offer a paid contract on someone's life (see [Bounties](../bounties.md)) |
| `/bounty accept [target]` | Accept a bounty offered to you |
| `/bounty deny [target]` | Decline a bounty offered to you |
| `/bounty cancel [target]` | Call off your own bounty and get refunded |

## Personal & world

| Command | Description |
|---|---|
| `/skills [player]` | Open the skills panel / view another player's |
| `/nation weblink` | Get a code to link the web map |
| `/rtp` · `/wild` | Teleport to a random, unclaimed, safe surface spot |
| `/map` | Open the live web map |
| `/help` · `/guide` | Open a quick overview of Nations, Skills, Leaderboards, RTP, Voting, and the Server Store |
