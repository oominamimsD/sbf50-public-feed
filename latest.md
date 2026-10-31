# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T13:30:33Z**
- feed_generated_utc: 2026-10-31T13:30:35+00:00
- source_sha256: `6b830f6c4ccda66e542dd34715c7b1ccd463d90d78b395264c9b2878f74fe9bc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T13:30+00:00, close=77438.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T13:00+00:00, close=77509.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011839|-37.42|-66.17|-37.24|11517944|5.07|
|Q_USDT|0.031960|-32.68|-72.99|-32.50|12191616|3.13|
|BTW_USDT|1.106100|-7.78|-35.02|-7.60|8472358|3.62|
|BEAT_USDT|0.099320|-5.54|36.82|-5.36|7321778|1.01|
|HYPE_USDT|87.432000|-5.31|11.51|-5.13|96077765|0.11|
|TRX_USDT|0.318700|-5.00|-3.23|-4.82|6682561|0.31|
|WLD_USDT|0.396700|-3.69|-25.48|-3.51|42816908|2.52|
|FET_USDT|0.160800|-3.48|-14.14|-3.30|6133438|6.22|
|DASH_USDT|48.010000|-2.10|-10.84|-1.92|9586927|2.08|
|PEPE_USDT|0.000005|-1.71|2.31|-1.53|109722053|0.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011839|0.011231|0.011860|0.63|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099320|0.098720|0.099320|0.89|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.106100|1.081300|1.106100|1.33|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.010000|47.750000|48.020000|0.77|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160800|0.160400|0.160800|1.61|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.432000|87.134000|87.453000|1.62|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.16|N|N/N|N/N|Y|N|
|Q_USDT|0.031960|0.031390|0.031960|0.89|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318700|0.317290|0.318700|0.27|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396700|0.394200|0.396700|0.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.012080, depth_time=2026-10-31T13:30:09+00:00, book20_bid_proxy_usdt=14246, book20_ask_proxy_usdt=12593, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.42%, turnover=11517944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.102150, depth_time=2026-10-31T13:30:17+00:00, book20_bid_proxy_usdt=14129, book20_ask_proxy_usdt=11041, funding_indicative=0.000179, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=7321778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=1.204600, depth_time=2026-10-31T13:30:12+00:00, book20_bid_proxy_usdt=13137, book20_ask_proxy_usdt=16700, funding_indicative=-0.000377, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.78%, turnover=8472358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=48.200000, depth_time=2026-10-31T13:30:28+00:00, book20_bid_proxy_usdt=609163, book20_ask_proxy_usdt=538931, funding_indicative=-0.000107, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=9586927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.161800, depth_time=2026-10-31T13:30:27+00:00, book20_bid_proxy_usdt=1224634, book20_ask_proxy_usdt=586727, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=6133438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=88.782000, depth_time=2026-10-31T13:30:19+00:00, book20_bid_proxy_usdt=174326, book20_ask_proxy_usdt=126800, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.31%, turnover=96077765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.000005, depth_time=2026-10-31T13:30:32+00:00, book20_bid_proxy_usdt=25495, book20_ask_proxy_usdt=35692, funding_indicative=-0.000740, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=109722053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.032210, depth_time=2026-10-31T13:30:11+00:00, book20_bid_proxy_usdt=54527, book20_ask_proxy_usdt=60470, funding_indicative=-0.000469, next_funding_utc=2026-10-31T14:00:00+00:00, funding_cycle_h=1, 24h_change=-32.68%, turnover=12191616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.322470, depth_time=2026-10-31T13:30:21+00:00, book20_bid_proxy_usdt=61972, book20_ask_proxy_usdt=36739, funding_indicative=-0.000886, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.00%, turnover=6682561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T13:30:03+00:00, last15m_closed_end=2026-10-31T13:30+00:00, prior8high=0.398800, depth_time=2026-10-31T13:30:24+00:00, book20_bid_proxy_usdt=2687430, book20_ask_proxy_usdt=3902881, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=42816908. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
