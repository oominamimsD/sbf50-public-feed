# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T17:15:13Z**
- feed_generated_utc: 2026-10-31T17:15:14+00:00
- source_sha256: `7c85f05e802f418d4b508c7144ded95bf78f50196557f187f667c22384c18990`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T17:15+00:00, close=77591, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T17:00+00:00, close=77578.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.104300|-1.56|-36.58|-1.59|7596417|4.53|
|WLD_USDT|0.398200|-1.53|-13.80|-1.56|40869910|2.51|
|Q_USDT|0.031610|-1.46|-59.95|-1.49|10707374|3.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.104300|1.091300|1.104200|1.84|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031610|0.030480|0.031610|0.54|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398200|0.397600|0.398200|1.69|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T17:15:00+00:00, last15m_closed_end=2026-10-31T17:15+00:00, prior8high=1.152900, depth_time=2026-10-31T17:15:07+00:00, book20_bid_proxy_usdt=14897, book20_ask_proxy_usdt=15921, funding_indicative=-0.000283, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=7596417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T17:15:00+00:00, last15m_closed_end=2026-10-31T17:15+00:00, prior8high=0.033260, depth_time=2026-10-31T17:15:11+00:00, book20_bid_proxy_usdt=56287, book20_ask_proxy_usdt=43788, funding_indicative=-0.000499, next_funding_utc=2026-10-31T18:00:00+00:00, funding_cycle_h=1, 24h_change=-1.46%, turnover=10707374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T17:15:00+00:00, last15m_closed_end=2026-10-31T17:15+00:00, prior8high=0.405900, depth_time=2026-10-31T17:15:10+00:00, book20_bid_proxy_usdt=2874993, book20_ask_proxy_usdt=2584468, funding_indicative=0.000009, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=40869910. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
