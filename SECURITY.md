# Security & privacy (public showcase)

This repository is a **presentation-only** portfolio for MoneyMiner. It must never contain secrets or private product material.

## Hard rules

- Do **not** commit API tokens, OAuth secrets, cookies, `.env` files, or SSH keys  
- Do **not** commit SQLite databases, ledger dumps, or activity logs  
- Do **not** publish private system prompts, bounty strategy docs, or internal issue logs  
- Do **not** imply verified earnings above **$0** or autonomous payouts  
- Do **not** link the private product repository as if it were public  
- Screenshots must use empty/sample/redacted data only  

## Audit checklist (run before every push)

- [ ] `git status` / `git log` show only intentional showcase files  
- [ ] No `*.db`, `.env`, `credentials*`, or key material  
- [ ] README earnings language still says **$0**  
- [ ] Images under `assets/` reviewed for tokens, emails, private URLs, bank data  
- [ ] Repo visibility remains **public** for *this* showcase only; product repo stays **private**  
- [ ] No copied private docs verbatim  

## Reporting

If you find sensitive material in this public repo, open an issue on **this** repository describing the path (do not paste the secret). The operator will rotate credentials and purge history if needed.
