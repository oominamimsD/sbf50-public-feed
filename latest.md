# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T00:15:37Z**
- feed_generated_utc: 2026-11-06T00:15:39+00:00
- source_sha256: `c6ec99b036271a160a10bdb61beee798bed15e9f429aecd86144149120e6c31c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T00:15+00:00, close=76098, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ATOM_USDT|1.360000|-4.22|-16.61|-4.33|5495166|7.35|
|FLUID_USDT|2.441000|-3.59|18.26|-3.70|7512865|4.10|
|PUMPFUN_USDT|0.003827|-2.81|-15.42|-2.92|12278700|2.61|
|XRP_USDT|1.211400|-2.66|-7.49|-2.77|432533076|0.83|
|HYPE_USDT|77.125000|-2.00|-17.89|-2.11|87719895|0.13|
|XPL_USDT|0.057410|-1.99|-27.26|-2.10|12527859|1.74|
|FET_USDT|0.144100|-1.90|-22.02|-2.01|7499965|6.94|
|ZRO_USDT|1.592000|-1.86|-9.76|-1.97|7054926|0.63|
|WLD_USDT|0.334600|-1.84|-23.30|-1.95|80408560|2.99|
|ONDO_USDT|0.365900|-1.77|-14.86|-1.88|30856076|2.73|
|BCH_USDT|274.480000|-1.66|-4.78|-1.77|8725105|3.64|
|QNT_USDT|189.360000|-1.28|-4.71|-1.39|42855230|1.58|
|ENA_USDT|0.160570|-1.27|-24.93|-1.38|51289742|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.360000|1.345000|1.360000|1.31|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|274.480000|266.300000|274.480000|1.27|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.160570|0.155920|0.160590|1.07|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.144100|0.141900|0.144100|0.44|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.441000|2.347000|2.441000|2.43|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.125000|76.284000|77.125000|0.59|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.365900|0.360600|0.365900|0.92|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003827|0.003844|0.003827|1.04|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.360000|185.570000|189.270000|0.92|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.334600|0.329300|0.334600|0.83|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057410|0.056610|0.057410|0.38|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.211400|1.199300|1.210900|0.95|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.592000|1.568700|1.591500|0.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=1.396000, depth_time=2026-11-06T00:15:05+00:00, book20_bid_proxy_usdt=1980985, book20_ask_proxy_usdt=1280957, funding_indicative=-0.000144, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.22%, turnover=5495166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=273.130000, depth_time=2026-11-06T00:15:32+00:00, book20_bid_proxy_usdt=65766, book20_ask_proxy_usdt=52789, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=8725105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=0.163270, depth_time=2026-11-06T00:15:37+00:00, book20_bid_proxy_usdt=96521, book20_ask_proxy_usdt=221874, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=51289742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=0.147300, depth_time=2026-11-06T00:15:22+00:00, book20_bid_proxy_usdt=1274148, book20_ask_proxy_usdt=952454, funding_indicative=-0.000231, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=7499965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=2.432000, depth_time=2026-11-06T00:15:09+00:00, book20_bid_proxy_usdt=175502, book20_ask_proxy_usdt=181153, funding_indicative=0.000633, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.59%, turnover=7512865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=77.727000, depth_time=2026-11-06T00:15:15+00:00, book20_bid_proxy_usdt=315992, book20_ask_proxy_usdt=124003, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=87719895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=0.369600, depth_time=2026-11-06T00:15:29+00:00, book20_bid_proxy_usdt=1544117, book20_ask_proxy_usdt=1452045, funding_indicative=-0.000027, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=30856076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=0.003970, depth_time=2026-11-06T00:15:12+00:00, book20_bid_proxy_usdt=1971396, book20_ask_proxy_usdt=791305, funding_indicative=-0.000007, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=12278700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=191.370000, depth_time=2026-11-06T00:15:34+00:00, book20_bid_proxy_usdt=70306, book20_ask_proxy_usdt=51619, funding_indicative=0.000007, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=42855230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=0.339500, depth_time=2026-11-06T00:15:27+00:00, book20_bid_proxy_usdt=2639443, book20_ask_proxy_usdt=3452368, funding_indicative=-0.000526, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=80408560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=0.059000, depth_time=2026-11-06T00:15:19+00:00, book20_bid_proxy_usdt=340397, book20_ask_proxy_usdt=416832, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=12527859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=1.226900, depth_time=2026-11-06T00:15:14+00:00, book20_bid_proxy_usdt=3439474, book20_ask_proxy_usdt=3014024, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=432533076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T00:14:59+00:00, last15m_closed_end=2026-11-06T00:15+00:00, prior8high=1.609800, depth_time=2026-11-06T00:15:24+00:00, book20_bid_proxy_usdt=19886, book20_ask_proxy_usdt=72044, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=7054926. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
