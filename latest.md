# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T03:45:20Z**
- feed_generated_utc: 2026-10-19T03:45:22+00:00
- source_sha256: `a151981e02ddb85b3e4a7e08a746e2b247c6f6b01aa622519e27479c460c65c5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T03:45+00:00, close=82494.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T03:00+00:00, close=82682.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.226400|-3.42|32.35|-5.09|21853229|1.35|
|BAT_USDT|0.171500|-2.21|2.91|-3.88|6293074|0.58|
|STRK_USDT|0.060260|-2.11|-49.47|-3.78|17392844|1.66|
|ICNT_USDT|0.175900|-1.95|65.94|-3.62|7715238|5.69|
|HBAR_USDT|0.084120|-1.93|-10.30|-3.60|51542429|1.19|
|TIA_USDT|0.615800|-0.33|4.60|-2.00|56477421|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.171500|0.170000|0.171500|0.76|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.226400|2.217800|2.226400|0.72|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084120|0.083740|0.084120|0.68|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.175900|0.163100|0.175900|0.87|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060260|0.060000|0.060260|0.54|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.615800|0.615200|0.615800|0.94|N|Y/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-19T03:44:59+00:00, last15m_closed_end=2026-10-19T03:45+00:00, prior8high=0.176060, depth_time=2026-10-19T03:45:09+00:00, book20_bid_proxy_usdt=28549, book20_ask_proxy_usdt=25545, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=6293074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T03:44:59+00:00, last15m_closed_end=2026-10-19T03:45+00:00, prior8high=2.347600, depth_time=2026-10-19T03:45:07+00:00, book20_bid_proxy_usdt=7577, book20_ask_proxy_usdt=21192, funding_indicative=-0.000249, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=21853229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T03:44:59+00:00, last15m_closed_end=2026-10-19T03:45+00:00, prior8high=0.084670, depth_time=2026-10-19T03:45:17+00:00, book20_bid_proxy_usdt=945563, book20_ask_proxy_usdt=610761, funding_indicative=-0.000027, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=51542429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T03:44:59+00:00, last15m_closed_end=2026-10-19T03:45+00:00, prior8high=0.180900, depth_time=2026-10-19T03:45:12+00:00, book20_bid_proxy_usdt=125292, book20_ask_proxy_usdt=122359, funding_indicative=-0.000094, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=7715238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T03:44:59+00:00, last15m_closed_end=2026-10-19T03:45+00:00, prior8high=0.061960, depth_time=2026-10-19T03:45:12+00:00, book20_bid_proxy_usdt=659344, book20_ask_proxy_usdt=654970, funding_indicative=0.000005, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=17392844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T03:44:59+00:00, last15m_closed_end=2026-10-19T03:45+00:00, prior8high=0.631600, depth_time=2026-10-19T03:45:18+00:00, book20_bid_proxy_usdt=334820, book20_ask_proxy_usdt=203403, funding_indicative=-0.000002, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.33%, turnover=56477421. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
