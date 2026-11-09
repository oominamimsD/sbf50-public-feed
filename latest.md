# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T18:00:19Z**
- feed_generated_utc: 2026-11-09T18:00:21+00:00
- source_sha256: `f9e5ddac93585cde2c193825ea56f41786b395a3c2e702a96f40dffa4e741645`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T18:00+00:00, close=74755.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T18:00+00:00, close=74755.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T16:00+00:00, close=75500.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ON_USDT|0.165700|-16.73|-2.24|-16.58|5053434|6.04|
|ZEC_USDT|1169.350000|-4.23|-6.75|-4.08|2417006810|0.09|
|ONE_USDT|0.001460|-3.21|30.85|-3.06|5082755|0.69|
|JCT_USDT|0.010719|-2.32|148.29|-2.17|52475516|6.53|
|QNT_USDT|195.360000|-2.28|-3.50|-2.13|43205150|0.51|
|TRUMPOFFICIAL_USDT|1.119000|-2.01|-31.60|-1.86|5739177|8.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.010719|0.009237|0.010715|0.82|N|N/N|N/N|Y|N|
|ONE_USDT|0.001460|0.001446|0.001460|0.92|N|Y/Y|Y/Y|Y|N|
|ON_USDT|0.165700|0.136700|0.165800|0.24|N|Y/Y|Y/N|Y|N|
|QNT_USDT|195.360000|193.980000|195.360000|1.19|N|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.119000|1.113000|1.119000|1.48|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1169.350000|1163.250000|1169.350000|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-11-09T18:00:00+00:00, last15m_closed_end=2026-11-09T18:00+00:00, prior8high=0.010884, depth_time=2026-11-09T18:00:13+00:00, book20_bid_proxy_usdt=45303, book20_ask_proxy_usdt=37377, funding_indicative=0.000846, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=52475516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T18:00:00+00:00, last15m_closed_end=2026-11-09T18:00+00:00, prior8high=0.001511, depth_time=2026-11-09T18:00:11+00:00, book20_bid_proxy_usdt=16233, book20_ask_proxy_usdt=14700, funding_indicative=-0.000587, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=5082755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-09T18:00:00+00:00, last15m_closed_end=2026-11-09T18:00+00:00, prior8high=0.184100, depth_time=2026-11-09T18:00:07+00:00, book20_bid_proxy_usdt=75644, book20_ask_proxy_usdt=88763, funding_indicative=0.000050, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-16.73%, turnover=5053434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T18:00:00+00:00, last15m_closed_end=2026-11-09T18:00+00:00, prior8high=201.280000, depth_time=2026-11-09T18:00:16+00:00, book20_bid_proxy_usdt=51050, book20_ask_proxy_usdt=59532, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=43205150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T18:00:00+00:00, last15m_closed_end=2026-11-09T18:00+00:00, prior8high=1.145000, depth_time=2026-11-09T18:00:17+00:00, book20_bid_proxy_usdt=2954391, book20_ask_proxy_usdt=2954452, funding_indicative=-0.000178, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=5739177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T18:00:00+00:00, last15m_closed_end=2026-11-09T18:00+00:00, prior8high=1233.770000, depth_time=2026-11-09T18:00:09+00:00, book20_bid_proxy_usdt=270016, book20_ask_proxy_usdt=188494, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=2417006810. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
