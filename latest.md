# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T03:15:15Z**
- feed_generated_utc: 2026-10-14T03:15:16+00:00
- source_sha256: `49f449c042d8843a1be4e3a3c8f9dce8e7051d9c762fa137989f534f7c67ba9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T03:15+00:00, close=83681.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T03:00+00:00, close=83609.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083990|-3.38|60.93|-3.72|30039839|1.19|
|OGN_USDT|0.034350|-2.41|53.27|-2.75|5029820|2.91|
|W_USDT|0.016496|-1.82|13.67|-2.16|7185758|3.03|
|MAGIC_USDT|0.116720|-1.62|71.34|-1.96|6040812|0.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.116720|0.115000|0.116720|2.03|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034350|0.033730|0.034360|1.11|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.083990|0.084040|0.083990|0.91|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016496|0.016378|0.016483|0.22|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T03:15:01+00:00, last15m_closed_end=2026-10-14T03:15+00:00, prior8high=0.122210, depth_time=2026-10-14T03:15:14+00:00, book20_bid_proxy_usdt=181159, book20_ask_proxy_usdt=166820, funding_indicative=-0.000140, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=6040812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T03:15:00+00:00, last15m_closed_end=2026-10-14T03:15+00:00, prior8high=0.034830, depth_time=2026-10-14T03:15:10+00:00, book20_bid_proxy_usdt=163391, book20_ask_proxy_usdt=103525, funding_indicative=-0.000226, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=5029820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T03:15:00+00:00, last15m_closed_end=2026-10-14T03:15+00:00, prior8high=0.086310, depth_time=2026-10-14T03:15:07+00:00, book20_bid_proxy_usdt=145972, book20_ask_proxy_usdt=207059, funding_indicative=0.000012, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=30039839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T03:15:00+00:00, last15m_closed_end=2026-10-14T03:15+00:00, prior8high=0.017059, depth_time=2026-10-14T03:15:08+00:00, book20_bid_proxy_usdt=19396, book20_ask_proxy_usdt=42122, funding_indicative=-0.000285, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=7185758. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
