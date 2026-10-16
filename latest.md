# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T21:15:43Z**
- feed_generated_utc: 2026-10-16T21:15:45+00:00
- source_sha256: `28b74c7c17156a29c49bd4336e46cf16c4da7f9240cea50c6ba1fb100625c082`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T21:15+00:00, close=81689, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T21:00+00:00, close=81694.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|8.512000|-5.19|22.84|-5.64|116010470|3.52|
|ZEC_USDT|1141.870000|-3.88|-6.27|-4.33|1446650920|0.09|
|BAT_USDT|0.197880|-3.48|62.65|-3.93|18981869|0.51|
|FILECOIN_USDT|1.126800|-3.42|5.30|-3.87|23250447|0.89|
|TAO_USDT|272.070000|-3.04|-0.94|-3.49|81289322|2.21|
|OP_USDT|0.136270|-2.66|10.59|-3.11|14639916|0.73|
|RIVER_USDT|1.102000|-2.13|-6.76|-2.58|5848929|9.08|
|STRK_USDT|0.072660|-1.74|-3.51|-2.19|22795139|1.38|
|APT_USDT|0.841500|-1.70|5.12|-2.15|12457782|3.57|
|ARB_USDT|0.191630|-1.69|5.99|-2.14|32830379|4.70|
|FARTCOIN_USDT|0.152520|-1.42|-6.64|-1.87|7208256|0.66|
|NEAR_USDT|4.977000|-1.36|4.75|-1.81|163597097|2.01|
|AAVE_USDT|155.160000|-1.34|-8.64|-1.79|31554894|1.29|
|DOT_USDT|1.155000|-1.34|-2.77|-1.79|22107178|0.87|
|HBAR_USDT|0.083000|-1.31|-8.65|-1.76|20726280|1.21|
|ICP_USDT|2.998000|-1.31|-0.69|-1.76|9115440|3.34|
|AVAX_USDT|9.965000|-1.17|-2.22|-1.62|126225728|1.00|
|ONDO_USDT|0.451800|-1.15|-5.89|-1.60|28495585|2.22|
|ENA_USDT|0.197760|-1.08|-8.26|-1.53|40446700|0.51|
|LTC_USDT|59.430000|-0.71|-6.55|-1.16|9757646|3.37|
|ETH_USDT|2416.560000|-0.56|-2.86|-1.01|1759384415|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.160000|154.580000|155.160000|1.19|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.841500|0.830600|0.841900|1.68|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191630|0.190240|0.191720|0.58|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.197880|0.193970|0.197880|1.09|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.155000|1.140000|1.155000|0.78|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.152520|0.151400|0.152520|1.29|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.126800|1.127300|1.126800|1.03|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.083000|0.082050|0.083020|1.55|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.512000|8.540000|8.515000|0.90|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.977000|4.955000|4.977000|0.61|N|Y/Y|Y/N|Y|N|
|OP_USDT|0.136270|0.134940|0.136270|0.72|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.102000|1.066000|1.102000|0.31|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.072660|0.071640|0.072660|0.40|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|272.070000|272.060000|272.110000|1.27|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1141.870000|1131.850000|1141.860000|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=156.610000, depth_time=2026-10-16T21:15:37+00:00, book20_bid_proxy_usdt=287150, book20_ask_proxy_usdt=226078, funding_indicative=0.000066, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=31554894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.848000, depth_time=2026-10-16T21:15:28+00:00, book20_bid_proxy_usdt=95683, book20_ask_proxy_usdt=140887, funding_indicative=0.000088, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=12457782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.194080, depth_time=2026-10-16T21:15:30+00:00, book20_bid_proxy_usdt=36015, book20_ask_proxy_usdt=47392, funding_indicative=-0.000025, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=32830379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.199860, depth_time=2026-10-16T21:15:14+00:00, book20_bid_proxy_usdt=24267, book20_ask_proxy_usdt=14162, funding_indicative=-0.000103, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=18981869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=1.162700, depth_time=2026-10-16T21:15:40+00:00, book20_bid_proxy_usdt=191406, book20_ask_proxy_usdt=429739, funding_indicative=0.000053, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=22107178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.153850, depth_time=2026-10-16T21:15:33+00:00, book20_bid_proxy_usdt=74296, book20_ask_proxy_usdt=39314, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=7208256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=1.145500, depth_time=2026-10-16T21:15:15+00:00, book20_bid_proxy_usdt=464985, book20_ask_proxy_usdt=580283, funding_indicative=0.000090, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=23250447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.083070, depth_time=2026-10-16T21:15:42+00:00, book20_bid_proxy_usdt=526608, book20_ask_proxy_usdt=1567924, funding_indicative=0.000010, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=20726280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=8.745000, depth_time=2026-10-16T21:15:08+00:00, book20_bid_proxy_usdt=212052, book20_ask_proxy_usdt=265725, funding_indicative=-0.000026, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.19%, turnover=116010470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=5.051000, depth_time=2026-10-16T21:15:35+00:00, book20_bid_proxy_usdt=3204100, book20_ask_proxy_usdt=3299387, funding_indicative=0.000011, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=163597097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.137590, depth_time=2026-10-16T21:15:21+00:00, book20_bid_proxy_usdt=34306, book20_ask_proxy_usdt=57441, funding_indicative=0.000033, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=14639916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=1.096000, depth_time=2026-10-16T21:15:24+00:00, book20_bid_proxy_usdt=542157, book20_ask_proxy_usdt=446232, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=5848929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=0.073730, depth_time=2026-10-16T21:15:26+00:00, book20_bid_proxy_usdt=249698, book20_ask_proxy_usdt=215459, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=22795139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=276.400000, depth_time=2026-10-16T21:15:19+00:00, book20_bid_proxy_usdt=98189, book20_ask_proxy_usdt=91830, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=81289322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T21:15:02+00:00, last15m_closed_end=2026-10-16T21:15+00:00, prior8high=1153.360000, depth_time=2026-10-16T21:15:09+00:00, book20_bid_proxy_usdt=271910, book20_ask_proxy_usdt=196459, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=1446650920. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
