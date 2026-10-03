# StableLedger
*Stablecoin tax CSV normalizer for freelancers and small business. A commercial product by Payload (v1.0.0).*
> **Payload** — small, sharp tools for developers. Developer portal: https://payloadhq.github.io/


Paid in USDC or USDT? Come tax season you face a choice: free developer CLI tools, $49–199/yr trader software that doesn't understand invoicing, or $299+/month enterprise accounting suites.

StableLedger is the fourth option: a one-time $49 utility that turns your exchange CSV exports into a clean, accountant-ready ledger. Runs offline — your financial exports never leave your machine.

**What's inside the paid kit**
- One command normalizes Coinbase, Binance, Kraken, or generic CSVs into a universal ledger: date, type, asset, amount, price, fees, tx id, source
- `ledger.csv` — hand this directly to your accountant
- `summary.csv` — per-asset totals plus simplified realized gain/loss (average cost)
- Case-insensitive header matching with aliases, so export format drift doesn't break it
- Unknown formats fail loudly instead of silently mis-parsing
- Sample exports included so you can try it before trusting it with real data

Setup (2 minutes): install Python 3.8+ (no third-party packages), export your CSV, run `python -m stableledger your_export.csv`, open ledger.csv and summary.csv.

Note: the summary uses simplified average-cost math as a bookkeeping aid — not tax advice. Your accountant makes the filing decisions; StableLedger gives them clean data.

**Buy** — $49 one-time. Yours forever. No subscriptions, no lock-in.
[Get StableLedger](https://payloadtools.gumroad.com/l/stableledger-tax-csv)

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

**Support** — kylers.partners@gmail.com

Sold by Payload. Small software that earns its keep.

---

**Payload** — small, sharp tools for developers.
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com
