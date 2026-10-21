# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T16:00:12Z**
- feed_generated_utc: 2026-10-21T16:00:14+00:00
- source_sha256: `8652775255bb37d4c9c1832bdd5ee6187e698f2c75c5e7be660e0a64486d54fd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.188500|-3.08|72.30|-3.10|5720074|5.31|
|DOOD_USDT|0.002787|-2.00|96.54|-2.02|8547079|7.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOOD_USDT|0.002787|0.003081|0.002844|2.28|Y|Y/N|N/N|N|N|
|ICNT_USDT|0.188500|0.190500|0.188500|1.05|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOOD_USDT: quote_utc=2026-10-21T16:00:03+00:00, last15m_closed_end=2026-10-21T16:00+00:00, prior8high=0.004950, depth_time=2026-10-21T16:00:11+00:00, book20_bid_proxy_usdt=127315, book20_ask_proxy_usdt=90265, funding_indicative=-0.020000, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=8547079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-21T16:00:03+00:00, last15m_closed_end=2026-10-21T16:00+00:00, prior8high=0.201600, depth_time=2026-10-21T16:00:08+00:00, book20_bid_proxy_usdt=146934, book20_ask_proxy_usdt=111761, funding_indicative=-0.000193, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=5720074. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
