# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T08:00:41Z**
- feed_generated_utc: 2026-11-07T08:00:43+00:00
- source_sha256: `20e1e1f3776f1aa0051e0d436099d910e9d5c10616f5ccb56deac6ac5929d163`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124600|-34.42|-53.08|-34.72|32179033|8.02|
|CYBER_USDT|0.324100|-8.44|18.63|-8.74|5317335|3.09|
|ANTHROPIC_USDT|1351.730000|-5.55|-19.36|-5.85|7571099|1.85|
|TRUMPOFFICIAL_USDT|1.184000|-4.66|-24.68|-4.96|9993089|8.44|
|BEAT_USDT|0.106110|-2.91|0.91|-3.21|8486040|0.94|
|DOT_USDT|0.910300|-2.85|-6.07|-3.15|6850440|1.10|
|OP_USDT|0.104260|-2.85|-3.65|-3.15|5668031|0.96|
|PEPE_USDT|0.000005|-2.79|-2.40|-3.09|90180984|0.20|
|PUMPFUN_USDT|0.003933|-2.76|-4.23|-3.06|12317761|2.54|
|ENA_USDT|0.164270|-1.93|-13.48|-2.23|28804255|0.61|
|ONDO_USDT|0.370400|-1.62|-7.26|-1.92|10718476|2.70|
|FARTCOIN_USDT|0.118170|-1.54|-1.77|-1.84|10473828|1.69|
|WLD_USDT|0.340500|-1.24|-17.33|-1.54|29079098|2.94|
|ARB_USDT|0.166130|-1.24|2.47|-1.54|22971520|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1351.730000|1342.600000|1351.730000|0.63|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166130|0.165260|0.166130|2.73|N|N/N|N/N|Y|N|
|BEAT_USDT|0.106110|0.105300|0.106110|2.16|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.324100|0.318700|0.324000|0.53|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.910300|0.905400|0.910300|2.06|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.164270|0.163460|0.164290|0.91|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118170|0.117990|0.118170|1.77|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.370400|0.368900|0.370400|0.37|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.104260|0.104210|0.104260|0.49|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.56|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003933|0.003893|0.003933|1.37|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.184000|1.179000|1.184000|0.63|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.124600|0.119000|0.124600|1.14|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.340500|0.338600|0.340500|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=1371.530000, depth_time=2026-11-07T08:00:12+00:00, book20_bid_proxy_usdt=18568, book20_ask_proxy_usdt=20524, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=7571099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.167280, depth_time=2026-11-07T08:00:40+00:00, book20_bid_proxy_usdt=109192, book20_ask_proxy_usdt=97650, funding_indicative=-0.000015, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=22971520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.107900, depth_time=2026-11-07T08:00:16+00:00, book20_bid_proxy_usdt=10365, book20_ask_proxy_usdt=16486, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=8486040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.330600, depth_time=2026-11-07T08:00:09+00:00, book20_bid_proxy_usdt=713356, book20_ask_proxy_usdt=78715, funding_indicative=-0.001239, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.44%, turnover=5317335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.911500, depth_time=2026-11-07T08:00:19+00:00, book20_bid_proxy_usdt=617415, book20_ask_proxy_usdt=366437, funding_indicative=0.000098, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=6850440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.165160, depth_time=2026-11-07T08:00:29+00:00, book20_bid_proxy_usdt=171607, book20_ask_proxy_usdt=217175, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=28804255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.118640, depth_time=2026-11-07T08:00:35+00:00, book20_bid_proxy_usdt=79305, book20_ask_proxy_usdt=76805, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=10473828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.371200, depth_time=2026-11-07T08:00:32+00:00, book20_bid_proxy_usdt=1790663, book20_ask_proxy_usdt=1941511, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=10718476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.104950, depth_time=2026-11-07T08:00:22+00:00, book20_bid_proxy_usdt=117796, book20_ask_proxy_usdt=68110, funding_indicative=0.000032, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=5668031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.000005, depth_time=2026-11-07T08:00:25+00:00, book20_bid_proxy_usdt=66189, book20_ask_proxy_usdt=23210, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=90180984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.003942, depth_time=2026-11-07T08:00:26+00:00, book20_bid_proxy_usdt=1985341, book20_ask_proxy_usdt=1977258, funding_indicative=-0.000013, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=12317761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=1.188000, depth_time=2026-11-07T08:00:14+00:00, book20_bid_proxy_usdt=1533764, book20_ask_proxy_usdt=1722844, funding_indicative=0.000037, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=9993089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.127300, depth_time=2026-11-07T08:00:07+00:00, book20_bid_proxy_usdt=103181, book20_ask_proxy_usdt=89260, funding_indicative=0.000014, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-34.42%, turnover=32179033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T07:59:59+00:00, last15m_closed_end=2026-11-07T08:00+00:00, prior8high=0.342400, depth_time=2026-11-07T08:00:35+00:00, book20_bid_proxy_usdt=3031552, book20_ask_proxy_usdt=3043182, funding_indicative=-0.000021, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=29079098. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
