# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T09:15:44Z**
- feed_generated_utc: 2026-11-07T09:15:46+00:00
- source_sha256: `0165ca76a9d36d1501f93804ea37c5099aae054fe5e3a8336a56bc7cb153d632`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T09:15+00:00, close=76159.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T09:00+00:00, close=76158.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.125100|-34.15|-52.89|-34.58|31123070|8.00|
|ANTHROPIC_USDT|1347.090000|-5.87|-19.64|-6.30|7983527|2.67|
|TRUMPOFFICIAL_USDT|1.183000|-4.75|-24.74|-5.18|9424749|8.45|
|OP_USDT|0.103090|-3.94|-4.73|-4.37|5587226|0.97|
|DOT_USDT|0.904700|-3.45|-6.65|-3.88|6410258|1.10|
|PUMPFUN_USDT|0.003928|-2.89|-4.35|-3.32|12017047|2.55|
|PEPE_USDT|0.000005|-2.62|-2.23|-3.05|85465025|0.20|
|ENA_USDT|0.163190|-2.57|-14.05|-3.00|27639470|0.61|
|BEAT_USDT|0.106540|-2.52|1.32|-2.95|7803524|3.75|
|ADA_USDT|0.183800|-2.28|-4.56|-2.71|26953728|5.44|
|ONDO_USDT|0.368500|-2.12|-7.73|-2.55|9882079|2.71|
|WLD_USDT|0.338500|-1.82|-17.81|-2.25|27782055|2.96|
|FARTCOIN_USDT|0.117930|-1.74|-1.97|-2.17|9442622|0.85|
|ARB_USDT|0.165510|-1.61|2.09|-2.04|22562451|0.60|
|DOGE_USDT|0.072080|-1.38|-4.93|-1.81|75555821|1.39|
|AVAX_USDT|8.309000|-1.17|-0.46|-1.60|11970182|1.20|
|XLM_USDT|0.153630|-0.92|-10.80|-1.35|22278462|1.95|
|NEAR_USDT|3.732000|-0.69|-13.65|-1.12|34526628|2.68|
|SOL_USDT|90.180000|-0.57|-4.88|-1.00|449821753|1.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.183800|0.184100|0.183800|1.24|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1347.090000|1343.740000|1347.150000|0.71|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165510|0.165540|0.165510|0.22|N|Y/N|N/N|Y|N|
|BEAT_USDT|0.106540|0.105600|0.106520|3.47|N|Y/Y|N/N|Y|N|
|DOGE_USDT|0.072080|0.071890|0.072080|0.48|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.904700|0.906500|0.904700|1.13|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163190|0.163580|0.163190|6.47|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.117930|0.117760|0.117930|1.92|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.368500|0.368600|0.368500|1.05|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.103090|0.103260|0.103100|6.92|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|0.74|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003928|0.003905|0.003928|2.03|N|N/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.183000|1.180000|1.183000|1.35|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.125100|0.121500|0.125100|1.43|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.338500|0.338400|0.338500|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.185200, depth_time=2026-11-07T09:15:30+00:00, book20_bid_proxy_usdt=10233208, book20_ask_proxy_usdt=8640326, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=26953728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=1361.580000, depth_time=2026-11-07T09:15:06+00:00, book20_bid_proxy_usdt=20478, book20_ask_proxy_usdt=36509, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.87%, turnover=7983527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.167180, depth_time=2026-11-07T09:15:38+00:00, book20_bid_proxy_usdt=1069682, book20_ask_proxy_usdt=45804, funding_indicative=-0.000034, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=22562451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.107900, depth_time=2026-11-07T09:15:27+00:00, book20_bid_proxy_usdt=11278, book20_ask_proxy_usdt=3961, funding_indicative=0.000128, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=7803524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.072140, depth_time=2026-11-07T09:15:43+00:00, book20_bid_proxy_usdt=5452062, book20_ask_proxy_usdt=5258303, funding_indicative=0.000036, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=75555821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.911600, depth_time=2026-11-07T09:15:17+00:00, book20_bid_proxy_usdt=589713, book20_ask_proxy_usdt=592745, funding_indicative=0.000040, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=6410258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.165160, depth_time=2026-11-07T09:15:25+00:00, book20_bid_proxy_usdt=302282, book20_ask_proxy_usdt=223450, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=27639470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.118640, depth_time=2026-11-07T09:15:38+00:00, book20_bid_proxy_usdt=58933, book20_ask_proxy_usdt=47427, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=9442622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.371200, depth_time=2026-11-07T09:15:33+00:00, book20_bid_proxy_usdt=2459886, book20_ask_proxy_usdt=2527977, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=9882079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.104590, depth_time=2026-11-07T09:15:12+00:00, book20_bid_proxy_usdt=124019, book20_ask_proxy_usdt=142569, funding_indicative=0.000023, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=5587226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.000005, depth_time=2026-11-07T09:15:23+00:00, book20_bid_proxy_usdt=44317, book20_ask_proxy_usdt=40964, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=85465025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.003955, depth_time=2026-11-07T09:15:20+00:00, book20_bid_proxy_usdt=2672210, book20_ask_proxy_usdt=2129107, funding_indicative=0.000008, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=12017047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=1.191000, depth_time=2026-11-07T09:15:12+00:00, book20_bid_proxy_usdt=1974721, book20_ask_proxy_usdt=1951706, funding_indicative=-0.000030, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.75%, turnover=9424749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.136000, depth_time=2026-11-07T09:15:07+00:00, book20_bid_proxy_usdt=127103, book20_ask_proxy_usdt=67917, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-34.15%, turnover=31123070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T09:14:59+00:00, last15m_closed_end=2026-11-07T09:15+00:00, prior8high=0.342400, depth_time=2026-11-07T09:15:34+00:00, book20_bid_proxy_usdt=3209274, book20_ask_proxy_usdt=3043079, funding_indicative=-0.000036, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=27782055. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
