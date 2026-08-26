# Creating & Joining a Nation

## Create a nation

```
/nation create <name>
```

Your nation starts with you as its **leader**, an auto-generated **tag** (a short label shown in
brackets, like `[TEST]`), and a default set of roles (Leader + Trusted + Member). You can change the
tag later with `/nation tag <tag>` (2–5 characters).

## Invite and join

- A leader/trusted runs **`/nation invite <player>`** - sends an invite that expires after
  **10 minutes** *(default)*.
- The invited player runs **`/nation accept`** to join, or **`/nation deny`** to decline.

## Leaving and removing members

- **`/nation leave`** - leave your nation. The leader can't leave without disbanding or handing off
  leadership first (see below).
- **`/nation transfer <player>`** then **`/nation transfer confirm`** - hand off leadership to another
  member. They become the new leader immediately (full control - disband, roles, everything), and you
  drop to the nation's default role. There's a 30-second confirm window, and it can't be done while
  your nation is at war (declared, approved, or mid-battle) - resolve the war first.
- **`/nation kick <player>`** - remove a member (needs the *Kick Players* permission).
- **`/nation disband`** then **`/nation disband confirm`** - permanently delete your nation. This
  releases **all** your claims, roles, treaties, letters, and bank balance. There's a 30-second
  confirm window before it's final.

!!! warning "Disbanding is permanent"
    There's no undo. Everything the nation owns - territory, treaties, mail, bank balance - is
    gone the moment you confirm.

## Viewing nations

- **`/nation info [name]`** - details of your nation (or another's): description, government,
  ideology, capital, bank balance, claims, and members.
- **`/nation list [page]`** - every nation on the server.
- **`/nation log [page]`** - a paginated history of who joined, left, or was kicked from your
  nation, and when.

## Nation & ally chat

Typing normally in chat is always **public** - everyone on the server sees it. To message a private
audience, use a dedicated command instead of switching channels:

- **`/nc <message>`** - only your own nation sees it.
- **`/ac <message>`** - your nation *and* any nation you're Allied with (or share a Mutual
  Defense/Aggression Pact with) sees it. A Non-Aggression Pact alone doesn't count.

A private message is easy to spot: it gets a coloured tag before your name - `[NC]` in blue for
nation chat, `[AC]` in green for ally chat - and the message text itself switches from the normal
grey to white.
