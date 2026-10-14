# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T18:45:23Z**
- feed_generated_utc: 2026-10-14T18:45:24+00:00
- source_sha256: `d63ddbbcc17e9f2733ac97ea3ae18e26ae1e84feebad9e1ed7bdfba35b16b1ae`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T18:45+00:00, close=81544.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T18:00+00:00, close=81556.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.155400|-9.39|74.34|-9.33|59309786|4.17|
|S_USDT|0.052770|-3.68|32.45|-3.62|7663153|1.90|
|STRK_USDT|0.075420|-2.28|52.48|-2.22|24958613|1.33|
|BAT_USDT|0.170720|-2.12|72.16|-2.06|36612947|0.59|
|FET_USDT|0.200200|-1.81|-11.61|-1.75|9399810|4.99|
|LDO_USDT|0.400600|-1.28|-6.27|-1.22|5562801|2.50|
|AAVE_USDT|154.030000|-1.19|-10.32|-1.13|24217519|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.030000|154.030000|154.030000|1.26|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.170720|0.169480|0.170610|0.28|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.155400|2.064400|2.155400|0.62|N|Y/Y|N/N|Y|N|
|FET_USDT|0.200200|0.200300|0.200200|1.47|Y|Y/Y|Y/Y|Y|Y|
|LDO_USDT|0.400600|0.402400|0.400600|0.97|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075420|0.075170|0.075430|0.43|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052770|0.052320|0.052800|0.22|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T18:45:00+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=158.400000, depth_time=2026-10-14T18:45:22+00:00, book20_bid_proxy_usdt=257783, book20_ask_proxy_usdt=327988, funding_indicative=0.000025, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=24217519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T18:45:00+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=0.174590, depth_time=2026-10-14T18:45:13+00:00, book20_bid_proxy_usdt=23718, book20_ask_proxy_usdt=32409, funding_indicative=0.000044, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=36612947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T18:45:00+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=2.406000, depth_time=2026-10-14T18:45:07+00:00, book20_bid_proxy_usdt=14005, book20_ask_proxy_usdt=15527, funding_indicative=-0.000005, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.39%, turnover=59309786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T18:45:00+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=0.208600, depth_time=2026-10-14T18:45:17+00:00, book20_bid_proxy_usdt=1347357, book20_ask_proxy_usdt=1342312, funding_indicative=-0.000027, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=9399810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T18:45:01+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=0.412700, depth_time=2026-10-14T18:45:19+00:00, book20_bid_proxy_usdt=496831, book20_ask_proxy_usdt=487460, funding_indicative=-0.000098, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=5562801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T18:45:00+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=0.077570, depth_time=2026-10-14T18:45:12+00:00, book20_bid_proxy_usdt=221085, book20_ask_proxy_usdt=244992, funding_indicative=0.000050, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=24958613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T18:45:00+00:00, last15m_closed_end=2026-10-14T18:45+00:00, prior8high=0.054000, depth_time=2026-10-14T18:45:10+00:00, book20_bid_proxy_usdt=188634, book20_ask_proxy_usdt=130892, funding_indicative=-0.000066, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=7663153. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
