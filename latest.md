# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T20:45:25Z**
- feed_generated_utc: 2026-10-31T20:45:27+00:00
- source_sha256: `6b6803c29de3c2280e51a7fe346fb7e1db90f7f957875b2b05f271ff07e0ac47`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T20:45+00:00, close=77536.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244920|-17.30|45.85|-17.27|27122047|1.63|
|INJ_USDT|7.225000|-3.48|-3.84|-3.45|22724387|1.38|
|TRX_USDT|0.305620|-2.14|-7.08|-2.11|9039980|0.33|
|WLD_USDT|0.396400|-1.97|-14.19|-1.94|35829413|2.52|
|FET_USDT|0.160400|-1.77|-6.90|-1.74|5452178|6.23|
|APT_USDT|0.631300|-1.48|-10.05|-1.45|5049306|1.58|
|ONDO_USDT|0.407600|-1.16|1.54|-1.13|25386246|2.45|
|DOT_USDT|0.948000|-1.14|-8.76|-1.11|5702532|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.631300|0.631800|0.631400|2.55|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.948000|0.947300|0.948000|0.95|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160400|0.160200|0.160400|2.11|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.225000|7.214000|7.225000|0.63|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.244920|0.237140|0.244910|0.60|N|Y/N|N/N|Y|N|
|ONDO_USDT|0.407600|0.407900|0.407600|0.87|N|Y/N|N/N|Y|N|
|TRX_USDT|0.305620|0.305250|0.305620|2.85|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396400|0.395800|0.396400|0.45|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-31T20:45:01+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.637400, depth_time=2026-10-31T20:45:18+00:00, book20_bid_proxy_usdt=138018, book20_ask_proxy_usdt=134107, funding_indicative=0.000060, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=5049306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-31T20:45:01+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.956800, depth_time=2026-10-31T20:45:23+00:00, book20_bid_proxy_usdt=649679, book20_ask_proxy_usdt=505738, funding_indicative=0.000081, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=5702532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T20:45:01+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.162200, depth_time=2026-10-31T20:45:15+00:00, book20_bid_proxy_usdt=1303966, book20_ask_proxy_usdt=892739, funding_indicative=-0.000143, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=5452178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T20:45:00+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=7.425000, depth_time=2026-10-31T20:45:09+00:00, book20_bid_proxy_usdt=400854, book20_ask_proxy_usdt=412331, funding_indicative=0.000204, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=22724387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T20:45:00+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.284740, depth_time=2026-10-31T20:45:07+00:00, book20_bid_proxy_usdt=10586, book20_ask_proxy_usdt=3221, funding_indicative=-0.000741, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.30%, turnover=27122047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-31T20:45:00+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.411600, depth_time=2026-10-31T20:45:20+00:00, book20_bid_proxy_usdt=1799154, book20_ask_proxy_usdt=1937335, funding_indicative=0.000030, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=25386246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T20:45:01+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.310250, depth_time=2026-10-31T20:45:12+00:00, book20_bid_proxy_usdt=63221, book20_ask_proxy_usdt=78745, funding_indicative=-0.000422, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=9039980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T20:45:00+00:00, last15m_closed_end=2026-10-31T20:45+00:00, prior8high=0.400400, depth_time=2026-10-31T20:45:12+00:00, book20_bid_proxy_usdt=2685145, book20_ask_proxy_usdt=3396472, funding_indicative=-0.000002, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=35829413. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
