# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T17:45:26Z**
- feed_generated_utc: 2026-10-17T17:45:28+00:00
- source_sha256: `dbecd746762ebc84e7d73d1b6d6a80035f6902bcb7e84b64504bd3735103f029`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T17:45+00:00, close=81249.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T17:00+00:00, close=81226.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.247600|-3.39|5.09|-3.31|9453235|4.04|
|DNA_USDT|0.263800|-3.05|UNKNOWN|-2.97|8050416|3.79|
|FILECOIN_USDT|1.061100|-2.41|-5.91|-2.33|26754513|0.94|
|ARB_USDT|0.180690|-1.75|-3.20|-1.67|29551129|0.55|
|QNT_USDT|197.050000|-1.67|-19.61|-1.59|64836901|1.01|
|ZEC_USDT|1123.890000|-1.52|-8.75|-1.44|1169738861|0.09|
|FET_USDT|0.187500|-1.36|-17.61|-1.28|11439390|5.33|
|DOT_USDT|1.104200|-1.18|-12.14|-1.10|16056717|0.91|
|SEI_USDT|0.061280|-1.17|-11.77|-1.09|14092064|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180690|0.180230|0.180610|0.55|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.263800|0.254400|0.263800|0.30|N|Y/Y|?|Y|N|
|DOT_USDT|1.104200|1.102200|1.104200|0.45|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.247600|0.248300|0.247600|0.77|N|Y/Y|N/N|Y|N|
|FET_USDT|0.187500|0.184200|0.187500|0.42|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.061100|1.061800|1.061100|2.67|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|197.050000|195.160000|197.050000|0.60|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.061280|0.061120|0.061250|1.78|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1123.890000|1111.380000|1123.910000|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=0.185530, depth_time=2026-10-17T17:45:14+00:00, book20_bid_proxy_usdt=81490, book20_ask_proxy_usdt=84235, funding_indicative=-0.000037, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=29551129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=0.275100, depth_time=2026-10-17T17:45:07+00:00, book20_bid_proxy_usdt=107608, book20_ask_proxy_usdt=85101, funding_indicative=-0.001364, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=8050416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=1.130400, depth_time=2026-10-17T17:45:22+00:00, book20_bid_proxy_usdt=145396, book20_ask_proxy_usdt=276340, funding_indicative=-0.000083, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=16056717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=0.258300, depth_time=2026-10-17T17:45:06+00:00, book20_bid_proxy_usdt=740857, book20_ask_proxy_usdt=384492, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=9453235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=0.192200, depth_time=2026-10-17T17:45:21+00:00, book20_bid_proxy_usdt=1621605, book20_ask_proxy_usdt=1432164, funding_indicative=-0.000101, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=11439390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=1.095900, depth_time=2026-10-17T17:45:12+00:00, book20_bid_proxy_usdt=419716, book20_ask_proxy_usdt=594520, funding_indicative=-0.000077, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=26754513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=201.480000, depth_time=2026-10-17T17:45:16+00:00, book20_bid_proxy_usdt=66360, book20_ask_proxy_usdt=59220, funding_indicative=-0.000092, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=64836901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T17:45:02+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=0.062850, depth_time=2026-10-17T17:45:25+00:00, book20_bid_proxy_usdt=134014, book20_ask_proxy_usdt=307304, funding_indicative=0.000097, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=14092064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T17:45:01+00:00, last15m_closed_end=2026-10-17T17:45+00:00, prior8high=1153.400000, depth_time=2026-10-17T17:45:19+00:00, book20_bid_proxy_usdt=866559, book20_ask_proxy_usdt=118630, funding_indicative=0.000061, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=1169738861. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
