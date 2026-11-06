# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T09:30:15Z**
- feed_generated_utc: 2026-11-06T09:30:16+00:00
- source_sha256: `dadab96c0b3856c8694dfae63e50ad36db48632407f61b3e54aef5e4b97f6994`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T09:30+00:00, close=76122.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T09:00+00:00, close=75643, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|268.370000|-3.85|-6.90|-3.99|7539324|2.24|
|XRP_USDT|1.199400|-3.63|-8.40|-3.77|476334780|0.83|
|XPL_USDT|0.057610|-1.65|-27.01|-1.79|12184196|1.74|
|QNT_USDT|189.300000|-1.31|-4.74|-1.45|36631190|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.370000|261.500000|268.370000|1.75|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.300000|187.280000|189.300000|0.97|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057610|0.056650|0.057610|0.58|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.199400|1.177100|1.199400|1.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T09:30:00+00:00, last15m_closed_end=2026-11-06T09:30+00:00, prior8high=268.950000, depth_time=2026-11-06T09:30:07+00:00, book20_bid_proxy_usdt=40433, book20_ask_proxy_usdt=51980, funding_indicative=-0.000017, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=7539324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T09:30:00+00:00, last15m_closed_end=2026-11-06T09:30+00:00, prior8high=190.420000, depth_time=2026-11-06T09:30:14+00:00, book20_bid_proxy_usdt=125096, book20_ask_proxy_usdt=98013, funding_indicative=0.000048, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=36631190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T09:30:00+00:00, last15m_closed_end=2026-11-06T09:30+00:00, prior8high=0.057950, depth_time=2026-11-06T09:30:12+00:00, book20_bid_proxy_usdt=480314, book20_ask_proxy_usdt=346989, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=12184196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T09:30:00+00:00, last15m_closed_end=2026-11-06T09:30+00:00, prior8high=1.196200, depth_time=2026-11-06T09:30:09+00:00, book20_bid_proxy_usdt=4266440, book20_ask_proxy_usdt=3919060, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=476334780. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
