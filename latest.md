# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T19:30:16Z**
- feed_generated_utc: 2026-10-31T19:30:17+00:00
- source_sha256: `d2ea67f5972595c9c891958f6c458446ac3b745eb15e4bb66b622599a840cf95`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T19:30+00:00, close=77545, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T19:00+00:00, close=77582.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WLD_USDT|0.397400|-1.73|-13.98|-1.72|36442564|2.52|
|TRX_USDT|0.307220|-1.63|-6.60|-1.62|8660454|0.33|
|FET_USDT|0.161200|-1.28|-6.44|-1.27|5305986|6.20|
|DASH_USDT|48.020000|-1.23|-2.98|-1.22|5087481|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|48.020000|48.050000|48.020000|1.68|Y|Y/N|Y/Y|Y|N|
|FET_USDT|0.161200|0.160900|0.161100|0.35|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.307220|0.305290|0.307220|5.73|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397400|0.397300|0.397400|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-31T19:30:03+00:00, last15m_closed_end=2026-10-31T19:30+00:00, prior8high=48.500000, depth_time=2026-10-31T19:30:13+00:00, book20_bid_proxy_usdt=633703, book20_ask_proxy_usdt=786649, funding_indicative=-0.000003, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=5087481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T19:30:03+00:00, last15m_closed_end=2026-10-31T19:30+00:00, prior8high=0.162300, depth_time=2026-10-31T19:30:13+00:00, book20_bid_proxy_usdt=1344731, book20_ask_proxy_usdt=934485, funding_indicative=-0.000099, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=5305986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T19:30:03+00:00, last15m_closed_end=2026-10-31T19:30+00:00, prior8high=0.310250, depth_time=2026-10-31T19:30:09+00:00, book20_bid_proxy_usdt=70102, book20_ask_proxy_usdt=60852, funding_indicative=-0.000428, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=8660454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T19:30:03+00:00, last15m_closed_end=2026-10-31T19:30+00:00, prior8high=0.400400, depth_time=2026-10-31T19:30:08+00:00, book20_bid_proxy_usdt=2353143, book20_ask_proxy_usdt=2733301, funding_indicative=-0.000042, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=36442564. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
