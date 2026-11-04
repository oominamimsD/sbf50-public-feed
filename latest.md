# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T14:30:20Z**
- feed_generated_utc: 2026-11-04T14:30:22+00:00
- source_sha256: `3bfe1c3f3f390c4e5f14585d2eb1f5e4fab0c64d19746c9030caa2abeae7d469`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T14:30+00:00, close=78287.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T14:00+00:00, close=78338.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.036570|-32.03|-23.04|-32.89|7815201|8.18|
|AKE_USDT|0.003156|-24.06|-85.06|-24.92|14743805|6.34|
|HOT_USDT|0.000472|-12.40|36.53|-13.26|5273382|4.24|
|TRUMPOFFICIAL_USDT|1.410000|-12.31|-16.46|-13.17|13144550|7.10|
|ZRO_USDT|1.822300|-3.79|8.10|-4.65|11578946|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.036570|0.032170|0.036600|2.01|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.003156|0.002758|0.003160|1.50|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000472|0.000466|0.000471|0.47|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.410000|1.407000|1.410000|1.47|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.822300|1.812400|1.822000|2.02|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T14:30:03+00:00, last15m_closed_end=2026-11-04T14:30+00:00, prior8high=0.037160, depth_time=2026-11-04T14:30:08+00:00, book20_bid_proxy_usdt=17126, book20_ask_proxy_usdt=28161, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.03%, turnover=7815201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T14:30:03+00:00, last15m_closed_end=2026-11-04T14:30+00:00, prior8high=0.003257, depth_time=2026-11-04T14:30:12+00:00, book20_bid_proxy_usdt=36320, book20_ask_proxy_usdt=39753, funding_indicative=-0.000059, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.06%, turnover=14743805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T14:30:03+00:00, last15m_closed_end=2026-11-04T14:30+00:00, prior8high=0.000498, depth_time=2026-11-04T14:30:13+00:00, book20_bid_proxy_usdt=64868, book20_ask_proxy_usdt=82416, funding_indicative=-0.000268, next_funding_utc=2026-11-04T15:00:00+00:00, funding_cycle_h=1, 24h_change=-12.40%, turnover=5273382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T14:30:03+00:00, last15m_closed_end=2026-11-04T14:30+00:00, prior8high=1.453000, depth_time=2026-11-04T14:30:17+00:00, book20_bid_proxy_usdt=2515885, book20_ask_proxy_usdt=2137964, funding_indicative=-0.000394, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.31%, turnover=13144550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T14:30:03+00:00, last15m_closed_end=2026-11-04T14:30+00:00, prior8high=1.888300, depth_time=2026-11-04T14:30:19+00:00, book20_bid_proxy_usdt=26978, book20_ask_proxy_usdt=59442, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=11578946. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
