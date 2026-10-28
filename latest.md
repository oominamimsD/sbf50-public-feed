# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T16:45:32Z**
- feed_generated_utc: 2026-10-28T16:45:37+00:00
- source_sha256: `c765e9d4100ca306a1f3fcc47c07b5eeb7dff5d503cc9fdeac46e09246ebb8f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T16:45+00:00, close=80420, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.059900|-2.71|-26.00|-2.58|6994220|5.01|
|STRK_USDT|0.045800|-2.13|-26.09|-2.00|5250675|2.18|
|TIA_USDT|0.531500|-1.59|-15.96|-1.46|14462974|1.88|
|ARB_USDT|0.165340|-1.41|-15.90|-1.28|18332886|0.60|
|WLD_USDT|0.426700|-1.40|-25.61|-1.27|61300559|2.35|
|FET_USDT|0.179400|-1.26|-10.56|-1.13|7190348|5.57|
|HBAR_USDT|0.074980|-1.22|-12.75|-1.09|10032136|1.33|
|NEAR_USDT|4.573000|-1.20|-15.07|-1.07|95693026|2.19|
|BCH_USDT|289.530000|-1.16|-0.05|-1.03|5159928|3.11|
|OP_USDT|0.109800|-1.15|-16.75|-1.02|6453892|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.165340|0.163540|0.165310|0.58|N|N/Y|Y/Y|Y|N|
|BCH_USDT|289.530000|289.630000|289.530000|0.15|N|Y/Y|N/N|Y|N|
|BULLA_USDT|0.059900|0.059370|0.059900|0.64|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.179400|0.179100|0.179400|0.83|N|N/Y|N/N|Y|N|
|HBAR_USDT|0.074980|0.075070|0.074980|2.01|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.573000|4.554000|4.573000|0.90|N|Y/Y|N/N|Y|N|
|OP_USDT|0.109800|0.109400|0.109800|0.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045800|0.045590|0.045800|1.65|N|N/Y|Y/Y|Y|N|
|TIA_USDT|0.531500|0.532200|0.531600|1.51|Y|N/N|N/Y|Y|N|
|WLD_USDT|0.426700|0.426400|0.426700|0.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.167890, depth_time=2026-10-28T16:45:16+00:00, book20_bid_proxy_usdt=120520, book20_ask_proxy_usdt=105447, funding_indicative=-0.000016, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=18332886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=294.880000, depth_time=2026-10-28T16:45:27+00:00, book20_bid_proxy_usdt=64506, book20_ask_proxy_usdt=70288, funding_indicative=0.000090, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=5159928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.068880, depth_time=2026-10-28T16:45:08+00:00, book20_bid_proxy_usdt=16691, book20_ask_proxy_usdt=12030, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=6994220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.182500, depth_time=2026-10-28T16:45:21+00:00, book20_bid_proxy_usdt=1903093, book20_ask_proxy_usdt=1060600, funding_indicative=0.000006, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=7190348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.075940, depth_time=2026-10-28T16:45:22+00:00, book20_bid_proxy_usdt=1401700, book20_ask_proxy_usdt=1082830, funding_indicative=-0.000027, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=10032136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=4.646000, depth_time=2026-10-28T16:45:26+00:00, book20_bid_proxy_usdt=3258542, book20_ask_proxy_usdt=4555904, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=95693026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.111260, depth_time=2026-10-28T16:45:30+00:00, book20_bid_proxy_usdt=124518, book20_ask_proxy_usdt=176855, funding_indicative=-0.000026, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=6453892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.047080, depth_time=2026-10-28T16:45:10+00:00, book20_bid_proxy_usdt=823536, book20_ask_proxy_usdt=839866, funding_indicative=0.000017, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=5250675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.546100, depth_time=2026-10-28T16:45:12+00:00, book20_bid_proxy_usdt=395648, book20_ask_proxy_usdt=280541, funding_indicative=0.000018, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=14462974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T16:45:02+00:00, last15m_closed_end=2026-10-28T16:45+00:00, prior8high=0.435200, depth_time=2026-10-28T16:45:18+00:00, book20_bid_proxy_usdt=3906094, book20_ask_proxy_usdt=3714172, funding_indicative=0.000000, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=61300559. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
