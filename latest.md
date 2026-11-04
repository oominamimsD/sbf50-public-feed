# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T13:00:16Z**
- feed_generated_utc: 2026-11-04T13:00:17+00:00
- source_sha256: `46a849c91b41d0a4b1bde34522731dc69996e8b3c4ef2aeff2ebb04f31325c78`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1185; contracts: 1177; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T13:00+00:00, close=78272, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T13:00+00:00, close=78272, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032900|-36.84|-30.76|-37.61|9412944|3.04|
|AKE_USDT|0.002918|-28.98|-86.18|-29.75|13920743|3.43|
|TRUMPOFFICIAL_USDT|1.418000|-11.70|-15.99|-12.47|12001698|7.05|
|HOT_USDT|0.000481|-10.73|39.14|-11.50|5927239|6.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032900|0.032170|0.032900|0.64|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002918|0.002804|0.002917|3.29|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000481|0.000484|0.000480|1.27|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.418000|1.431000|1.418000|4.15|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T13:00:00+00:00, last15m_closed_end=2026-11-04T13:00+00:00, prior8high=0.033970, depth_time=2026-11-04T13:00:05+00:00, book20_bid_proxy_usdt=27092, book20_ask_proxy_usdt=38952, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-36.84%, turnover=9412944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T13:00:00+00:00, last15m_closed_end=2026-11-04T13:00+00:00, prior8high=0.003257, depth_time=2026-11-04T13:00:10+00:00, book20_bid_proxy_usdt=119792, book20_ask_proxy_usdt=35375, funding_indicative=0.000037, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-28.98%, turnover=13920743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T13:00:00+00:00, last15m_closed_end=2026-11-04T13:00+00:00, prior8high=0.000521, depth_time=2026-11-04T13:00:14+00:00, book20_bid_proxy_usdt=101323, book20_ask_proxy_usdt=103798, funding_indicative=-0.000124, next_funding_utc=2026-11-04T14:00:00+00:00, funding_cycle_h=1, 24h_change=-10.73%, turnover=5927239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T13:00:01+00:00, last15m_closed_end=2026-11-04T13:00+00:00, prior8high=1.490000, depth_time=2026-11-04T13:00:12+00:00, book20_bid_proxy_usdt=2125407, book20_ask_proxy_usdt=2919744, funding_indicative=-0.000349, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.70%, turnover=12001698. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
