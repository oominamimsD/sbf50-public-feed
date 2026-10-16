# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T22:15:42Z**
- feed_generated_utc: 2026-10-16T22:15:44+00:00
- source_sha256: `2536f1c608b789e3daa84df48df8ae88821d3092686f6da8e732232065ed4db4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T22:15+00:00, close=81742.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T22:00+00:00, close=81648.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|8.610000|-4.09|24.26|-4.60|116451149|1.16|
|ZEC_USDT|1144.710000|-3.64|-6.04|-4.15|1423360922|0.09|
|FILECOIN_USDT|1.129800|-3.17|5.58|-3.68|23184504|0.89|
|ZRO_USDT|2.039000|-2.96|0.10|-3.47|15953883|0.98|
|RIVER_USDT|1.096000|-2.66|-7.27|-3.17|5679622|9.13|
|TAO_USDT|273.160000|-2.65|-0.54|-3.16|82047335|1.46|
|BAT_USDT|0.199880|-2.51|64.29|-3.02|18163338|2.00|
|OP_USDT|0.136560|-2.45|10.82|-2.96|14445516|1.47|
|APT_USDT|0.836600|-2.27|4.50|-2.78|12399081|1.20|
|ARB_USDT|0.191550|-1.73|5.94|-2.24|32445123|0.52|
|AAVE_USDT|154.750000|-1.60|-8.88|-2.11|31407623|0.65|
|DOT_USDT|1.153700|-1.46|-2.88|-1.97|21794795|0.87|
|AVAX_USDT|9.975000|-1.07|-2.12|-1.58|127497774|1.00|
|ICP_USDT|3.006000|-1.05|-0.43|-1.56|8783650|3.33|
|ENA_USDT|0.198110|-0.91|-8.10|-1.42|40679039|0.51|
|LTC_USDT|59.370000|-0.81|-6.65|-1.32|9863657|1.68|
|HBAR_USDT|0.083520|-0.70|-8.07|-1.21|20765658|1.20|
|FARTCOIN_USDT|0.153700|-0.65|-5.91|-1.16|7053417|0.65|
|ONDO_USDT|0.454500|-0.56|-5.33|-1.07|28293101|2.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.750000|153.830000|154.740000|0.80|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.836600|0.834600|0.836600|0.16|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191550|0.190740|0.191550|0.48|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.975000|9.920000|9.975000|0.90|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.199880|0.195230|0.199880|0.82|N|N/Y|N/N|Y|N|
|DOT_USDT|1.153700|1.145400|1.153700|0.34|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.198110|0.196720|0.198110|1.18|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.129800|1.120000|1.129800|0.25|N|Y/Y|N/N|Y|N|
|ICP_USDT|3.006000|2.984000|3.006000|0.66|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.610000|8.469000|8.609000|0.86|N|Y/Y|N/N|Y|N|
|OP_USDT|0.136560|0.135160|0.136560|0.25|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.096000|1.072000|1.096000|1.62|N|Y/Y|Y/N|Y|N|
|TAO_USDT|273.160000|270.100000|273.200000|1.50|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1144.710000|1134.590000|1145.290000|0.88|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.039000|2.044700|2.039000|0.20|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=156.290000, depth_time=2026-10-16T22:15:28+00:00, book20_bid_proxy_usdt=319637, book20_ask_proxy_usdt=301354, funding_indicative=0.000069, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=31407623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=0.848000, depth_time=2026-10-16T22:15:26+00:00, book20_bid_proxy_usdt=119476, book20_ask_proxy_usdt=113091, funding_indicative=0.000053, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=12399081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=0.193380, depth_time=2026-10-16T22:15:29+00:00, book20_bid_proxy_usdt=84829, book20_ask_proxy_usdt=58118, funding_indicative=-0.000083, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=32445123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=10.024000, depth_time=2026-10-16T22:15:35+00:00, book20_bid_proxy_usdt=839305, book20_ask_proxy_usdt=847035, funding_indicative=-0.000007, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=127497774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=0.202830, depth_time=2026-10-16T22:15:21+00:00, book20_bid_proxy_usdt=22028, book20_ask_proxy_usdt=25842, funding_indicative=-0.000105, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=18163338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=1.162700, depth_time=2026-10-16T22:15:34+00:00, book20_bid_proxy_usdt=286374, book20_ask_proxy_usdt=351138, funding_indicative=0.000029, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=21794795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=0.199440, depth_time=2026-10-16T22:15:41+00:00, book20_bid_proxy_usdt=169850, book20_ask_proxy_usdt=217887, funding_indicative=0.000027, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=40679039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=1.145500, depth_time=2026-10-16T22:15:10+00:00, book20_bid_proxy_usdt=418437, book20_ask_proxy_usdt=404189, funding_indicative=0.000095, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=23184504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=3.023000, depth_time=2026-10-16T22:15:37+00:00, book20_bid_proxy_usdt=839538, book20_ask_proxy_usdt=1176121, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=8783650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=8.745000, depth_time=2026-10-16T22:15:07+00:00, book20_bid_proxy_usdt=328992, book20_ask_proxy_usdt=187155, funding_indicative=-0.000051, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=116451149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=0.137470, depth_time=2026-10-16T22:15:24+00:00, book20_bid_proxy_usdt=44782, book20_ask_proxy_usdt=60220, funding_indicative=0.000063, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=14445516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=1.112000, depth_time=2026-10-16T22:15:15+00:00, book20_bid_proxy_usdt=403399, book20_ask_proxy_usdt=313038, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=5679622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=276.330000, depth_time=2026-10-16T22:15:19+00:00, book20_bid_proxy_usdt=107723, book20_ask_proxy_usdt=94864, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=82047335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=1153.360000, depth_time=2026-10-16T22:15:09+00:00, book20_bid_proxy_usdt=464756, book20_ask_proxy_usdt=347959, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=1423360922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T22:15:01+00:00, last15m_closed_end=2026-10-16T22:15+00:00, prior8high=2.113300, depth_time=2026-10-16T22:15:14+00:00, book20_bid_proxy_usdt=40926, book20_ask_proxy_usdt=47593, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=15953883. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
