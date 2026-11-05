# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T23:45:43Z**
- feed_generated_utc: 2026-11-05T23:45:45+00:00
- source_sha256: `473fabd812ced6844e1afeb51ba05f5e403f9c2499aee44669418093abc4de97`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T23:45+00:00, close=76048, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T23:00+00:00, close=75684.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002184|-15.34|-89.63|-15.38|19626138|4.58|
|ATOM_USDT|1.356000|-4.50|-16.86|-4.54|5437510|7.37|
|FLUID_USDT|2.420000|-4.42|17.24|-4.46|7777307|4.13|
|BCH_USDT|271.240000|-2.82|-5.91|-2.86|8734664|3.31|
|XRP_USDT|1.210800|-2.71|-7.53|-2.75|439163026|0.83|
|XPL_USDT|0.057260|-2.25|-27.45|-2.29|12555368|3.49|
|HYPE_USDT|77.016000|-2.13|-18.01|-2.17|89751199|1.17|
|FET_USDT|0.144000|-1.97|-22.07|-2.01|7589315|6.95|
|ONDO_USDT|0.365600|-1.85|-14.93|-1.89|31277663|2.73|
|WLD_USDT|0.334600|-1.84|-23.30|-1.88|81134187|2.99|
|ZRO_USDT|1.592200|-1.84|-9.75|-1.88|7154986|0.63|
|PUMPFUN_USDT|0.003869|-1.75|-14.49|-1.79|12342485|2.58|
|SEI_USDT|0.044810|-1.36|-16.14|-1.40|6352445|2.23|
|ENA_USDT|0.160440|-1.35|-25.00|-1.39|51619705|1.25|
|SUI_USDT|0.841400|-1.33|-11.77|-1.37|73400490|1.19|
|QNT_USDT|189.330000|-1.29|-4.73|-1.33|44122263|0.53|
|NEAR_USDT|3.665000|-1.07|-21.16|-1.11|70102783|2.73|
|DOGE_USDT|0.071080|-1.03|-11.84|-1.07|156728206|1.41|
|ADA_USDT|0.180500|-0.98|-12.54|-1.02|45307188|5.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002184|0.002129|0.002184|0.45|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.356000|1.345000|1.356000|0.30|N|Y/Y|Y/N|Y|N|
|BCH_USDT|271.240000|266.300000|271.240000|1.67|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.160440|0.155920|0.160440|1.31|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.144000|0.141900|0.144000|1.53|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.420000|2.347000|2.420000|0.56|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.016000|76.284000|77.016000|0.43|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.365600|0.360600|0.365600|0.64|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003869|0.003847|0.003869|0.69|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.044810|0.044230|0.044810|0.89|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.841400|0.830000|0.841400|1.45|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.334600|0.329300|0.334600|0.55|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057260|0.056610|0.057260|0.55|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.210800|1.199300|1.210800|0.41|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.592200|1.568700|1.592200|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T23:44:59+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.002275, depth_time=2026-11-05T23:45:07+00:00, book20_bid_proxy_usdt=61443, book20_ask_proxy_usdt=44632, funding_indicative=-0.000727, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.34%, turnover=19626138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=1.411000, depth_time=2026-11-05T23:45:10+00:00, book20_bid_proxy_usdt=2723154, book20_ask_proxy_usdt=1780603, funding_indicative=-0.000137, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.50%, turnover=5437510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=274.910000, depth_time=2026-11-05T23:45:14+00:00, book20_bid_proxy_usdt=72017, book20_ask_proxy_usdt=47176, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=8734664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.164690, depth_time=2026-11-05T23:45:40+00:00, book20_bid_proxy_usdt=122673, book20_ask_proxy_usdt=104450, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=51619705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.148900, depth_time=2026-11-05T23:45:24+00:00, book20_bid_proxy_usdt=1126365, book20_ask_proxy_usdt=824798, funding_indicative=-0.000237, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=7589315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T23:44:59+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=2.411000, depth_time=2026-11-05T23:45:11+00:00, book20_bid_proxy_usdt=219112, book20_ask_proxy_usdt=174080, funding_indicative=0.000445, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=7777307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T23:44:59+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=78.964000, depth_time=2026-11-05T23:45:23+00:00, book20_bid_proxy_usdt=341304, book20_ask_proxy_usdt=96442, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=89751199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.372400, depth_time=2026-11-05T23:45:28+00:00, book20_bid_proxy_usdt=1559421, book20_ask_proxy_usdt=1543031, funding_indicative=-0.000015, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=31277663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.003982, depth_time=2026-11-05T23:45:35+00:00, book20_bid_proxy_usdt=361253, book20_ask_proxy_usdt=409925, funding_indicative=0.000003, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=12342485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.045850, depth_time=2026-11-05T23:45:37+00:00, book20_bid_proxy_usdt=233233, book20_ask_proxy_usdt=268345, funding_indicative=0.000049, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=6352445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.851400, depth_time=2026-11-05T23:45:42+00:00, book20_bid_proxy_usdt=449709, book20_ask_proxy_usdt=1318131, funding_indicative=-0.000015, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=73400490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.342000, depth_time=2026-11-05T23:45:30+00:00, book20_bid_proxy_usdt=3379016, book20_ask_proxy_usdt=2479941, funding_indicative=-0.000524, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=81134187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=0.059490, depth_time=2026-11-05T23:45:20+00:00, book20_bid_proxy_usdt=504609, book20_ask_proxy_usdt=370701, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=12555368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T23:44:59+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=1.227900, depth_time=2026-11-05T23:45:17+00:00, book20_bid_proxy_usdt=2263131, book20_ask_proxy_usdt=3028692, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=439163026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T23:45:00+00:00, last15m_closed_end=2026-11-05T23:45+00:00, prior8high=1.626200, depth_time=2026-11-05T23:45:32+00:00, book20_bid_proxy_usdt=37715, book20_ask_proxy_usdt=15701, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=7154986. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
