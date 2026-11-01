# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T08:45:29Z**
- feed_generated_utc: 2026-11-01T08:45:31+00:00
- source_sha256: `7fd0e915420c1a2ad887f03ffeea37a1a20544897a90b65a182bdcbc82c69562`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T08:45+00:00, close=78131.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.224860|-24.07|33.90|-24.80|31023194|1.33|
|AKE_USDT|0.008768|-21.27|-70.00|-22.00|10337886|3.43|
|BLESS_USDT|0.009523|-9.85|17.37|-10.58|6333710|3.15|
|XPL_USDT|0.074190|-8.75|2.74|-9.48|6661583|1.35|
|ENA_USDT|0.188170|-3.01|0.73|-3.74|44061206|0.53|
|ZEC_USDT|1252.110000|-2.52|9.33|-3.25|931802479|0.08|
|TIA_USDT|0.478700|-2.32|-8.94|-3.05|8419738|2.09|
|NEAR_USDT|4.393000|-1.85|-0.20|-2.58|53130268|2.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.008768|0.009160|0.008767|2.79|Y|Y/Y|Y/Y|Y|Y|
|BLESS_USDT|0.009523|0.009395|0.009523|1.28|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188170|0.186980|0.188170|1.98|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.224860|0.219110|0.224960|0.73|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.393000|4.356000|4.393000|1.39|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.478700|0.477200|0.478700|0.87|N|N/N|Y/Y|Y|N|
|XPL_USDT|0.074190|0.072520|0.074190|0.18|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1252.110000|1239.270000|1252.100000|1.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=0.009782, depth_time=2026-11-01T08:45:12+00:00, book20_bid_proxy_usdt=8414, book20_ask_proxy_usdt=17609, funding_indicative=-0.002463, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.27%, turnover=10337886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=0.009612, depth_time=2026-11-01T08:45:11+00:00, book20_bid_proxy_usdt=19934, book20_ask_proxy_usdt=10294, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.85%, turnover=6333710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=0.188640, depth_time=2026-11-01T08:45:20+00:00, book20_bid_proxy_usdt=135600, book20_ask_proxy_usdt=185105, funding_indicative=0.000025, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=44061206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=0.239180, depth_time=2026-11-01T08:45:09+00:00, book20_bid_proxy_usdt=11693, book20_ask_proxy_usdt=14889, funding_indicative=-0.002347, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.07%, turnover=31023194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=4.393000, depth_time=2026-11-01T08:45:28+00:00, book20_bid_proxy_usdt=5882185, book20_ask_proxy_usdt=4917397, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=53130268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=0.482600, depth_time=2026-11-01T08:45:25+00:00, book20_bid_proxy_usdt=235800, book20_ask_proxy_usdt=219506, funding_indicative=-0.000079, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=8419738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=0.074940, depth_time=2026-11-01T08:45:17+00:00, book20_bid_proxy_usdt=335282, book20_ask_proxy_usdt=314883, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.75%, turnover=6661583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T08:45:00+00:00, last15m_closed_end=2026-11-01T08:45+00:00, prior8high=1248.860000, depth_time=2026-11-01T08:45:22+00:00, book20_bid_proxy_usdt=587236, book20_ask_proxy_usdt=273691, funding_indicative=-0.000068, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=931802479. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
