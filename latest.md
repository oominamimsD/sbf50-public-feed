# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T15:30:37Z**
- feed_generated_utc: 2026-10-23T15:30:39+00:00
- source_sha256: `b49fec4ac94d8f77d038533233608ac75b66a03e250db932f41491ac0489b407`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T15:30+00:00, close=81555.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T15:00+00:00, close=81750, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.337100|-7.66|7.94|-7.54|8923787|0.30|
|QNT_USDT|180.580000|-5.31|-13.14|-5.19|59818142|2.21|
|TIA_USDT|0.543800|-4.32|-9.74|-4.20|25387067|3.68|
|STRK_USDT|0.052070|-4.21|-45.96|-4.09|11615658|1.92|
|ARB_USDT|0.178650|-2.71|-5.94|-2.59|28135803|0.56|
|PUMPFUN_USDT|0.004568|-2.37|0.92|-2.25|35228046|2.19|
|APT_USDT|0.755800|-2.12|-8.57|-2.00|7886123|3.97|
|OP_USDT|0.117650|-1.83|-15.28|-1.71|6705661|1.70|
|NEAR_USDT|4.863000|-1.63|-5.00|-1.51|121079477|2.06|
|HBAR_USDT|0.078910|-1.49|-5.55|-1.37|19905797|3.80|
|XAU_USDT|4005.720000|-1.32|-3.61|-1.20|639408334|0.03|
|XAUT_USDT|4000.830000|-1.31|-3.47|-1.19|232487523|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.755800|0.740700|0.755800|0.74|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.178650|0.175900|0.178660|3.15|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.078910|0.078580|0.078900|2.73|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.337100|3.279300|3.337000|1.99|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.863000|4.788000|4.866000|0.85|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.117650|0.115530|0.117650|1.57|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004568|0.004485|0.004569|0.50|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|180.580000|177.480000|180.610000|0.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052070|0.051770|0.052070|0.92|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.543800|0.535200|0.544100|0.96|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4000.830000|3978.250000|4000.830000|1.18|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4005.720000|3985.020000|4005.720000|0.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.769200, depth_time=2026-10-23T15:30:23+00:00, book20_bid_proxy_usdt=113344, book20_ask_proxy_usdt=132305, funding_indicative=0.000018, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=7886123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.182320, depth_time=2026-10-23T15:30:18+00:00, book20_bid_proxy_usdt=76481, book20_ask_proxy_usdt=97806, funding_indicative=-0.000001, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=28135803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.080450, depth_time=2026-10-23T15:30:31+00:00, book20_bid_proxy_usdt=628209, book20_ask_proxy_usdt=1203996, funding_indicative=0.000038, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=19905797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=3.409500, depth_time=2026-10-23T15:30:08+00:00, book20_bid_proxy_usdt=23704, book20_ask_proxy_usdt=18642, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.66%, turnover=8923787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=4.980000, depth_time=2026-10-23T15:30:28+00:00, book20_bid_proxy_usdt=2347737, book20_ask_proxy_usdt=206648, funding_indicative=0.000022, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=121079477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.118860, depth_time=2026-10-23T15:30:26+00:00, book20_bid_proxy_usdt=93657, book20_ask_proxy_usdt=78256, funding_indicative=-0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=6705661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.004677, depth_time=2026-10-23T15:30:20+00:00, book20_bid_proxy_usdt=1355114, book20_ask_proxy_usdt=1236789, funding_indicative=0.000030, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=35228046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=183.630000, depth_time=2026-10-23T15:30:10+00:00, book20_bid_proxy_usdt=83819, book20_ask_proxy_usdt=66814, funding_indicative=-0.000166, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.31%, turnover=59818142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.053090, depth_time=2026-10-23T15:30:15+00:00, book20_bid_proxy_usdt=880163, book20_ask_proxy_usdt=591465, funding_indicative=0.000013, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=11615658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=0.550800, depth_time=2026-10-23T15:30:12+00:00, book20_bid_proxy_usdt=291458, book20_ask_proxy_usdt=420802, funding_indicative=-0.000003, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.32%, turnover=25387067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=4035.760000, depth_time=2026-10-23T15:30:36+00:00, book20_bid_proxy_usdt=129692, book20_ask_proxy_usdt=97671, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=232487523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T15:30:02+00:00, last15m_closed_end=2026-10-23T15:30+00:00, prior8high=4042.750000, depth_time=2026-10-23T15:30:33+00:00, book20_bid_proxy_usdt=2404721, book20_ask_proxy_usdt=1270144, funding_indicative=0.000176, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=639408334. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
