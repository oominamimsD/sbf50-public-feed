# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T06:15:21Z**
- feed_generated_utc: 2026-11-08T06:15:22+00:00
- source_sha256: `b091b51419dd1fe3dccea7a453341c400b32666a546115c3c4bf8faa12487175`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T06:15+00:00, close=75757.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T06:00+00:00, close=75800, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005148|-13.95|-53.77|-13.99|40472294|3.89|
|ONE_USDT|0.001910|-6.21|62.67|-6.25|26086369|0.52|
|ENA_USDT|0.154690|-2.20|-20.26|-2.24|28389910|0.65|
|TIA_USDT|0.433400|-1.85|-11.56|-1.89|7460954|2.31|
|WLD_USDT|0.330400|-1.54|-18.29|-1.58|23385178|3.03|
|QNT_USDT|195.900000|-1.48|-2.56|-1.52|45913598|2.55|
|ONDO_USDT|0.358900|-1.15|-12.97|-1.19|8601473|2.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005148|0.005077|0.005148|0.53|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.154690|0.153230|0.154690|0.44|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358900|0.357400|0.358900|0.16|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001910|0.001804|0.001910|1.35|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.900000|193.770000|195.900000|0.44|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.433400|0.432200|0.433400|2.39|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330400|0.329900|0.330400|1.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=0.005418, depth_time=2026-11-08T06:15:06+00:00, book20_bid_proxy_usdt=58323, book20_ask_proxy_usdt=46235, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.95%, turnover=40472294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=0.154920, depth_time=2026-11-08T06:15:04+00:00, book20_bid_proxy_usdt=234405, book20_ask_proxy_usdt=255812, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=28389910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=0.361500, depth_time=2026-11-08T06:15:20+00:00, book20_bid_proxy_usdt=1465992, book20_ask_proxy_usdt=1387506, funding_indicative=-0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=8601473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=0.002018, depth_time=2026-11-08T06:15:08+00:00, book20_bid_proxy_usdt=19452, book20_ask_proxy_usdt=16317, funding_indicative=-0.000073, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.21%, turnover=26086369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=196.790000, depth_time=2026-11-08T06:15:18+00:00, book20_bid_proxy_usdt=89953, book20_ask_proxy_usdt=54172, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=45913598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=0.438300, depth_time=2026-11-08T06:15:13+00:00, book20_bid_proxy_usdt=296463, book20_ask_proxy_usdt=309435, funding_indicative=0.000026, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=7460954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T06:14:59+00:00, last15m_closed_end=2026-11-08T06:15+00:00, prior8high=0.332600, depth_time=2026-11-08T06:15:15+00:00, book20_bid_proxy_usdt=3712503, book20_ask_proxy_usdt=3555897, funding_indicative=-0.000166, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=23385178. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
