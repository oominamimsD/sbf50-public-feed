# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T11:00:42Z**
- feed_generated_utc: 2026-11-09T11:00:44+00:00
- source_sha256: `b2e3cb80a308cf766431197f4d4d37c53444bbe3c05e832d910344b37f495cf3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T11:00+00:00, close=74125.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T11:00+00:00, close=74125.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001545|-18.33|32.65|-15.82|6517137|0.65|
|ASTER_USDT|0.628200|-7.27|-10.18|-4.76|5506222|1.59|
|XRP_USDT|1.084400|-6.50|-13.24|-3.99|263678004|0.92|
|NEAR_USDT|3.487000|-6.16|-19.48|-3.65|44459919|2.87|
|ZEC_USDT|1194.910000|-6.15|-3.47|-3.64|2266118803|0.08|
|ETH_USDT|2106.840000|-5.99|-7.01|-3.48|1533411397|0.05|
|HYPE_USDT|72.977000|-5.80|-16.77|-3.29|47139712|0.14|
|JCT_USDT|0.009291|-5.52|86.60|-3.01|73722893|1.08|
|TAO_USDT|215.910000|-4.55|-8.06|-2.04|51678914|1.39|
|PUMPFUN_USDT|0.003574|-4.28|-15.26|-1.77|10396934|2.80|
|TRUMPOFFICIAL_USDT|1.134000|-4.06|-33.91|-1.55|6353767|8.82|
|SOL_USDT|85.930000|-4.02|-9.31|-1.51|698684687|1.16|
|DOT_USDT|0.857100|-3.62|-9.49|-1.11|10322896|1.17|
|DOGE_USDT|0.068740|-3.60|-9.12|-1.09|72528448|1.46|
|UNI_USDT|6.728000|-3.59|-7.27|-1.08|26674329|1.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.628200|0.623900|0.628200|0.39|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068740|0.068630|0.068740|0.13|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.857100|0.855100|0.857100|0.11|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2106.840000|2098.500000|2106.840000|0.50|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|72.977000|72.807000|72.977000|0.46|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009291|0.008269|0.009290|0.46|N|N/Y|N/N|Y|N|
|NEAR_USDT|3.487000|3.496000|3.487000|1.34|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001545|0.001531|0.001545|1.09|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003574|0.003542|0.003574|1.02|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.930000|85.850000|85.930000|0.23|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|215.910000|215.040000|215.910000|0.27|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.134000|1.126000|1.134000|0.30|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.728000|6.714000|6.728000|0.10|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.084400|1.085000|1.084400|1.14|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1194.910000|1196.700000|1194.910000|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=0.637200, depth_time=2026-11-09T11:00:09+00:00, book20_bid_proxy_usdt=539887, book20_ask_proxy_usdt=827816, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.27%, turnover=5506222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=0.069600, depth_time=2026-11-09T11:00:36+00:00, book20_bid_proxy_usdt=5925546, book20_ask_proxy_usdt=4814339, funding_indicative=0.000022, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.60%, turnover=72528448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=0.872200, depth_time=2026-11-09T11:00:36+00:00, book20_bid_proxy_usdt=1015843, book20_ask_proxy_usdt=513940, funding_indicative=0.000054, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.62%, turnover=10322896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=2127.470000, depth_time=2026-11-09T11:00:18+00:00, book20_bid_proxy_usdt=6849351, book20_ask_proxy_usdt=2967327, funding_indicative=-0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.99%, turnover=1533411397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=74.219000, depth_time=2026-11-09T11:00:21+00:00, book20_bid_proxy_usdt=111448, book20_ask_proxy_usdt=83457, funding_indicative=0.000039, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.80%, turnover=47139712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=0.009792, depth_time=2026-11-09T11:00:24+00:00, book20_bid_proxy_usdt=64410, book20_ask_proxy_usdt=49499, funding_indicative=0.001336, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.52%, turnover=73722893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=3.578000, depth_time=2026-11-09T11:00:14+00:00, book20_bid_proxy_usdt=2220316, book20_ask_proxy_usdt=2336459, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.16%, turnover=44459919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=0.001610, depth_time=2026-11-09T11:00:07+00:00, book20_bid_proxy_usdt=21153, book20_ask_proxy_usdt=15012, funding_indicative=-0.000042, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.33%, turnover=6517137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=0.003597, depth_time=2026-11-09T11:00:29+00:00, book20_bid_proxy_usdt=2716225, book20_ask_proxy_usdt=2400965, funding_indicative=0.000037, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.28%, turnover=10396934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=87.260000, depth_time=2026-11-09T11:00:34+00:00, book20_bid_proxy_usdt=17128656, book20_ask_proxy_usdt=15004520, funding_indicative=0.000005, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=698684687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=218.060000, depth_time=2026-11-09T11:00:24+00:00, book20_bid_proxy_usdt=106049, book20_ask_proxy_usdt=231549, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=51678914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=1.153000, depth_time=2026-11-09T11:00:30+00:00, book20_bid_proxy_usdt=2377099, book20_ask_proxy_usdt=2879861, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.06%, turnover=6353767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=6.802000, depth_time=2026-11-09T11:00:40+00:00, book20_bid_proxy_usdt=3709373, book20_ask_proxy_usdt=2694180, funding_indicative=0.000085, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.59%, turnover=26674329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=1.101300, depth_time=2026-11-09T11:00:11+00:00, book20_bid_proxy_usdt=3517758, book20_ask_proxy_usdt=3230914, funding_indicative=0.000088, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.50%, turnover=263678004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T11:00:00+00:00, last15m_closed_end=2026-11-09T11:00+00:00, prior8high=1233.140000, depth_time=2026-11-09T11:00:14+00:00, book20_bid_proxy_usdt=262136, book20_ask_proxy_usdt=334057, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.15%, turnover=2266118803. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
