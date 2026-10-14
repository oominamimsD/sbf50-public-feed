# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T02:15:14Z**
- feed_generated_utc: 2026-10-14T02:15:16+00:00
- source_sha256: `b98bc2b78e469fc64e89db55268be95319b505e69f01d68e6c063d9ec56afc8b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T02:15+00:00, close=83310.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T02:00+00:00, close=83281.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|OGN_USDT|0.034180|-2.89|52.52|-2.78|5028984|2.93|
|STRK_USDT|0.084700|-2.56|62.29|-2.45|31182917|1.18|
|MAGIC_USDT|0.115720|-2.46|69.87|-2.35|7340989|1.73|
|W_USDT|0.016588|-1.27|14.30|-1.16|7798655|3.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.115720|0.115510|0.115760|1.52|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034180|0.034090|0.034180|0.82|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.084700|0.084230|0.084730|0.29|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016588|0.016647|0.016598|1.06|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T02:15:02+00:00, last15m_closed_end=2026-10-14T02:15+00:00, prior8high=0.123370, depth_time=2026-10-14T02:15:11+00:00, book20_bid_proxy_usdt=169835, book20_ask_proxy_usdt=168358, funding_indicative=-0.000075, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=7340989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T02:15:02+00:00, last15m_closed_end=2026-10-14T02:15+00:00, prior8high=0.035070, depth_time=2026-10-14T02:15:07+00:00, book20_bid_proxy_usdt=176591, book20_ask_proxy_usdt=138423, funding_indicative=-0.000154, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=5028984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T02:15:02+00:00, last15m_closed_end=2026-10-14T02:15+00:00, prior8high=0.086530, depth_time=2026-10-14T02:15:05+00:00, book20_bid_proxy_usdt=137253, book20_ask_proxy_usdt=323068, funding_indicative=0.000012, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=31182917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T02:15:02+00:00, last15m_closed_end=2026-10-14T02:15+00:00, prior8high=0.017269, depth_time=2026-10-14T02:15:12+00:00, book20_bid_proxy_usdt=25247, book20_ask_proxy_usdt=25120, funding_indicative=-0.000416, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=7798655. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
