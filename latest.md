# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T08:30:17Z**
- feed_generated_utc: 2026-10-14T08:30:19+00:00
- source_sha256: `78a613f3df06b22e24f56dcb287cf368ed01a5cb421c1cbf4e237c0b258ea5cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T08:30+00:00, close=83808.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.082070|-5.59|57.25|-6.07|30484520|1.22|
|TIA_USDT|0.555100|-3.84|16.54|-4.32|39891161|1.80|
|MAGIC_USDT|0.114440|-3.54|67.99|-4.02|5298702|3.50|
|W_USDT|0.016399|-2.40|13.00|-2.88|6753996|0.61|
|SILVER_USDT|58.890000|-0.84|-4.04|-1.32|250300276|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.114440|0.110660|0.114440|1.45|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.890000|58.560000|58.890000|0.54|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.082070|0.080270|0.082070|0.61|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.555100|0.553900|0.555100|1.95|N|Y/Y|Y/N|N|N|
|W_USDT|0.016399|0.015906|0.016399|1.50|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T08:30:02+00:00, last15m_closed_end=2026-10-14T08:30+00:00, prior8high=0.114510, depth_time=2026-10-14T08:30:12+00:00, book20_bid_proxy_usdt=175341, book20_ask_proxy_usdt=175518, funding_indicative=-0.000023, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=5298702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T08:30:02+00:00, last15m_closed_end=2026-10-14T08:30+00:00, prior8high=59.150000, depth_time=2026-10-14T08:30:16+00:00, book20_bid_proxy_usdt=45396014, book20_ask_proxy_usdt=36809864, funding_indicative=0.000066, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=250300276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T08:30:02+00:00, last15m_closed_end=2026-10-14T08:30+00:00, prior8high=0.083840, depth_time=2026-10-14T08:30:06+00:00, book20_bid_proxy_usdt=244034, book20_ask_proxy_usdt=182344, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.59%, turnover=30484520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T08:30:02+00:00, last15m_closed_end=2026-10-14T08:30+00:00, prior8high=0.564000, depth_time=2026-10-14T08:30:08+00:00, book20_bid_proxy_usdt=121958, book20_ask_proxy_usdt=194805, funding_indicative=0.000002, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=39891161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T08:30:02+00:00, last15m_closed_end=2026-10-14T08:30+00:00, prior8high=0.016564, depth_time=2026-10-14T08:30:14+00:00, book20_bid_proxy_usdt=28204, book20_ask_proxy_usdt=49045, funding_indicative=-0.000265, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=6753996. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
