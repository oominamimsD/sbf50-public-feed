# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T23:00:29Z**
- feed_generated_utc: 2026-11-07T23:00:31+00:00
- source_sha256: `f7db4978171dbfabac33d10765d7b8f5d9d5a5abe1d39adf580616c39f3c6347`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T23:00+00:00, close=75749.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T23:00+00:00, close=75749.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124000|-2.20|-60.09|-2.23|8487783|8.07|
|QNT_USDT|195.510000|-1.81|-2.75|-1.84|40602511|0.51|
|ENA_USDT|0.157490|-1.72|-18.82|-1.75|27284931|0.64|
|PEPE_USDT|0.000005|-1.56|-2.64|-1.59|40663797|1.66|
|PUMPFUN_USDT|0.003685|-1.52|-11.88|-1.55|17169856|2.71|
|ZEC_USDT|1257.530000|-1.10|-2.10|-1.13|1820912296|0.08|
|LINK_USDT|10.786000|-1.09|-6.78|-1.12|71949702|0.93|
|WLD_USDT|0.332800|-1.07|-17.70|-1.10|24985935|3.00|
|DOT_USDT|0.891500|-0.98|-7.03|-1.01|6050981|1.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.891500|0.878700|0.891500|1.33|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.157490|0.155860|0.157490|0.45|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.786000|10.708000|10.786000|0.62|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.97|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003685|0.003634|0.003685|1.38|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.510000|195.390000|195.590000|2.13|N|Y/Y|N/N|Y|N|
|UAI_USDT|0.124000|0.119900|0.124000|0.26|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.332800|0.327700|0.332800|0.06|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1257.530000|1235.840000|1257.530000|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=0.896500, depth_time=2026-11-07T23:00:29+00:00, book20_bid_proxy_usdt=460810, book20_ask_proxy_usdt=440403, funding_indicative=0.000085, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=6050981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=0.157810, depth_time=2026-11-07T23:00:13+00:00, book20_bid_proxy_usdt=190464, book20_ask_proxy_usdt=81924, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=27284931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=10.797000, depth_time=2026-11-07T23:00:24+00:00, book20_bid_proxy_usdt=204107, book20_ask_proxy_usdt=237436, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=71949702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=0.000005, depth_time=2026-11-07T23:00:16+00:00, book20_bid_proxy_usdt=44160, book20_ask_proxy_usdt=64361, funding_indicative=0.000049, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=40663797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=0.003720, depth_time=2026-11-07T23:00:17+00:00, book20_bid_proxy_usdt=2174549, book20_ask_proxy_usdt=1920560, funding_indicative=0.000002, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=17169856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=197.780000, depth_time=2026-11-07T23:00:05+00:00, book20_bid_proxy_usdt=75897, book20_ask_proxy_usdt=57030, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=40602511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=0.123000, depth_time=2026-11-07T23:00:08+00:00, book20_bid_proxy_usdt=257932, book20_ask_proxy_usdt=196440, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=8487783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=0.333600, depth_time=2026-11-07T23:00:24+00:00, book20_bid_proxy_usdt=3037802, book20_ask_proxy_usdt=2425513, funding_indicative=-0.000073, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=24985935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T23:00:01+00:00, last15m_closed_end=2026-11-07T23:00+00:00, prior8high=1260.240000, depth_time=2026-11-07T23:00:21+00:00, book20_bid_proxy_usdt=118120, book20_ask_proxy_usdt=520346, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=1820912296. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
