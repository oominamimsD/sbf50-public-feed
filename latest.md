# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T07:30:45Z**
- feed_generated_utc: 2026-10-17T07:30:47+00:00
- source_sha256: `57e50208f218bd277fd154088d58876c203130bbc843e37b53385ed42459b2e4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T07:30+00:00, close=81614.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T07:00+00:00, close=81593.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.952100|-7.10|-4.15|-7.45|13142051|2.05|
|RIVER_USDT|1.076000|-4.44|-8.96|-4.79|5012275|9.30|
|STRK_USDT|0.071060|-3.90|-5.64|-4.25|21075478|1.41|
|ARB_USDT|0.188340|-3.38|4.17|-3.73|29564128|0.53|
|APT_USDT|0.828000|-3.28|3.43|-3.63|12055386|1.21|
|OP_USDT|0.135960|-2.88|10.33|-3.23|14483055|0.74|
|FET_USDT|0.194400|-2.60|-10.41|-2.95|12116600|5.14|
|TAO_USDT|274.800000|-2.07|0.04|-2.42|66772540|1.09|
|SEI_USDT|0.063120|-1.83|-3.60|-2.18|19233334|1.58|
|ZEC_USDT|1167.740000|-1.70|-4.15|-2.05|1343627856|0.09|
|ICP_USDT|2.993000|-1.48|-0.86|-1.83|8907800|3.34|
|SUI_USDT|1.008200|-1.20|-4.67|-1.55|92567653|0.99|
|FARTCOIN_USDT|0.152930|-1.15|-6.39|-1.50|7089633|0.65|
|DOT_USDT|1.158500|-1.05|-2.48|-1.40|19429982|0.86|
|AVAX_USDT|9.994000|-0.88|-1.94|-1.23|112999773|1.00|
|ENA_USDT|0.198160|-0.88|-8.08|-1.23|38624252|0.51|
|AAVE_USDT|156.100000|-0.75|-8.08|-1.10|27397606|0.64|
|LTC_USDT|59.410000|-0.75|-6.58|-1.10|8710928|3.37|
|XLM_USDT|0.179330|-0.74|-6.93|-1.09|14730257|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.828000|0.826200|0.828000|4.13|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188340|0.188230|0.188340|0.56|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.994000|9.973000|9.994000|1.15|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.158500|1.159800|1.158500|5.18|Y|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.152930|0.152810|0.152940|2.64|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194400|0.193700|0.194400|3.47|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.993000|2.991000|2.993000|3.54|N|Y/N|Y/Y|Y|N|
|OP_USDT|0.135960|0.135900|0.135980|4.01|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.076000|1.070000|1.076000|4.28|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.063120|0.063420|0.063120|1.18|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.071060|0.070440|0.071040|0.55|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.008200|1.007000|1.008200|1.66|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.800000|274.740000|274.800000|2.58|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1167.740000|1159.260000|1167.690000|0.97|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.952100|1.945500|1.952600|1.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.847500, depth_time=2026-10-17T07:30:18+00:00, book20_bid_proxy_usdt=94894, book20_ask_proxy_usdt=129343, funding_indicative=0.000072, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=12055386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T07:30:01+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.191260, depth_time=2026-10-17T07:30:15+00:00, book20_bid_proxy_usdt=38825, book20_ask_proxy_usdt=60034, funding_indicative=-0.000022, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=29564128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=10.030000, depth_time=2026-10-17T07:30:44+00:00, book20_bid_proxy_usdt=737320, book20_ask_proxy_usdt=3212900, funding_indicative=0.000005, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=112999773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=1.194100, depth_time=2026-10-17T07:30:42+00:00, book20_bid_proxy_usdt=99107, book20_ask_proxy_usdt=221102, funding_indicative=-0.000015, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=19429982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.154340, depth_time=2026-10-17T07:30:39+00:00, book20_bid_proxy_usdt=55584, book20_ask_proxy_usdt=45105, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=7089633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.195600, depth_time=2026-10-17T07:30:23+00:00, book20_bid_proxy_usdt=1812188, book20_ask_proxy_usdt=1252155, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=12116600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=3.039000, depth_time=2026-10-17T07:30:34+00:00, book20_bid_proxy_usdt=872986, book20_ask_proxy_usdt=823765, funding_indicative=0.000020, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=8907800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.138800, depth_time=2026-10-17T07:30:21+00:00, book20_bid_proxy_usdt=45390, book20_ask_proxy_usdt=48432, funding_indicative=-0.000042, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=14483055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=1.082000, depth_time=2026-10-17T07:30:10+00:00, book20_bid_proxy_usdt=400245, book20_ask_proxy_usdt=441964, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=5012275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.064210, depth_time=2026-10-17T07:30:29+00:00, book20_bid_proxy_usdt=157504, book20_ask_proxy_usdt=247790, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=19233334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T07:30:02+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=0.071660, depth_time=2026-10-17T07:30:12+00:00, book20_bid_proxy_usdt=275562, book20_ask_proxy_usdt=409368, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=21075478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T07:30:01+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=1.017100, depth_time=2026-10-17T07:30:36+00:00, book20_bid_proxy_usdt=825924, book20_ask_proxy_usdt=1035612, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=92567653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T07:30:01+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=276.750000, depth_time=2026-10-17T07:30:24+00:00, book20_bid_proxy_usdt=48992, book20_ask_proxy_usdt=127045, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=66772540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T07:30:01+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=1168.640000, depth_time=2026-10-17T07:30:31+00:00, book20_bid_proxy_usdt=659277, book20_ask_proxy_usdt=135347, funding_indicative=0.000021, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=1343627856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T07:30:01+00:00, last15m_closed_end=2026-10-17T07:30+00:00, prior8high=1.977200, depth_time=2026-10-17T07:30:08+00:00, book20_bid_proxy_usdt=44520, book20_ask_proxy_usdt=38402, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.10%, turnover=13142051. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
