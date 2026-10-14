# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T21:15:22Z**
- feed_generated_utc: 2026-10-14T21:15:24+00:00
- source_sha256: `896288510557ed62ec418b6057770df49e6b74f12d3a191e87e040a278738167`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T21:15+00:00, close=81711, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T21:00+00:00, close=81735.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.239100|-5.87|81.11|-6.00|61229951|2.68|
|FET_USDT|0.196400|-3.67|-13.28|-3.80|10844684|5.09|
|S_USDT|0.053120|-3.04|33.33|-3.17|5724632|3.77|
|BAT_USDT|0.169250|-2.96|70.68|-3.09|29560910|1.77|
|AAVE_USDT|154.150000|-1.11|-10.25|-1.24|24585168|0.65|
|INJ_USDT|7.558000|-1.06|3.40|-1.19|36055840|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.150000|153.860000|154.150000|1.60|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169250|0.167120|0.169250|1.01|N|Y/Y|Y/N|Y|N|
|BTW_USDT|2.239100|2.065400|2.236500|0.60|N|Y/Y|N/N|Y|N|
|FET_USDT|0.196400|0.192700|0.196400|0.47|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.558000|7.560000|7.558000|1.33|Y|Y/Y|Y/Y|Y|Y|
|S_USDT|0.053120|0.052450|0.053120|0.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T21:15:02+00:00, last15m_closed_end=2026-10-14T21:15+00:00, prior8high=155.360000, depth_time=2026-10-14T21:15:19+00:00, book20_bid_proxy_usdt=257490, book20_ask_proxy_usdt=287049, funding_indicative=0.000069, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=24585168. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T21:15:02+00:00, last15m_closed_end=2026-10-14T21:15+00:00, prior8high=0.172860, depth_time=2026-10-14T21:15:17+00:00, book20_bid_proxy_usdt=21796, book20_ask_proxy_usdt=25245, funding_indicative=0.000029, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=29560910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T21:15:02+00:00, last15m_closed_end=2026-10-14T21:15+00:00, prior8high=2.275500, depth_time=2026-10-14T21:15:08+00:00, book20_bid_proxy_usdt=13654, book20_ask_proxy_usdt=11878, funding_indicative=0.000050, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.87%, turnover=61229951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T21:15:02+00:00, last15m_closed_end=2026-10-14T21:15+00:00, prior8high=0.200900, depth_time=2026-10-14T21:15:11+00:00, book20_bid_proxy_usdt=986877, book20_ask_proxy_usdt=1179994, funding_indicative=0.000062, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=10844684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-14T21:15:02+00:00, last15m_closed_end=2026-10-14T21:15+00:00, prior8high=7.767000, depth_time=2026-10-14T21:15:19+00:00, book20_bid_proxy_usdt=173074, book20_ask_proxy_usdt=194386, funding_indicative=0.000130, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=36055840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T21:15:02+00:00, last15m_closed_end=2026-10-14T21:15+00:00, prior8high=0.053720, depth_time=2026-10-14T21:15:13+00:00, book20_bid_proxy_usdt=121041, book20_ask_proxy_usdt=130014, funding_indicative=-0.000093, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=5724632. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
