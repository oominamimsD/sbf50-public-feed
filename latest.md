# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T05:15:18Z**
- feed_generated_utc: 2026-10-20T05:15:20+00:00
- source_sha256: `96af4683d17f314c6e717a41c81ea5ff2314171efabba7706ab888561954951d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T05:15+00:00, close=81995.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T05:00+00:00, close=82060.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.307010|-6.99|-10.26|-7.09|5396712|2.60|
|SAND_USDT|0.056820|-3.92|-8.48|-4.02|8668244|1.76|
|BTW_USDT|1.701300|-2.89|-3.10|-2.99|29717248|3.53|
|ZRO_USDT|1.852200|-2.61|-18.08|-2.71|7571534|1.08|
|NEAR_USDT|4.817000|-1.77|-13.19|-1.87|165727299|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.701300|1.797500|1.703000|4.04|Y|Y/Y|Y/Y|N|Y|
|CT_USDT|0.307010|0.305750|0.307010|1.16|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.817000|4.796000|4.817000|0.45|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.056820|0.056910|0.056820|1.40|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.852200|1.850000|1.852200|0.56|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-20T05:15:02+00:00, last15m_closed_end=2026-10-20T05:15+00:00, prior8high=1.942600, depth_time=2026-10-20T05:15:12+00:00, book20_bid_proxy_usdt=12510, book20_ask_proxy_usdt=10326, funding_indicative=-0.003390, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=29717248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T05:15:02+00:00, last15m_closed_end=2026-10-20T05:15+00:00, prior8high=0.338440, depth_time=2026-10-20T05:15:08+00:00, book20_bid_proxy_usdt=9182, book20_ask_proxy_usdt=8673, funding_indicative=-0.002677, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.99%, turnover=5396712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T05:15:02+00:00, last15m_closed_end=2026-10-20T05:15+00:00, prior8high=4.872000, depth_time=2026-10-20T05:15:16+00:00, book20_bid_proxy_usdt=3332701, book20_ask_proxy_usdt=3287826, funding_indicative=0.000022, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=165727299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T05:15:03+00:00, last15m_closed_end=2026-10-20T05:15+00:00, prior8high=0.058600, depth_time=2026-10-20T05:15:09+00:00, book20_bid_proxy_usdt=664571, book20_ask_proxy_usdt=969206, funding_indicative=-0.001867, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=8668244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T05:15:03+00:00, last15m_closed_end=2026-10-20T05:15+00:00, prior8high=1.880400, depth_time=2026-10-20T05:15:14+00:00, book20_bid_proxy_usdt=47282, book20_ask_proxy_usdt=32843, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=7571534. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
