# Overthrow

Don't like your leader? Vote them out.

```
/nation overthrow
```

Running this starts a vote to remove your nation's current leader - your own vote counts
immediately as the first one. Any other member can run the same command to add their vote to the
one already underway; it doesn't start a second vote, it just joins the existing one.

## Reaching a majority

A vote succeeds once it reaches **50% of the nation's total member count**, rounded up. A 20-member
nation needs **10 votes**. A 7-member nation needs **4**. The moment that threshold is hit, the vote
resolves immediately - whoever started it becomes the new leader on the spot, with full control:
disband, roles, everything. The old leader drops to the nation's default role, same as a normal
`/nation transfer`.

You can't vote to overthrow yourself, so the current leader has no way to take part in (or block) a
vote against them.

## If it doesn't reach a majority

A vote has **48 hours** to reach its threshold. If it doesn't, it fails automatically and the nation
keeps its current leader. Nothing is lost by trying - a failed vote doesn't block a new one from
starting later.

## Staying in the loop

If you log in while your nation has an active vote, you'll get a reminder:

- Haven't voted yet? You'll be told the vote is underway and how to add your own (`/nation
  overthrow`).
- Already voted? No repeat reminder - you already know.
- You're the leader being challenged? You'll be told your leadership is being contested, with the
  current vote count.

A vote in progress survives a server restart - nothing about it resets just because the server goes
down and comes back up.
