# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T17:00:14Z**
- feed_generated_utc: 2026-10-31T17:00:15+00:00
- source_sha256: `d3c5bdc43ff01a27689225f001d63b831dbe8110126a95f99fbecac54c2a9a9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T17:00+00:00, close=77578.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T17:00+00:00, close=77578.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.031370|-5.14|-60.25|-5.15|10685651|3.19|
|BTW_USDT|1.095000|-4.06|-37.11|-4.07|7493412|6.39|
|WLD_USDT|0.399300|-1.26|-13.57|-1.27|40270194|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.095000|1.093600|1.095000|0.74|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031370|0.030480|0.031370|0.59|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399300|0.396600|0.399200|0.68|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T17:00:02+00:00, last15m_closed_end=2026-10-31T17:00+00:00, prior8high=1.152900, depth_time=2026-10-31T17:00:10+00:00, book20_bid_proxy_usdt=12173, book20_ask_proxy_usdt=29674, funding_indicative=-0.000238, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.06%, turnover=7493412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T17:00:02+00:00, last15m_closed_end=2026-10-31T17:00+00:00, prior8high=0.033470, depth_time=2026-10-31T17:00:08+00:00, book20_bid_proxy_usdt=41865, book20_ask_proxy_usdt=76414, funding_indicative=-0.000546, next_funding_utc=2026-10-31T18:00:00+00:00, funding_cycle_h=1, 24h_change=-5.14%, turnover=10685651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T17:00:02+00:00, last15m_closed_end=2026-10-31T17:00+00:00, prior8high=0.405900, depth_time=2026-10-31T17:00:11+00:00, book20_bid_proxy_usdt=3031813, book20_ask_proxy_usdt=2948949, funding_indicative=0.000008, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=40270194. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
