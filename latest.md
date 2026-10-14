# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T08:15:18Z**
- feed_generated_utc: 2026-10-14T08:15:20+00:00
- source_sha256: `e97e291002f9b3dda83f361ced456f2dbb8d6508eb8861705d46d77174b25d19`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T08:15+00:00, close=83886.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.082550|-5.03|58.17|-5.63|30349377|1.21|
|MAGIC_USDT|0.113990|-3.92|67.33|-4.52|5264311|2.63|
|TIA_USDT|0.559600|-3.06|17.48|-3.66|39623882|1.79|
|W_USDT|0.016500|-1.80|13.69|-2.40|6691728|3.03|
|SILVER_USDT|58.900000|-0.82|-4.02|-1.42|249506284|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.113990|0.110660|0.113990|1.76|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.900000|58.510000|58.900000|1.26|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.082550|0.080270|0.082550|0.81|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.559600|0.551300|0.559400|2.16|N|Y/Y|Y/N|N|N|
|W_USDT|0.016500|0.015869|0.016500|0.42|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T08:14:59+00:00, last15m_closed_end=2026-10-14T08:15+00:00, prior8high=0.114360, depth_time=2026-10-14T08:15:10+00:00, book20_bid_proxy_usdt=180371, book20_ask_proxy_usdt=173202, funding_indicative=-0.000013, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=5264311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T08:14:59+00:00, last15m_closed_end=2026-10-14T08:15+00:00, prior8high=59.160000, depth_time=2026-10-14T08:15:15+00:00, book20_bid_proxy_usdt=42833334, book20_ask_proxy_usdt=46298595, funding_indicative=0.000069, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=249506284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T08:14:59+00:00, last15m_closed_end=2026-10-14T08:15+00:00, prior8high=0.083840, depth_time=2026-10-14T08:15:08+00:00, book20_bid_proxy_usdt=226497, book20_ask_proxy_usdt=128176, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=30349377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T08:14:59+00:00, last15m_closed_end=2026-10-14T08:15+00:00, prior8high=0.560600, depth_time=2026-10-14T08:15:13+00:00, book20_bid_proxy_usdt=171507, book20_ask_proxy_usdt=177619, funding_indicative=0.000012, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=39623882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T08:14:59+00:00, last15m_closed_end=2026-10-14T08:15+00:00, prior8high=0.016564, depth_time=2026-10-14T08:15:14+00:00, book20_bid_proxy_usdt=34569, book20_ask_proxy_usdt=30229, funding_indicative=-0.000253, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=6691728. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
