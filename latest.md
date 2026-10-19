# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T10:00:21Z**
- feed_generated_utc: 2026-10-19T10:00:23+00:00
- source_sha256: `9b8e081b206f5f12ac30295f2e8d7c9742dd066f66ba215d13169bd08bcd7ba3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T10:00+00:00, close=82729.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T10:00+00:00, close=82729.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.186500|-5.15|29.97|-7.11|22115700|1.83|
|STRK_USDT|0.059280|-2.53|-50.29|-4.49|17460096|1.69|
|HBAR_USDT|0.084060|-2.00|-10.36|-3.96|46773265|1.19|
|TIA_USDT|0.610800|-1.14|3.75|-3.10|56606083|1.64|
|SAND_USDT|0.058210|-0.93|-12.38|-2.89|17107707|1.72|
|SEI_USDT|0.060280|0.41|-14.96|-1.55|8631758|3.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.186500|2.155000|2.186900|1.23|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084060|0.084210|0.084060|0.71|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.058210|0.058330|0.058210|0.75|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060280|0.060240|0.060280|1.48|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.059280|0.059130|0.059280|0.63|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.610800|0.605200|0.610800|0.63|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T09:59:59+00:00, last15m_closed_end=2026-10-19T10:00+00:00, prior8high=2.310800, depth_time=2026-10-19T10:00:08+00:00, book20_bid_proxy_usdt=10647, book20_ask_proxy_usdt=13709, funding_indicative=-0.000557, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=22115700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T09:59:59+00:00, last15m_closed_end=2026-10-19T10:00+00:00, prior8high=0.084960, depth_time=2026-10-19T10:00:13+00:00, book20_bid_proxy_usdt=541840, book20_ask_proxy_usdt=829758, funding_indicative=-0.000061, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=46773265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T09:59:59+00:00, last15m_closed_end=2026-10-19T10:00+00:00, prior8high=0.060670, depth_time=2026-10-19T10:00:16+00:00, book20_bid_proxy_usdt=487474, book20_ask_proxy_usdt=838575, funding_indicative=-0.004238, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=17107707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T10:00:00+00:00, last15m_closed_end=2026-10-19T10:00+00:00, prior8high=0.061640, depth_time=2026-10-19T10:00:20+00:00, book20_bid_proxy_usdt=255771, book20_ask_proxy_usdt=423525, funding_indicative=0.000028, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.41%, turnover=8631758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T10:00:00+00:00, last15m_closed_end=2026-10-19T10:00+00:00, prior8high=0.059970, depth_time=2026-10-19T10:00:10+00:00, book20_bid_proxy_usdt=840866, book20_ask_proxy_usdt=647120, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=17460096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T09:59:59+00:00, last15m_closed_end=2026-10-19T10:00+00:00, prior8high=0.616200, depth_time=2026-10-19T10:00:16+00:00, book20_bid_proxy_usdt=264440, book20_ask_proxy_usdt=335718, funding_indicative=0.000000, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=56606083. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
