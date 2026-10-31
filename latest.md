# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T20:30:22Z**
- feed_generated_utc: 2026-10-31T20:30:24+00:00
- source_sha256: `83e9ee9424187529564310edef1f5c56dee660a0006a7fb94d4e1839c45b551a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T20:30+00:00, close=77544.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244860|-17.32|45.81|-17.30|26940667|0.41|
|INJ_USDT|7.227000|-3.45|-3.81|-3.43|22504634|1.38|
|TRX_USDT|0.305510|-2.18|-7.12|-2.16|8805451|0.98|
|WLD_USDT|0.396400|-1.97|-14.19|-1.95|35682128|2.52|
|FET_USDT|0.160200|-1.89|-7.02|-1.87|5334349|6.24|
|DOT_USDT|0.948000|-1.14|-8.76|-1.12|5664570|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.948000|0.947500|0.948000|1.35|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160200|0.160400|0.160200|1.46|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.227000|7.214000|7.227000|0.42|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.244860|0.237770|0.245110|1.22|N|Y/N|N/N|Y|N|
|TRX_USDT|0.305510|0.305290|0.305510|0.57|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396400|0.395800|0.396400|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-31T20:30:01+00:00, last15m_closed_end=2026-10-31T20:30+00:00, prior8high=0.956800, depth_time=2026-10-31T20:30:20+00:00, book20_bid_proxy_usdt=447756, book20_ask_proxy_usdt=563834, funding_indicative=0.000074, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=5664570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T20:30:01+00:00, last15m_closed_end=2026-10-31T20:30+00:00, prior8high=0.162200, depth_time=2026-10-31T20:30:19+00:00, book20_bid_proxy_usdt=1336933, book20_ask_proxy_usdt=1117416, funding_indicative=-0.000153, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=5334349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T20:30:01+00:00, last15m_closed_end=2026-10-31T20:30+00:00, prior8high=7.427000, depth_time=2026-10-31T20:30:11+00:00, book20_bid_proxy_usdt=491267, book20_ask_proxy_usdt=338000, funding_indicative=0.000205, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=22504634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T20:30:01+00:00, last15m_closed_end=2026-10-31T20:30+00:00, prior8high=0.284740, depth_time=2026-10-31T20:30:08+00:00, book20_bid_proxy_usdt=4584, book20_ask_proxy_usdt=10455, funding_indicative=-0.000685, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.32%, turnover=26940667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T20:30:01+00:00, last15m_closed_end=2026-10-31T20:30+00:00, prior8high=0.310250, depth_time=2026-10-31T20:30:13+00:00, book20_bid_proxy_usdt=181499, book20_ask_proxy_usdt=61883, funding_indicative=-0.000369, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=8805451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T20:30:01+00:00, last15m_closed_end=2026-10-31T20:30+00:00, prior8high=0.400400, depth_time=2026-10-31T20:30:15+00:00, book20_bid_proxy_usdt=3008581, book20_ask_proxy_usdt=2506627, funding_indicative=-0.000025, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=35682128. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
