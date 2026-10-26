# Active locks

One writer per portfolio repo at a time. Claim by committing a row here **before** pushing to that repo. Release by removing the row when done.

| repo | holder | claimed_at (ET) | purpose |
| --- | --- | --- | --- |
| Jagadish-agent-commerce-streaming | grokbot-portfolio | 2026-10-23 21:08 | initial build + standardization |
| Jagadish-agent-training-distill-rl | grokbot-portfolio | 2026-10-23 21:08 | initial build + standardization |
| Jagadish-finance-kyc-aml-pipeline | external-assistant | 2026-10-26 08:40 | email CI-refusal fix |
| Jagadish-finance-credit-memo | external-assistant | 2026-10-26 08:40 | email CI-refusal fix + scorer import fix |
| Jagadish-finance-portfolio-risk-agent | external-assistant | 2026-10-26 08:40 | email CI-refusal fix |
| Jagadish-finance-bank-in-a-box | external-assistant | 2026-10-26 08:40 | email CI-refusal fix |
| Jagadish-finance-governance-poc | external-assistant | 2026-10-26 08:40 | email CI-refusal fix |

## Holders

| holder id | who |
| --- | --- |
| `grokbot-portfolio` | Portfolio / GitHub fixing assistant (this side) |
| `external-assistant` | Jagadishs other assistant (builds and betterment batches) |
| `jagadish` | Jagadish Meduri (the owner) |
