# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T19:30:25Z**
- feed_generated_utc: 2026-10-14T19:30:26+00:00
- source_sha256: `cabad3405ddb68fcb3bd41835acc59fcf9def091dbfd8faddea108438c3a7321`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T19:30+00:00, close=81760.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T19:00+00:00, close=81679.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.200800|-7.48|78.01|-7.67|60059012|3.18|
|S_USDT|0.052840|-3.55|32.63|-3.74|6906481|1.89|
|BAT_USDT|0.169120|-3.03|70.55|-3.22|35685188|0.59|
|FET_USDT|0.197800|-2.99|-12.67|-3.18|9906398|5.05|
|STRK_USDT|0.075550|-2.11|52.74|-2.30|24088939|1.32|
|COPPER_USDT|6.618000|-0.83|-1.00|-1.02|6423994|1.51|
|LDO_USDT|0.402400|-0.83|-5.84|-1.02|5023268|2.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.169120|0.169480|0.169120|1.81|Y|Y/Y|N/N|Y|N|
|BTW_USDT|2.200800|2.064400|2.201900|1.80|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.618000|6.616000|6.618000|0.89|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.197800|0.198300|0.197700|1.39|Y|Y/Y|Y/Y|Y|Y|
|LDO_USDT|0.402400|0.400200|0.402400|0.28|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075550|0.075170|0.075580|0.62|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052840|0.052320|0.052840|0.95|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-14T19:30:00+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=0.174050, depth_time=2026-10-14T19:30:14+00:00, book20_bid_proxy_usdt=20151, book20_ask_proxy_usdt=35444, funding_indicative=0.000042, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=35685188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T19:30:00+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=2.279300, depth_time=2026-10-14T19:30:09+00:00, book20_bid_proxy_usdt=12884, book20_ask_proxy_usdt=21355, funding_indicative=-0.000017, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.48%, turnover=60059012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T19:30:01+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=6.664000, depth_time=2026-10-14T19:30:18+00:00, book20_bid_proxy_usdt=1546406, book20_ask_proxy_usdt=1256888, funding_indicative=0.000000, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=6423994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T19:30:00+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=0.207500, depth_time=2026-10-14T19:30:16+00:00, book20_bid_proxy_usdt=1150620, book20_ask_proxy_usdt=1001988, funding_indicative=0.000025, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=9906398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T19:30:00+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=0.410500, depth_time=2026-10-14T19:30:24+00:00, book20_bid_proxy_usdt=715801, book20_ask_proxy_usdt=603378, funding_indicative=-0.000102, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=5023268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T19:30:00+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=0.076630, depth_time=2026-10-14T19:30:19+00:00, book20_bid_proxy_usdt=201128, book20_ask_proxy_usdt=370728, funding_indicative=0.000039, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=24088939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T19:30:00+00:00, last15m_closed_end=2026-10-14T19:30+00:00, prior8high=0.053510, depth_time=2026-10-14T19:30:11+00:00, book20_bid_proxy_usdt=164851, book20_ask_proxy_usdt=180260, funding_indicative=-0.000081, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=6906481. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
