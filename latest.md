# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T00:30:22Z**
- feed_generated_utc: 2026-11-09T00:30:24+00:00
- source_sha256: `eef97da63f7a1302882604daa3f1b54dcb60411881ac5942b3482f1b8c5c8770`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T00:30+00:00, close=75015, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001736|-11.33|49.08|-9.99|11986802|0.58|
|PUMPFUN_USDT|0.003562|-4.68|-15.55|-3.34|8670727|2.81|
|LIT_USDT|3.065200|-4.01|-5.10|-2.67|11153508|0.33|
|WLD_USDT|0.313100|-3.92|-20.87|-2.58|31276483|3.19|
|HYPE_USDT|74.793000|-3.40|-14.70|-2.06|37425318|0.13|
|XRP_USDT|1.117800|-3.28|-10.56|-1.94|230221090|0.90|
|AKE_USDT|0.005197|-2.98|-43.26|-1.64|14576959|1.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005197|0.005106|0.005197|0.66|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.793000|73.900000|74.793000|0.60|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.065200|3.023100|3.065200|0.30|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001736|0.001657|0.001736|0.66|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003562|0.003495|0.003562|1.31|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.313100|0.308200|0.313200|1.67|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.117800|1.105100|1.117800|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=0.005394, depth_time=2026-11-09T00:30:21+00:00, book20_bid_proxy_usdt=47007, book20_ask_proxy_usdt=56312, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=14576959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=75.837000, depth_time=2026-11-09T00:30:17+00:00, book20_bid_proxy_usdt=36097, book20_ask_proxy_usdt=90532, funding_indicative=0.000022, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.40%, turnover=37425318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=3.135200, depth_time=2026-11-09T00:30:07+00:00, book20_bid_proxy_usdt=48623, book20_ask_proxy_usdt=24763, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=11153508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=0.001757, depth_time=2026-11-09T00:30:07+00:00, book20_bid_proxy_usdt=7263, book20_ask_proxy_usdt=5297, funding_indicative=-0.001003, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.33%, turnover=11986802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=0.003662, depth_time=2026-11-09T00:30:06+00:00, book20_bid_proxy_usdt=4059064, book20_ask_proxy_usdt=3707631, funding_indicative=-0.000021, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=8670727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=0.319800, depth_time=2026-11-09T00:30:13+00:00, book20_bid_proxy_usdt=3902135, book20_ask_proxy_usdt=4819834, funding_indicative=-0.000159, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=31276483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T00:30:00+00:00, last15m_closed_end=2026-11-09T00:30+00:00, prior8high=1.131800, depth_time=2026-11-09T00:30:19+00:00, book20_bid_proxy_usdt=4334606, book20_ask_proxy_usdt=2774795, funding_indicative=0.000060, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=230221090. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
