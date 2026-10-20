# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T16:00:27Z**
- feed_generated_utc: 2026-10-20T16:00:29+00:00
- source_sha256: `efae372f314a0b929a99ad559cd242784e74dc0673b2db34096ffe7c17994c0d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ENA_USDT|0.189880|-5.26|-9.38|-4.47|37615534|0.53|
|Q_USDT|0.122755|-4.86|198.47|-4.07|6924177|2.36|
|PHA_USDT|0.057820|-4.00|5.06|-3.21|20781769|3.46|
|ARB_USDT|0.188950|-3.86|2.32|-3.07|104250077|0.53|
|INJ_USDT|8.599000|-3.44|9.72|-2.65|45839450|2.33|
|STRK_USDT|0.055450|-3.41|-36.21|-2.62|17674640|1.80|
|UNI_USDT|7.270000|-3.37|-3.98|-2.58|12780214|2.75|
|TIA_USDT|0.622700|-2.83|7.86|-2.04|40214434|1.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.188950|0.186880|0.188950|0.83|N|Y/Y|Y/Y|N|N|
|ENA_USDT|0.189880|0.189160|0.189880|4.24|N|N/N|N/Y|N|N|
|INJ_USDT|8.599000|8.533000|8.600000|4.47|N|N/N|N/N|N|N|
|PHA_USDT|0.057820|0.057560|0.057820|0.50|N|Y/Y|N/N|N|N|
|Q_USDT|0.122755|0.119102|0.122755|0.42|N|Y/N|N/N|N|N|
|STRK_USDT|0.055450|0.054770|0.055450|2.06|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.622700|0.615900|0.622700|1.67|N|Y/N|Y/N|N|N|
|UNI_USDT|7.270000|7.164000|7.271000|1.90|N|N/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=0.198770, depth_time=2026-10-20T16:00:17+00:00, book20_bid_proxy_usdt=30225, book20_ask_proxy_usdt=51152, funding_indicative=-0.000043, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=104250077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=0.202960, depth_time=2026-10-20T16:00:09+00:00, book20_bid_proxy_usdt=227148, book20_ask_proxy_usdt=133606, funding_indicative=0.000050, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.26%, turnover=37615534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=9.170000, depth_time=2026-10-20T16:00:19+00:00, book20_bid_proxy_usdt=132326, book20_ask_proxy_usdt=183969, funding_indicative=0.000151, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=45839450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=0.060470, depth_time=2026-10-20T16:00:12+00:00, book20_bid_proxy_usdt=45813, book20_ask_proxy_usdt=63937, funding_indicative=-0.000315, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=20781769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=0.131229, depth_time=2026-10-20T16:00:12+00:00, book20_bid_proxy_usdt=17825, book20_ask_proxy_usdt=16657, funding_indicative=-0.000045, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.86%, turnover=6924177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=0.059770, depth_time=2026-10-20T16:00:19+00:00, book20_bid_proxy_usdt=517282, book20_ask_proxy_usdt=559793, funding_indicative=-0.000010, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=17674640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=0.658500, depth_time=2026-10-20T16:00:26+00:00, book20_bid_proxy_usdt=113932, book20_ask_proxy_usdt=175872, funding_indicative=-0.000118, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=40214434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T16:00:01+00:00, last15m_closed_end=2026-10-20T16:00+00:00, prior8high=7.570000, depth_time=2026-10-20T16:00:24+00:00, book20_bid_proxy_usdt=1887584, book20_ask_proxy_usdt=2072870, funding_indicative=-0.000013, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=12780214. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
