# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T22:45:15Z**
- feed_generated_utc: 2026-10-18T22:45:16+00:00
- source_sha256: `73ffed56ca4ae29e59f039d20f2bff13c52b73faf913c909193bdae6c92fb16b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T22:45+00:00, close=81771.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T22:00+00:00, close=81181.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.062623|-7.26|254.10|-8.04|10155434|1.44|
|STRK_USDT|0.059670|-3.07|-49.97|-3.85|15898949|3.35|
|SAND_USDT|0.057820|-1.59|-12.97|-2.37|34500058|1.73|
|TIA_USDT|0.608600|-1.50|3.38|-2.28|52395209|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062623|0.061280|0.062623|0.67|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.057820|0.056220|0.057820|1.25|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059670|0.058420|0.059670|0.29|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.608600|0.586400|0.608700|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T22:45:01+00:00, last15m_closed_end=2026-10-18T22:45+00:00, prior8high=0.065893, depth_time=2026-10-18T22:45:06+00:00, book20_bid_proxy_usdt=2535, book20_ask_proxy_usdt=5753, funding_indicative=0.000254, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.26%, turnover=10155434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T22:45:01+00:00, last15m_closed_end=2026-10-18T22:45+00:00, prior8high=0.058220, depth_time=2026-10-18T22:45:11+00:00, book20_bid_proxy_usdt=762937, book20_ask_proxy_usdt=675042, funding_indicative=-0.002312, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=34500058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T22:45:01+00:00, last15m_closed_end=2026-10-18T22:45+00:00, prior8high=0.061020, depth_time=2026-10-18T22:45:09+00:00, book20_bid_proxy_usdt=454409, book20_ask_proxy_usdt=378626, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=15898949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T22:45:01+00:00, last15m_closed_end=2026-10-18T22:45+00:00, prior8high=0.605800, depth_time=2026-10-18T22:45:14+00:00, book20_bid_proxy_usdt=189450, book20_ask_proxy_usdt=165157, funding_indicative=0.000023, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=52395209. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
