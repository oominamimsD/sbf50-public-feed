# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T01:30:27Z**
- feed_generated_utc: 2026-11-06T01:30:29+00:00
- source_sha256: `d8bf62c626e3c92ae0f2d2276d22ca3073893caf962ed2f0c63d8905309e1d9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T01:30+00:00, close=76038, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T01:00+00:00, close=76300, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002122|-17.75|-89.92|-17.78|19765691|4.72|
|FLUID_USDT|2.427000|-4.14|17.58|-4.17|7117998|4.12|
|XPL_USDT|0.057090|-2.54|-27.67|-2.57|12623786|1.75|
|XRP_USDT|1.214100|-2.45|-7.28|-2.48|436198623|1.65|
|HYPE_USDT|77.360000|-1.70|-17.64|-1.73|87502060|0.13|
|BCH_USDT|274.370000|-1.70|-4.82|-1.73|8732928|2.55|
|ZRO_USDT|1.595000|-1.67|-9.59|-1.70|7205454|4.39|
|ATOM_USDT|1.399000|-1.47|-14.22|-1.50|6417136|7.15|
|PUMPFUN_USDT|0.003896|-1.06|-13.90|-1.09|12219921|2.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002122|0.002077|0.002122|0.78|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.399000|1.346000|1.399000|0.26|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|274.370000|266.300000|274.430000|0.78|N|N/Y|Y/Y|Y|N|
|FLUID_USDT|2.427000|2.362000|2.427000|0.15|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.360000|76.284000|77.355000|0.94|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003896|0.003823|0.003899|0.64|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057090|0.056610|0.057090|0.64|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.214100|1.199300|1.214100|1.04|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.595000|1.570000|1.596600|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T01:30:01+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=0.002257, depth_time=2026-11-06T01:30:07+00:00, book20_bid_proxy_usdt=111884, book20_ask_proxy_usdt=25773, funding_indicative=-0.001062, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.75%, turnover=19765691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T01:30:02+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=1.401000, depth_time=2026-11-06T01:30:23+00:00, book20_bid_proxy_usdt=1714765, book20_ask_proxy_usdt=1953980, funding_indicative=-0.000051, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=6417136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T01:30:02+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=279.250000, depth_time=2026-11-06T01:30:19+00:00, book20_bid_proxy_usdt=70027, book20_ask_proxy_usdt=53021, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=8732928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T01:30:01+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=2.470000, depth_time=2026-11-06T01:30:09+00:00, book20_bid_proxy_usdt=176429, book20_ask_proxy_usdt=166593, funding_indicative=0.000551, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=7117998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T01:30:01+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=77.943000, depth_time=2026-11-06T01:30:16+00:00, book20_bid_proxy_usdt=77003, book20_ask_proxy_usdt=139106, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.70%, turnover=87502060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T01:30:02+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=0.003946, depth_time=2026-11-06T01:30:26+00:00, book20_bid_proxy_usdt=1584181, book20_ask_proxy_usdt=416061, funding_indicative=0.000032, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=12219921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T01:30:02+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=0.058300, depth_time=2026-11-06T01:30:12+00:00, book20_bid_proxy_usdt=526002, book20_ask_proxy_usdt=396524, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=12623786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T01:30:01+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=1.222700, depth_time=2026-11-06T01:30:14+00:00, book20_bid_proxy_usdt=4495580, book20_ask_proxy_usdt=2601683, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=436198623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T01:30:02+00:00, last15m_closed_end=2026-11-06T01:30+00:00, prior8high=1.618800, depth_time=2026-11-06T01:30:22+00:00, book20_bid_proxy_usdt=35960, book20_ask_proxy_usdt=68132, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=7205454. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
