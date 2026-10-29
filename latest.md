# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T17:45:32Z**
- feed_generated_utc: 2026-10-29T17:45:35+00:00
- source_sha256: `0b36f36e427d3d085fb75fb607c070126b51e3a2bc4c101dce1684fd1bd15724`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T17:45+00:00, close=80859.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T17:00+00:00, close=81232.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.527900|-6.72|-14.64|-5.66|9795556|0.65|
|NEAR_USDT|4.486000|-3.50|-9.26|-2.44|118447356|2.23|
|QNT_USDT|191.770000|-3.50|0.55|-2.44|64098936|2.09|
|WLD_USDT|0.423200|-3.00|-20.46|-1.94|84346832|2.36|
|FARTCOIN_USDT|0.130610|-2.81|-8.56|-1.75|11841121|0.77|
|AKE_USDT|0.020486|-2.73|-33.53|-1.67|5725399|2.44|
|TRUMPOFFICIAL_USDT|1.681000|-2.71|-3.61|-1.65|6904706|5.95|
|FET_USDT|0.180100|-2.54|-2.80|-1.48|9650912|5.55|
|SEI_USDT|0.052160|-2.39|-10.17|-1.33|5841634|1.92|
|HBAR_USDT|0.073600|-2.21|-8.12|-1.15|16217810|2.72|
|ICP_USDT|2.572000|-2.09|-6.37|-1.03|5411069|3.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020486|0.020451|0.020436|1.51|Y|Y/Y|Y/Y|N|Y|
|BTW_USDT|1.527900|1.509900|1.530300|0.88|N|Y/Y|Y/N|N|N|
|FARTCOIN_USDT|0.130610|0.131600|0.130480|0.99|N|N/N|N/Y|N|N|
|FET_USDT|0.180100|0.181300|0.180100|2.01|Y|N/N|N/N|N|N|
|HBAR_USDT|0.073600|0.074110|0.073580|1.20|N|N/N|Y/Y|N|N|
|ICP_USDT|2.572000|2.585000|2.572000|0.42|N|N/N|N/Y|N|N|
|NEAR_USDT|4.486000|4.550000|4.485000|1.15|N|N/N|N/Y|N|N|
|QNT_USDT|191.770000|194.300000|191.780000|1.20|N|N/N|N/Y|N|N|
|SEI_USDT|0.052160|0.052470|0.052160|0.49|N|N/N|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.681000|1.695000|1.681000|1.42|Y|N/N|N/Y|N|N|
|WLD_USDT|0.423200|0.427800|0.423200|1.62|Y|N/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=0.021138, depth_time=2026-10-29T17:45:17+00:00, book20_bid_proxy_usdt=3539, book20_ask_proxy_usdt=5471, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=5725399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=1.650600, depth_time=2026-10-29T17:45:07+00:00, book20_bid_proxy_usdt=26925, book20_ask_proxy_usdt=16552, funding_indicative=-0.000049, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.72%, turnover=9795556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=0.136060, depth_time=2026-10-29T17:45:17+00:00, book20_bid_proxy_usdt=50715, book20_ask_proxy_usdt=76065, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=11841121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=0.185600, depth_time=2026-10-29T17:45:22+00:00, book20_bid_proxy_usdt=1526146, book20_ask_proxy_usdt=963189, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=9650912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=0.075780, depth_time=2026-10-29T17:45:28+00:00, book20_bid_proxy_usdt=558246, book20_ask_proxy_usdt=863167, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=16217810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=2.641000, depth_time=2026-10-29T17:45:31+00:00, book20_bid_proxy_usdt=870784, book20_ask_proxy_usdt=1233268, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=5411069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=4.689000, depth_time=2026-10-29T17:45:09+00:00, book20_bid_proxy_usdt=2508215, book20_ask_proxy_usdt=811405, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=118447356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=199.910000, depth_time=2026-10-29T17:45:12+00:00, book20_bid_proxy_usdt=46322, book20_ask_proxy_usdt=58304, funding_indicative=-0.000040, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=64098936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=0.053940, depth_time=2026-10-29T17:45:26+00:00, book20_bid_proxy_usdt=190848, book20_ask_proxy_usdt=171590, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=5841634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T17:45:03+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=1.739000, depth_time=2026-10-29T17:45:21+00:00, book20_bid_proxy_usdt=1588705, book20_ask_proxy_usdt=1746082, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=6904706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T17:45:02+00:00, last15m_closed_end=2026-10-29T17:45+00:00, prior8high=0.443700, depth_time=2026-10-29T17:45:15+00:00, book20_bid_proxy_usdt=2798763, book20_ask_proxy_usdt=4256368, funding_indicative=0.000031, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=84346832. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
