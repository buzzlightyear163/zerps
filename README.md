# ZEROS

Hash for zeros. The deepest one wins.

Browser SHA-256 mining for $ZEROS. Your tab searches for hashes with leading zero bits, every proof is re-checked, and the deepest hash of each round takes a bonus. Testnet beta: peers are simulated and nothing is paid until mainnet.

## Files

- `index.html`: the whole site (miner, 3D shaft, console). three.js loads from cdnjs.
- `og.png`: share image for X and other link previews.
- `icon.png`: favicon and home-screen icon.
- `shaft.jpg`: fallback image when WebGL isn't available.

## Before launch

Open `index.html` and edit `CONFIG` near the top of the main script:

- `ca`: the contract address, once the coin exists on chain
- `xUrl`: the X profile link

When the domain is live, change `og:image` and `twitter:image` in the head to the full URL, for example `https://yourdomain/og.png`.

Deploy as a static site (Vercel: import the repo, no build step).
