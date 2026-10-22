# Solista ($SOLISTA)

The whole site is one file, `index.html`. Upload it to any static host. You don't need a build step.

## Settings to edit
These are at the top of the `<script>` in `index.html`:

```js
var CONFIG = {
  xUrl: 'https://x.com/SolistaLive',
  xHandle: '@SolistaLive',
  token: '',     // $SOLISTA mint at launch (shows in the hero pill + address card, and links pump.fun)
  program: '',   // program address once deployed
  rpcUrl: 'https://api.mainnet-beta.solana.com'
};
```

## Features
- **Full-screen pixel meadow hero.**
  - **Scene:** drifting clouds, layered hills, a mossy seed vault with a leaf dial, a waving "$0.05 PAID" flag, a blossom tree with falling petals, swaying grass, wildflowers, butterflies, and bunnies, sprouts and a snail.
  - **Clicking:** click the ground to plant flowers, or click the critters.
  - **Modes:** Day, Golden hour or Night (with fireflies).
- **Sections, in the same layout as Nocta:**
  - a statement panel with leaf pixels that drift away from the cursor;
  - four products: Pay, Ask, Roots and Burrow;
  - a live panel (the latest Solana slot is read for real; pool stats switch on at launch);
  - a three-step "Plant / Grow / Bloom" explainer with small animations;
  - a merchant comparison table with animated footprint trails;
  - code tabs with a copy button;
  - address cards;
  - an FAQ.
- **Garden simulator (labelled SIMULATION):** deposit, then watch one-time wallets sprout, pay a merchant and wilt. It has an auto mode and a log. No funds move.

The site shows no contract address until you set `token`; the launch is posted on X.
