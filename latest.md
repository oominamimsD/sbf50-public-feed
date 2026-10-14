# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T09:00:28Z**
- feed_generated_utc: 2026-10-14T09:00:31+00:00
- source_sha256: `3f0c587dd396351e37832c5a119a61b9fe6500c3630bad1a4e6781b5d137755c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T09:00+00:00, close=83400.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T09:00+00:00, close=83400.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056860|-19.46|30.11|-19.46|24623102|1.76|
|W_USDT|0.016298|-9.31|12.30|-9.31|6646177|4.91|
|TIA_USDT|0.551900|-5.65|15.87|-5.65|38324709|1.81|
|STRK_USDT|0.081270|-4.85|55.71|-4.85|29384120|1.23|
|DOT_USDT|1.143600|-3.45|-4.81|-3.45|19478516|0.88|
|UNI_USDT|7.347000|-2.37|-15.21|-2.37|19482351|1.36|
|SILVER_USDT|58.660000|-1.59|-4.41|-1.59|248858547|1.71|
|ICP_USDT|3.094000|-1.49|-9.05|-1.49|9795185|3.23|
|RENDER_USDT|1.993000|-1.28|-6.43|-1.28|10131498|5.02|
|AVAX_USDT|10.172000|-1.10|-11.58|-1.10|41636245|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|10.172000|10.151000|10.172000|1.61|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.143600|1.143700|1.143600|2.46|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|3.094000|3.081000|3.094000|1.29|N|Y/Y|Y/Y|N|N|
|RENDER_USDT|1.993000|1.988000|1.993000|4.26|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.660000|58.560000|58.660000|0.42|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.081270|0.081200|0.081250|0.41|N|Y/Y|Y/Y|N|N|
|S_USDT|0.056860|0.055750|0.056860|1.16|N|Y/Y|N/N|N|N|
|TIA_USDT|0.551900|0.550900|0.552000|1.66|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.347000|7.344000|7.347000|0.57|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016298|0.016124|0.016298|2.27|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=10.333000, depth_time=2026-10-14T09:00:27+00:00, book20_bid_proxy_usdt=564316, book20_ask_proxy_usdt=549696, funding_indicative=0.000025, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=41636245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=1.164200, depth_time=2026-10-14T09:00:15+00:00, book20_bid_proxy_usdt=271307, book20_ask_proxy_usdt=288554, funding_indicative=-0.000009, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=19478516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=3.139000, depth_time=2026-10-14T09:00:23+00:00, book20_bid_proxy_usdt=899943, book20_ask_proxy_usdt=769002, funding_indicative=0.000086, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=9795185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=2.037000, depth_time=2026-10-14T09:00:24+00:00, book20_bid_proxy_usdt=1970984, book20_ask_proxy_usdt=1124560, funding_indicative=0.000009, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=10131498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=59.010000, depth_time=2026-10-14T09:00:20+00:00, book20_bid_proxy_usdt=56298771, book20_ask_proxy_usdt=41901953, funding_indicative=0.000069, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=248858547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=0.083840, depth_time=2026-10-14T09:00:12+00:00, book20_bid_proxy_usdt=228593, book20_ask_proxy_usdt=249988, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.85%, turnover=29384120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=0.057560, depth_time=2026-10-14T09:00:07+00:00, book20_bid_proxy_usdt=168227, book20_ask_proxy_usdt=114955, funding_indicative=-0.000076, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.46%, turnover=24623102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=0.564000, depth_time=2026-10-14T09:00:11+00:00, book20_bid_proxy_usdt=112971, book20_ask_proxy_usdt=219798, funding_indicative=0.000021, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.65%, turnover=38324709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=7.502000, depth_time=2026-10-14T09:00:18+00:00, book20_bid_proxy_usdt=1407622, book20_ask_proxy_usdt=1624975, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=19482351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T09:00:00+00:00, last15m_closed_end=2026-10-14T09:00+00:00, prior8high=0.016686, depth_time=2026-10-14T09:00:09+00:00, book20_bid_proxy_usdt=24244, book20_ask_proxy_usdt=25430, funding_indicative=-0.000316, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.31%, turnover=6646177. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
