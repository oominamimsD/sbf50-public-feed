# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T02:45:23Z**
- feed_generated_utc: 2026-10-23T02:45:25+00:00
- source_sha256: `2790133aacf89190728d54d21bb7d94b652e1184d6e06f569872756d9a6579c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T02:45+00:00, close=81837.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T02:00+00:00, close=81311.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004338|-5.85|118.53|-6.08|9610254|9.23|
|LIT_USDT|3.462000|-4.21|11.98|-4.44|11686559|0.29|
|PHA_USDT|0.060120|-3.11|19.00|-3.34|8291978|1.66|
|STRK_USDT|0.052900|-2.68|-45.10|-2.91|12320063|1.89|
|SILVER_USDT|54.380000|-1.59|-4.83|-1.82|388112252|1.84|
|TIA_USDT|0.563100|-0.93|-6.53|-1.16|23813418|1.78|
|XAU_USDT|4027.990000|-0.78|-3.08|-1.01|767727348|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004338|0.004323|0.004338|1.40|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.462000|3.372400|3.462000|3.59|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.060120|0.059190|0.060120|0.21|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.380000|53.570000|54.360000|0.55|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052900|0.052330|0.052900|1.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.563100|0.554300|0.563100|1.68|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4027.990000|3989.000000|4027.430000|1.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T02:45:02+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=0.004579, depth_time=2026-10-23T02:45:06+00:00, book20_bid_proxy_usdt=33303, book20_ask_proxy_usdt=33753, funding_indicative=0.000071, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=9610254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T02:45:03+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=3.472900, depth_time=2026-10-23T02:45:10+00:00, book20_bid_proxy_usdt=24493, book20_ask_proxy_usdt=21459, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=11686559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T02:45:03+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=0.061460, depth_time=2026-10-23T02:45:10+00:00, book20_bid_proxy_usdt=58890, book20_ask_proxy_usdt=72555, funding_indicative=-0.000509, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=8291978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T02:45:02+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=54.870000, depth_time=2026-10-23T02:45:17+00:00, book20_bid_proxy_usdt=29064221, book20_ask_proxy_usdt=25970845, funding_indicative=0.000089, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=388112252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T02:45:03+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=0.053250, depth_time=2026-10-23T02:45:15+00:00, book20_bid_proxy_usdt=549972, book20_ask_proxy_usdt=580816, funding_indicative=0.000040, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=12320063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T02:45:03+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=0.567500, depth_time=2026-10-23T02:45:20+00:00, book20_bid_proxy_usdt=469065, book20_ask_proxy_usdt=281073, funding_indicative=0.000009, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=23813418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T02:45:02+00:00, last15m_closed_end=2026-10-23T02:45+00:00, prior8high=4040.120000, depth_time=2026-10-23T02:45:22+00:00, book20_bid_proxy_usdt=853909, book20_ask_proxy_usdt=498947, funding_indicative=0.000102, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=767727348. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
