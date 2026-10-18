# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T18:45:23Z**
- feed_generated_utc: 2026-10-18T18:45:24+00:00
- source_sha256: `7e621cd65a466e86884156e8d434e8576ab74e7311da8c5a1be300ea4d54c626`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T18:45+00:00, close=81091.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T18:00+00:00, close=81150, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059150|-3.91|-50.40|-3.86|16215932|1.69|
|BAT_USDT|0.169070|-3.59|1.45|-3.54|8873181|1.18|
|HBAR_USDT|0.084320|-1.70|-10.08|-1.65|43590401|1.19|
|PUMPFUN_USDT|0.004127|-1.62|-28.53|-1.57|29653329|2.42|
|WLD_USDT|0.469900|-1.34|-18.87|-1.29|75267625|2.13|
|XPL_USDT|0.075100|-1.10|-15.85|-1.05|6672878|1.33|
|FET_USDT|0.185400|-1.06|-22.00|-1.01|8971589|5.39|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.169070|0.169830|0.169070|1.80|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.185400|0.185000|0.185400|0.92|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.084320|0.084060|0.084320|2.04|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004127|0.004107|0.004127|0.07|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059150|0.058920|0.059170|1.17|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.469900|0.468000|0.470000|0.71|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.075100|0.075050|0.075100|0.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.175450, depth_time=2026-10-18T18:45:09+00:00, book20_bid_proxy_usdt=24589, book20_ask_proxy_usdt=30694, funding_indicative=0.000019, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.59%, turnover=8873181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.188200, depth_time=2026-10-18T18:45:22+00:00, book20_bid_proxy_usdt=1835073, book20_ask_proxy_usdt=1107422, funding_indicative=-0.000006, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=8971589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.086450, depth_time=2026-10-18T18:45:13+00:00, book20_bid_proxy_usdt=760741, book20_ask_proxy_usdt=1047937, funding_indicative=0.000033, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=43590401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.004143, depth_time=2026-10-18T18:45:14+00:00, book20_bid_proxy_usdt=1724991, book20_ask_proxy_usdt=1879897, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=29653329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.061180, depth_time=2026-10-18T18:45:08+00:00, book20_bid_proxy_usdt=249599, book20_ask_proxy_usdt=449828, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.91%, turnover=16215932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.480000, depth_time=2026-10-18T18:45:15+00:00, book20_bid_proxy_usdt=1715549, book20_ask_proxy_usdt=2052790, funding_indicative=-0.000205, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=75267625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T18:45:01+00:00, last15m_closed_end=2026-10-18T18:45+00:00, prior8high=0.076130, depth_time=2026-10-18T18:45:19+00:00, book20_bid_proxy_usdt=693128, book20_ask_proxy_usdt=628726, funding_indicative=-0.000016, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=6672878. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
