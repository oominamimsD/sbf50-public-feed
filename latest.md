# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T15:45:35Z**
- feed_generated_utc: 2026-10-16T15:45:37+00:00
- source_sha256: `7056c9041fc60f0bf354708683a1778b67f68cd5649f015286dfe57f88b50577`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T15:45+00:00, close=81634.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T15:00+00:00, close=81943.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.074450|-22.73|23.75|-21.84|39151294|1.34|
|PYTH_USDT|0.086670|-10.96|17.75|-10.07|8341781|3.46|
|AKE_USDT|0.029031|-8.14|0.02|-7.25|14318121|1.38|
|PUMPFUN_USDT|0.004319|-4.57|-20.89|-3.68|19061557|2.32|
|PEPE_USDT|0.000004|-3.73|6.95|-2.84|105626450|0.25|
|FET_USDT|0.201600|-3.54|-6.10|-2.65|11746762|4.96|
|UNI_USDT|7.298000|-3.27|-0.25|-2.38|16113548|1.37|
|HYPE_USDT|79.067000|-3.18|-5.14|-2.29|72319735|0.13|
|JUP_USDT|0.303800|-2.87|-12.57|-1.98|5974580|3.29|
|QNT_USDT|202.850000|-2.43|-11.44|-1.54|70532218|1.48|
|ADA_USDT|0.225600|-2.12|-2.50|-1.23|43070387|4.44|
|XPL_USDT|0.083070|-1.97|-0.15|-1.08|5630836|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.225600|0.223300|0.225500|0.35|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.029031|0.028349|0.029031|1.11|N|Y/Y|N/N|Y|N|
|FET_USDT|0.201600|0.198700|0.201600|1.74|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|79.067000|78.812000|79.085000|1.19|N|Y/Y|N/Y|Y|N|
|JUP_USDT|0.303800|0.301400|0.303800|2.98|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.13|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004319|0.004290|0.004319|4.04|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.086670|0.085560|0.086680|0.36|N|Y/Y|N/N|Y|N|
|QNT_USDT|202.850000|201.300000|202.820000|0.96|N|Y/Y|N/Y|Y|N|
|STRK_USDT|0.074450|0.074060|0.074450|0.77|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.298000|7.186000|7.298000|1.33|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.083070|0.082320|0.083130|0.18|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.230800, depth_time=2026-10-16T15:45:32+00:00, book20_bid_proxy_usdt=6406257, book20_ask_proxy_usdt=6631973, funding_indicative=-0.000014, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=43070387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.029607, depth_time=2026-10-16T15:45:12+00:00, book20_bid_proxy_usdt=13575, book20_ask_proxy_usdt=12164, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.14%, turnover=14318121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.206900, depth_time=2026-10-16T15:45:18+00:00, book20_bid_proxy_usdt=1338704, book20_ask_proxy_usdt=1330682, funding_indicative=0.000100, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=11746762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=81.537000, depth_time=2026-10-16T15:45:24+00:00, book20_bid_proxy_usdt=53401, book20_ask_proxy_usdt=233465, funding_indicative=0.000002, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=72319735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-16T15:45:01+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.310600, depth_time=2026-10-16T15:45:22+00:00, book20_bid_proxy_usdt=491156, book20_ask_proxy_usdt=355660, funding_indicative=-0.000037, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=5974580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.000004, depth_time=2026-10-16T15:45:17+00:00, book20_bid_proxy_usdt=38590, book20_ask_proxy_usdt=60581, funding_indicative=0.000007, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=105626450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.004461, depth_time=2026-10-16T15:45:15+00:00, book20_bid_proxy_usdt=1704962, book20_ask_proxy_usdt=1732332, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.57%, turnover=19061557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.089670, depth_time=2026-10-16T15:45:10+00:00, book20_bid_proxy_usdt=102449, book20_ask_proxy_usdt=167931, funding_indicative=0.000022, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.96%, turnover=8341781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=208.330000, depth_time=2026-10-16T15:45:28+00:00, book20_bid_proxy_usdt=100703, book20_ask_proxy_usdt=54458, funding_indicative=-0.000006, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=70532218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.077680, depth_time=2026-10-16T15:45:08+00:00, book20_bid_proxy_usdt=643131, book20_ask_proxy_usdt=388012, funding_indicative=-0.000004, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.73%, turnover=39151294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-16T15:45:00+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=7.456000, depth_time=2026-10-16T15:45:22+00:00, book20_bid_proxy_usdt=1367061, book20_ask_proxy_usdt=1664483, funding_indicative=-0.000004, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=16113548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-16T15:45:01+00:00, last15m_closed_end=2026-10-16T15:45+00:00, prior8high=0.085030, depth_time=2026-10-16T15:45:34+00:00, book20_bid_proxy_usdt=243966, book20_ask_proxy_usdt=510078, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=5630836. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
