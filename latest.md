# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T12:15:39Z**
- feed_generated_utc: 2026-11-03T12:15:41+00:00
- source_sha256: `9c67c4e29bd6317da7e13046f6f158f309d52ddd2cececdcd6624c22f1d2b344`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T12:15+00:00, close=77160.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004466|-18.82|-85.49|-18.40|12065766|2.24|
|BTW_USDT|0.941500|-14.15|-21.25|-13.73|10007087|1.06|
|XPL_USDT|0.064360|-7.50|-13.36|-7.08|11611272|1.55|
|SILVER_USDT|49.080000|-3.87|-9.49|-3.45|423363587|2.04|
|NEAR_USDT|3.861000|-3.71|-15.56|-3.29|77982915|2.59|
|TIA_USDT|0.442400|-3.17|-17.41|-2.75|12930558|4.52|
|TRUMPOFFICIAL_USDT|1.586000|-3.05|-6.09|-2.63|9210825|6.31|
|DASH_USDT|45.960000|-2.62|-11.98|-2.20|9329665|2.18|
|XLM_USDT|0.163330|-2.54|-3.69|-2.12|34434710|0.61|
|ENA_USDT|0.171160|-2.21|-18.63|-1.79|73113862|0.58|
|FARTCOIN_USDT|0.116920|-1.96|-8.89|-1.54|9543284|0.85|
|APT_USDT|0.616800|-1.64|-12.13|-1.22|5189535|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004466|0.004436|0.004466|1.08|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.616800|0.611300|0.616800|0.97|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.941500|0.870600|0.941500|0.85|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.960000|45.630000|45.960000|3.20|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171160|0.169020|0.171080|1.04|N|N/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116920|0.115950|0.116910|0.53|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.861000|3.824000|3.863000|1.05|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.080000|48.980000|49.090000|0.72|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.442400|0.437200|0.442300|1.52|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.586000|1.584000|1.586000|0.71|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163330|0.161580|0.163330|1.27|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064360|0.063400|0.064360|1.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.004632, depth_time=2026-11-03T12:15:07+00:00, book20_bid_proxy_usdt=40579, book20_ask_proxy_usdt=100718, funding_indicative=-0.001998, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.82%, turnover=12065766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.620100, depth_time=2026-11-03T12:15:39+00:00, book20_bid_proxy_usdt=172564, book20_ask_proxy_usdt=152708, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=5189535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.973900, depth_time=2026-11-03T12:15:10+00:00, book20_bid_proxy_usdt=16356, book20_ask_proxy_usdt=17146, funding_indicative=-0.000225, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.15%, turnover=10007087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=45.990000, depth_time=2026-11-03T12:15:27+00:00, book20_bid_proxy_usdt=594027, book20_ask_proxy_usdt=592144, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=9329665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.173110, depth_time=2026-11-03T12:15:33+00:00, book20_bid_proxy_usdt=156746, book20_ask_proxy_usdt=161682, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=73113862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.117450, depth_time=2026-11-03T12:15:36+00:00, book20_bid_proxy_usdt=72864, book20_ask_proxy_usdt=67647, funding_indicative=0.000080, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=9543284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=3.888000, depth_time=2026-11-03T12:15:18+00:00, book20_bid_proxy_usdt=4629141, book20_ask_proxy_usdt=2608679, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=77982915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=49.240000, depth_time=2026-11-03T12:15:15+00:00, book20_bid_proxy_usdt=40030095, book20_ask_proxy_usdt=52039739, funding_indicative=0.000086, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.87%, turnover=423363587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.444300, depth_time=2026-11-03T12:15:21+00:00, book20_bid_proxy_usdt=308640, book20_ask_proxy_usdt=322597, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=12930558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=1.602000, depth_time=2026-11-03T12:15:24+00:00, book20_bid_proxy_usdt=2013512, book20_ask_proxy_usdt=1771156, funding_indicative=0.000017, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=9210825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.163180, depth_time=2026-11-03T12:15:29+00:00, book20_bid_proxy_usdt=107704, book20_ask_proxy_usdt=176658, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=34434710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T12:15:02+00:00, last15m_closed_end=2026-11-03T12:15+00:00, prior8high=0.065520, depth_time=2026-11-03T12:15:08+00:00, book20_bid_proxy_usdt=332062, book20_ask_proxy_usdt=381698, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.50%, turnover=11611272. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
