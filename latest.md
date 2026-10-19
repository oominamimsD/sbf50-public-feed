# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T08:15:20Z**
- feed_generated_utc: 2026-10-19T08:15:22+00:00
- source_sha256: `7d82972fca96294ca01e999f963466614f0cb5f711a6e073134e4382f22b5525`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T08:15+00:00, close=82656.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.170800|-4.79|61.13|-6.66|6812125|5.86|
|STRK_USDT|0.059850|-2.77|-49.81|-4.64|17838098|1.67|
|BTW_USDT|2.265100|-1.74|34.65|-3.61|21499749|0.44|
|HBAR_USDT|0.084320|-1.70|-10.08|-3.57|47849647|1.19|
|TIA_USDT|0.610300|-1.22|3.66|-3.09|57222783|1.64|
|SAND_USDT|0.058980|0.37|-11.22|-1.50|22058113|3.39|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.265100|2.166400|2.265200|0.66|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084320|0.084010|0.084320|0.65|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.170800|0.167000|0.170900|0.49|N|Y/Y|Y/N|N|N|
|SAND_USDT|0.058980|0.059860|0.058980|17.83|Y|N/N|N/N|N|N|
|STRK_USDT|0.059850|0.059350|0.059850|1.51|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.610300|0.606800|0.610300|1.75|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T08:15:01+00:00, last15m_closed_end=2026-10-19T08:15+00:00, prior8high=2.321000, depth_time=2026-10-19T08:15:12+00:00, book20_bid_proxy_usdt=23101, book20_ask_proxy_usdt=17231, funding_indicative=-0.000310, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=21499749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T08:15:01+00:00, last15m_closed_end=2026-10-19T08:15+00:00, prior8high=0.085160, depth_time=2026-10-19T08:15:14+00:00, book20_bid_proxy_usdt=548322, book20_ask_proxy_usdt=850075, funding_indicative=-0.000059, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=47849647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T08:15:01+00:00, last15m_closed_end=2026-10-19T08:15+00:00, prior8high=0.176800, depth_time=2026-10-19T08:15:08+00:00, book20_bid_proxy_usdt=173319, book20_ask_proxy_usdt=139605, funding_indicative=-0.000123, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.79%, turnover=6812125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T08:15:01+00:00, last15m_closed_end=2026-10-19T08:15+00:00, prior8high=0.061560, depth_time=2026-10-19T08:15:19+00:00, book20_bid_proxy_usdt=238987, book20_ask_proxy_usdt=393269, funding_indicative=-0.006675, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.37%, turnover=22058113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T08:15:01+00:00, last15m_closed_end=2026-10-19T08:15+00:00, prior8high=0.060350, depth_time=2026-10-19T08:15:09+00:00, book20_bid_proxy_usdt=492925, book20_ask_proxy_usdt=615672, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=17838098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T08:15:01+00:00, last15m_closed_end=2026-10-19T08:15+00:00, prior8high=0.620500, depth_time=2026-10-19T08:15:17+00:00, book20_bid_proxy_usdt=216135, book20_ask_proxy_usdt=297126, funding_indicative=-0.000055, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=57222783. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
