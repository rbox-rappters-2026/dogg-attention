# dogg-attention — a federated node of the global tick network

**What humanity is looking at, per tick: Hacker News front page, Lobsters hottest,
yesterday's most-read Wikipedia articles.**

This node is operated by RapterBox (rbox-rappters-2026) — a DIFFERENT owner than the
spine at [kody-w/dogg](https://github.com/kody-w/dogg), which is the point: the network
is cross-owner by construction. Its chain lives in `attention/`, appended every half
hour by a GitHub Action, each frame referencing the spine's current tick anchor.
Verify: `python3 tools/verify_thread.py`. Fork it, change three lines, run your own.
