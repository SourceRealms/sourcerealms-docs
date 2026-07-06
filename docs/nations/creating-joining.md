# Creating & Joining a Nation

## Create a nation

```
/nation create <name>
```

Your nation starts with you as its **leader**, an auto-generated **tag** (a short label shown in
brackets, like `[TEST]`), and a default set of roles (Leader + Officer + Member). You can change the
tag later with `/nation tag <tag>` (2–5 characters).

New nations start **neutral** (peaceful) by default — see [Neutrality](../war/neutrality.md) before
you decide whether to opt into the war game.

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
