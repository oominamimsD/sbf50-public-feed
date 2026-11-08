# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T23:30:20Z**
- feed_generated_utc: 2026-11-08T23:30:22+00:00
- source_sha256: `ad113a57a518891a3db65cc2464723c80a9e7431a3ae5dc5acd67dd62c385967`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T23:30+00:00, close=75380.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T23:00+00:00, close=74432.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001720|-12.17|47.66|-11.31|12549737|0.58|
|DASH_USDT|45.820000|-4.16|-5.72|-3.30|14888909|2.18|
|WLD_USDT|0.315000|-3.34|-20.39|-2.48|29822117|3.17|
|LIT_USDT|3.100500|-2.90|-4.01|-2.04|10616341|0.32|
|HYPE_USDT|75.323000|-2.72|-14.10|-1.86|35566137|0.13|
|UNI_USDT|6.859000|-2.05|-5.47|-1.19|30804753|1.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|45.820000|44.290000|45.820000|2.11|N|Y/Y|N/N|Y|N|
|HYPE_USDT|75.323000|73.578000|75.323000|0.78|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.100500|3.007700|3.100000|2.01|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001720|0.001607|0.001720|0.86|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.859000|6.616000|6.859000|1.09|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.315000|0.301700|0.315000|2.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-08T23:29:59+00:00, last15m_closed_end=2026-11-08T23:30+00:00, prior8high=47.240000, depth_time=2026-11-08T23:30:06+00:00, book20_bid_proxy_usdt=512371, book20_ask_proxy_usdt=488719, funding_indicative=0.000057, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=14888909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T23:29:59+00:00, last15m_closed_end=2026-11-08T23:30+00:00, prior8high=76.222000, depth_time=2026-11-08T23:30:17+00:00, book20_bid_proxy_usdt=94252, book20_ask_proxy_usdt=34731, funding_indicative=0.000039, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=35566137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T23:29:59+00:00, last15m_closed_end=2026-11-08T23:30+00:00, prior8high=3.171300, depth_time=2026-11-08T23:30:15+00:00, book20_bid_proxy_usdt=33361, book20_ask_proxy_usdt=28960, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=10616341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T23:29:59+00:00, last15m_closed_end=2026-11-08T23:30+00:00, prior8high=0.001757, depth_time=2026-11-08T23:30:07+00:00, book20_bid_proxy_usdt=6747, book20_ask_proxy_usdt=11089, funding_indicative=-0.000543, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.17%, turnover=12549737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-08T23:29:59+00:00, last15m_closed_end=2026-11-08T23:30+00:00, prior8high=6.962000, depth_time=2026-11-08T23:30:19+00:00, book20_bid_proxy_usdt=1716369, book20_ask_proxy_usdt=1549025, funding_indicative=0.000032, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=30804753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T23:29:59+00:00, last15m_closed_end=2026-11-08T23:30+00:00, prior8high=0.321600, depth_time=2026-11-08T23:30:12+00:00, book20_bid_proxy_usdt=4442680, book20_ask_proxy_usdt=2730056, funding_indicative=-0.000111, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=29822117. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
