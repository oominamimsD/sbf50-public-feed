# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T04:45:13Z**
- feed_generated_utc: 2026-10-14T04:45:14+00:00
- source_sha256: `af1e10756a857d38b7d18d0e91bf0f6b1aa857b8926ee3145b0d59690d1494bb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T04:45+00:00, close=83695.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083740|-3.66|60.45|-4.02|30184585|1.19|
|MAGIC_USDT|0.115280|-2.84|69.23|-3.20|5667434|2.60|
|W_USDT|0.016342|-2.74|12.61|-3.10|7116311|2.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.115280|0.113190|0.115280|0.91|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.083740|0.081770|0.083790|0.91|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016342|0.016080|0.016275|1.33|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T04:45:02+00:00, last15m_closed_end=2026-10-14T04:45+00:00, prior8high=0.118420, depth_time=2026-10-14T04:45:09+00:00, book20_bid_proxy_usdt=178190, book20_ask_proxy_usdt=191964, funding_indicative=-0.000166, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=5667434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T04:45:02+00:00, last15m_closed_end=2026-10-14T04:45+00:00, prior8high=0.085080, depth_time=2026-10-14T04:45:07+00:00, book20_bid_proxy_usdt=169235, book20_ask_proxy_usdt=163626, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=30184585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T04:45:02+00:00, last15m_closed_end=2026-10-14T04:45+00:00, prior8high=0.016637, depth_time=2026-10-14T04:45:11+00:00, book20_bid_proxy_usdt=27362, book20_ask_proxy_usdt=20500, funding_indicative=-0.000170, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=7116311. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
