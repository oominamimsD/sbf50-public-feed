# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T22:00:29Z**
- feed_generated_utc: 2026-10-14T22:00:30+00:00
- source_sha256: `32f0c511d0f8d5728b1d4a0454231ca36f2144770b9615ed386e9b6063872c8d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T22:00+00:00, close=81736.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T22:00+00:00, close=81736.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.197600|-5.04|-12.75|-5.20|10662361|5.06|
|S_USDT|0.052830|-4.87|32.60|-5.03|5445220|1.89|
|BAT_USDT|0.169520|-3.99|70.95|-4.15|27112101|0.59|
|NEAR_USDT|4.845000|-3.13|-3.75|-3.29|175822718|2.06|
|LDO_USDT|0.400100|-2.41|-6.38|-2.57|5027137|2.50|
|INJ_USDT|7.650000|-2.39|4.66|-2.55|34498177|1.31|
|STRK_USDT|0.076150|-2.22|53.96|-2.38|24354645|1.31|
|AAVE_USDT|153.680000|-1.96|-10.52|-2.12|25271587|0.65|
|ENA_USDT|0.196310|-1.18|-13.95|-1.34|36637807|0.51|
|UNI_USDT|7.119000|-1.16|-9.21|-1.32|17487126|1.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.680000|153.400000|153.680000|1.45|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169520|0.167700|0.169520|1.00|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.196310|0.194310|0.196310|1.54|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.197600|0.192700|0.197600|0.40|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.650000|7.530000|7.648000|0.53|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.400100|0.394500|0.400100|0.38|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.845000|4.765000|4.844000|0.48|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.076150|0.075440|0.076150|0.54|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052830|0.052850|0.052830|2.07|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|7.119000|7.053000|7.119000|0.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=155.360000, depth_time=2026-10-14T22:00:23+00:00, book20_bid_proxy_usdt=217490, book20_ask_proxy_usdt=241653, funding_indicative=0.000082, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=25271587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=0.172860, depth_time=2026-10-14T22:00:12+00:00, book20_bid_proxy_usdt=26924, book20_ask_proxy_usdt=30754, funding_indicative=0.000025, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=27112101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=0.197440, depth_time=2026-10-14T22:00:26+00:00, book20_bid_proxy_usdt=99638, book20_ask_proxy_usdt=118724, funding_indicative=0.000037, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=36637807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=0.198200, depth_time=2026-10-14T22:00:07+00:00, book20_bid_proxy_usdt=1134585, book20_ask_proxy_usdt=996242, funding_indicative=0.000007, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.04%, turnover=10662361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=7.708000, depth_time=2026-10-14T22:00:17+00:00, book20_bid_proxy_usdt=191966, book20_ask_proxy_usdt=221642, funding_indicative=0.000155, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=34498177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T22:00:01+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=0.404100, depth_time=2026-10-14T22:00:13+00:00, book20_bid_proxy_usdt=582656, book20_ask_proxy_usdt=644565, funding_indicative=-0.000084, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=5027137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=4.867000, depth_time=2026-10-14T22:00:14+00:00, book20_bid_proxy_usdt=1177177, book20_ask_proxy_usdt=1730238, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=175822718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=0.078300, depth_time=2026-10-14T22:00:20+00:00, book20_bid_proxy_usdt=228376, book20_ask_proxy_usdt=299693, funding_indicative=0.000017, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=24354645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=0.053720, depth_time=2026-10-14T22:00:09+00:00, book20_bid_proxy_usdt=192900, book20_ask_proxy_usdt=214663, funding_indicative=-0.000071, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=5445220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T22:00:00+00:00, last15m_closed_end=2026-10-14T22:00+00:00, prior8high=7.144000, depth_time=2026-10-14T22:00:27+00:00, book20_bid_proxy_usdt=1069858, book20_ask_proxy_usdt=1631528, funding_indicative=0.000096, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=17487126. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
