# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T04:15:13Z**
- feed_generated_utc: 2026-10-14T04:15:15+00:00
- source_sha256: `ccde689385850cdb962a46858400d450955c41cb811403a2838d50a33d50e562`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T04:15+00:00, close=83685.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083180|-4.31|59.37|-4.66|29863193|1.20|
|W_USDT|0.016150|-3.88|11.28|-4.23|7028134|1.86|
|MAGIC_USDT|0.114560|-3.44|68.17|-3.79|5616304|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.114560|0.114950|0.114580|1.75|Y|Y/Y|Y/N|N|N|
|STRK_USDT|0.083180|0.083200|0.083250|5.62|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016150|0.016170|0.016150|1.00|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T04:15:01+00:00, last15m_closed_end=2026-10-14T04:15+00:00, prior8high=0.118420, depth_time=2026-10-14T04:15:12+00:00, book20_bid_proxy_usdt=173567, book20_ask_proxy_usdt=184650, funding_indicative=-0.000174, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=5616304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T04:15:01+00:00, last15m_closed_end=2026-10-14T04:15+00:00, prior8high=0.085610, depth_time=2026-10-14T04:15:08+00:00, book20_bid_proxy_usdt=178176, book20_ask_proxy_usdt=184128, funding_indicative=0.000043, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=29863193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T04:15:01+00:00, last15m_closed_end=2026-10-14T04:15+00:00, prior8high=0.016787, depth_time=2026-10-14T04:15:10+00:00, book20_bid_proxy_usdt=35706, book20_ask_proxy_usdt=72147, funding_indicative=-0.000193, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=7028134. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
