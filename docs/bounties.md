# Bounties

Pay someone to kill someone else. It's exactly what it sounds like.

## Placing a bounty

```
/bounty <target> <killer> <amount>
```

This offers **`<killer>`** a contract: kill **`<target>`** and get paid **`<amount>`** gold. The
gold is taken from you the moment you place the offer - it's held safely until the contract is
resolved one way or another, so you're never on the hook for more than you agreed to pay.

You have to be **within 10 blocks of the killer** (and they have to be online) to place the offer
- it's a face-to-face handoff, not something you can arrange remotely.

## Accepting or declining

The player you named as killer gets a private heads-up and has to respond:

```
/bounty accept
/bounty deny
```

If more than one offer is waiting for you, add the target's name to say which one you mean -
e.g. `/bounty accept Steve`.

- **Accept** and the clock starts: you have **48 hours** to land the kill.
- **Decline**, and the requester gets their gold back immediately.
- **Don't respond** within a few days and the offer quietly expires - the requester is refunded
  either way.

## The locator compass

The moment you accept a contract, you're handed a compass named **Locator: `<target>`** - its
needle actually points toward them, and its lore shows your live distance in blocks. Both update
every second while you're in the same world; if they're offline the lore says so instead, and if
they're in a different world the needle just holds its last direction until you're back in range.

It's a tracking tool for the contract, not a real item - it can be moved around your inventory
freely, but it can't be dropped, stashed in a chest or any other container, fed into crafting, or
nested inside a bundle/shulker box. It survives death rather than dropping, and disappears
automatically the moment the contract resolves - killed, or the window running out.

## Getting paid

Land the kill (PvP - melee or a projectile both count) within your 48-hour window and the payout
happens automatically. It's then announced to the whole server. If the window runs out first, the
contract fails and the requester's gold is refunded.

## Who knows what

Bounties are quiet by design:

- The **target is never told** they have a price on their head.
- Nobody but the requester and the killer hears about the offer, the accept/decline, or the
  countdown.
- The **only public moment** is a successful kill - that gets announced for everyone to see.
