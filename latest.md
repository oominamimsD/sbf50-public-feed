# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T08:30:43Z**
- feed_generated_utc: 2026-11-07T08:30:45+00:00
- source_sha256: `26841f7f27720036a85fdef2d6e34b60b58b924f424f4c6e8c9a585f08dadd60`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T08:30+00:00, close=76079, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-07T08:00+00:00, close=76053.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124500|-34.47|-53.12|-34.79|31399419|8.04|
|ANTHROPIC_USDT|1358.860000|-5.05|-18.94|-5.37|7565397|2.94|
|TRUMPOFFICIAL_USDT|1.188000|-4.34|-24.42|-4.66|9621183|8.41|
|OP_USDT|0.103660|-3.41|-4.20|-3.73|5589484|0.96|
|BEAT_USDT|0.106040|-2.98|0.84|-3.30|8276321|3.77|
|DOT_USDT|0.909200|-2.97|-6.19|-3.29|6449570|1.10|
|PUMPFUN_USDT|0.003933|-2.76|-4.23|-3.08|12179697|2.54|
|PEPE_USDT|0.000005|-2.51|-2.12|-2.83|88691044|0.20|
|ONDO_USDT|0.369100|-1.96|-7.58|-2.28|10516860|2.71|
|ENA_USDT|0.164250|-1.94|-13.49|-2.26|28040252|0.61|
|ADA_USDT|0.184700|-1.80|-4.10|-2.12|27241362|5.42|
|FARTCOIN_USDT|0.117940|-1.74|-1.96|-2.06|9796374|0.85|
|WLD_USDT|0.339400|-1.56|-17.60|-1.88|27944738|2.95|
|DOGE_USDT|0.072060|-1.40|-4.95|-1.72|76644635|1.39|
|ARB_USDT|0.165990|-1.32|2.38|-1.64|22164245|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184700|0.184300|0.184700|1.38|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1358.860000|1342.910000|1358.860000|0.86|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165990|0.165260|0.165990|2.53|N|N/N|N/N|Y|N|
|BEAT_USDT|0.106040|0.105300|0.106000|0.69|N|Y/Y|N/N|Y|N|
|DOGE_USDT|0.072060|0.071870|0.072060|0.19|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.909200|0.905400|0.909200|1.17|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.164250|0.163460|0.164250|2.05|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117940|0.117990|0.117940|1.00|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.369100|0.368900|0.369100|2.01|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.103660|0.103970|0.103660|2.91|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|0.83|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003933|0.003893|0.003933|1.13|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.188000|1.179000|1.188000|0.29|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.124500|0.121500|0.124500|0.76|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.339400|0.339100|0.339400|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.185200, depth_time=2026-11-07T08:30:33+00:00, book20_bid_proxy_usdt=8823348, book20_ask_proxy_usdt=9305906, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=27241362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=1358.000000, depth_time=2026-11-07T08:30:08+00:00, book20_bid_proxy_usdt=20213, book20_ask_proxy_usdt=14925, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.05%, turnover=7565397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.167180, depth_time=2026-11-07T08:30:42+00:00, book20_bid_proxy_usdt=60977, book20_ask_proxy_usdt=70586, funding_indicative=-0.000020, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=22164245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.107900, depth_time=2026-11-07T08:30:14+00:00, book20_bid_proxy_usdt=6585, book20_ask_proxy_usdt=3521, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=8276321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.072140, depth_time=2026-11-07T08:30:38+00:00, book20_bid_proxy_usdt=4775178, book20_ask_proxy_usdt=5542318, funding_indicative=0.000047, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=76644635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.911600, depth_time=2026-11-07T08:30:19+00:00, book20_bid_proxy_usdt=563762, book20_ask_proxy_usdt=499795, funding_indicative=0.000072, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=6449570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.165160, depth_time=2026-11-07T08:30:29+00:00, book20_bid_proxy_usdt=167904, book20_ask_proxy_usdt=241044, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=28040252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.118640, depth_time=2026-11-07T08:30:35+00:00, book20_bid_proxy_usdt=59907, book20_ask_proxy_usdt=63625, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=9796374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.371200, depth_time=2026-11-07T08:30:27+00:00, book20_bid_proxy_usdt=1805565, book20_ask_proxy_usdt=1197486, funding_indicative=0.000050, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=10516860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.104620, depth_time=2026-11-07T08:30:10+00:00, book20_bid_proxy_usdt=103496, book20_ask_proxy_usdt=93412, funding_indicative=0.000005, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=5589484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.000005, depth_time=2026-11-07T08:30:24+00:00, book20_bid_proxy_usdt=39936, book20_ask_proxy_usdt=30774, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=88691044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.003955, depth_time=2026-11-07T08:30:18+00:00, book20_bid_proxy_usdt=2452211, book20_ask_proxy_usdt=2232998, funding_indicative=-0.000016, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=12179697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=1.190000, depth_time=2026-11-07T08:30:07+00:00, book20_bid_proxy_usdt=1451548, book20_ask_proxy_usdt=1462374, funding_indicative=0.000010, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=9621183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.127400, depth_time=2026-11-07T08:30:07+00:00, book20_bid_proxy_usdt=155150, book20_ask_proxy_usdt=83696, funding_indicative=0.000026, next_funding_utc=2026-11-07T12:00:00+00:00, funding_cycle_h=4, 24h_change=-34.47%, turnover=31399419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T08:29:59+00:00, last15m_closed_end=2026-11-07T08:30+00:00, prior8high=0.342400, depth_time=2026-11-07T08:30:37+00:00, book20_bid_proxy_usdt=2822204, book20_ask_proxy_usdt=2803481, funding_indicative=-0.000056, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=27944738. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
