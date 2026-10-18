# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T09:30:27Z**
- feed_generated_utc: 2026-10-18T09:30:29+00:00
- source_sha256: `487175af61be376242dd63156585fd1f31a42cfdf6fcbdb0e7f9ba6ab7d6209a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T09:30+00:00, close=81992.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T09:00+00:00, close=81705.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063280|-4.33|-32.27|-5.16|14597803|1.58|
|EIGEN_USDT|0.247700|-3.35|5.13|-4.18|6763201|4.04|
|FILECOIN_USDT|1.055700|-2.91|-6.39|-3.74|18904595|1.89|
|PUMPFUN_USDT|0.004303|-2.47|-24.83|-3.30|23191309|2.32|
|ZRO_USDT|1.845900|-2.08|-8.64|-2.91|7277216|0.54|
|XPL_USDT|0.078500|-2.03|-9.52|-2.86|5652392|1.27|
|OP_USDT|0.126840|-1.67|-8.45|-2.50|8627959|0.79|
|DOT_USDT|1.112000|-0.48|-11.52|-1.31|16573605|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.112000|1.098300|1.111900|0.64|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.247700|0.245800|0.247700|0.51|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.055700|1.044000|1.055700|0.38|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126840|0.125540|0.126840|0.41|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004303|0.004250|0.004300|2.38|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063280|0.062200|0.063280|3.24|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078500|0.077860|0.078500|0.19|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.845900|1.823800|1.845900|1.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=1.112700, depth_time=2026-10-18T09:30:26+00:00, book20_bid_proxy_usdt=263684, book20_ask_proxy_usdt=200045, funding_indicative=-0.000131, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=16573605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=0.249100, depth_time=2026-10-18T09:30:08+00:00, book20_bid_proxy_usdt=501008, book20_ask_proxy_usdt=327896, funding_indicative=0.000010, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=6763201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=1.059600, depth_time=2026-10-18T09:30:14+00:00, book20_bid_proxy_usdt=463965, book20_ask_proxy_usdt=659436, funding_indicative=-0.000064, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=18904595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=0.127200, depth_time=2026-10-18T09:30:23+00:00, book20_bid_proxy_usdt=40800, book20_ask_proxy_usdt=73867, funding_indicative=-0.000170, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=8627959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=0.004307, depth_time=2026-10-18T09:30:16+00:00, book20_bid_proxy_usdt=1529420, book20_ask_proxy_usdt=1709274, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=23191309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=0.064850, depth_time=2026-10-18T09:30:08+00:00, book20_bid_proxy_usdt=304253, book20_ask_proxy_usdt=313732, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=14597803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=0.078700, depth_time=2026-10-18T09:30:21+00:00, book20_bid_proxy_usdt=511152, book20_ask_proxy_usdt=465302, funding_indicative=0.000039, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=5652392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T09:30:01+00:00, last15m_closed_end=2026-10-18T09:30+00:00, prior8high=1.857500, depth_time=2026-10-18T09:30:19+00:00, book20_bid_proxy_usdt=37984, book20_ask_proxy_usdt=43282, funding_indicative=0.000033, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=7277216. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
