# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T05:00:15Z**
- feed_generated_utc: 2026-10-19T05:00:16+00:00
- source_sha256: `561afd4ae175738ff33356589a6fec6c33131296638fe66fb8eec4cd9d192300`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T05:00+00:00, close=82748.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T05:00+00:00, close=82748.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.060000|-2.53|-49.69|-4.51|17703657|1.67|
|BTW_USDT|2.260500|-1.94|34.37|-3.92|22086839|0.89|
|TIA_USDT|0.607600|-1.66|3.21|-3.64|57094479|1.65|
|HBAR_USDT|0.084370|-1.64|-10.03|-3.62|51101798|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.260500|2.217800|2.260400|0.73|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084370|0.083880|0.084370|0.78|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060000|0.059440|0.060000|3.81|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.607600|0.607400|0.607600|1.11|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T04:59:59+00:00, last15m_closed_end=2026-10-19T05:00+00:00, prior8high=2.328900, depth_time=2026-10-19T05:00:09+00:00, book20_bid_proxy_usdt=8128, book20_ask_proxy_usdt=9267, funding_indicative=-0.000052, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=22086839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T04:59:59+00:00, last15m_closed_end=2026-10-19T05:00+00:00, prior8high=0.084590, depth_time=2026-10-19T05:00:14+00:00, book20_bid_proxy_usdt=730186, book20_ask_proxy_usdt=884122, funding_indicative=-0.000037, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=51101798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T04:59:59+00:00, last15m_closed_end=2026-10-19T05:00+00:00, prior8high=0.061120, depth_time=2026-10-19T05:00:06+00:00, book20_bid_proxy_usdt=668994, book20_ask_proxy_usdt=648440, funding_indicative=0.000041, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=17703657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T04:59:59+00:00, last15m_closed_end=2026-10-19T05:00+00:00, prior8high=0.623800, depth_time=2026-10-19T05:00:11+00:00, book20_bid_proxy_usdt=189923, book20_ask_proxy_usdt=423959, funding_indicative=0.000028, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=57094479. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
