# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T04:45:16Z**
- feed_generated_utc: 2026-10-19T04:45:17+00:00
- source_sha256: `0c2be6531b2bb8438881d404e738c346f0f2be73bdf816e11c94ee22911f7b2d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T04:45+00:00, close=82748.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.261300|-1.91|34.42|-3.89|21989543|1.77|
|STRK_USDT|0.060400|-1.88|-49.35|-3.86|17332056|1.66|
|HBAR_USDT|0.084410|-1.59|-9.99|-3.57|50978230|1.19|
|TIA_USDT|0.610000|-1.27|3.61|-3.25|56657169|3.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.261300|2.217800|2.258400|1.18|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084410|0.083810|0.084410|0.37|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060400|0.059440|0.060400|1.43|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.610000|0.607400|0.610000|0.38|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T04:45:02+00:00, last15m_closed_end=2026-10-19T04:45+00:00, prior8high=2.328900, depth_time=2026-10-19T04:45:06+00:00, book20_bid_proxy_usdt=10656, book20_ask_proxy_usdt=13164, funding_indicative=-0.000084, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=21989543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T04:45:02+00:00, last15m_closed_end=2026-10-19T04:45+00:00, prior8high=0.084590, depth_time=2026-10-19T04:45:11+00:00, book20_bid_proxy_usdt=973896, book20_ask_proxy_usdt=690238, funding_indicative=-0.000037, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=50978230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T04:45:02+00:00, last15m_closed_end=2026-10-19T04:45+00:00, prior8high=0.061260, depth_time=2026-10-19T04:45:09+00:00, book20_bid_proxy_usdt=892333, book20_ask_proxy_usdt=640994, funding_indicative=0.000038, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=17332056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T04:45:02+00:00, last15m_closed_end=2026-10-19T04:45+00:00, prior8high=0.623800, depth_time=2026-10-19T04:45:14+00:00, book20_bid_proxy_usdt=297963, book20_ask_proxy_usdt=236317, funding_indicative=0.000025, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=56657169. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
