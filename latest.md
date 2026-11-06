# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T11:00:44Z**
- feed_generated_utc: 2026-11-06T11:00:46+00:00
- source_sha256: `d7adfb9c8a58162af48a6be7bcd6aad47f3893516b7531cdc8628f743799ca3a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T11:00+00:00, close=76033.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T11:00+00:00, close=76033.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|267.540000|-6.06|-7.19|-6.10|7351887|2.62|
|QNT_USDT|189.370000|-5.14|-4.71|-5.18|34979483|0.53|
|ATOM_USDT|1.405000|-4.81|-13.85|-4.85|6845502|7.12|
|DASH_USDT|45.510000|-4.57|-11.61|-4.61|15321500|2.20|
|ZRO_USDT|1.623300|-4.32|-7.99|-4.36|7255995|0.62|
|PUMPFUN_USDT|0.003951|-4.19|-12.68|-4.23|11174947|2.53|
|XRP_USDT|1.195800|-3.92|-8.68|-3.96|476820205|0.84|
|PENGU_USDT|0.006662|-3.54|-18.06|-3.58|5721779|1.50|
|TIA_USDT|0.424400|-3.30|-22.72|-3.34|11194256|2.35|
|NEAR_USDT|3.743000|-3.23|-19.48|-3.27|71831411|2.67|
|ONDO_USDT|0.376900|-3.11|-12.30|-3.15|27233435|2.65|
|AVAX_USDT|8.346000|-2.23|-7.30|-2.27|19074469|1.20|
|LTC_USDT|52.910000|-2.10|-9.72|-2.14|8202084|1.89|
|HBAR_USDT|0.068510|-1.58|-8.98|-1.62|9510419|1.46|
|XPL_USDT|0.057740|-1.43|-26.84|-1.47|12165256|1.73|
|XAUT_USDT|4049.720000|-1.07|0.70|-1.11|182382769|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.405000|1.409000|1.405000|0.16|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.346000|8.236000|8.346000|0.34|N|N/Y|Y/Y|Y|N|
|BCH_USDT|267.540000|265.820000|267.540000|0.84|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.510000|44.670000|45.510000|0.10|N|N/Y|Y/Y|Y|N|
|HBAR_USDT|0.068510|0.067980|0.068510|1.77|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|52.910000|52.270000|52.910000|0.66|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|3.743000|3.710000|3.743000|1.38|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.376900|0.373000|0.376900|0.70|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.006662|0.006614|0.006662|0.97|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003951|0.003934|0.003951|0.64|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.370000|188.370000|189.370000|0.65|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.424400|0.417300|0.424400|0.91|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.057740|0.057490|0.057750|0.90|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.195800|1.187400|1.196000|1.31|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.623300|1.595000|1.623300|5.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=1.423000, depth_time=2026-11-06T11:00:12+00:00, book20_bid_proxy_usdt=1914937, book20_ask_proxy_usdt=1953831, funding_indicative=0.000046, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.81%, turnover=6845502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=8.370000, depth_time=2026-11-06T11:00:35+00:00, book20_bid_proxy_usdt=2227233, book20_ask_proxy_usdt=1602547, funding_indicative=0.000031, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=19074469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=269.310000, depth_time=2026-11-06T11:00:07+00:00, book20_bid_proxy_usdt=46817, book20_ask_proxy_usdt=86368, funding_indicative=-0.000053, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.06%, turnover=7351887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=45.690000, depth_time=2026-11-06T11:00:14+00:00, book20_bid_proxy_usdt=774465, book20_ask_proxy_usdt=628256, funding_indicative=0.000036, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.57%, turnover=15321500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=0.068720, depth_time=2026-11-06T11:00:40+00:00, book20_bid_proxy_usdt=1014618, book20_ask_proxy_usdt=788747, funding_indicative=0.000039, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=9510419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=52.970000, depth_time=2026-11-06T11:00:35+00:00, book20_bid_proxy_usdt=1725117, book20_ask_proxy_usdt=1752436, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=8202084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-06T11:00:02+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=3.756000, depth_time=2026-11-06T11:00:30+00:00, book20_bid_proxy_usdt=3833917, book20_ask_proxy_usdt=2310532, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=71831411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=0.377900, depth_time=2026-11-06T11:00:33+00:00, book20_bid_proxy_usdt=1690107, book20_ask_proxy_usdt=1716546, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=27233435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=0.006710, depth_time=2026-11-06T11:00:24+00:00, book20_bid_proxy_usdt=256570, book20_ask_proxy_usdt=167665, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=5721779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=0.003995, depth_time=2026-11-06T11:00:20+00:00, book20_bid_proxy_usdt=2173000, book20_ask_proxy_usdt=1773835, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=11174947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=189.850000, depth_time=2026-11-06T11:00:10+00:00, book20_bid_proxy_usdt=95550, book20_ask_proxy_usdt=115249, funding_indicative=0.000013, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.14%, turnover=34979483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=0.427000, depth_time=2026-11-06T11:00:28+00:00, book20_bid_proxy_usdt=412209, book20_ask_proxy_usdt=330859, funding_indicative=0.000021, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=11194256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=0.057930, depth_time=2026-11-06T11:00:43+00:00, book20_bid_proxy_usdt=465384, book20_ask_proxy_usdt=348471, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=12165256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T11:00:02+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=1.201800, depth_time=2026-11-06T11:00:22+00:00, book20_bid_proxy_usdt=3415092, book20_ask_proxy_usdt=3495568, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=476820205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T11:00:03+00:00, last15m_closed_end=2026-11-06T11:00+00:00, prior8high=1.634300, depth_time=2026-11-06T11:00:17+00:00, book20_bid_proxy_usdt=115176, book20_ask_proxy_usdt=159604, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.32%, turnover=7255995. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
