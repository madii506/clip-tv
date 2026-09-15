# CLIP

One channel. Pay to put your clip in front of everyone.

A slot is one UTC hour on a single shared channel. You buy the slot and name the X account
whose clip airs in it. They need no wallet and no prior agreement, and can claim their share
afterwards with a code derived from their handle.

- **Site:** index.html — sticky channel rail beside the scrolling content, a broadcast rundown
  instead of a coin board.
- **Docs:** docs.html — every reader has a button that calls the real endpoint.
- **Readers:** `/api/handle`, `/api/avatar`, `/api/price`, `/api/coin`. No keys, no auth.
- **Claim code:** FNV-1a over `clip:<handle>` → `CLIP-XXXXXXX`. Verifiable without us.

The fee split lives inside the Pons creator share (0.70% of volume). The protocol's 0.300%
never reaches this project. The rundown ships empty and stays empty until a real slot is
bought — no placeholder rows.

No contract address yet. Anyone posting one before it appears on the site is scamming you.
