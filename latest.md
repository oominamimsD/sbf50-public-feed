# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T15:30:23Z**
- feed_generated_utc: 2026-10-21T15:30:25+00:00
- source_sha256: `3bdda0444eff49c8a014532631b694736117fb424d68de3399fb2b0eb13a895e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T15:30+00:00, close=84374.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T15:00+00:00, close=84530, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.049279|-23.75|204.62|-25.92|6243710|1.82|
|BR_USDT|0.533920|-17.94|23.30|-20.11|19692613|1.69|
|BTW_USDT|1.526100|-17.49|-21.83|-19.66|26707733|3.93|
|BAT_USDT|0.178430|-17.30|0.59|-19.47|9301996|1.68|
|AKE_USDT|0.027131|-12.73|8.23|-14.90|9757129|1.11|
|JCT_USDT|0.004090|-10.83|107.82|-13.00|19064325|4.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.049279|0.044780|0.049309|1.34|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027131|0.026563|0.027131|0.75|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.178430|0.177360|0.178400|0.98|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.533920|0.558250|0.533920|4.24|Y|Y/Y|N/N|N|N|
|BTW_USDT|1.526100|1.471900|1.526100|0.54|N|Y/Y|Y/Y|N|N|
|JCT_USDT|0.004090|0.004155|0.004093|1.17|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T15:30:00+00:00, last15m_closed_end=2026-10-21T15:30+00:00, prior8high=0.047116, depth_time=2026-10-21T15:30:10+00:00, book20_bid_proxy_usdt=6429, book20_ask_proxy_usdt=5585, funding_indicative=0.000193, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.75%, turnover=6243710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T15:30:00+00:00, last15m_closed_end=2026-10-21T15:30+00:00, prior8high=0.028653, depth_time=2026-10-21T15:30:20+00:00, book20_bid_proxy_usdt=11305, book20_ask_proxy_usdt=10670, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.73%, turnover=9757129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T15:30:00+00:00, last15m_closed_end=2026-10-21T15:30+00:00, prior8high=0.181140, depth_time=2026-10-21T15:30:17+00:00, book20_bid_proxy_usdt=21879, book20_ask_proxy_usdt=82640, funding_indicative=-0.000252, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-17.30%, turnover=9301996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T15:30:00+00:00, last15m_closed_end=2026-10-21T15:30+00:00, prior8high=0.634300, depth_time=2026-10-21T15:30:13+00:00, book20_bid_proxy_usdt=2764, book20_ask_proxy_usdt=8822, funding_indicative=-0.000011, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.94%, turnover=19692613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T15:30:00+00:00, last15m_closed_end=2026-10-21T15:30+00:00, prior8high=1.641600, depth_time=2026-10-21T15:30:15+00:00, book20_bid_proxy_usdt=17527, book20_ask_proxy_usdt=6258, funding_indicative=-0.004609, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.49%, turnover=26707733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T15:30:00+00:00, last15m_closed_end=2026-10-21T15:30+00:00, prior8high=0.004835, depth_time=2026-10-21T15:30:22+00:00, book20_bid_proxy_usdt=53946, book20_ask_proxy_usdt=52541, funding_indicative=0.000132, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.83%, turnover=19064325. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
