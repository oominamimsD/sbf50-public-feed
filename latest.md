# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T12:30:20Z**
- feed_generated_utc: 2026-10-14T12:30:22+00:00
- source_sha256: `33c8d767d8bfb58ee4e0ec1c172fec82fef02dc2f1a57e44d5161ef167bc86e0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T12:30+00:00, close=83829.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.080400|-7.51|54.05|-8.03|27625131|1.24|
|W_USDT|0.015878|-5.50|9.41|-6.02|6325933|7.56|
|TIA_USDT|0.559200|-3.13|17.40|-3.65|34149469|1.79|
|UNI_USDT|7.400000|-2.27|-14.59|-2.79|17599932|2.70|
|SILVER_USDT|58.870000|-0.87|-4.07|-1.39|282436197|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SILVER_USDT|58.870000|58.480000|58.870000|6.93|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.080400|0.077420|0.080400|1.25|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.559200|0.540100|0.559500|3.01|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.400000|7.313000|7.404000|1.14|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015878|0.015698|0.015878|1.63|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- SILVER_USDT: quote_utc=2026-10-14T12:29:59+00:00, last15m_closed_end=2026-10-14T12:30+00:00, prior8high=58.860000, depth_time=2026-10-14T12:30:19+00:00, book20_bid_proxy_usdt=8361378, book20_ask_proxy_usdt=6929511, funding_indicative=0.000102, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=282436197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T12:29:59+00:00, last15m_closed_end=2026-10-14T12:30+00:00, prior8high=0.080580, depth_time=2026-10-14T12:30:09+00:00, book20_bid_proxy_usdt=52903, book20_ask_proxy_usdt=69857, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.51%, turnover=27625131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T12:29:59+00:00, last15m_closed_end=2026-10-14T12:30+00:00, prior8high=0.560900, depth_time=2026-10-14T12:30:14+00:00, book20_bid_proxy_usdt=31120, book20_ask_proxy_usdt=23084, funding_indicative=-0.000048, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=34149469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T12:29:59+00:00, last15m_closed_end=2026-10-14T12:30+00:00, prior8high=7.401000, depth_time=2026-10-14T12:30:16+00:00, book20_bid_proxy_usdt=336308, book20_ask_proxy_usdt=319449, funding_indicative=0.000095, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=17599932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T12:29:59+00:00, last15m_closed_end=2026-10-14T12:30+00:00, prior8high=0.016220, depth_time=2026-10-14T12:30:11+00:00, book20_bid_proxy_usdt=12058, book20_ask_proxy_usdt=10284, funding_indicative=-0.000218, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.50%, turnover=6325933. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
