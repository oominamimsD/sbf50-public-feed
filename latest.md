# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T23:15:19Z**
- feed_generated_utc: 2026-10-20T23:15:22+00:00
- source_sha256: `efcda7b4408a6ce1de5a1bcaefe16ed68f2e34d2a5a4ff2a20ccebbf11215008`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T23:15+00:00, close=82940.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T23:00+00:00, close=83059.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.057936|-10.35|258.13|-10.78|7052306|3.28|
|BAT_USDT|0.194300|-9.95|9.53|-10.38|10011625|0.52|
|XMR_USDT|600.000000|-3.25|13.65|-3.68|13088566|1.50|
|DOT_USDT|1.148000|-0.82|-0.76|-1.25|12664943|0.87|
|ARB_USDT|0.187850|-0.58|1.73|-1.01|83939102|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.057936|0.056252|0.057950|1.10|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.187850|0.188060|0.187800|1.70|Y|Y/Y|Y/Y|N|Y|
|BAT_USDT|0.194300|0.193360|0.193590|0.34|N|Y/Y|N/N|N|N|
|DOT_USDT|1.148000|1.150100|1.148000|1.13|N|Y/N|N/N|N|N|
|XMR_USDT|600.000000|609.000000|600.000000|33.64|Y|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T23:15:00+00:00, last15m_closed_end=2026-10-20T23:15+00:00, prior8high=0.058996, depth_time=2026-10-20T23:15:07+00:00, book20_bid_proxy_usdt=42832, book20_ask_proxy_usdt=11928, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.35%, turnover=7052306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T23:15:00+00:00, last15m_closed_end=2026-10-20T23:15+00:00, prior8high=0.191850, depth_time=2026-10-20T23:15:17+00:00, book20_bid_proxy_usdt=88289, book20_ask_proxy_usdt=109492, funding_indicative=-0.000076, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.58%, turnover=83939102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T23:15:01+00:00, last15m_closed_end=2026-10-20T23:15+00:00, prior8high=0.200820, depth_time=2026-10-20T23:15:10+00:00, book20_bid_proxy_usdt=19406, book20_ask_proxy_usdt=15969, funding_indicative=0.000027, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.95%, turnover=10011625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-20T23:15:01+00:00, last15m_closed_end=2026-10-20T23:15+00:00, prior8high=1.169500, depth_time=2026-10-20T23:15:16+00:00, book20_bid_proxy_usdt=238352, book20_ask_proxy_usdt=320409, funding_indicative=0.000049, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=12664943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-20T23:15:01+00:00, last15m_closed_end=2026-10-20T23:15+00:00, prior8high=624.900000, depth_time=2026-10-20T23:15:13+00:00, book20_bid_proxy_usdt=5466, book20_ask_proxy_usdt=23635, funding_indicative=0.000100, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=13088566. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
