<p align="center"><img src="docs/logo.png" alt="stableledger logo" width="200"></p>
# StableLedger

*Turn your stablecoin exchange CSV exports into an accountant-ready ledger. A commercial product by Payload.*

> **This repo is the product page.** The paid package ships to you when you buy; it is not open source. Buy links are below.

Paid in USDC or USDT? Come tax season you face a choice: free developer CLI tools, $49–199/yr trader software that doesn't understand invoicing, or $299+/month enterprise accounting suites.

StableLedger is the fourth option: a one-time $49 utility that turns your exchange CSV exports into a clean, accountant-ready ledger. Runs offline — your financial exports never leave your machine.

## Who it's for

Freelancers and small businesses paid in USDC or USDT who need clean records for their accountant at tax time — without cloud accounting software or per-record fees.

## What you receive

The paid package ($49, one-time) includes:

- **One command** that normalizes Coinbase, Binance, Kraken, or generic CSVs into a universal ledger: date, type, asset, amount, price, fees, tx id, source
- **`ledger.csv`** — hand this directly to your accountant
- **`summary.csv`** — per-asset totals plus simplified realized gain/loss (average cost)
- **Case-insensitive header matching with aliases**, so export format drift doesn't break it
- **Loud failure on unknown formats** instead of silently mis-parsing
- **Sample exports** so you can try it before trusting it with real data

Setup (2 minutes): install Python 3.8+ (no third-party packages), export your CSV, run `python -m stableledger.cli --input your_export.csv --format coinbase --outdir ./out`, then open `./out/ledger.csv` and `./out/summary.csv`. Use `binance`, `kraken`, or `generic` for `--format` to match your export.

## What it does NOT include

- **Not tax advice.** The summary uses simplified average-cost math as a bookkeeping aid. Your accountant makes the filing decisions; StableLedger gives them clean data.
- It does not connect to exchanges or import anything automatically. You export the CSV; StableLedger normalizes it.
- It does not file anything. It produces the ledger and summary your accountant works from.

## Buy

**$49 one-time. Yours forever. No subscriptions, no lock-in.**

[Get StableLedger](https://payloadtools.gumroad.com/l/stableledger-tax-csv)

**License** — Single-seat commercial license, perpetual. Full text ships inside the package (LICENSE.txt). Not open source.

## Support and updates

- Support: kylers.partners@gmail.com
- Sold and supported by Payload. Small software that earns its keep.

---

**Payload** — small, sharp tools for developers.
Developer portal: https://payloadhq.github.io/ ·
All products: https://payloadtools.gumroad.com/ ·
Contact: kylers.partners@gmail.com
