# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T16:45:14Z**
- feed_generated_utc: 2026-10-31T16:45:15+00:00
- source_sha256: `9f6332738dcae227adf7ccf1931f954fd5aaf47730f39189b670ac37742c67bc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T16:45+00:00, close=77549.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.098000|-2.13|-36.94|-2.12|7808567|1.82|
|Q_USDT|0.031440|-1.99|-60.16|-1.98|11127463|3.18|
|AKE_USDT|0.010973|-1.48|-62.45|-1.47|12433063|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010973|0.010824|0.010973|0.43|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.098000|1.110000|1.098000|1.38|Y|Y/Y|Y/Y|Y|Y|
|Q_USDT|0.031440|0.030480|0.031440|1.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T16:45:02+00:00, last15m_closed_end=2026-10-31T16:45+00:00, prior8high=0.011362, depth_time=2026-10-31T16:45:12+00:00, book20_bid_proxy_usdt=9313, book20_ask_proxy_usdt=16511, funding_indicative=0.000050, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=12433063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T16:45:02+00:00, last15m_closed_end=2026-10-31T16:45+00:00, prior8high=1.152900, depth_time=2026-10-31T16:45:07+00:00, book20_bid_proxy_usdt=22807, book20_ask_proxy_usdt=11422, funding_indicative=-0.000203, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=7808567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T16:45:02+00:00, last15m_closed_end=2026-10-31T16:45+00:00, prior8high=0.033470, depth_time=2026-10-31T16:45:10+00:00, book20_bid_proxy_usdt=73784, book20_ask_proxy_usdt=42618, funding_indicative=-0.000544, next_funding_utc=2026-10-31T17:00:00+00:00, funding_cycle_h=1, 24h_change=-1.99%, turnover=11127463. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
