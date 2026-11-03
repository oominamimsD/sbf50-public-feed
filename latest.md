# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T14:00:22Z**
- feed_generated_utc: 2026-11-03T14:00:24+00:00
- source_sha256: `b79665e2c7f5f7097a05996c6d244500436ae2af4433a1bd65cdd1ae056efa27`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T14:00+00:00, close=77368.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T14:00+00:00, close=77368.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004184|-23.95|-86.40|-23.80|12121494|2.39|
|BTW_USDT|0.989300|-9.27|-17.26|-9.12|8484336|3.04|
|XPL_USDT|0.064670|-7.05|-12.94|-6.90|11445460|3.09|
|TIA_USDT|0.442900|-3.48|-17.32|-3.33|13369887|2.26|
|DASH_USDT|46.370000|-2.76|-11.20|-2.61|9124192|2.16|
|ENA_USDT|0.171200|-2.19|-18.61|-2.04|70040735|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004184|0.004150|0.004182|1.96|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.989300|0.929000|0.989300|0.42|N|N/N|Y/Y|Y|N|
|DASH_USDT|46.370000|45.720000|46.370000|0.25|N|N/N|Y/Y|Y|N|
|ENA_USDT|0.171200|0.170200|0.171120|4.70|N|Y/N|Y/Y|Y|N|
|TIA_USDT|0.442900|0.440200|0.442900|4.98|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064670|0.064160|0.064660|1.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T14:00:01+00:00, last15m_closed_end=2026-11-03T14:00+00:00, prior8high=0.004535, depth_time=2026-11-03T14:00:08+00:00, book20_bid_proxy_usdt=44135, book20_ask_proxy_usdt=58023, funding_indicative=-0.001270, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.95%, turnover=12121494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T14:00:02+00:00, last15m_closed_end=2026-11-03T14:00+00:00, prior8high=1.032400, depth_time=2026-11-03T14:00:11+00:00, book20_bid_proxy_usdt=16946, book20_ask_proxy_usdt=17268, funding_indicative=0.000015, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=8484336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T14:00:02+00:00, last15m_closed_end=2026-11-03T14:00+00:00, prior8high=46.820000, depth_time=2026-11-03T14:00:13+00:00, book20_bid_proxy_usdt=830582, book20_ask_proxy_usdt=545379, funding_indicative=0.000080, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=9124192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T14:00:01+00:00, last15m_closed_end=2026-11-03T14:00+00:00, prior8high=0.174220, depth_time=2026-11-03T14:00:21+00:00, book20_bid_proxy_usdt=100729, book20_ask_proxy_usdt=183851, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=70040735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T14:00:02+00:00, last15m_closed_end=2026-11-03T14:00+00:00, prior8high=0.449000, depth_time=2026-11-03T14:00:14+00:00, book20_bid_proxy_usdt=324814, book20_ask_proxy_usdt=369165, funding_indicative=-0.000009, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=13369887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T14:00:02+00:00, last15m_closed_end=2026-11-03T14:00+00:00, prior8high=0.065540, depth_time=2026-11-03T14:00:14+00:00, book20_bid_proxy_usdt=432348, book20_ask_proxy_usdt=279456, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.05%, turnover=11445460. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
