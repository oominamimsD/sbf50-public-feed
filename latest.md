# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T09:15:26Z**
- feed_generated_utc: 2026-10-21T09:15:28+00:00
- source_sha256: `46e181f42d583cbd1dd5619c0d1cd362950484c96ff2c535d1a6a6dbd6977515`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T09:15+00:00, close=83509.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T09:00+00:00, close=83217, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.043826|-32.18|170.91|-33.32|6696486|2.99|
|BAT_USDT|0.184950|-14.28|4.26|-15.42|10851506|0.54|
|BR_USDT|0.592290|-8.97|36.78|-10.11|26368902|5.91|
|XMR_USDT|592.130000|-4.52|12.16|-5.66|20525014|0.17|
|SILVER_USDT|57.470000|-0.82|-3.23|-1.96|214132962|1.74|
|Q_USDT|0.121786|-0.78|196.12|-1.92|5815853|2.22|
|XAU_USDT|4131.840000|-0.18|-0.80|-1.32|383654212|0.02|
|XAUT_USDT|4123.690000|-0.10|-0.79|-1.24|159626707|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.043826|0.039757|0.043826|0.73|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.184950|0.183460|0.185030|0.36|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.592290|0.575440|0.592440|0.87|N|Y/Y|N/N|N|N|
|Q_USDT|0.121786|0.120575|0.121786|0.69|N|Y/N|N/N|N|N|
|SILVER_USDT|57.470000|57.240000|57.470000|1.09|N|Y/Y|N/N|N|N|
|XAUT_USDT|4123.690000|4112.000000|4123.710000|1.77|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4131.840000|4119.770000|4131.820000|1.53|N|Y/Y|Y/Y|N|N|
|XMR_USDT|592.130000|579.840000|592.130000|0.94|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=0.046764, depth_time=2026-10-21T09:15:08+00:00, book20_bid_proxy_usdt=8216, book20_ask_proxy_usdt=8462, funding_indicative=0.000053, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-32.18%, turnover=6696486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=0.190510, depth_time=2026-10-21T09:15:10+00:00, book20_bid_proxy_usdt=20472, book20_ask_proxy_usdt=20860, funding_indicative=-0.000113, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.28%, turnover=10851506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=0.627970, depth_time=2026-10-21T09:15:13+00:00, book20_bid_proxy_usdt=2861, book20_ask_proxy_usdt=2811, funding_indicative=0.000006, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.97%, turnover=26368902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=0.146637, depth_time=2026-10-21T09:15:20+00:00, book20_bid_proxy_usdt=16112, book20_ask_proxy_usdt=17137, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=5815853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=57.550000, depth_time=2026-10-21T09:15:17+00:00, book20_bid_proxy_usdt=32579536, book20_ask_proxy_usdt=42344053, funding_indicative=0.000038, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=214132962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=4125.440000, depth_time=2026-10-21T09:15:24+00:00, book20_bid_proxy_usdt=153099, book20_ask_proxy_usdt=105947, funding_indicative=0.000027, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.10%, turnover=159626707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=4132.430000, depth_time=2026-10-21T09:15:22+00:00, book20_bid_proxy_usdt=278222, book20_ask_proxy_usdt=1221402, funding_indicative=0.000063, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.18%, turnover=383654212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T09:15:03+00:00, last15m_closed_end=2026-10-21T09:15+00:00, prior8high=590.720000, depth_time=2026-10-21T09:15:14+00:00, book20_bid_proxy_usdt=7980, book20_ask_proxy_usdt=54199, funding_indicative=0.000100, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.52%, turnover=20525014. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
