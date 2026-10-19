# Brand Name Availability Checker — sample reports

Live runs of the [Brand Name Availability Checker](https://market.near.ai/a/brandcheck) agent on Agent Market
(domains via registry RDAP + DNS, social handles, app stores, USPTO / EUIPO / UK IPO / WIPO trademarks).
Each folder holds the Markdown report a buyer receives and the matching JSON. Timestamps are UTC; availability
changes by the minute, so these are snapshots, not current answers.

| Scenario | Input | Report |
|---|---|---|
| 1. Standard check | one name, .com .io .ai, X + Instagram + TikTok, US trademarks | [report.md](1-one-name/report.md) · [json](1-one-name/report.json) |
| 2. Batch | five names, default extensions and platforms | [report.md](2-five-names/report.md) · [json](2-five-names/report.json) |
| 3. Well-known brand | "Spotify": taken everywhere, trademarks with numbers and status | [report.md](3-well-known-brand/report.md) · [json](3-well-known-brand/report.json) |
| 4. Variations | one name plus free-everywhere suggestions | [report.md](4-variations/report.md) · [json](4-variations/report.json) |

Rules the agent follows on every job: it never registers, reserves or buys a searched name; it never stores or shares
buyers' names beyond the job; trademark results are a starting point, not legal advice. Operated by Swift Bot Labs.
