# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T09:15:19Z**
- feed_generated_utc: 2026-10-19T09:15:21+00:00
- source_sha256: `b4b5e30f32ebd61affb9b62f2cb0bdc0914382f87a42eb25d29170f2b806708a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T09:15+00:00, close=82790.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T09:00+00:00, close=82786, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.167300|-6.74|57.83|-8.77|6673167|5.98|
|STRK_USDT|0.059470|-3.39|-50.13|-5.42|17870792|5.04|
|BTW_USDT|2.251000|-2.35|33.81|-4.38|21448788|1.78|
|TIA_USDT|0.606600|-1.82|3.04|-3.85|55525983|1.65|
|HBAR_USDT|0.084450|-1.55|-9.94|-3.58|46502825|1.18|
|SAND_USDT|0.058800|0.06|-11.49|-1.97|16814736|3.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.251000|2.206900|2.251000|1.62|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084450|0.084210|0.084450|0.38|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.167300|0.167000|0.167300|1.81|N|Y/Y|Y/N|N|N|
|SAND_USDT|0.058800|0.058430|0.058800|0.69|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059470|0.059240|0.059470|0.57|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.606600|0.605400|0.606600|0.97|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T09:14:59+00:00, last15m_closed_end=2026-10-19T09:15+00:00, prior8high=2.290900, depth_time=2026-10-19T09:15:11+00:00, book20_bid_proxy_usdt=9486, book20_ask_proxy_usdt=11305, funding_indicative=-0.000436, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=21448788. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T09:14:59+00:00, last15m_closed_end=2026-10-19T09:15+00:00, prior8high=0.085160, depth_time=2026-10-19T09:15:16+00:00, book20_bid_proxy_usdt=742893, book20_ask_proxy_usdt=559518, funding_indicative=-0.000072, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=46502825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T09:14:59+00:00, last15m_closed_end=2026-10-19T09:15+00:00, prior8high=0.175400, depth_time=2026-10-19T09:15:07+00:00, book20_bid_proxy_usdt=231411, book20_ask_proxy_usdt=151672, funding_indicative=-0.000277, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.74%, turnover=6673167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T09:14:59+00:00, last15m_closed_end=2026-10-19T09:15+00:00, prior8high=0.061170, depth_time=2026-10-19T09:15:18+00:00, book20_bid_proxy_usdt=444951, book20_ask_proxy_usdt=612298, funding_indicative=-0.005302, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.06%, turnover=16814736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T09:14:59+00:00, last15m_closed_end=2026-10-19T09:15+00:00, prior8high=0.060350, depth_time=2026-10-19T09:15:09+00:00, book20_bid_proxy_usdt=536776, book20_ask_proxy_usdt=533833, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=17870792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T09:14:59+00:00, last15m_closed_end=2026-10-19T09:15+00:00, prior8high=0.620500, depth_time=2026-10-19T09:15:14+00:00, book20_bid_proxy_usdt=186610, book20_ask_proxy_usdt=202839, funding_indicative=-0.000024, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=55525983. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
