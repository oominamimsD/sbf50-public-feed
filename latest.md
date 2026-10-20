# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T08:30:33Z**
- feed_generated_utc: 2026-10-20T08:30:36+00:00
- source_sha256: `f3f9009dd5dd857e1b0c86cfa7b4b05af58bd820e0971c95451487a30fa68313`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T08:30+00:00, close=81500.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.069674|-19.95|318.16|-19.44|10715367|4.45|
|BTW_USDT|1.532600|-12.52|-12.71|-12.01|31914908|2.61|
|Q_USDT|0.120144|-4.63|290.19|-4.12|6684362|1.58|
|SAND_USDT|0.056580|-4.32|-8.87|-3.81|7299667|1.77|
|NEAR_USDT|4.736000|-3.42|-14.65|-2.91|164509760|2.11|
|ATOM_USDT|1.728000|-2.70|-5.47|-2.19|5198360|5.79|
|ARB_USDT|0.190530|-2.60|1.09|-2.09|96077722|0.53|
|QNT_USDT|191.840000|-1.97|-15.99|-1.46|81337930|0.52|
|TAO_USDT|263.010000|-1.97|-8.13|-1.46|57052335|1.14|
|UNI_USDT|7.150000|-1.89|-3.61|-1.38|10000105|1.40|
|SEI_USDT|0.059730|-1.54|-10.00|-1.03|6753088|1.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.069674|0.074750|0.069683|4.14|Y|Y/Y|N/N|Y|N|
|ARB_USDT|0.190530|0.190220|0.190530|0.79|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.728000|1.731000|1.728000|3.19|Y|Y/N|N/N|Y|N|
|BTW_USDT|1.532600|1.571700|1.534400|3.69|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.736000|4.727000|4.736000|0.87|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.840000|189.730000|191.910000|1.24|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.120144|0.116403|0.120079|0.49|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056580|0.056480|0.056590|0.21|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059730|0.059680|0.059750|0.71|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.010000|262.780000|263.140000|1.70|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.150000|7.121000|7.153000|1.83|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=0.085987, depth_time=2026-10-20T08:30:08+00:00, book20_bid_proxy_usdt=25255, book20_ask_proxy_usdt=97661, funding_indicative=0.000104, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.95%, turnover=10715367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=0.199790, depth_time=2026-10-20T08:30:22+00:00, book20_bid_proxy_usdt=61172, book20_ask_proxy_usdt=115136, funding_indicative=-0.000025, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=96077722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=1.757000, depth_time=2026-10-20T08:30:18+00:00, book20_bid_proxy_usdt=1171266, book20_ask_proxy_usdt=1205555, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=5198360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=1.772400, depth_time=2026-10-20T08:30:11+00:00, book20_bid_proxy_usdt=18084, book20_ask_proxy_usdt=11973, funding_indicative=-0.004885, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.52%, turnover=31914908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=4.806000, depth_time=2026-10-20T08:30:18+00:00, book20_bid_proxy_usdt=4211007, book20_ask_proxy_usdt=2192361, funding_indicative=-0.000008, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=164509760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=194.060000, depth_time=2026-10-20T08:30:24+00:00, book20_bid_proxy_usdt=65270, book20_ask_proxy_usdt=76104, funding_indicative=0.000025, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=81337930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=0.124230, depth_time=2026-10-20T08:30:13+00:00, book20_bid_proxy_usdt=17333, book20_ask_proxy_usdt=17320, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.63%, turnover=6684362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=0.057290, depth_time=2026-10-20T08:30:16+00:00, book20_bid_proxy_usdt=1138302, book20_ask_proxy_usdt=1029083, funding_indicative=-0.001382, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=7299667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=0.060420, depth_time=2026-10-20T08:30:32+00:00, book20_bid_proxy_usdt=417559, book20_ask_proxy_usdt=210246, funding_indicative=0.000031, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=6753088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=266.450000, depth_time=2026-10-20T08:30:27+00:00, book20_bid_proxy_usdt=239950, book20_ask_proxy_usdt=60331, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=57052335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T08:30:02+00:00, last15m_closed_end=2026-10-20T08:30+00:00, prior8high=7.224000, depth_time=2026-10-20T08:30:30+00:00, book20_bid_proxy_usdt=2008188, book20_ask_proxy_usdt=2002396, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=10000105. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
