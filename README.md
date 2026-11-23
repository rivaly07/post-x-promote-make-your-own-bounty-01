# post-x-promote-make-your-own-bounty-01

Entry for the "Promote make.fun's make-your-own-bounty post on X" competition.

## Structure

- `main.ts` - Copies POST.json to /output (Node 22, standard library only)
- `POST.json` - Contains the X post URL (to be updated after posting)
- `LICENSE` - MIT License

## Competition

Quote or link make.fun's make-your-own-bounty post (https://x.com/makefunai/status/2124915864336236646) in a post of your own on X with a photo, make.fun/@makefunai tag, and play code. Top 50 posts by replies+reposts+quotes share $250.

## Usage

```bash
mkdir -p out
MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```