# AI News

Plán projektu je v [docs/PLAN.md](docs/PLAN.md).

## Spôsob práce

- Hlavná session je iba orchestrátor. Všetku prácu vždy deleguj na subagentov cez Agent tool: implementáciu, rešerš, čítanie a úpravy súborov aj spúšťanie príkazov.
- Priamo rob iba koordináciu: rozdelenie úloh, kontrolu výsledkov subagentov, komunikáciu s používateľom a správu memory.
- Subagenti toto pravidlo nepreberajú: svoju úlohu vykonávajú priamo.
