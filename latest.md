# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T01:45:16Z**
- feed_generated_utc: 2026-10-25T01:45:19+00:00
- source_sha256: `687ac491ada55f3ed35a8177c4d39ca052fb4c30ccfd8ee16aab1adc31aa6856`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T01:45+00:00, close=80836.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T01:00+00:00, close=80842.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.031820|-30.90|149.37|-32.24|34596528|3.14|
|BIRB_USDT|0.071220|-27.07|46.78|-28.41|10305056|5.63|
|ORDER_USDT|0.052310|-22.38|69.01|-23.72|13345240|3.82|
|STRK_USDT|0.046580|-0.32|-29.58|-1.66|8250796|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.071220|0.069260|0.071190|1.04|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.031820|0.033300|0.031720|3.01|Y|Y/Y|Y/Y|Y|Y|
|ORDER_USDT|0.052310|0.053730|0.052260|0.74|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046580|0.046500|0.046580|1.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T01:45:03+00:00, last15m_closed_end=2026-10-25T01:45+00:00, prior8high=0.100590, depth_time=2026-10-25T01:45:09+00:00, book20_bid_proxy_usdt=14580, book20_ask_proxy_usdt=17524, funding_indicative=-0.018053, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-27.07%, turnover=10305056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T01:45:03+00:00, last15m_closed_end=2026-10-25T01:45+00:00, prior8high=0.047160, depth_time=2026-10-25T01:45:07+00:00, book20_bid_proxy_usdt=52106, book20_ask_proxy_usdt=60018, funding_indicative=-0.000084, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-30.90%, turnover=34596528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T01:45:03+00:00, last15m_closed_end=2026-10-25T01:45+00:00, prior8high=0.073400, depth_time=2026-10-25T01:45:13+00:00, book20_bid_proxy_usdt=50791, book20_ask_proxy_usdt=80705, funding_indicative=-0.001697, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-22.38%, turnover=13345240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T01:45:04+00:00, last15m_closed_end=2026-10-25T01:45+00:00, prior8high=0.047560, depth_time=2026-10-25T01:45:15+00:00, book20_bid_proxy_usdt=911704, book20_ask_proxy_usdt=570241, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.32%, turnover=8250796. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
