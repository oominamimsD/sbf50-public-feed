# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T13:30:43Z**
- feed_generated_utc: 2026-10-13T13:30:46+00:00
- source_sha256: `c7484eaf4a03e088ae7f3df0c6e692f550ce35d511bc832aa415b150fb2b7d69`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T13:30+00:00, close=83394.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T13:00+00:00, close=83324.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.220200|-23.93|3.38|-24.79|9468032|4.54|
|W_USDT|0.018400|-23.52|30.09|-24.38|16493962|4.89|
|ZRO_USDT|2.019500|-10.68|-1.27|-11.54|18627504|3.46|
|QNT_USDT|205.290000|-10.11|-20.04|-10.97|89737460|1.46|
|RLC_USDT|0.901100|-8.85|64.43|-9.71|6526368|1.11|
|NEAR_USDT|5.072000|-8.59|0.99|-9.45|274325038|1.97|
|LIT_USDT|3.332600|-8.07|-12.34|-8.93|8568303|0.30|
|PYTH_USDT|0.082080|-7.40|7.56|-8.26|10547417|7.32|
|USELESS_USDT|0.169680|-6.56|-25.16|-7.42|5913993|1.18|
|SEI_USDT|0.062410|-5.96|-13.21|-6.82|9959036|1.60|
|ONDO_USDT|0.468700|-5.90|-4.11|-6.76|66170522|2.13|
|PUMPFUN_USDT|0.005025|-5.34|-20.67|-6.20|34685812|1.99|
|GRASS_USDT|0.712200|-4.65|0.99|-5.51|5592522|1.40|
|JUP_USDT|0.328500|-4.19|-2.78|-5.05|8789853|3.04|
|HYPE_USDT|81.330000|-3.60|-12.21|-4.46|84031054|0.12|
|LTC_USDT|61.160000|-2.85|-12.57|-3.71|23351695|3.27|
|STRK_USDT|0.088350|-2.55|69.54|-3.41|58684850|1.13|
|MAGIC_USDT|0.120000|-1.60|93.57|-2.46|8364343|1.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.220200|0.217900|0.220200|0.40|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.712200|0.709600|0.712100|1.54|N|Y/Y|Y/N|N|N|
|HYPE_USDT|81.330000|80.799000|81.330000|0.53|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.328500|0.321900|0.328500|1.18|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.332600|3.270000|3.331400|1.00|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.072000|4.984000|5.074000|1.21|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.468700|0.459900|0.468700|0.53|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005025|0.004859|0.005027|0.96|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.082080|0.081500|0.082080|0.48|N|Y/Y|N/N|N|N|
|QNT_USDT|205.290000|201.440000|205.460000|1.23|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.901100|0.896200|0.901000|0.44|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.062410|0.061440|0.062410|1.44|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.169680|0.163600|0.169680|1.40|N|Y/Y|Y/Y|N|N|
|W_USDT|0.018400|0.018139|0.018400|0.62|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.019500|2.023200|2.019500|2.28|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T13:30:03+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.224800, depth_time=2026-10-13T13:30:08+00:00, book20_bid_proxy_usdt=79817, book20_ask_proxy_usdt=106077, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.93%, turnover=9468032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.727200, depth_time=2026-10-13T13:30:35+00:00, book20_bid_proxy_usdt=89413, book20_ask_proxy_usdt=94076, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=5592522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-13T13:30:03+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=82.881000, depth_time=2026-10-13T13:30:42+00:00, book20_bid_proxy_usdt=92491, book20_ask_proxy_usdt=193095, funding_indicative=0.000037, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.60%, turnover=84031054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.330300, depth_time=2026-10-13T13:30:39+00:00, book20_bid_proxy_usdt=450099, book20_ask_proxy_usdt=507834, funding_indicative=-0.000052, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=8789853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=3.343600, depth_time=2026-10-13T13:30:23+00:00, book20_bid_proxy_usdt=28794, book20_ask_proxy_usdt=22625, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.07%, turnover=8568303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T13:30:03+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=5.152000, depth_time=2026-10-13T13:30:21+00:00, book20_bid_proxy_usdt=1567066, book20_ask_proxy_usdt=1956804, funding_indicative=0.000040, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.59%, turnover=274325038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T13:30:03+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.471400, depth_time=2026-10-13T13:30:33+00:00, book20_bid_proxy_usdt=1626993, book20_ask_proxy_usdt=1150360, funding_indicative=-0.000077, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.90%, turnover=66170522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.004996, depth_time=2026-10-13T13:30:35+00:00, book20_bid_proxy_usdt=1307772, book20_ask_proxy_usdt=833158, funding_indicative=0.000030, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.34%, turnover=34685812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.083980, depth_time=2026-10-13T13:30:25+00:00, book20_bid_proxy_usdt=128574, book20_ask_proxy_usdt=61532, funding_indicative=-0.000029, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.40%, turnover=10547417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T13:30:03+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=209.790000, depth_time=2026-10-13T13:30:16+00:00, book20_bid_proxy_usdt=42823, book20_ask_proxy_usdt=31587, funding_indicative=-0.000171, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.11%, turnover=89737460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.928800, depth_time=2026-10-13T13:30:19+00:00, book20_bid_proxy_usdt=132709, book20_ask_proxy_usdt=41384, funding_indicative=-0.000322, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.85%, turnover=6526368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.063040, depth_time=2026-10-13T13:30:30+00:00, book20_bid_proxy_usdt=141211, book20_ask_proxy_usdt=77084, funding_indicative=0.000082, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.96%, turnover=9959036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.170590, depth_time=2026-10-13T13:30:28+00:00, book20_bid_proxy_usdt=24670, book20_ask_proxy_usdt=12934, funding_indicative=0.000057, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.56%, turnover=5913993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T13:30:03+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=0.019623, depth_time=2026-10-13T13:30:11+00:00, book20_bid_proxy_usdt=35298, book20_ask_proxy_usdt=49467, funding_indicative=-0.000432, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.52%, turnover=16493962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T13:30:04+00:00, last15m_closed_end=2026-10-13T13:30+00:00, prior8high=2.092600, depth_time=2026-10-13T13:30:13+00:00, book20_bid_proxy_usdt=21583, book20_ask_proxy_usdt=38781, funding_indicative=0.000016, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.68%, turnover=18627504. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
