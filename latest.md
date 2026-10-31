# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T18:45:14Z**
- feed_generated_utc: 2026-10-31T18:45:15+00:00
- source_sha256: `c5aebab1a446f3c1b56648c20f726a735f10541378f2e12da8f4ee2acf2606f6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T18:45+00:00, close=77657.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T18:00+00:00, close=77664.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WLD_USDT|0.399700|-1.16|-13.48|-1.28|38725189|2.50|
|DASH_USDT|48.130000|-1.00|-2.76|-1.12|5414899|2.08|
|FET_USDT|0.161700|-0.97|-6.15|-1.09|5877587|6.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|48.130000|48.050000|48.130000|0.30|N|Y/N|Y/Y|Y|N|
|FET_USDT|0.161700|0.161100|0.161700|0.46|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399700|0.397400|0.399700|0.81|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-31T18:45:01+00:00, last15m_closed_end=2026-10-31T18:45+00:00, prior8high=48.840000, depth_time=2026-10-31T18:45:10+00:00, book20_bid_proxy_usdt=925810, book20_ask_proxy_usdt=730163, funding_indicative=0.000017, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=5414899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T18:45:01+00:00, last15m_closed_end=2026-10-31T18:45+00:00, prior8high=0.162800, depth_time=2026-10-31T18:45:09+00:00, book20_bid_proxy_usdt=1321834, book20_ask_proxy_usdt=717829, funding_indicative=-0.000041, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=5877587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T18:45:00+00:00, last15m_closed_end=2026-10-31T18:45+00:00, prior8high=0.401700, depth_time=2026-10-31T18:45:06+00:00, book20_bid_proxy_usdt=2725669, book20_ask_proxy_usdt=2558328, funding_indicative=-0.000006, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=38725189. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
