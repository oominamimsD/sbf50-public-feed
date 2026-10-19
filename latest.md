# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T13:00:27Z**
- feed_generated_utc: 2026-10-19T13:00:49+00:00
- source_sha256: `a841115ee10d74c3fb126ffa10f64597e15cad9fee8d476846c92a1b2934d030`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.35 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T13:00+00:00, close=82567.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T13:00+00:00, close=82567.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.937200|-15.97|15.15|-17.70|21346528|3.61|
|STRK_USDT|0.058410|-3.96|-51.02|-5.69|17971657|1.71|
|TIA_USDT|0.603100|-2.39|2.44|-4.12|45961089|1.66|
|HBAR_USDT|0.083910|-2.17|-10.52|-3.90|38230296|1.19|
|XAU_USDT|4168.950000|0.12|-0.83|-1.61|257352964|0.02|
|XAUT_USDT|4155.840000|0.19|-0.80|-1.54|96908498|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.937200|1.931700|1.936000|2.18|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.083910|0.082730|0.083910|0.72|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058410|0.057800|0.058410|3.62|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.603100|0.601500|0.603200|0.96|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4155.840000|4154.090000|4156.690000|0.94|N|Y/Y|Y/N|N|N|
|XAU_USDT|4168.950000|4165.540000|4168.950000|0.51|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T13:00:03+00:00, last15m_closed_end=2026-10-19T13:00+00:00, prior8high=2.157000, depth_time=2026-10-19T13:00:10+00:00, book20_bid_proxy_usdt=11416, book20_ask_proxy_usdt=10463, funding_indicative=-0.000788, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.97%, turnover=21346528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T13:00:03+00:00, last15m_closed_end=2026-10-19T13:00+00:00, prior8high=0.083810, depth_time=2026-10-19T13:00:18+00:00, book20_bid_proxy_usdt=467050, book20_ask_proxy_usdt=1161014, funding_indicative=0.000002, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=38230296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T13:00:03+00:00, last15m_closed_end=2026-10-19T13:00+00:00, prior8high=0.058940, depth_time=2026-10-19T13:00:12+00:00, book20_bid_proxy_usdt=647278, book20_ask_proxy_usdt=617584, funding_indicative=0.000050, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.96%, turnover=17971657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T13:00:03+00:00, last15m_closed_end=2026-10-19T13:00+00:00, prior8high=0.614900, depth_time=2026-10-19T13:00:15+00:00, book20_bid_proxy_usdt=241067, book20_ask_proxy_usdt=301497, funding_indicative=0.000004, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=45961089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-19T13:00:03+00:00, last15m_closed_end=2026-10-19T13:00+00:00, prior8high=4169.510000, depth_time=2026-10-19T13:00:24+00:00, book20_bid_proxy_usdt=202212, book20_ask_proxy_usdt=276801, funding_indicative=0.000006, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.19%, turnover=96908498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-19T13:00:03+00:00, last15m_closed_end=2026-10-19T13:00+00:00, prior8high=4183.360000, depth_time=2026-10-19T13:00:21+00:00, book20_bid_proxy_usdt=602554, book20_ask_proxy_usdt=1066134, funding_indicative=0.000000, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.12%, turnover=257352964. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
