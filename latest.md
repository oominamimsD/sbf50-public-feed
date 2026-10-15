# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T00:45:19Z**
- feed_generated_utc: 2026-10-15T00:45:21+00:00
- source_sha256: `2d247b1268dc56ef7792a3083cc9847d3fb820b150d648b28722facb68797c89`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T00:45+00:00, close=81509.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.317000|-7.84|-22.77|-7.73|6982082|6.31|
|BAT_USDT|0.169170|-3.00|70.60|-2.89|24519500|2.37|
|FET_USDT|0.198700|-2.55|-12.27|-2.44|10913436|5.03|
|FARTCOIN_USDT|0.154280|-1.50|-3.68|-1.39|8002782|0.65|
|AAVE_USDT|153.680000|-1.41|-10.52|-1.30|26265943|0.65|
|S_USDT|0.054050|-1.35|35.66|-1.24|5232823|1.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.680000|152.860000|153.680000|0.50|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169170|0.168540|0.169170|0.68|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.154280|0.154450|0.154280|1.14|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.198700|0.196400|0.198700|1.72|N|Y/Y|Y/Y|Y|N|
|PONS_USDT|0.317000|0.325300|0.317000|2.24|Y|Y/N|N/N|Y|N|
|S_USDT|0.054050|0.052980|0.054050|1.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T00:44:58+00:00, last15m_closed_end=2026-10-15T00:45+00:00, prior8high=154.460000, depth_time=2026-10-15T00:45:15+00:00, book20_bid_proxy_usdt=370748, book20_ask_proxy_usdt=279714, funding_indicative=0.000061, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=26265943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T00:44:58+00:00, last15m_closed_end=2026-10-15T00:45+00:00, prior8high=0.178290, depth_time=2026-10-15T00:45:09+00:00, book20_bid_proxy_usdt=20008, book20_ask_proxy_usdt=31512, funding_indicative=0.000033, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=24519500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T00:44:59+00:00, last15m_closed_end=2026-10-15T00:45+00:00, prior8high=0.157710, depth_time=2026-10-15T00:45:13+00:00, book20_bid_proxy_usdt=44202, book20_ask_proxy_usdt=55536, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=8002782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T00:44:58+00:00, last15m_closed_end=2026-10-15T00:45+00:00, prior8high=0.199300, depth_time=2026-10-15T00:45:11+00:00, book20_bid_proxy_usdt=1016971, book20_ask_proxy_usdt=835563, funding_indicative=0.000026, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=10913436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T00:44:58+00:00, last15m_closed_end=2026-10-15T00:45+00:00, prior8high=0.340600, depth_time=2026-10-15T00:45:06+00:00, book20_bid_proxy_usdt=194664, book20_ask_proxy_usdt=203915, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.84%, turnover=6982082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-15T00:44:58+00:00, last15m_closed_end=2026-10-15T00:45+00:00, prior8high=0.054490, depth_time=2026-10-15T00:45:18+00:00, book20_bid_proxy_usdt=98328, book20_ask_proxy_usdt=173449, funding_indicative=-0.000108, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=5232823. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
