# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T15:45:25Z**
- feed_generated_utc: 2026-10-20T15:45:27+00:00
- source_sha256: `c07b6c34275fa986292e801cfa87f6807ee68527fad553591cb456da5f233117`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T15:45+00:00, close=82450.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T15:00+00:00, close=83242.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.065178|-25.11|291.17|-25.75|8301822|0.15|
|ARB_USDT|0.187910|-3.94|-0.29|-4.58|106831970|0.53|
|STRK_USDT|0.055150|-2.52|-39.17|-3.16|18874786|3.63|
|Q_USDT|0.123123|-2.27|299.86|-2.91|7096635|1.79|
|NEAR_USDT|4.803000|-2.05|-13.44|-2.69|191019436|2.08|
|QNT_USDT|194.060000|-0.83|-15.02|-1.47|76336103|1.55|
|UNI_USDT|7.232000|-0.76|-2.50|-1.40|12857390|1.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.065178|0.063039|0.065178|0.76|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.187910|0.187280|0.187910|2.61|N|N/Y|Y/N|Y|N|
|NEAR_USDT|4.803000|4.665000|4.803000|1.26|N|N/N|Y/Y|Y|N|
|QNT_USDT|194.060000|191.320000|194.350000|1.61|N|N/N|Y/Y|Y|N|
|Q_USDT|0.123123|0.119102|0.123123|0.82|N|N/N|N/N|Y|N|
|STRK_USDT|0.055150|0.054770|0.055190|2.54|N|N/N|Y/Y|Y|N|
|UNI_USDT|7.232000|7.125000|7.235000|2.49|N|N/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=0.067629, depth_time=2026-10-20T15:45:07+00:00, book20_bid_proxy_usdt=5885, book20_ask_proxy_usdt=7089, funding_indicative=0.000055, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.11%, turnover=8301822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=0.198770, depth_time=2026-10-20T15:45:11+00:00, book20_bid_proxy_usdt=97222, book20_ask_proxy_usdt=46657, funding_indicative=-0.000031, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=106831970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=5.094000, depth_time=2026-10-20T15:45:18+00:00, book20_bid_proxy_usdt=1902388, book20_ask_proxy_usdt=188147, funding_indicative=0.000046, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=191019436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=202.750000, depth_time=2026-10-20T15:45:21+00:00, book20_bid_proxy_usdt=65136, book20_ask_proxy_usdt=70397, funding_indicative=0.000029, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=76336103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=0.131229, depth_time=2026-10-20T15:45:16+00:00, book20_bid_proxy_usdt=20111, book20_ask_proxy_usdt=15370, funding_indicative=-0.000017, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=7096635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=0.059770, depth_time=2026-10-20T15:45:13+00:00, book20_bid_proxy_usdt=471903, book20_ask_proxy_usdt=580923, funding_indicative=-0.000006, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=18874786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T15:45:00+00:00, last15m_closed_end=2026-10-20T15:45+00:00, prior8high=7.570000, depth_time=2026-10-20T15:45:24+00:00, book20_bid_proxy_usdt=1344415, book20_ask_proxy_usdt=1372711, funding_indicative=-0.000002, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=12857390. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
