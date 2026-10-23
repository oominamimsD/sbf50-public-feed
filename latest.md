# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T08:15:28Z**
- feed_generated_utc: 2026-10-23T08:15:29+00:00
- source_sha256: `2347887eb878f482d704ee7662e0cbb7a9ede03318acdae0cf9521e15f01e6cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T08:15+00:00, close=81736.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004245|-7.87|113.85|-7.97|8050284|9.43|
|LIT_USDT|3.416400|-5.47|10.51|-5.57|9608446|0.29|
|STRK_USDT|0.052990|-2.52|-45.00|-2.62|10649208|1.89|
|SILVER_USDT|53.990000|-2.29|-5.51|-2.39|341511785|1.85|
|TIA_USDT|0.555700|-2.23|-7.76|-2.33|24519362|3.60|
|PUMPFUN_USDT|0.004613|-1.41|1.92|-1.51|37347196|2.17|
|QNT_USDT|188.180000|-1.32|-9.48|-1.42|47876387|0.53|
|XAUT_USDT|4016.310000|-0.93|-3.10|-1.03|266904914|0.07|
|XAU_USDT|4022.340000|-0.92|-3.21|-1.02|641166490|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004245|0.004176|0.004245|0.52|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.416400|3.409100|3.416400|1.78|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004613|0.004580|0.004613|1.17|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.180000|187.530000|188.180000|0.93|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.990000|53.900000|53.990000|2.83|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052990|0.052400|0.052990|3.16|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.555700|0.553400|0.555700|0.27|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4016.310000|4014.410000|4016.420000|0.66|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4022.340000|4020.010000|4022.340000|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=0.004316, depth_time=2026-10-23T08:15:06+00:00, book20_bid_proxy_usdt=54969, book20_ask_proxy_usdt=44732, funding_indicative=0.000085, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.87%, turnover=8050284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=3.450000, depth_time=2026-10-23T08:15:08+00:00, book20_bid_proxy_usdt=24130, book20_ask_proxy_usdt=27055, funding_indicative=0.000000, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.47%, turnover=9608446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=0.004684, depth_time=2026-10-23T08:15:19+00:00, book20_bid_proxy_usdt=1986704, book20_ask_proxy_usdt=2249436, funding_indicative=0.000012, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=37347196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=190.170000, depth_time=2026-10-23T08:15:22+00:00, book20_bid_proxy_usdt=57418, book20_ask_proxy_usdt=145633, funding_indicative=-0.000143, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=47876387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=54.490000, depth_time=2026-10-23T08:15:14+00:00, book20_bid_proxy_usdt=28733704, book20_ask_proxy_usdt=31412142, funding_indicative=0.000167, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=341511785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=0.053510, depth_time=2026-10-23T08:15:12+00:00, book20_bid_proxy_usdt=522942, book20_ask_proxy_usdt=560323, funding_indicative=-0.000033, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=10649208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=0.562000, depth_time=2026-10-23T08:15:17+00:00, book20_bid_proxy_usdt=377936, book20_ask_proxy_usdt=371674, funding_indicative=-0.000015, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=24519362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=4026.740000, depth_time=2026-10-23T08:15:23+00:00, book20_bid_proxy_usdt=207394, book20_ask_proxy_usdt=124179, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=266904914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T08:14:59+00:00, last15m_closed_end=2026-10-23T08:15+00:00, prior8high=4031.160000, depth_time=2026-10-23T08:15:27+00:00, book20_bid_proxy_usdt=904059, book20_ask_proxy_usdt=2192765, funding_indicative=0.000111, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=641166490. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
