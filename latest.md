# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T05:15:35Z**
- feed_generated_utc: 2026-10-18T05:15:37+00:00
- source_sha256: `de3d720ba8eb7c5848250a7738a008cd7ee54820c0ab91cb7790be49fbb3df5c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T05:15+00:00, close=81791.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T05:00+00:00, close=81766.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063270|-4.35|-32.28|-4.93|13998273|1.58|
|TIA_USDT|0.630900|-4.11|22.98|-4.69|64625991|1.58|
|EIGEN_USDT|0.247100|-3.58|4.88|-4.16|9022479|4.05|
|FILECOIN_USDT|1.052900|-3.17|-6.64|-3.75|19812035|0.95|
|QNT_USDT|194.870000|-2.76|-20.50|-3.34|70602516|1.54|
|PUMPFUN_USDT|0.004306|-2.40|-24.78|-2.98|23099186|2.32|
|OP_USDT|0.126890|-1.63|-8.41|-2.21|9414808|0.79|
|DOT_USDT|1.101300|-1.44|-12.37|-2.02|16704113|0.91|
|ZRO_USDT|1.859500|-1.36|-7.97|-1.94|7198337|1.61|
|WLD_USDT|0.489700|-1.19|-12.39|-1.77|61238847|2.04|
|APT_USDT|0.788200|-1.16|-4.66|-1.74|10090182|1.27|
|ARB_USDT|0.182240|-0.91|-2.37|-1.49|31001862|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.788200|0.788500|0.788200|4.96|Y|Y/Y|Y/Y|N|Y|
|ARB_USDT|0.182240|0.181890|0.182240|0.33|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.101300|1.100800|1.101300|2.86|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.247100|0.247800|0.247100|4.22|Y|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.052900|1.053400|1.052900|0.66|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.126890|0.127140|0.126890|3.20|Y|Y/Y|Y/Y|N|Y|
|PUMPFUN_USDT|0.004306|0.004305|0.004306|1.49|N|Y/Y|Y/Y|N|N|
|QNT_USDT|194.870000|193.320000|194.870000|1.09|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063270|0.062790|0.063270|0.54|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.630900|0.626300|0.630900|0.82|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.489700|0.489900|0.489700|1.25|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.859500|1.860800|1.859500|0.61|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.800600, depth_time=2026-10-18T05:15:31+00:00, book20_bid_proxy_usdt=99785, book20_ask_proxy_usdt=168075, funding_indicative=-0.000102, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=10090182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.185600, depth_time=2026-10-18T05:15:34+00:00, book20_bid_proxy_usdt=111520, book20_ask_proxy_usdt=94594, funding_indicative=-0.000025, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=31001862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=1.120700, depth_time=2026-10-18T05:15:23+00:00, book20_bid_proxy_usdt=328416, book20_ask_proxy_usdt=328105, funding_indicative=-0.000034, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=16704113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.253900, depth_time=2026-10-18T05:15:13+00:00, book20_bid_proxy_usdt=508135, book20_ask_proxy_usdt=296840, funding_indicative=-0.000020, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=9022479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=1.074100, depth_time=2026-10-18T05:15:13+00:00, book20_bid_proxy_usdt=516399, book20_ask_proxy_usdt=834695, funding_indicative=-0.000114, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=19812035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.129950, depth_time=2026-10-18T05:15:22+00:00, book20_bid_proxy_usdt=29485, book20_ask_proxy_usdt=64802, funding_indicative=-0.000184, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=9414808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.004401, depth_time=2026-10-18T05:15:20+00:00, book20_bid_proxy_usdt=1512699, book20_ask_proxy_usdt=1533909, funding_indicative=0.000018, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=23099186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=197.180000, depth_time=2026-10-18T05:15:17+00:00, book20_bid_proxy_usdt=98066, book20_ask_proxy_usdt=65429, funding_indicative=-0.000108, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=70602516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.064400, depth_time=2026-10-18T05:15:07+00:00, book20_bid_proxy_usdt=560128, book20_ask_proxy_usdt=351205, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=13998273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.638400, depth_time=2026-10-18T05:15:09+00:00, book20_bid_proxy_usdt=182117, book20_ask_proxy_usdt=296228, funding_indicative=-0.000002, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.11%, turnover=64625991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=0.498500, depth_time=2026-10-18T05:15:26+00:00, book20_bid_proxy_usdt=1728583, book20_ask_proxy_usdt=2147583, funding_indicative=-0.000157, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=61238847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T05:14:59+00:00, last15m_closed_end=2026-10-18T05:15+00:00, prior8high=1.918400, depth_time=2026-10-18T05:15:26+00:00, book20_bid_proxy_usdt=68605, book20_ask_proxy_usdt=53598, funding_indicative=0.000016, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=7198337. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
