# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T04:15:21Z**
- feed_generated_utc: 2026-11-08T04:15:22+00:00
- source_sha256: `4d04c21e33c4e0d5bb0887445b4223b9aac61a4c49d6887fd2a37af258059967`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T04:15+00:00, close=75893.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.139060|-10.73|-40.10|-10.95|9277607|4.30|
|ONE_USDT|0.001860|-8.67|58.41|-8.89|26409635|0.54|
|ENA_USDT|0.154370|-2.40|-20.43|-2.62|27736693|0.65|
|QNT_USDT|194.760000|-2.05|-3.12|-2.27|44810641|1.54|
|WLD_USDT|0.330400|-1.54|-18.29|-1.76|24273822|3.03|
|TIA_USDT|0.436800|-1.08|-10.87|-1.30|7210096|2.29|
|ONDO_USDT|0.360200|-0.79|-12.65|-1.01|8380318|2.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.139060|0.117040|0.139060|0.71|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154370|0.153550|0.154370|0.23|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360200|0.358700|0.360200|1.14|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001860|0.001812|0.001858|0.74|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.760000|193.120000|194.730000|1.00|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.436800|0.434500|0.436800|0.40|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330400|0.329000|0.330400|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=0.157480, depth_time=2026-11-08T04:15:03+00:00, book20_bid_proxy_usdt=5616, book20_ask_proxy_usdt=7142, funding_indicative=0.000267, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.73%, turnover=9277607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=0.156000, depth_time=2026-11-08T04:15:10+00:00, book20_bid_proxy_usdt=129584, book20_ask_proxy_usdt=257576, funding_indicative=0.000010, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=27736693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=0.362000, depth_time=2026-11-08T04:15:20+00:00, book20_bid_proxy_usdt=1405613, book20_ask_proxy_usdt=2279937, funding_indicative=-0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=8380318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=0.002025, depth_time=2026-11-08T04:15:09+00:00, book20_bid_proxy_usdt=7500, book20_ask_proxy_usdt=24642, funding_indicative=0.000016, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.67%, turnover=26409635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=195.100000, depth_time=2026-11-08T04:15:12+00:00, book20_bid_proxy_usdt=104764, book20_ask_proxy_usdt=176736, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=44810641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=0.438500, depth_time=2026-11-08T04:15:18+00:00, book20_bid_proxy_usdt=345858, book20_ask_proxy_usdt=306091, funding_indicative=0.000026, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=7210096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T04:14:59+00:00, last15m_closed_end=2026-11-08T04:15+00:00, prior8high=0.332300, depth_time=2026-11-08T04:15:15+00:00, book20_bid_proxy_usdt=3701321, book20_ask_proxy_usdt=3205944, funding_indicative=-0.000123, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=24273822. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
