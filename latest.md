# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T08:30:18Z**
- feed_generated_utc: 2026-11-06T08:30:19+00:00
- source_sha256: `588667def992eaa5c49620d293f6c7b7efbf8670d22850368ec2f500f18a5778`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T08:30+00:00, close=75616.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|265.400000|-4.91|-7.93|-4.37|7646793|3.77|
|XRP_USDT|1.188900|-4.47|-9.20|-3.93|470815134|0.84|
|FLUID_USDT|2.419000|-4.46|17.19|-3.92|5061105|4.13|
|XPL_USDT|0.057450|-1.92|-27.21|-1.38|12227290|1.74|
|ELSA_USDT|0.079900|-1.54|6.96|-1.00|5184123|5.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|265.400000|261.500000|265.550000|0.83|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.079900|0.076440|0.079900|3.14|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.419000|2.384000|2.419000|4.70|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057450|0.056530|0.057480|1.87|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.188900|1.177100|1.189500|1.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T08:30:03+00:00, last15m_closed_end=2026-11-06T08:30+00:00, prior8high=277.780000, depth_time=2026-11-06T08:30:08+00:00, book20_bid_proxy_usdt=43451, book20_ask_proxy_usdt=107464, funding_indicative=0.000010, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=7646793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T08:30:03+00:00, last15m_closed_end=2026-11-06T08:30+00:00, prior8high=0.079370, depth_time=2026-11-06T08:30:17+00:00, book20_bid_proxy_usdt=27101, book20_ask_proxy_usdt=31780, funding_indicative=0.000130, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=5184123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T08:30:03+00:00, last15m_closed_end=2026-11-06T08:30+00:00, prior8high=2.459000, depth_time=2026-11-06T08:30:10+00:00, book20_bid_proxy_usdt=221005, book20_ask_proxy_usdt=114907, funding_indicative=0.000063, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=5061105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T08:30:03+00:00, last15m_closed_end=2026-11-06T08:30+00:00, prior8high=0.057590, depth_time=2026-11-06T08:30:15+00:00, book20_bid_proxy_usdt=418029, book20_ask_proxy_usdt=454368, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=12227290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T08:30:02+00:00, last15m_closed_end=2026-11-06T08:30+00:00, prior8high=1.199400, depth_time=2026-11-06T08:30:10+00:00, book20_bid_proxy_usdt=3931080, book20_ask_proxy_usdt=3878427, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.47%, turnover=470815134. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
