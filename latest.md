# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T06:00:17Z**
- feed_generated_utc: 2026-10-19T06:00:19+00:00
- source_sha256: `4c2f1cb11e9b9544efb22f54e093ac9264bd02b5ca98ef26ce79b2314df9b78b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T06:00+00:00, close=82726.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T06:00+00:00, close=82726.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.199400|-6.34|30.74|-8.29|21271459|0.46|
|ICNT_USDT|0.173700|-5.59|63.86|-7.54|7177094|5.75|
|HBAR_USDT|0.084120|-1.93|-10.30|-3.88|50496579|1.19|
|STRK_USDT|0.060150|-1.10|-49.56|-3.05|17342662|1.66|
|TIA_USDT|0.612900|0.17|4.11|-1.78|57075220|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.199400|2.185300|2.199500|2.15|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084120|0.083810|0.084150|0.69|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.173700|0.172200|0.173600|1.78|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060150|0.059440|0.060150|0.16|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.612900|0.604400|0.612800|0.51|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T06:00:01+00:00, last15m_closed_end=2026-10-19T06:00+00:00, prior8high=2.328900, depth_time=2026-10-19T06:00:07+00:00, book20_bid_proxy_usdt=11862, book20_ask_proxy_usdt=9235, funding_indicative=-0.000083, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=21271459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T06:00:01+00:00, last15m_closed_end=2026-10-19T06:00+00:00, prior8high=0.084640, depth_time=2026-10-19T06:00:12+00:00, book20_bid_proxy_usdt=648883, book20_ask_proxy_usdt=691123, funding_indicative=-0.000040, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=50496579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T06:00:01+00:00, last15m_closed_end=2026-10-19T06:00+00:00, prior8high=0.194500, depth_time=2026-10-19T06:00:09+00:00, book20_bid_proxy_usdt=143055, book20_ask_proxy_usdt=123261, funding_indicative=-0.000190, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.59%, turnover=7177094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T06:00:01+00:00, last15m_closed_end=2026-10-19T06:00+00:00, prior8high=0.060780, depth_time=2026-10-19T06:00:14+00:00, book20_bid_proxy_usdt=881223, book20_ask_proxy_usdt=513128, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=17342662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T06:00:01+00:00, last15m_closed_end=2026-10-19T06:00+00:00, prior8high=0.617600, depth_time=2026-10-19T06:00:17+00:00, book20_bid_proxy_usdt=310293, book20_ask_proxy_usdt=231509, funding_indicative=-0.000010, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.17%, turnover=57075220. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
