# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T05:45:19Z**
- feed_generated_utc: 2026-10-20T05:45:22+00:00
- source_sha256: `da7d15ce06324f35dc227a93baf789d9f495f22b7e9f138d2d362c9d667622c6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T05:45+00:00, close=81907.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T05:00+00:00, close=82060.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.115369|-8.42|274.68|-8.42|11919120|3.73|
|CT_USDT|0.308920|-6.41|-9.70|-6.41|5428523|5.83|
|SAND_USDT|0.057140|-3.38|-7.97|-3.38|8736590|1.75|
|ZRO_USDT|1.849400|-2.76|-18.20|-2.76|7650216|0.54|
|NEAR_USDT|4.798000|-2.16|-13.53|-2.16|167754089|2.08|
|PUMPFUN_USDT|0.004404|-1.16|-17.04|-1.16|29800019|2.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.308920|0.302430|0.308920|1.01|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.798000|4.788000|4.798000|1.46|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004404|0.004395|0.004404|1.36|N|N/N|N/N|N|N|
|Q_USDT|0.115369|0.113888|0.115276|5.19|N|Y/Y|N/N|N|N|
|SAND_USDT|0.057140|0.056650|0.057140|0.17|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.849400|1.844100|1.849400|0.98|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T05:45:00+00:00, last15m_closed_end=2026-10-20T05:45+00:00, prior8high=0.337010, depth_time=2026-10-20T05:45:07+00:00, book20_bid_proxy_usdt=11421, book20_ask_proxy_usdt=9046, funding_indicative=-0.002591, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=5428523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T05:45:00+00:00, last15m_closed_end=2026-10-20T05:45+00:00, prior8high=4.872000, depth_time=2026-10-20T05:45:16+00:00, book20_bid_proxy_usdt=2172661, book20_ask_proxy_usdt=2989024, funding_indicative=0.000009, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=167754089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T05:45:00+00:00, last15m_closed_end=2026-10-20T05:45+00:00, prior8high=0.004489, depth_time=2026-10-20T05:45:19+00:00, book20_bid_proxy_usdt=927604, book20_ask_proxy_usdt=1651748, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=29800019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T05:45:00+00:00, last15m_closed_end=2026-10-20T05:45+00:00, prior8high=0.133766, depth_time=2026-10-20T05:45:07+00:00, book20_bid_proxy_usdt=21165, book20_ask_proxy_usdt=16253, funding_indicative=-0.000248, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.42%, turnover=11919120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T05:45:00+00:00, last15m_closed_end=2026-10-20T05:45+00:00, prior8high=0.058280, depth_time=2026-10-20T05:45:07+00:00, book20_bid_proxy_usdt=763008, book20_ask_proxy_usdt=917344, funding_indicative=-0.001803, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=8736590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T05:45:00+00:00, last15m_closed_end=2026-10-20T05:45+00:00, prior8high=1.880400, depth_time=2026-10-20T05:45:14+00:00, book20_bid_proxy_usdt=25123, book20_ask_proxy_usdt=59144, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=7650216. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
