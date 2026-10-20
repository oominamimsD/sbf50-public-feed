# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T23:00:25Z**
- feed_generated_utc: 2026-10-20T23:00:28+00:00
- source_sha256: `eac0de4140790f25c045b8e69be65e836181060c3f8782f3618cff5878efdd44`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T23:00+00:00, close=83059.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T23:00+00:00, close=83059.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.194710|-9.76|9.76|-10.33|9985030|3.08|
|AGT_USDT|0.058074|-8.79|258.99|-9.36|7015066|0.17|
|ARB_USDT|0.188200|-4.24|1.92|-4.81|83177229|0.53|
|TIA_USDT|0.618300|-3.52|7.10|-4.09|45337616|3.24|
|PHA_USDT|0.058250|-3.28|5.85|-3.85|11841951|3.44|
|XMR_USDT|609.600000|-1.76|15.47|-2.33|11443687|0.82|
|XAU_USDT|4127.810000|-0.55|-0.90|-1.12|408602546|0.02|
|XAUT_USDT|4120.100000|-0.45|-0.88|-1.02|200576607|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.058074|0.056252|0.058074|0.68|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.188200|0.188680|0.188200|1.41|Y|Y/Y|Y/Y|N|Y|
|BAT_USDT|0.194710|0.193360|0.194720|1.38|N|Y/Y|N/N|N|N|
|PHA_USDT|0.058250|0.057740|0.058250|0.16|N|Y/Y|N/N|N|N|
|TIA_USDT|0.618300|0.618200|0.618300|1.34|N|Y/Y|Y/N|N|N|
|XAUT_USDT|4120.100000|4120.390000|4120.100000|2.50|Y|Y/Y|Y/Y|N|Y|
|XAU_USDT|4127.810000|4129.610000|4127.810000|1.49|Y|Y/Y|Y/Y|N|Y|
|XMR_USDT|609.600000|615.820000|609.600000|44.04|Y|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=0.058996, depth_time=2026-10-20T23:00:10+00:00, book20_bid_proxy_usdt=7971, book20_ask_proxy_usdt=11798, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.79%, turnover=7015066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=0.191850, depth_time=2026-10-20T23:00:12+00:00, book20_bid_proxy_usdt=66394, book20_ask_proxy_usdt=70150, funding_indicative=-0.000070, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=83177229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=0.200820, depth_time=2026-10-20T23:00:07+00:00, book20_bid_proxy_usdt=16071, book20_ask_proxy_usdt=20194, funding_indicative=0.000021, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.76%, turnover=9985030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=0.059700, depth_time=2026-10-20T23:00:15+00:00, book20_bid_proxy_usdt=73273, book20_ask_proxy_usdt=61090, funding_indicative=-0.000038, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=11841951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=0.637500, depth_time=2026-10-20T23:00:15+00:00, book20_bid_proxy_usdt=235143, book20_ask_proxy_usdt=240960, funding_indicative=-0.000122, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=45337616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=4130.040000, depth_time=2026-10-20T23:00:24+00:00, book20_bid_proxy_usdt=148772, book20_ask_proxy_usdt=173080, funding_indicative=0.000050, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.45%, turnover=200576607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=4139.290000, depth_time=2026-10-20T23:00:22+00:00, book20_bid_proxy_usdt=502280, book20_ask_proxy_usdt=1144416, funding_indicative=0.000178, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.55%, turnover=408602546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-20T23:00:01+00:00, last15m_closed_end=2026-10-20T23:00+00:00, prior8high=624.130000, depth_time=2026-10-20T23:00:19+00:00, book20_bid_proxy_usdt=16124, book20_ask_proxy_usdt=20582, funding_indicative=0.000105, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=11443687. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
