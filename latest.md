# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T00:30:34Z**
- feed_generated_utc: 2026-11-07T00:30:36+00:00
- source_sha256: `5acca8f27cd18f950cfd5171b3988ee95424515e807f33a4f69b5d835bde2955`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T00:30+00:00, close=75895.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1336.160000|-6.64|-20.29|-6.72|7480148|3.82|
|CYBER_USDT|0.333000|-5.93|21.88|-6.01|6901273|3.01|
|TRUMPOFFICIAL_USDT|1.198000|-3.54|-23.79|-3.62|12669448|8.34|
|PUMPFUN_USDT|0.003911|-3.31|-4.77|-3.39|12721667|2.56|
|DOT_USDT|0.909800|-2.91|-6.12|-2.99|7367645|1.10|
|ENA_USDT|0.163360|-2.47|-13.96|-2.55|33055111|0.61|
|ADA_USDT|0.184000|-2.17|-4.46|-2.25|28377918|5.43|
|LIT_USDT|3.325400|-1.97|17.74|-2.05|9387518|0.30|
|ONDO_USDT|0.370800|-1.51|-7.16|-1.59|11774633|2.70|
|HBAR_USDT|0.067650|-1.09|-5.84|-1.17|5183796|1.48|
|XLM_USDT|0.153400|-1.07|-10.93|-1.15|23489215|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184000|0.183700|0.184100|0.96|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1336.160000|1322.000000|1336.160000|0.13|N|Y/Y|Y/Y|Y|N|
|CYBER_USDT|0.333000|0.327000|0.333000|1.15|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.909800|0.909000|0.909800|0.67|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163360|0.163440|0.163360|0.92|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067650|0.067340|0.067660|0.88|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.325400|3.292600|3.325400|0.23|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.370800|0.369900|0.370800|0.65|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003911|0.003882|0.003912|0.40|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.198000|1.199000|1.198000|0.50|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.153400|0.153080|0.153410|0.55|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.186500, depth_time=2026-11-07T00:30:22+00:00, book20_bid_proxy_usdt=8884144, book20_ask_proxy_usdt=7181682, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=28377918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=1360.980000, depth_time=2026-11-07T00:30:01+00:00, book20_bid_proxy_usdt=24388, book20_ask_proxy_usdt=37584, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.64%, turnover=7480148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.353200, depth_time=2026-11-07T00:30:10+00:00, book20_bid_proxy_usdt=273735, book20_ask_proxy_usdt=78149, funding_indicative=-0.002236, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.93%, turnover=6901273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.922500, depth_time=2026-11-07T00:30:13+00:00, book20_bid_proxy_usdt=369985, book20_ask_proxy_usdt=305550, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=7367645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.165100, depth_time=2026-11-07T00:30:17+00:00, book20_bid_proxy_usdt=281824, book20_ask_proxy_usdt=215545, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=33055111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.067860, depth_time=2026-11-07T00:30:31+00:00, book20_bid_proxy_usdt=894536, book20_ask_proxy_usdt=803044, funding_indicative=-0.000008, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=5183796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=3.352300, depth_time=2026-11-07T00:30:23+00:00, book20_bid_proxy_usdt=30651, book20_ask_proxy_usdt=25179, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=9387518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.373800, depth_time=2026-11-07T00:30:24+00:00, book20_bid_proxy_usdt=1998818, book20_ask_proxy_usdt=1693315, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=11774633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.003985, depth_time=2026-11-07T00:30:13+00:00, book20_bid_proxy_usdt=2762480, book20_ask_proxy_usdt=2072145, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=12721667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=1.223000, depth_time=2026-11-07T00:30:09+00:00, book20_bid_proxy_usdt=1157603, book20_ask_proxy_usdt=1424616, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=12669448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T00:30:02+00:00, last15m_closed_end=2026-11-07T00:30+00:00, prior8high=0.155040, depth_time=2026-11-07T00:30:33+00:00, book20_bid_proxy_usdt=230255, book20_ask_proxy_usdt=202360, funding_indicative=0.000004, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=23489215. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
