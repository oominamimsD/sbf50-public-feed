# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T16:45:22Z**
- feed_generated_utc: 2026-11-03T16:45:23+00:00
- source_sha256: `aa423380c576ae92ba8aedec2dec0ccad6b53f836d67aed5ed8b8d674d4a0ea0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T16:45+00:00, close=77450, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.090280|-4.76|-0.88|-4.49|8675408|5.54|
|AKE_USDT|0.004025|-3.15|-80.94|-2.88|12970909|2.48|
|NEAR_USDT|3.799000|-1.55|-16.72|-1.28|83129537|2.63|
|TRUMPOFFICIAL_USDT|1.586000|-1.36|-6.04|-1.09|7575362|6.30|
|WLD_USDT|0.367100|-1.34|-15.80|-1.07|47674316|2.73|
|QNT_USDT|192.830000|-1.32|-2.55|-1.05|57531219|6.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004025|0.003956|0.004022|1.36|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.090280|0.091120|0.090130|2.46|Y|Y/Y|Y/N|N|N|
|NEAR_USDT|3.799000|3.800000|3.802000|0.61|N|Y/Y|Y/Y|N|N|
|QNT_USDT|192.830000|193.330000|192.870000|3.20|Y|Y/Y|Y/Y|N|Y|
|TRUMPOFFICIAL_USDT|1.586000|1.586000|1.586000|0.65|N|N/N|Y/Y|N|N|
|WLD_USDT|0.367100|0.366300|0.367100|0.72|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T16:45:00+00:00, last15m_closed_end=2026-11-03T16:45+00:00, prior8high=0.004218, depth_time=2026-11-03T16:45:10+00:00, book20_bid_proxy_usdt=47740, book20_ask_proxy_usdt=41755, funding_indicative=-0.000253, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=12970909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T16:45:00+00:00, last15m_closed_end=2026-11-03T16:45+00:00, prior8high=0.099670, depth_time=2026-11-03T16:45:08+00:00, book20_bid_proxy_usdt=16871, book20_ask_proxy_usdt=20232, funding_indicative=0.000336, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.76%, turnover=8675408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T16:45:00+00:00, last15m_closed_end=2026-11-03T16:45+00:00, prior8high=3.892000, depth_time=2026-11-03T16:45:13+00:00, book20_bid_proxy_usdt=4506298, book20_ask_proxy_usdt=4700934, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=83129537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T16:45:00+00:00, last15m_closed_end=2026-11-03T16:45+00:00, prior8high=196.170000, depth_time=2026-11-03T16:45:21+00:00, book20_bid_proxy_usdt=75696, book20_ask_proxy_usdt=76222, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=57531219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T16:45:00+00:00, last15m_closed_end=2026-11-03T16:45+00:00, prior8high=1.613000, depth_time=2026-11-03T16:45:15+00:00, book20_bid_proxy_usdt=2497993, book20_ask_proxy_usdt=1988879, funding_indicative=0.000023, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=7575362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T16:45:00+00:00, last15m_closed_end=2026-11-03T16:45+00:00, prior8high=0.374900, depth_time=2026-11-03T16:45:18+00:00, book20_bid_proxy_usdt=4408815, book20_ask_proxy_usdt=3505986, funding_indicative=0.000060, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=47674316. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
