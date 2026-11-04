# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T22:30:25Z**
- feed_generated_utc: 2026-11-04T22:30:27+00:00
- source_sha256: `9a3fc9b20514ae3380cd8d09436165c80dd9a55433f126bd797ba7e2771d7f73`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T22:30+00:00, close=80623.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T22:00+00:00, close=80198.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.272000|-10.67|-25.57|-11.10|26405481|7.85|
|AKE_USDT|0.002538|-9.67|-87.37|-10.10|16578601|7.89|
|IDOL_USDT|0.021305|-9.21|146.10|-9.64|6319498|7.51|
|BTW_USDT|1.036200|-5.71|-40.37|-6.14|6258583|2.90|
|PUMPFUN_USDT|0.004277|-3.88|1.66|-4.31|18577326|2.34|
|HYPE_USDT|83.809000|-2.43|4.94|-2.86|92183078|0.12|
|ZRO_USDT|1.826000|-2.07|6.65|-2.50|11128704|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002538|0.002493|0.002538|0.44|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.036200|1.026000|1.036200|1.39|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.809000|82.778000|83.809000|1.56|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021305|0.020994|0.021305|0.47|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004277|0.004189|0.004277|0.45|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.272000|1.257000|1.272000|0.27|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.826000|1.773000|1.827100|1.12|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=0.002701, depth_time=2026-11-04T22:30:07+00:00, book20_bid_proxy_usdt=64603, book20_ask_proxy_usdt=97381, funding_indicative=-0.000869, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.67%, turnover=16578601. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=1.055600, depth_time=2026-11-04T22:30:13+00:00, book20_bid_proxy_usdt=22771, book20_ask_proxy_usdt=24060, funding_indicative=0.000022, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=6258583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=84.049000, depth_time=2026-11-04T22:30:19+00:00, book20_bid_proxy_usdt=36312, book20_ask_proxy_usdt=149918, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=92183078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=0.022314, depth_time=2026-11-04T22:30:12+00:00, book20_bid_proxy_usdt=11361, book20_ask_proxy_usdt=4289, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.21%, turnover=6319498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=0.004266, depth_time=2026-11-04T22:30:18+00:00, book20_bid_proxy_usdt=2101369, book20_ask_proxy_usdt=1642820, funding_indicative=0.000033, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=18577326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=1.301000, depth_time=2026-11-04T22:30:06+00:00, book20_bid_proxy_usdt=849747, book20_ask_proxy_usdt=1134047, funding_indicative=-0.000156, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.67%, turnover=26405481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T22:30:01+00:00, last15m_closed_end=2026-11-04T22:30+00:00, prior8high=1.826200, depth_time=2026-11-04T22:30:23+00:00, book20_bid_proxy_usdt=23979, book20_ask_proxy_usdt=21153, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=11128704. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
