# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T02:00:18Z**
- feed_generated_utc: 2026-10-20T02:00:20+00:00
- source_sha256: `c7f036fa7fc5551bd1c50e374601e03e2d5fcef81171ded9089b8156511307bf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T02:00+00:00, close=81765.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T02:00+00:00, close=81765.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|SAND_USDT|0.057980|-2.65|-6.61|-2.47|8925891|1.72|
|TAO_USDT|266.600000|-1.28|-6.87|-1.10|54951547|1.12|
|APT_USDT|0.758000|-1.27|-10.01|-1.09|10093597|1.32|
|NEAR_USDT|4.866000|-1.25|-12.30|-1.07|166118423|2.06|
|FILECOIN_USDT|1.011200|-1.19|-13.00|-1.01|8817248|1.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.758000|0.748000|0.758000|0.55|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.011200|0.996900|1.011200|0.76|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.866000|4.785000|4.866000|0.71|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057980|0.057130|0.057980|6.45|N|Y/Y|N/Y|Y|N|
|TAO_USDT|266.600000|262.770000|266.600000|1.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-20T02:00:02+00:00, last15m_closed_end=2026-10-20T02:00+00:00, prior8high=0.769800, depth_time=2026-10-20T02:00:12+00:00, book20_bid_proxy_usdt=129862, book20_ask_proxy_usdt=111432, funding_indicative=-0.000082, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=10093597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-20T02:00:02+00:00, last15m_closed_end=2026-10-20T02:00+00:00, prior8high=1.021000, depth_time=2026-10-20T02:00:17+00:00, book20_bid_proxy_usdt=385208, book20_ask_proxy_usdt=558253, funding_indicative=0.000005, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=8817248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T02:00:01+00:00, last15m_closed_end=2026-10-20T02:00+00:00, prior8high=4.926000, depth_time=2026-10-20T02:00:14+00:00, book20_bid_proxy_usdt=531305, book20_ask_proxy_usdt=2777213, funding_indicative=0.000048, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=166118423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T02:00:02+00:00, last15m_closed_end=2026-10-20T02:00+00:00, prior8high=0.059320, depth_time=2026-10-20T02:00:08+00:00, book20_bid_proxy_usdt=541738, book20_ask_proxy_usdt=756890, funding_indicative=-0.002381, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=8925891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T02:00:01+00:00, last15m_closed_end=2026-10-20T02:00+00:00, prior8high=268.840000, depth_time=2026-10-20T02:00:10+00:00, book20_bid_proxy_usdt=53657, book20_ask_proxy_usdt=196334, funding_indicative=0.000043, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=54951547. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
