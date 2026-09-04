# Random Teleport (RTP)

`/rtp` (alias `/wild`) scatters you to a random, safe, unclaimed surface spot in the overworld -
useful for finding a fresh place to settle, or just exploring somewhere new.

- Always lands on the true **surface** (never a cave), and never inside water, lava, or another
  hazard.
- Never lands inside a **nation's claim** - you'll always arrive on free land.
- Stays within the world border.
- There's a **cooldown** *(default: 2 hours)* between uses.

## First join

Brand-new players are scattered to a random claim-free spot automatically on their **first join**,
instead of a fixed spawn hub - so everyone starts somewhere different. This doesn't use up your
`/rtp` cooldown, and lands you a bit closer in than a manual `/rtp` would.

## If it fails

If no safe spot can be found after several attempts (rare), you'll be told to just try again -
nothing is lost, and no cooldown is consumed on a failed attempt.
