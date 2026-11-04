# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T20:00:32Z**
- feed_generated_utc: 2026-11-04T20:00:35+00:00
- source_sha256: `55a28d286806f65d0dfd5dd3f893a472103cf6e12d36b709be68cd4553b8db70`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002500|-21.60|-87.55|-21.22|16944917|3.99|
|TRUMPOFFICIAL_USDT|1.297000|-9.04|-24.10|-8.66|24591964|7.71|
|AGT_USDT|0.032700|-8.91|-27.47|-8.53|5080909|3.06|
|ZRO_USDT|1.770400|-6.31|3.41|-5.93|11170056|1.13|
|PUMPFUN_USDT|0.004177|-6.13|-0.71|-5.75|19014622|4.79|
|WLD_USDT|0.373700|-4.30|-13.65|-3.92|74490751|2.68|
|WLFI_USDT|0.047420|-4.24|-9.64|-3.86|5909651|2.11|
|OP_USDT|0.109450|-3.51|-1.46|-3.13|11560497|1.83|
|HYPE_USDT|83.383000|-2.93|4.41|-2.55|88473819|0.12|
|PEPE_USDT|0.000005|-2.19|2.05|-1.81|145124334|0.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032700|0.031770|0.032690|0.66|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002500|0.002455|0.002500|0.21|N|Y/Y|Y/Y|N|N|
|HYPE_USDT|83.383000|83.840000|83.440000|2.47|Y|Y/Y|Y/Y|N|Y|
|OP_USDT|0.109450|0.109230|0.109450|0.74|N|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.71|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004177|0.004138|0.004173|1.28|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.297000|1.215000|1.297000|0.23|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.373700|0.374000|0.373700|1.33|Y|Y/Y|Y/N|N|N|
|WLFI_USDT|0.047420|0.046640|0.047420|0.13|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.770400|1.778700|1.770400|2.69|Y|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.034090, depth_time=2026-11-04T20:00:13+00:00, book20_bid_proxy_usdt=30356, book20_ask_proxy_usdt=22628, funding_indicative=0.000053, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.91%, turnover=5080909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.002842, depth_time=2026-11-04T20:00:09+00:00, book20_bid_proxy_usdt=90557, book20_ask_proxy_usdt=69844, funding_indicative=-0.000483, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-21.60%, turnover=16944917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=85.210000, depth_time=2026-11-04T20:00:29+00:00, book20_bid_proxy_usdt=103214, book20_ask_proxy_usdt=199101, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=88473819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.112460, depth_time=2026-11-04T20:00:25+00:00, book20_bid_proxy_usdt=104930, book20_ask_proxy_usdt=70314, funding_indicative=0.000071, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.51%, turnover=11560497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.000005, depth_time=2026-11-04T20:00:31+00:00, book20_bid_proxy_usdt=38768, book20_ask_proxy_usdt=80502, funding_indicative=0.000100, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=145124334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.004301, depth_time=2026-11-04T20:00:19+00:00, book20_bid_proxy_usdt=1510196, book20_ask_proxy_usdt=2007453, funding_indicative=0.000048, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.13%, turnover=19014622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=1.327000, depth_time=2026-11-04T20:00:11+00:00, book20_bid_proxy_usdt=1226184, book20_ask_proxy_usdt=1033504, funding_indicative=-0.000334, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.04%, turnover=24591964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.383900, depth_time=2026-11-04T20:00:21+00:00, book20_bid_proxy_usdt=2383401, book20_ask_proxy_usdt=1867561, funding_indicative=-0.000435, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=74490751. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=0.048210, depth_time=2026-11-04T20:00:22+00:00, book20_bid_proxy_usdt=358054, book20_ask_proxy_usdt=261474, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=5909651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T20:00:02+00:00, last15m_closed_end=2026-11-04T20:00+00:00, prior8high=1.845000, depth_time=2026-11-04T20:00:17+00:00, book20_bid_proxy_usdt=23649, book20_ask_proxy_usdt=44206, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.31%, turnover=11170056. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
