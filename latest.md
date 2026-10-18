# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T23:45:14Z**
- feed_generated_utc: 2026-10-18T23:45:16+00:00
- source_sha256: `cf4960461c4006378c8df968a8352521f01a6b22c0d762d5234bec29a091c0db`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T23:45+00:00, close=82073.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T23:00+00:00, close=81727.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.112102|-8.09|295.81|-9.24|9972702|1.43|
|AGT_USDT|0.066367|-1.72|275.27|-2.87|10161847|3.47|
|STRK_USDT|0.060560|-1.62|-49.22|-2.77|16047673|3.31|
|SAND_USDT|0.058640|-0.20|-11.73|-1.35|34092834|3.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066367|0.060544|0.066367|1.70|N|Y/Y|N/N|Y|N|
|Q_USDT|0.112102|0.111654|0.112102|0.72|N|N/N|N/N|Y|N|
|SAND_USDT|0.058640|0.056260|0.058640|0.53|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.060560|0.058910|0.060560|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T23:44:59+00:00, last15m_closed_end=2026-10-18T23:45+00:00, prior8high=0.068584, depth_time=2026-10-18T23:45:09+00:00, book20_bid_proxy_usdt=3628, book20_ask_proxy_usdt=3422, funding_indicative=0.000247, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=10161847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-18T23:44:59+00:00, last15m_closed_end=2026-10-18T23:45+00:00, prior8high=0.122022, depth_time=2026-10-18T23:45:06+00:00, book20_bid_proxy_usdt=7962, book20_ask_proxy_usdt=8494, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.09%, turnover=9972702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T23:44:59+00:00, last15m_closed_end=2026-10-18T23:45+00:00, prior8high=0.058890, depth_time=2026-10-18T23:45:12+00:00, book20_bid_proxy_usdt=610377, book20_ask_proxy_usdt=645036, funding_indicative=-0.002684, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.20%, turnover=34092834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T23:44:59+00:00, last15m_closed_end=2026-10-18T23:45+00:00, prior8high=0.061020, depth_time=2026-10-18T23:45:11+00:00, book20_bid_proxy_usdt=488572, book20_ask_proxy_usdt=386511, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=16047673. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
