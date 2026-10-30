# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T19:45:16Z**
- feed_generated_utc: 2026-10-30T19:45:18+00:00
- source_sha256: `eb41cc70f2e9317fd00162d5007c8bd545fbd2f9abaaa9d1545b83fae3efcb00`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T19:45+00:00, close=76614, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T19:00+00:00, close=76616.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.120200|-12.62|113.41|-11.38|6755959|1.78|
|BLESS_USDT|0.009103|-7.59|11.54|-6.35|15109099|4.40|
|LIT_USDT|2.734100|-3.19|-17.74|-1.95|12436725|0.37|
|PUMPFUN_USDT|0.004013|-2.28|-12.05|-1.04|25672835|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009103|0.008731|0.009103|0.32|N|Y/Y|Y/N|Y|N|
|EVAA_USDT|1.120200|1.072200|1.120200|0.47|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.734100|2.683300|2.734100|0.35|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004013|0.003918|0.004013|1.41|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T19:45:00+00:00, last15m_closed_end=2026-10-30T19:45+00:00, prior8high=0.009789, depth_time=2026-10-30T19:45:10+00:00, book20_bid_proxy_usdt=12268, book20_ask_proxy_usdt=12106, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.59%, turnover=15109099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T19:45:00+00:00, last15m_closed_end=2026-10-30T19:45+00:00, prior8high=1.289400, depth_time=2026-10-30T19:45:00+00:00, book20_bid_proxy_usdt=6516, book20_ask_proxy_usdt=11416, funding_indicative=0.000127, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-12.62%, turnover=6755959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T19:45:00+00:00, last15m_closed_end=2026-10-30T19:45+00:00, prior8high=2.800000, depth_time=2026-10-30T19:45:12+00:00, book20_bid_proxy_usdt=26799, book20_ask_proxy_usdt=30309, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=12436725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T19:45:00+00:00, last15m_closed_end=2026-10-30T19:45+00:00, prior8high=0.004056, depth_time=2026-10-30T19:45:15+00:00, book20_bid_proxy_usdt=1542868, book20_ask_proxy_usdt=1261646, funding_indicative=-0.000027, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=25672835. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
