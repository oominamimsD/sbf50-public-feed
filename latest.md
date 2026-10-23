# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T02:15:23Z**
- feed_generated_utc: 2026-10-23T02:15:25+00:00
- source_sha256: `f763e5d232477ec80a4bafecc345c3ec7f99a80e605bebb9a04085d4502c5e1a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T02:15+00:00, close=81372.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T02:00+00:00, close=81311.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.435300|-4.94|11.12|-4.61|11441984|0.29|
|PHA_USDT|0.060060|-3.20|18.88|-2.87|8255944|1.67|
|STRK_USDT|0.052850|-2.77|-45.15|-2.44|12198577|1.89|
|SILVER_USDT|54.210000|-1.90|-5.12|-1.57|381854507|1.84|
|ARB_USDT|0.180530|-1.69|-4.95|-1.36|30318715|0.55|
|ZEC_USDT|1216.740000|-1.41|3.13|-1.08|1900824598|0.08|
|PUMPFUN_USDT|0.004614|-1.38|1.94|-1.05|36969522|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180530|0.178680|0.180530|1.16|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.435300|3.363100|3.434000|0.80|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.060060|0.059760|0.060070|0.71|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004614|0.004531|0.004614|6.34|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.210000|53.630000|54.210000|4.86|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052850|0.052330|0.052860|0.21|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1216.740000|1210.650000|1216.740000|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T02:14:59+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=0.182060, depth_time=2026-10-23T02:15:17+00:00, book20_bid_proxy_usdt=116919, book20_ask_proxy_usdt=85468, funding_indicative=-0.000107, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=30318715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T02:14:59+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=3.472900, depth_time=2026-10-23T02:15:07+00:00, book20_bid_proxy_usdt=22007, book20_ask_proxy_usdt=21097, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.94%, turnover=11441984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T02:14:59+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=0.061510, depth_time=2026-10-23T02:15:07+00:00, book20_bid_proxy_usdt=62878, book20_ask_proxy_usdt=77594, funding_indicative=-0.000581, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=8255944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T02:14:59+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=0.004670, depth_time=2026-10-23T02:15:21+00:00, book20_bid_proxy_usdt=2411224, book20_ask_proxy_usdt=1628062, funding_indicative=0.000018, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=36969522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T02:14:58+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=54.870000, depth_time=2026-10-23T02:15:14+00:00, book20_bid_proxy_usdt=33286900, book20_ask_proxy_usdt=31865492, funding_indicative=0.000100, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=381854507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T02:14:59+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=0.053310, depth_time=2026-10-23T02:15:12+00:00, book20_bid_proxy_usdt=823728, book20_ask_proxy_usdt=535945, funding_indicative=0.000038, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=12198577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T02:14:58+00:00, last15m_closed_end=2026-10-23T02:15+00:00, prior8high=1244.740000, depth_time=2026-10-23T02:15:19+00:00, book20_bid_proxy_usdt=147763, book20_ask_proxy_usdt=364707, funding_indicative=0.000032, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=1900824598. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
