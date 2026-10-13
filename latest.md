# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T06:15:37Z**
- feed_generated_utc: 2026-10-13T06:15:40+00:00
- source_sha256: `90539879c9ea1730303afa3e745e294737b632c17982c7d2329327fc2452a5d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T06:15+00:00, close=83589.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T06:00+00:00, close=83646.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.231200|-20.13|8.54|-21.22|9285747|4.32|
|W_USDT|0.019320|-19.70|36.60|-20.79|34279778|8.30|
|RSR_USDT|0.002108|-10.29|23.92|-11.38|17610585|9.50|
|ZRO_USDT|2.099500|-7.14|2.63|-8.23|29456082|1.43|
|LIT_USDT|3.452400|-4.76|-9.19|-5.85|10597531|0.29|
|STRK_USDT|0.086380|-4.73|65.76|-5.82|63857016|1.16|
|ICP_USDT|3.161000|-4.06|-8.79|-5.15|17029252|3.16|
|PUMPFUN_USDT|0.005100|-3.93|-19.49|-5.02|31356073|1.96|
|RLC_USDT|0.952800|-3.62|73.86|-4.71|6864362|3.15|
|HBAR_USDT|0.087710|-3.08|-12.89|-4.17|22109252|1.14|
|USELESS_USDT|0.177070|-2.49|-21.90|-3.58|6666317|0.56|
|PONS_USDT|0.289800|-1.66|-24.43|-2.75|6278533|3.45|
|MAGIC_USDT|0.122000|0.03|96.80|-1.06|10304198|2.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.231200|0.227700|0.231200|0.31|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.087710|0.087260|0.087690|0.77|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.161000|3.151000|3.161000|1.87|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.452400|3.427200|3.452400|0.86|N|Y/Y|Y/Y|N|N|
|MAGIC_USDT|0.122000|0.121350|0.121870|0.41|N|Y/N|N/N|N|N|
|PONS_USDT|0.289800|0.281600|0.289800|1.14|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005100|0.005031|0.005100|3.89|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.952800|0.939400|0.952800|0.28|N|Y/Y|Y/Y|N|N|
|RSR_USDT|0.002108|0.002015|0.002106|0.47|N|Y/Y|N/N|N|N|
|STRK_USDT|0.086380|0.082590|0.086340|1.11|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.177070|0.175310|0.177070|0.96|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019320|0.018943|0.019320|0.85|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.099500|2.098900|2.099500|1.43|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.251000, depth_time=2026-10-13T06:15:07+00:00, book20_bid_proxy_usdt=65084, book20_ask_proxy_usdt=60517, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.13%, turnover=9285747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.088580, depth_time=2026-10-13T06:15:28+00:00, book20_bid_proxy_usdt=509106, book20_ask_proxy_usdt=699951, funding_indicative=-0.000001, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=22109252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=3.205000, depth_time=2026-10-13T06:15:20+00:00, book20_bid_proxy_usdt=962938, book20_ask_proxy_usdt=824503, funding_indicative=-0.000040, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=17029252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T06:15:03+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=3.476600, depth_time=2026-10-13T06:15:17+00:00, book20_bid_proxy_usdt=34860, book20_ask_proxy_usdt=22406, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.76%, turnover=10597531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.127660, depth_time=2026-10-13T06:15:36+00:00, book20_bid_proxy_usdt=175915, book20_ask_proxy_usdt=175783, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.03%, turnover=10304198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.291600, depth_time=2026-10-13T06:15:33+00:00, book20_bid_proxy_usdt=214167, book20_ask_proxy_usdt=224068, funding_indicative=0.000089, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=6278533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.005113, depth_time=2026-10-13T06:15:23+00:00, book20_bid_proxy_usdt=1545522, book20_ask_proxy_usdt=1530381, funding_indicative=0.000027, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=31356073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.964300, depth_time=2026-10-13T06:15:25+00:00, book20_bid_proxy_usdt=60478, book20_ask_proxy_usdt=61693, funding_indicative=-0.000581, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=6864362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RSR_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.002194, depth_time=2026-10-13T06:15:11+00:00, book20_bid_proxy_usdt=146735, book20_ask_proxy_usdt=219330, funding_indicative=-0.008784, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.29%, turnover=17610585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.089670, depth_time=2026-10-13T06:15:19+00:00, book20_bid_proxy_usdt=134145, book20_ask_proxy_usdt=168917, funding_indicative=0.000031, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=63857016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.179140, depth_time=2026-10-13T06:15:29+00:00, book20_bid_proxy_usdt=15217, book20_ask_proxy_usdt=27374, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=6666317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=0.019641, depth_time=2026-10-13T06:15:09+00:00, book20_bid_proxy_usdt=22997, book20_ask_proxy_usdt=21437, funding_indicative=-0.000479, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.70%, turnover=34279778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T06:15:02+00:00, last15m_closed_end=2026-10-13T06:15+00:00, prior8high=2.149200, depth_time=2026-10-13T06:15:14+00:00, book20_bid_proxy_usdt=56705, book20_ask_proxy_usdt=41187, funding_indicative=0.000044, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.14%, turnover=29456082. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
