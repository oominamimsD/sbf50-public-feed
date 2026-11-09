# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T15:00:24Z**
- feed_generated_utc: 2026-11-09T15:00:25+00:00
- source_sha256: `38e80bbe7b2e0949dc3064a84b8ec36045bf5593696bec0d5fd32ecd7f36cd99`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T15:00+00:00, close=74871.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T15:00+00:00, close=74871.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001508|-20.26|29.52|-18.77|5886018|0.66|
|AKE_USDT|0.004751|-10.87|-48.13|-9.38|8732517|4.21|
|ASTER_USDT|0.640600|-5.44|-8.40|-3.95|5779351|1.56|
|XRP_USDT|1.100500|-5.11|-11.95|-3.62|284753425|0.91|
|ETH_USDT|2128.350000|-4.97|-6.06|-3.48|1662398958|0.05|
|TRUMPOFFICIAL_USDT|1.133000|-4.70|-33.97|-3.21|6307878|8.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004751|0.004671|0.004751|0.73|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.640600|0.637900|0.640600|2.36|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2128.350000|2113.380000|2128.350000|3.22|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001508|0.001470|0.001509|1.28|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.133000|1.113000|1.132000|2.39|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.100500|1.090100|1.100500|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T15:00:00+00:00, last15m_closed_end=2026-11-09T15:00+00:00, prior8high=0.004890, depth_time=2026-11-09T15:00:10+00:00, book20_bid_proxy_usdt=39557, book20_ask_proxy_usdt=38227, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.87%, turnover=8732517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T15:00:00+00:00, last15m_closed_end=2026-11-09T15:00+00:00, prior8high=0.643800, depth_time=2026-11-09T15:00:09+00:00, book20_bid_proxy_usdt=817148, book20_ask_proxy_usdt=621920, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.44%, turnover=5779351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T15:00:00+00:00, last15m_closed_end=2026-11-09T15:00+00:00, prior8high=2131.940000, depth_time=2026-11-09T15:00:18+00:00, book20_bid_proxy_usdt=2134656, book20_ask_proxy_usdt=4295044, funding_indicative=0.000007, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.97%, turnover=1662398958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T15:00:00+00:00, last15m_closed_end=2026-11-09T15:00+00:00, prior8high=0.001538, depth_time=2026-11-09T15:00:08+00:00, book20_bid_proxy_usdt=22330, book20_ask_proxy_usdt=24262, funding_indicative=-0.000150, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.26%, turnover=5886018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T15:00:00+00:00, last15m_closed_end=2026-11-09T15:00+00:00, prior8high=1.148000, depth_time=2026-11-09T15:00:21+00:00, book20_bid_proxy_usdt=2856254, book20_ask_proxy_usdt=2340640, funding_indicative=0.000037, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=6307878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T15:00:00+00:00, last15m_closed_end=2026-11-09T15:00+00:00, prior8high=1.110100, depth_time=2026-11-09T15:00:16+00:00, book20_bid_proxy_usdt=2464360, book20_ask_proxy_usdt=2728752, funding_indicative=0.000079, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.11%, turnover=284753425. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
