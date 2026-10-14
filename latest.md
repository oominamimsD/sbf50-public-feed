# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T17:45:17Z**
- feed_generated_utc: 2026-10-14T17:45:19+00:00
- source_sha256: `202618ab4eb6fee235b89a44e57afa6f4babb6fd0dc6ad4015fef1eee7f49edd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T17:45+00:00, close=81745.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T17:00+00:00, close=81967.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.192200|-7.84|77.31|-8.00|58144918|4.56|
|S_USDT|0.052480|-4.21|31.72|-4.37|8257621|1.91|
|STRK_USDT|0.075370|-2.34|52.38|-2.50|25542291|1.33|
|BAT_USDT|0.171640|-1.59|73.09|-1.75|38082485|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.171640|0.171090|0.171690|0.52|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.192200|2.161400|2.195900|1.57|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.075370|0.075190|0.075330|0.83|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052480|0.052320|0.052480|1.10|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-14T17:45:02+00:00, last15m_closed_end=2026-10-14T17:45+00:00, prior8high=0.176560, depth_time=2026-10-14T17:45:16+00:00, book20_bid_proxy_usdt=27282, book20_ask_proxy_usdt=36468, funding_indicative=0.000016, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=38082485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T17:45:02+00:00, last15m_closed_end=2026-10-14T17:45+00:00, prior8high=2.425200, depth_time=2026-10-14T17:45:08+00:00, book20_bid_proxy_usdt=12906, book20_ask_proxy_usdt=10948, funding_indicative=-0.000002, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.84%, turnover=58144918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T17:45:02+00:00, last15m_closed_end=2026-10-14T17:45+00:00, prior8high=0.079070, depth_time=2026-10-14T17:45:13+00:00, book20_bid_proxy_usdt=243949, book20_ask_proxy_usdt=302463, funding_indicative=0.000039, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=25542291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T17:45:02+00:00, last15m_closed_end=2026-10-14T17:45+00:00, prior8high=0.055570, depth_time=2026-10-14T17:45:10+00:00, book20_bid_proxy_usdt=132545, book20_ask_proxy_usdt=143603, funding_indicative=-0.000048, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=8257621. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
