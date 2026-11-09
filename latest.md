# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T05:30:31Z**
- feed_generated_utc: 2026-11-09T05:30:33+00:00
- source_sha256: `32cf07eecc5be8934048828ce23c875962ec8091d38f3c6da835d5d47e332aa7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T05:30+00:00, close=74528.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T05:00+00:00, close=74800, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001640|-16.24|40.83|-14.27|10095802|0.61|
|AKE_USDT|0.004588|-14.35|-49.91|-12.38|11375950|2.18|
|ASTER_USDT|0.639600|-5.91|-8.55|-3.94|5156577|1.56|
|PUMPFUN_USDT|0.003549|-5.03|-15.86|-3.06|9332289|2.81|
|ETH_USDT|2133.180000|-4.81|-5.85|-2.84|1232753682|0.05|
|XRP_USDT|1.102000|-4.65|-11.83|-2.68|233048969|0.91|
|TAO_USDT|216.120000|-4.38|-7.97|-2.41|32555659|1.39|
|HYPE_USDT|74.194000|-4.18|-15.38|-2.21|40086260|0.14|
|LIT_USDT|3.091900|-3.17|-4.27|-1.20|13601253|0.32|
|XLM_USDT|0.146420|-3.16|-13.03|-1.19|24703907|0.68|
|DOT_USDT|0.864300|-2.98|-8.73|-1.01|7665907|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004588|0.004620|0.004588|1.03|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.639600|0.637000|0.639600|0.16|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.864300|0.862200|0.864200|3.91|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2133.180000|2131.600000|2132.480000|1.09|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.194000|74.245000|74.194000|1.05|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.091900|3.086100|3.091900|0.30|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001640|0.001627|0.001640|1.61|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003549|0.003539|0.003549|0.17|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|216.120000|215.940000|216.120000|0.86|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.146420|0.146480|0.146400|0.94|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.102000|1.102100|1.101700|1.64|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=0.005027, depth_time=2026-11-09T05:30:06+00:00, book20_bid_proxy_usdt=50806, book20_ask_proxy_usdt=54718, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.35%, turnover=11375950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=0.645100, depth_time=2026-11-09T05:30:10+00:00, book20_bid_proxy_usdt=543757, book20_ask_proxy_usdt=694834, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.91%, turnover=5156577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=0.880100, depth_time=2026-11-09T05:30:28+00:00, book20_bid_proxy_usdt=489502, book20_ask_proxy_usdt=496231, funding_indicative=-0.000097, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=7665907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=2146.900000, depth_time=2026-11-09T05:30:16+00:00, book20_bid_proxy_usdt=3409272, book20_ask_proxy_usdt=5140288, funding_indicative=-0.000046, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.81%, turnover=1232753682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=75.000000, depth_time=2026-11-09T05:30:23+00:00, book20_bid_proxy_usdt=102367, book20_ask_proxy_usdt=65706, funding_indicative=0.000036, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.18%, turnover=40086260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T05:30:02+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=3.158400, depth_time=2026-11-09T05:30:26+00:00, book20_bid_proxy_usdt=24202, book20_ask_proxy_usdt=17729, funding_indicative=-0.000021, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=13601253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=0.001693, depth_time=2026-11-09T05:30:06+00:00, book20_bid_proxy_usdt=12774, book20_ask_proxy_usdt=8456, funding_indicative=-0.000189, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.24%, turnover=10095802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T05:30:02+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=0.003640, depth_time=2026-11-09T05:30:12+00:00, book20_bid_proxy_usdt=2850310, book20_ask_proxy_usdt=2286905, funding_indicative=0.000036, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=9332289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=218.700000, depth_time=2026-11-09T05:30:21+00:00, book20_bid_proxy_usdt=140357, book20_ask_proxy_usdt=84450, funding_indicative=0.000046, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=32555659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T05:30:02+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=0.147940, depth_time=2026-11-09T05:30:28+00:00, book20_bid_proxy_usdt=102838, book20_ask_proxy_usdt=209639, funding_indicative=0.000052, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=24703907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T05:30:01+00:00, last15m_closed_end=2026-11-09T05:30+00:00, prior8high=1.116100, depth_time=2026-11-09T05:30:19+00:00, book20_bid_proxy_usdt=4740614, book20_ask_proxy_usdt=3652786, funding_indicative=-0.000007, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.65%, turnover=233048969. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
