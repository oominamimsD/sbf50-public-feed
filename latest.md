# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T08:30:21Z**
- feed_generated_utc: 2026-10-21T08:30:24+00:00
- source_sha256: `23001899bb3bdb9e5d1af42e446c4fb0a7a015373e381e6b098d25c99364b4aa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T08:30+00:00, close=83217.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045086|-30.23|178.70|-30.99|7183959|1.55|
|BAT_USDT|0.186870|-13.39|5.35|-14.15|11115641|1.07|
|XMR_USDT|584.580000|-5.74|10.73|-6.50|21358181|1.03|
|BR_USDT|0.619150|-4.84|42.98|-5.60|28219602|1.94|
|SILVER_USDT|57.460000|-0.84|-3.24|-1.60|214004173|1.74|
|PHA_USDT|0.057550|-0.46|4.57|-1.22|5159121|8.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045086|0.038698|0.045086|4.62|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186870|0.181950|0.186870|1.47|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.619150|0.575440|0.619350|2.86|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057550|0.056570|0.057550|0.29|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.460000|57.210000|57.460000|0.84|N|Y/Y|N/N|N|N|
|XMR_USDT|584.580000|576.740000|584.420000|2.42|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T08:30:00+00:00, last15m_closed_end=2026-10-21T08:30+00:00, prior8high=0.059349, depth_time=2026-10-21T08:30:08+00:00, book20_bid_proxy_usdt=9316, book20_ask_proxy_usdt=7893, funding_indicative=0.000053, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-30.23%, turnover=7183959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T08:30:00+00:00, last15m_closed_end=2026-10-21T08:30+00:00, prior8high=0.190510, depth_time=2026-10-21T08:30:11+00:00, book20_bid_proxy_usdt=25957, book20_ask_proxy_usdt=23799, funding_indicative=-0.000130, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-13.39%, turnover=11115641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T08:30:00+00:00, last15m_closed_end=2026-10-21T08:30+00:00, prior8high=0.606650, depth_time=2026-10-21T08:30:15+00:00, book20_bid_proxy_usdt=3528, book20_ask_proxy_usdt=4365, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=28219602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T08:30:00+00:00, last15m_closed_end=2026-10-21T08:30+00:00, prior8high=0.057270, depth_time=2026-10-21T08:30:20+00:00, book20_bid_proxy_usdt=98039, book20_ask_proxy_usdt=83876, funding_indicative=-0.000007, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.46%, turnover=5159121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T08:30:00+00:00, last15m_closed_end=2026-10-21T08:30+00:00, prior8high=57.550000, depth_time=2026-10-21T08:30:18+00:00, book20_bid_proxy_usdt=33435808, book20_ask_proxy_usdt=36680630, funding_indicative=0.000022, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=214004173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T08:30:00+00:00, last15m_closed_end=2026-10-21T08:30+00:00, prior8high=588.220000, depth_time=2026-10-21T08:30:13+00:00, book20_bid_proxy_usdt=9643, book20_ask_proxy_usdt=20052, funding_indicative=0.000100, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.74%, turnover=21358181. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
