# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T09:00:44Z**
- feed_generated_utc: 2026-11-07T09:00:45+00:00
- source_sha256: `9d92c6e10479fbcca96033415fdbc68c8cfd6ab8a971d193baca567c4a099332`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T09:00+00:00, close=76158.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T09:00+00:00, close=76158.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.127900|-32.68|-51.84|-33.11|30986267|7.82|
|ANTHROPIC_USDT|1349.980000|-7.12|-19.47|-7.55|7967338|1.85|
|TRUMPOFFICIAL_USDT|1.190000|-5.10|-24.30|-5.53|9399793|8.41|
|OP_USDT|0.103270|-3.77|-4.56|-4.20|5481762|1.94|
|ENA_USDT|0.163790|-3.35|-13.74|-3.78|27326264|0.61|
|DOT_USDT|0.906700|-3.24|-6.44|-3.67|6377000|1.10|
|WLD_USDT|0.339000|-2.86|-17.69|-3.29|27577102|2.95|
|FARTCOIN_USDT|0.117860|-2.35|-2.02|-2.78|9413675|0.85|
|PUMPFUN_USDT|0.003951|-2.32|-3.79|-2.75|11945060|2.53|
|INJ_USDT|8.239000|-2.28|15.66|-2.71|31452141|1.21|
|ARB_USDT|0.165600|-2.25|2.14|-2.68|22536175|0.60|
|PEPE_USDT|0.000005|-2.15|-1.76|-2.58|85152095|0.60|
|ADA_USDT|0.184200|-2.07|-4.36|-2.50|26898813|5.43|
|ONDO_USDT|0.368800|-1.99|-7.66|-2.42|9831830|2.71|
|AVAX_USDT|8.321000|-1.08|-0.32|-1.51|11910562|1.20|
|DOGE_USDT|0.072130|-1.05|-4.86|-1.48|75451591|1.39|
|BEAT_USDT|0.106810|-0.99|1.57|-1.42|7754140|3.75|
|XLM_USDT|0.153800|-0.83|-10.70|-1.26|22061857|0.65|
|SOL_USDT|90.250000|-0.76|-4.80|-1.19|447958245|1.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184200|0.184400|0.184100|2.14|Y|Y/Y|Y/Y|Y|Y|
|ANTHROPIC_USDT|1349.980000|1346.300000|1349.980000|11.58|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165600|0.165260|0.165600|5.49|N|Y/N|N/N|Y|N|
|AVAX_USDT|8.321000|8.318000|8.321000|1.16|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.906700|0.906700|0.906600|1.97|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.163790|0.163670|0.163800|3.46|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117860|0.117760|0.117860|3.31|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.239000|8.239000|8.244000|0.36|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.368800|0.368700|0.368800|2.79|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.103270|0.103480|0.103280|5.73|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|1.02|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003951|0.003900|0.003952|0.89|N|N/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.190000|1.180000|1.190000|0.74|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.127900|0.121500|0.128000|1.39|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.339000|0.338900|0.339000|1.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.185200, depth_time=2026-11-07T09:00:37+00:00, book20_bid_proxy_usdt=13346060, book20_ask_proxy_usdt=10865609, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=26898813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=1361.580000, depth_time=2026-11-07T09:00:10+00:00, book20_bid_proxy_usdt=20172, book20_ask_proxy_usdt=15392, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.12%, turnover=7967338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.167180, depth_time=2026-11-07T09:00:32+00:00, book20_bid_proxy_usdt=84423, book20_ask_proxy_usdt=71478, funding_indicative=-0.000031, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=22536175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=8.357000, depth_time=2026-11-07T09:00:42+00:00, book20_bid_proxy_usdt=1432698, book20_ask_proxy_usdt=1135881, funding_indicative=0.000028, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=11910562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.911600, depth_time=2026-11-07T09:00:19+00:00, book20_bid_proxy_usdt=578889, book20_ask_proxy_usdt=311481, funding_indicative=0.000047, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=6377000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.165160, depth_time=2026-11-07T09:00:17+00:00, book20_bid_proxy_usdt=259242, book20_ask_proxy_usdt=173572, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=27326264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.118640, depth_time=2026-11-07T09:00:22+00:00, book20_bid_proxy_usdt=43019, book20_ask_proxy_usdt=48816, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=9413675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=8.392000, depth_time=2026-11-07T09:00:29+00:00, book20_bid_proxy_usdt=254205, book20_ask_proxy_usdt=210290, funding_indicative=0.000229, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=31452141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.371200, depth_time=2026-11-07T09:00:40+00:00, book20_bid_proxy_usdt=1829543, book20_ask_proxy_usdt=1593314, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=9831830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.104590, depth_time=2026-11-07T09:00:09+00:00, book20_bid_proxy_usdt=110492, book20_ask_proxy_usdt=124486, funding_indicative=0.000012, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=5481762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T09:00:02+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.000005, depth_time=2026-11-07T09:00:34+00:00, book20_bid_proxy_usdt=50854, book20_ask_proxy_usdt=37541, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=85152095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.003955, depth_time=2026-11-07T09:00:27+00:00, book20_bid_proxy_usdt=2162448, book20_ask_proxy_usdt=2366589, funding_indicative=0.000000, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=11945060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=1.191000, depth_time=2026-11-07T09:00:09+00:00, book20_bid_proxy_usdt=1956806, book20_ask_proxy_usdt=1574582, funding_indicative=-0.000016, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.10%, turnover=9399793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T09:00:02+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.136000, depth_time=2026-11-07T09:00:07+00:00, book20_bid_proxy_usdt=140466, book20_ask_proxy_usdt=103952, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-32.68%, turnover=30986267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T09:00:03+00:00, last15m_closed_end=2026-11-07T09:00+00:00, prior8high=0.342400, depth_time=2026-11-07T09:00:22+00:00, book20_bid_proxy_usdt=3443567, book20_ask_proxy_usdt=3410305, funding_indicative=-0.000048, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=27577102. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
