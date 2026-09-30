# Blockchain Infographic

An interactive, plain-language explainer of how Bitcoin's blockchain works, built as a classroom resource.

**Live site:** https://byrevive.github.io/blockchain-infographic/

## What's inside

- **The problem**: a two-click demo of double-spending, with and without a shared ledger
- **Inside a block**: the real Bitcoin genesis block, field by field
- **Hash lab**: type anything and watch its SHA-256 fingerprint change
- **Tamper lab**: edit a payment in a four-block chain, see what breaks, then try to cover your tracks by re-mining
- **Mine a block**: proof of work with adjustable difficulty, starting from a random nonce every run
- **Confirmations chart**: reversal odds from Nakamoto's 2008 paper (§11)
- **Check yourself**: a four-question quiz

## Running it

It's a single self-contained `index.html` with no build step and no dependencies. Hashing runs in the page, so everything works offline (only the web fonts need a connection, and they fall back cleanly).

Open `index.html` in any browser, or visit the live site.
