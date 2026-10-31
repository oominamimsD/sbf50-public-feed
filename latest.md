# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T21:30:27Z**
- feed_generated_utc: 2026-10-31T21:30:28+00:00
- source_sha256: `71077cc52bee6aa9bf5ea87ef7eeb41b8002395736fe06b7ee6c6826500e1515`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T21:30+00:00, close=77477.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T21:00+00:00, close=77523.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.243330|-17.83|44.90|-17.73|27384517|2.46|
|BLESS_USDT|0.009526|-9.82|17.41|-9.72|8068727|5.25|
|INJ_USDT|7.232000|-3.39|-3.75|-3.29|22081266|1.38|
|TRX_USDT|0.302790|-3.05|-7.94|-2.95|9532429|0.33|
|ENA_USDT|0.188670|-2.75|1.00|-2.65|47882146|0.53|
|IDOL_USDT|0.017062|-2.61|115.97|-2.51|7075178|0.59|
|WLD_USDT|0.397600|-1.68|-13.93|-1.58|34284426|2.52|
|FET_USDT|0.160600|-1.65|-6.79|-1.55|5748899|6.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009526|0.009313|0.009526|0.89|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188670|0.187500|0.188670|0.73|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160600|0.159500|0.160600|0.94|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.017062|0.016323|0.017031|1.77|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.232000|7.202000|7.234000|0.67|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.243330|0.237140|0.243000|0.34|N|Y/N|N/N|Y|N|
|TRX_USDT|0.302790|0.302520|0.302790|1.31|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397600|0.394900|0.397600|0.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-31T21:30:02+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.010395, depth_time=2026-10-31T21:30:10+00:00, book20_bid_proxy_usdt=15349, book20_ask_proxy_usdt=11071, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.82%, turnover=8068727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T21:30:01+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.191110, depth_time=2026-10-31T21:30:18+00:00, book20_bid_proxy_usdt=173759, book20_ask_proxy_usdt=115886, funding_indicative=-0.000005, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=47882146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T21:30:02+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.161600, depth_time=2026-10-31T21:30:25+00:00, book20_bid_proxy_usdt=1250508, book20_ask_proxy_usdt=779603, funding_indicative=-0.000169, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=5748899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T21:30:01+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.018263, depth_time=2026-10-31T21:30:21+00:00, book20_bid_proxy_usdt=8835, book20_ask_proxy_usdt=6738, funding_indicative=0.000108, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=7075178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T21:30:02+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=7.327000, depth_time=2026-10-31T21:30:11+00:00, book20_bid_proxy_usdt=333536, book20_ask_proxy_usdt=302522, funding_indicative=0.000188, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=22081266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T21:30:02+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.281310, depth_time=2026-10-31T21:30:08+00:00, book20_bid_proxy_usdt=10720, book20_ask_proxy_usdt=9295, funding_indicative=-0.000910, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.83%, turnover=27384517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T21:30:02+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.308070, depth_time=2026-10-31T21:30:16+00:00, book20_bid_proxy_usdt=310088, book20_ask_proxy_usdt=192152, funding_indicative=-0.000562, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=9532429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T21:30:02+00:00, last15m_closed_end=2026-10-31T21:30+00:00, prior8high=0.398700, depth_time=2026-10-31T21:30:22+00:00, book20_bid_proxy_usdt=2532884, book20_ask_proxy_usdt=3539207, funding_indicative=0.000081, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=34284426. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
