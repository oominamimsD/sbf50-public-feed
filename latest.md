# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T00:00:15Z**
- feed_generated_utc: 2026-10-27T00:00:18+00:00
- source_sha256: `5214dc91e27f0b2548462be2ed600fbf912d762406819d36c01ea08c91a565a4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.487600|-5.68|-20.84|-5.33|9282547|2.05|
|ZRO_USDT|1.629500|-4.54|-14.32|-4.19|5399650|3.07|
|NEAR_USDT|4.506000|-3.20|-8.11|-2.85|108613339|2.22|
|DOT_USDT|1.010600|-1.99|-11.87|-1.64|10381125|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BR_USDT|0.487600|0.473800|0.487500|0.88|N|N/Y|N/N|Y|N|
|DOT_USDT|1.010600|0.999000|1.010900|0.37|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.506000|4.422000|4.506000|0.36|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.629500|1.610100|1.629500|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BR_USDT: quote_utc=2026-10-27T00:00:03+00:00, last15m_closed_end=2026-10-27T00:00+00:00, prior8high=0.491500, depth_time=2026-10-27T00:00:07+00:00, book20_bid_proxy_usdt=41007, book20_ask_proxy_usdt=39537, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.68%, turnover=9282547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T00:00:03+00:00, last15m_closed_end=2026-10-27T00:00+00:00, prior8high=1.011100, depth_time=2026-10-27T00:00:14+00:00, book20_bid_proxy_usdt=304642, book20_ask_proxy_usdt=365606, funding_indicative=-0.000004, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=10381125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T00:00:03+00:00, last15m_closed_end=2026-10-27T00:00+00:00, prior8high=4.506000, depth_time=2026-10-27T00:00:12+00:00, book20_bid_proxy_usdt=3653335, book20_ask_proxy_usdt=3189137, funding_indicative=0.000044, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.20%, turnover=108613339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T23:59:59+00:00, last15m_closed_end=2026-10-27T00:00+00:00, prior8high=1.643300, depth_time=2026-10-27T00:00:09+00:00, book20_bid_proxy_usdt=32958, book20_ask_proxy_usdt=53068, funding_indicative=0.000018, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.54%, turnover=5399650. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
