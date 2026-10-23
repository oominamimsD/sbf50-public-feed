# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T10:15:27Z**
- feed_generated_utc: 2026-10-23T10:15:29+00:00
- source_sha256: `b8ff4c5f63f9e923a03462345f34bbaa4ce2e40f77ffa943727dae60b40580bb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T10:15+00:00, close=81780, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T10:00+00:00, close=81630.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004092|-11.19|106.14|-11.35|7749545|7.33|
|LIT_USDT|3.387600|-6.26|9.58|-6.42|9225187|0.29|
|STRK_USDT|0.051750|-4.80|-46.29|-4.96|11788022|1.93|
|QNT_USDT|183.290000|-3.89|-11.84|-4.05|49597031|2.73|
|TIA_USDT|0.552000|-2.88|-8.38|-3.04|25081625|1.81|
|SILVER_USDT|54.010000|-2.26|-5.47|-2.42|332136840|1.85|
|PUMPFUN_USDT|0.004590|-1.90|1.41|-2.06|35650914|2.18|
|OP_USDT|0.118260|-1.32|-14.84|-1.48|6195778|1.69|
|HBAR_USDT|0.079410|-0.87|-4.95|-1.03|19929055|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|HBAR_USDT|0.079410|0.079040|0.079430|2.57|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004092|0.004082|0.004092|1.48|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.387600|3.369300|3.387600|1.47|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.118260|0.117700|0.118260|0.84|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004590|0.004556|0.004590|2.50|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|183.290000|183.630000|183.290000|3.28|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|54.010000|53.870000|54.010000|0.40|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051750|0.051520|0.051750|0.16|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.552000|0.548100|0.552100|0.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- HBAR_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=0.080330, depth_time=2026-10-23T10:15:26+00:00, book20_bid_proxy_usdt=652663, book20_ask_proxy_usdt=1179477, funding_indicative=0.000041, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.87%, turnover=19929055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T10:15:01+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=0.004279, depth_time=2026-10-23T10:15:08+00:00, book20_bid_proxy_usdt=45208, book20_ask_proxy_usdt=67957, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.19%, turnover=7749545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=3.438600, depth_time=2026-10-23T10:15:10+00:00, book20_bid_proxy_usdt=22235, book20_ask_proxy_usdt=27548, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.26%, turnover=9225187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=0.120000, depth_time=2026-10-23T10:15:24+00:00, book20_bid_proxy_usdt=85124, book20_ask_proxy_usdt=93612, funding_indicative=0.000010, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=6195778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=0.004660, depth_time=2026-10-23T10:15:21+00:00, book20_bid_proxy_usdt=1685028, book20_ask_proxy_usdt=2488225, funding_indicative=0.000005, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=35650914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=189.100000, depth_time=2026-10-23T10:15:14+00:00, book20_bid_proxy_usdt=72541, book20_ask_proxy_usdt=99981, funding_indicative=-0.000168, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=49597031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T10:15:01+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=54.210000, depth_time=2026-10-23T10:15:12+00:00, book20_bid_proxy_usdt=38296975, book20_ask_proxy_usdt=32942336, funding_indicative=0.000073, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=332136840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=0.053160, depth_time=2026-10-23T10:15:11+00:00, book20_bid_proxy_usdt=657658, book20_ask_proxy_usdt=657530, funding_indicative=0.000029, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=11788022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T10:15:02+00:00, last15m_closed_end=2026-10-23T10:15+00:00, prior8high=0.556900, depth_time=2026-10-23T10:15:16+00:00, book20_bid_proxy_usdt=436031, book20_ask_proxy_usdt=433326, funding_indicative=0.000009, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=25081625. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
