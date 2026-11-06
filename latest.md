# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T19:00:12Z**
- feed_generated_utc: 2026-11-06T19:00:13+00:00
- source_sha256: `ed3768f0563741af945b2c4c398eb71c9cbb97c5b89efecf1a1a966825e3ab54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T19:00+00:00, close=75764.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T19:00+00:00, close=75764.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.114500|-39.73|-56.89|-39.65|28811734|8.73|
|ANTHROPIC_USDT|1355.010000|-5.32|-19.17|-5.24|6505230|0.07|
|LIT_USDT|3.306800|-2.52|17.08|-2.44|12927076|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1355.010000|1326.270000|1354.730000|0.83|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.306800|3.314000|3.306100|1.89|Y|Y/Y|N/N|Y|N|
|UAI_USDT|0.114500|0.147000|0.113000|4.10|Y|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T18:59:59+00:00, last15m_closed_end=2026-11-06T19:00+00:00, prior8high=1398.960000, depth_time=2026-11-06T19:00:08+00:00, book20_bid_proxy_usdt=14480, book20_ask_proxy_usdt=35244, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=6505230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T18:59:59+00:00, last15m_closed_end=2026-11-06T19:00+00:00, prior8high=3.455000, depth_time=2026-11-06T19:00:11+00:00, book20_bid_proxy_usdt=35355, book20_ask_proxy_usdt=37866, funding_indicative=0.000048, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=12927076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T18:59:59+00:00, last15m_closed_end=2026-11-06T19:00+00:00, prior8high=0.249200, depth_time=2026-11-06T19:00:06+00:00, book20_bid_proxy_usdt=108043, book20_ask_proxy_usdt=154225, funding_indicative=0.000099, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-39.73%, turnover=28811734. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
