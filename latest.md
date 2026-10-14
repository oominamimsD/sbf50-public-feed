# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T05:15:13Z**
- feed_generated_utc: 2026-10-14T05:15:14+00:00
- source_sha256: `0a4bdd6d7b55cdca078876f13decc9187679ec37eb0f3d95cb49444430984ea9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T05:15+00:00, close=83497.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T05:00+00:00, close=83704.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083080|-4.42|59.18|-4.54|29248931|1.20|
|MAGIC_USDT|0.115110|-2.98|68.98|-3.10|5503205|0.87|
|W_USDT|0.016455|-2.07|13.38|-2.19|6945940|3.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.115110|0.113190|0.115090|0.99|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.083080|0.081770|0.083080|4.44|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016455|0.016080|0.016455|3.13|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T05:15:01+00:00, last15m_closed_end=2026-10-14T05:15+00:00, prior8high=0.118420, depth_time=2026-10-14T05:15:10+00:00, book20_bid_proxy_usdt=179633, book20_ask_proxy_usdt=165970, funding_indicative=-0.000137, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=5503205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T05:15:01+00:00, last15m_closed_end=2026-10-14T05:15+00:00, prior8high=0.085530, depth_time=2026-10-14T05:15:06+00:00, book20_bid_proxy_usdt=376571, book20_ask_proxy_usdt=164673, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=29248931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T05:15:01+00:00, last15m_closed_end=2026-10-14T05:15+00:00, prior8high=0.016514, depth_time=2026-10-14T05:15:12+00:00, book20_bid_proxy_usdt=23248, book20_ask_proxy_usdt=25195, funding_indicative=-0.000146, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=6945940. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
