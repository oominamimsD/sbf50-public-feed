# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T10:15:37Z**
- feed_generated_utc: 2026-11-09T10:15:39+00:00
- source_sha256: `0ab21071f697d455dd9dd8f602ea877239b93312a87932b2dddded82b8b60293`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T10:15+00:00, close=74149.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T10:00+00:00, close=74254.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001552|-20.73|33.28|-18.25|7592233|1.29|
|JCT_USDT|0.008754|-10.98|75.81|-8.50|73315870|4.57|
|ASTER_USDT|0.630200|-7.29|-9.89|-4.81|5455310|1.59|
|ETH_USDT|2100.340000|-6.28|-7.30|-3.80|1505995892|0.05|
|HYPE_USDT|72.949000|-5.78|-16.80|-3.30|47084130|0.14|
|XRP_USDT|1.090200|-5.67|-12.77|-3.19|266797114|0.92|
|NEAR_USDT|3.507000|-5.24|-19.02|-2.76|43906445|2.85|
|ZEC_USDT|1204.670000|-5.19|-2.68|-2.71|2275753075|0.08|
|PUMPFUN_USDT|0.003564|-4.62|-15.50|-2.14|10392717|2.81|
|TAO_USDT|215.810000|-4.52|-8.10|-2.04|51486877|1.39|
|TRUMPOFFICIAL_USDT|1.138000|-4.28|-33.68|-1.80|6614542|8.79|
|SOL_USDT|86.070000|-4.02|-9.17|-1.54|697068295|1.16|
|UNI_USDT|6.757000|-3.51|-6.87|-1.03|27730377|2.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.630200|0.627800|0.630200|0.11|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2100.340000|2088.450000|2100.340000|1.00|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|72.949000|72.471000|72.949000|2.65|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008754|0.007940|0.008754|0.81|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.507000|3.460000|3.507000|1.25|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001552|0.001557|0.001552|1.46|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003564|0.003487|0.003564|0.55|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.070000|85.420000|86.070000|1.51|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|215.810000|212.080000|215.810000|0.18|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.138000|1.122000|1.138000|0.47|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.757000|6.646000|6.757000|0.17|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.090200|1.082800|1.090200|1.07|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1204.670000|1185.330000|1204.670000|0.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=0.637200, depth_time=2026-11-09T10:15:09+00:00, book20_bid_proxy_usdt=651452, book20_ask_proxy_usdt=800032, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.29%, turnover=5455310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=2127.470000, depth_time=2026-11-09T10:15:14+00:00, book20_bid_proxy_usdt=3158857, book20_ask_proxy_usdt=2462557, funding_indicative=-0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.28%, turnover=1505995892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=74.219000, depth_time=2026-11-09T10:15:14+00:00, book20_bid_proxy_usdt=81179, book20_ask_proxy_usdt=94563, funding_indicative=0.000039, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.78%, turnover=47084130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=0.009792, depth_time=2026-11-09T10:15:09+00:00, book20_bid_proxy_usdt=47210, book20_ask_proxy_usdt=82369, funding_indicative=0.001337, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.98%, turnover=73315870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=3.578000, depth_time=2026-11-09T10:15:22+00:00, book20_bid_proxy_usdt=2592661, book20_ask_proxy_usdt=2423348, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=43906445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=0.001610, depth_time=2026-11-09T10:15:06+00:00, book20_bid_proxy_usdt=10473, book20_ask_proxy_usdt=8886, funding_indicative=-0.000131, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.73%, turnover=7592233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=0.003597, depth_time=2026-11-09T10:15:27+00:00, book20_bid_proxy_usdt=1393554, book20_ask_proxy_usdt=1561590, funding_indicative=0.000035, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=10392717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=87.260000, depth_time=2026-11-09T10:15:33+00:00, book20_bid_proxy_usdt=13958190, book20_ask_proxy_usdt=16391181, funding_indicative=-0.000003, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=697068295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=218.060000, depth_time=2026-11-09T10:15:29+00:00, book20_bid_proxy_usdt=118085, book20_ask_proxy_usdt=132763, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=51486877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=1.153000, depth_time=2026-11-09T10:15:31+00:00, book20_bid_proxy_usdt=2882811, book20_ask_proxy_usdt=2203480, funding_indicative=0.000040, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.28%, turnover=6614542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=6.798000, depth_time=2026-11-09T10:15:34+00:00, book20_bid_proxy_usdt=2441140, book20_ask_proxy_usdt=2271574, funding_indicative=0.000072, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.51%, turnover=27730377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=1.101300, depth_time=2026-11-09T10:15:19+00:00, book20_bid_proxy_usdt=3558289, book20_ask_proxy_usdt=3768013, funding_indicative=0.000080, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.67%, turnover=266797114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T10:15:00+00:00, last15m_closed_end=2026-11-09T10:15+00:00, prior8high=1233.140000, depth_time=2026-11-09T10:15:24+00:00, book20_bid_proxy_usdt=348128, book20_ask_proxy_usdt=425874, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.19%, turnover=2275753075. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
