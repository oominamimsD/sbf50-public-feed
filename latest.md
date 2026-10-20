# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T19:00:24Z**
- feed_generated_utc: 2026-10-20T19:00:26+00:00
- source_sha256: `b9d6a8bcaae1c7571093d7d6a2a8f89bf93cbd3d1119aa126ca44cd573f782d0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T19:00+00:00, close=82503.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T19:00+00:00, close=82503.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.705700|-7.01|-12.64|-6.92|30435862|2.36|
|INJ_USDT|8.546000|-4.04|9.04|-3.95|42379196|2.34|
|PHA_USDT|0.057990|-3.71|5.37|-3.62|18713932|1.73|
|AGT_USDT|0.062278|-3.63|284.97|-3.54|7210016|2.57|
|ARB_USDT|0.190560|-3.04|3.20|-2.95|102590321|0.53|
|DASH_USDT|49.680000|-2.01|0.04|-1.92|9798057|2.01|
|STRK_USDT|0.056690|-1.25|-34.78|-1.16|17349826|5.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062278|0.061470|0.062211|0.73|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.190560|0.187210|0.190570|0.53|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.705700|1.674000|1.705700|0.81|N|Y/Y|Y/Y|N|N|
|DASH_USDT|49.680000|49.530000|49.680000|0.63|N|Y/N|N/N|N|N|
|INJ_USDT|8.546000|8.491000|8.546000|0.22|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057990|0.056980|0.057990|0.66|N|Y/Y|N/N|N|N|
|STRK_USDT|0.056690|0.054980|0.056690|0.20|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T19:00:02+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=0.064934, depth_time=2026-10-20T19:00:15+00:00, book20_bid_proxy_usdt=12410, book20_ask_proxy_usdt=8527, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=7210016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T19:00:02+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=0.192550, depth_time=2026-10-20T19:00:17+00:00, book20_bid_proxy_usdt=85088, book20_ask_proxy_usdt=67414, funding_indicative=-0.000117, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=102590321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T19:00:02+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=1.812200, depth_time=2026-10-20T19:00:09+00:00, book20_bid_proxy_usdt=14898, book20_ask_proxy_usdt=9831, funding_indicative=-0.002527, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=30435862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-20T19:00:03+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=50.200000, depth_time=2026-10-20T19:00:19+00:00, book20_bid_proxy_usdt=1075755, book20_ask_proxy_usdt=658978, funding_indicative=-0.000103, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=9798057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-20T19:00:02+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=8.660000, depth_time=2026-10-20T19:00:10+00:00, book20_bid_proxy_usdt=573285, book20_ask_proxy_usdt=197195, funding_indicative=0.000112, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=42379196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-20T19:00:02+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=0.058770, depth_time=2026-10-20T19:00:11+00:00, book20_bid_proxy_usdt=78494, book20_ask_proxy_usdt=72985, funding_indicative=-0.000009, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=18713932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T19:00:02+00:00, last15m_closed_end=2026-10-20T19:00+00:00, prior8high=0.057450, depth_time=2026-10-20T19:00:22+00:00, book20_bid_proxy_usdt=666240, book20_ask_proxy_usdt=537276, funding_indicative=0.000034, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=17349826. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
