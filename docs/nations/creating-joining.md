# Creating & Joining a Nation

## Create a nation

```
/nation create <name>
```

Your nation starts with you as its **leader**, an auto-generated **tag** (a short label shown in
brackets, like `[TEST]`), and a default set of roles (Leader + Officer + Member). You can change the
tag later with `/nation tag <tag>` (2–5 characters).

New nations start **warlike** by default — see [Neutrality](../war/neutrality.md) if you'd rather
opt into peaceful, neutral status instead.

## Invite and join

- A leader/officer runs **`/nation invite <player>`** — sends an invite that expires after
  **10 minutes** *(default)*.
- The invited player runs **`/nation accept`** to join, or **`/nation deny`** to decline.

## Leaving and removing members

- **`/nation leave`** — leave your nation. The leader can't leave without disbanding or handing off
  leadership first.
- **`/nation kick <player>`** — remove a member (needs the *Kick Players* permission).
- **`/nation disband`** then **`/nation disband confirm`** — permanently delete your nation. This
  releases **all** your claims, roles, treaties, letters, and bank balance. There's a 30-second
  confirm window before it's final.

!!! warning "Disbanding is permanent"
    There's no undo. Everything the nation owns — territory, treaties, mail, bank balance — is
    gone the moment you confirm.

## Viewing nations

- **`/nation info [name]`** — details of your nation (or another's): description, government,
  ideology, **neutral/warlike status**, capital, bank balance, claims, and members.
- **`/nation list [page]`** — every nation on the server.

## Nation & ally chat

By default you're in **public** chat — everyone on the server sees your messages. Switch channels
with `/nation chat <public|nation|ally>`:

- **`/nation chat nation`** — only your own nation sees your messages.
- **`/nation chat ally`** — your nation *and* any nation you're Allied with (or share a Mutual
  Defense/Aggression Pact with) sees your messages. A Non-Aggression Pact alone doesn't count.
- **`/nation chat public`** — back to everyone.

A private channel (nation or ally) is easy to spot: your messages get a coloured tag before your
name — `[NC]` in blue for nation chat, `[AC]` in green for ally chat — and the message text itself
switches from the normal grey to white.

Your channel choice resets to public whenever you log back in — it isn't saved between sessions.
