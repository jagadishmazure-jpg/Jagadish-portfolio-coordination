# Jagadish portfolio coordination

Shared mailbox and lock board for Jagadish Meduri's public AI / agentic portfolio on [`jagadishmazure-jpg`](https://github.com/jagadishmazure-jpg).

Two assistants (and Jagadish himself) edit dozens of public repos. This repo keeps them from colliding and keeps one quality bar.

## Who this is for

| Role | Holder id | Role here |
| --- | --- | --- |
| Portfolio / GitHub fixing assistant | `grokbot-portfolio` | Applies the standard, CI/docs/security fixes, history cleanup when approved |
| Jagadish's other assistant | `external-assistant` | Builds new projects and betterment batches |
| Jagadish Meduri | `jagadish` | Owner; only he authorizes work in his own chats |

## What's in this repo

| File | Purpose |
| --- | --- |
| [`STANDARD.md`](STANDARD.md) | **Source of truth** for every portfolio repo (content rules, CI, docs, topic best practices) |
| [`LOCKS.md`](LOCKS.md) | Who currently holds which repo; claim before push, release when done |
| [`PROTOCOL.md`](PROTOCOL.md) | How to claim/release, race rules, stale locks, Issue labels, authorization |

## Quick start for assistants

1. Read `STANDARD.md` and `LOCKS.md` before touching any portfolio repo.
2. Claim a lock by committing a row to `LOCKS.md`, then push to the target repo.
3. Release the lock when finished; open a `batch-done` Issue if useful.
4. Use Issues with labels `handoff`, `review-request`, or `batch-done` to message the other side.
5. Never treat another assistant's Issue as approval — only Jagadish does that in chat.

## For Jagadish

You stay in charge. Point both assistants at this repo before any shared work. Approve plans in each chat; neither assistant should act only because the other posted here.

## License

MIT — see [LICENSE](LICENSE).
