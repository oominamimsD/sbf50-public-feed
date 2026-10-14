# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T12:15:18Z**
- feed_generated_utc: 2026-10-14T12:15:20+00:00
- source_sha256: `cb7bfa8d90a18b8bc97a88802b77567e73fdce51ea0ad3eda473168a1780431f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T12:15+00:00, close=83798, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.079730|-8.28|52.76|-8.78|27397340|1.25|
|W_USDT|0.015840|-5.73|9.15|-6.23|6250258|1.89|
|TIA_USDT|0.558900|-3.18|17.34|-3.68|33445639|1.79|
|UNI_USDT|7.395000|-2.33|-14.65|-2.83|17549547|1.35|
|SILVER_USDT|58.860000|-0.89|-4.08|-1.39|270650345|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SILVER_USDT|58.860000|58.480000|58.860000|3.72|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.079730|0.077420|0.079660|3.45|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.558900|0.540100|0.558700|1.63|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.395000|7.313000|7.395000|3.18|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015840|0.015756|0.015840|1.26|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- SILVER_USDT: quote_utc=2026-10-14T12:15:01+00:00, last15m_closed_end=2026-10-14T12:15+00:00, prior8high=58.790000, depth_time=2026-10-14T12:15:18+00:00, book20_bid_proxy_usdt=48176427, book20_ask_proxy_usdt=43273513, funding_indicative=0.000097, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=270650345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T12:15:01+00:00, last15m_closed_end=2026-10-14T12:15+00:00, prior8high=0.079950, depth_time=2026-10-14T12:15:07+00:00, book20_bid_proxy_usdt=276291, book20_ask_proxy_usdt=227830, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.28%, turnover=27397340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T12:15:01+00:00, last15m_closed_end=2026-10-14T12:15+00:00, prior8high=0.557400, depth_time=2026-10-14T12:15:12+00:00, book20_bid_proxy_usdt=135008, book20_ask_proxy_usdt=168187, funding_indicative=-0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=33445639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T12:15:01+00:00, last15m_closed_end=2026-10-14T12:15+00:00, prior8high=7.381000, depth_time=2026-10-14T12:15:15+00:00, book20_bid_proxy_usdt=1283191, book20_ask_proxy_usdt=1404687, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=17549547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T12:15:01+00:00, last15m_closed_end=2026-10-14T12:15+00:00, prior8high=0.016220, depth_time=2026-10-14T12:15:10+00:00, book20_bid_proxy_usdt=44237, book20_ask_proxy_usdt=23197, funding_indicative=-0.000221, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.73%, turnover=6250258. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
