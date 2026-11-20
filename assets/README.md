# Assets

| File | Type | What it is |
|---|---|---|
| `banner.svg` | Conceptual brand art | Hero banner for the README (labeled conceptual — not a live screenshot) |
| `architecture-pipeline.svg` | Conceptual diagram | Discovery → tracking pipeline + 17 logical roles |
| `roles-vs-models.svg` | Conceptual diagram | Logical roles vs independently running AI models |
| `mission-control-army.png` | **Real** screenshot | Local Mission Control Agent Army (sample empty DB; Cursor tasks redacted) |
| `mission-control-opportunities.png` | **Real** screenshot | Opportunities panel (zeros / empty sample data) |
| `mission-control-execution.png` | **Real** screenshot | Execution gate; Actual paid $0.00 |
| `mission-control-earnings.png` | **Real** screenshot | Earnings ledger all $0.00 |
| `mission-control-discovery.png` | **Real** screenshot | Discovery lane on sample empty DB |

## Capture notes

- Source: `python3 -m moneyminer army-serve` on `127.0.0.1` with a fresh empty SQLite file  
- Private Cursor/PR task rows were DOM-redacted before capture  
- Live UI reported `roles: 11` (base set on that checkout); architecture docs describe the full ~17-role design  

## Operator follow-ups (optional)

- Working-state army diagram without private URLs in activity text  
- Sanitized awaiting-approval example rows  
- 45–90s recording per `docs/demo-storyboard.md`  
