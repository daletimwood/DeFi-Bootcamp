# Forward Notice: Tokenisation and Digital Payment Regulation

A monthly register of cryptoasset, stablecoin, tokenisation and digital payment regulation that creates deadlines or obligations for blockchain infrastructure vendors: oracle networks, cross-chain interoperability, proof-of-reserve and NAV reporting, and tokenised fund workflow.

Page: https://daletimwood.github.io/DeFi-Bootcamp/forward-notice/

## Files

- `register.json` is the source of truth. One entry per instrument: jurisdiction, instrument, body, stage, key dates, who is obliged, effect on vendors, horizon, confidence, primary sources, date last verified and a change log.
- `index.html` renders the register. The data sits in a single `<script id="register" type="application/json">` block; an update replaces only that block.
- `YYYYMMDD index.html` files are earlier versions of the page, kept unchanged.

## Method

- Primary sources only: regulators, legislatures, official journals and standard setters. Secondary sources are used only to locate primary ones.
- Relative deadlines (for example, "60 days after Federal Register publication") are recorded as stated, not converted into calendar dates.
- Effect on vendors is one of: direct, passed down via customers, demand driver, constraint. Definitions are on the page.
- Horizon runs from the update date to the next dated milestone.
- Entries are never deleted. A withdrawn instrument is marked withdrawn, and every change is logged with its date.

Updated monthly. Not legal advice: whether a rule applies to a particular firm depends on what that firm does and where.
