# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T20:00:13Z**
- feed_generated_utc: 2026-10-31T20:00:15+00:00
- source_sha256: `1655181b96ffe947f70684802cae4d6cb30cf4f24f3dddc3376fc114178cda9c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.243340|-17.83|44.91|-17.81|26276215|0.41|
|WLD_USDT|0.396400|-1.97|-14.19|-1.95|36939035|2.52|
|TRX_USDT|0.306340|-1.91|-6.86|-1.89|8758021|1.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LSK_USDT|0.243340|0.257860|0.243340|2.28|Y|Y/N|N/N|Y|N|
|TRX_USDT|0.306340|0.305290|0.306340|0.92|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396400|0.396500|0.396400|0.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LSK_USDT: quote_utc=2026-10-31T19:59:59+00:00, last15m_closed_end=2026-10-31T20:00+00:00, prior8high=0.284740, depth_time=2026-10-31T20:00:08+00:00, book20_bid_proxy_usdt=11836, book20_ask_proxy_usdt=7446, funding_indicative=-0.000865, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.83%, turnover=26276215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T19:59:59+00:00, last15m_closed_end=2026-10-31T20:00+00:00, prior8high=0.310250, depth_time=2026-10-31T20:00:12+00:00, book20_bid_proxy_usdt=121787, book20_ask_proxy_usdt=79784, funding_indicative=-0.000376, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=8758021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T19:59:59+00:00, last15m_closed_end=2026-10-31T20:00+00:00, prior8high=0.400400, depth_time=2026-10-31T20:00:07+00:00, book20_bid_proxy_usdt=3252102, book20_ask_proxy_usdt=3204816, funding_indicative=-0.000060, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=36939035. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
