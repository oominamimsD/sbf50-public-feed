# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T13:15:24Z**
- feed_generated_utc: 2026-11-03T13:15:26+00:00
- source_sha256: `dcbc300831b757f9a8507cbd848ab68fe37276fa76c2de50a9d0ea209a3903c6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T13:15+00:00, close=77321.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T13:00+00:00, close=77400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004268|-22.42|-86.13|-22.22|12086764|2.34|
|BTW_USDT|0.980800|-10.57|-17.97|-10.37|9334862|6.10|
|XPL_USDT|0.064690|-7.02|-12.92|-6.82|11591716|1.55|
|NEAR_USDT|3.888000|-3.04|-14.97|-2.84|78670591|2.57|
|TIA_USDT|0.444500|-2.71|-17.02|-2.51|13303892|2.25|
|ENA_USDT|0.171590|-1.97|-18.43|-1.77|71612300|0.58|
|DASH_USDT|46.440000|-1.61|-11.06|-1.41|9412189|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004268|0.004240|0.004267|2.45|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.980800|0.870600|0.980800|0.77|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.440000|45.680000|46.440000|0.66|N|N/Y|Y/Y|Y|N|
|ENA_USDT|0.171590|0.169890|0.171590|1.01|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|3.888000|3.829000|3.888000|2.04|N|N/Y|Y/Y|Y|N|
|TIA_USDT|0.444500|0.437700|0.444500|1.73|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.064690|0.063400|0.064690|1.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=0.004586, depth_time=2026-11-03T13:15:08+00:00, book20_bid_proxy_usdt=31017, book20_ask_proxy_usdt=35621, funding_indicative=-0.001842, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.42%, turnover=12086764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=1.032400, depth_time=2026-11-03T13:15:10+00:00, book20_bid_proxy_usdt=17002, book20_ask_proxy_usdt=33877, funding_indicative=-0.000087, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.57%, turnover=9334862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=46.650000, depth_time=2026-11-03T13:15:21+00:00, book20_bid_proxy_usdt=719272, book20_ask_proxy_usdt=588299, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=9412189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=0.173500, depth_time=2026-11-03T13:15:21+00:00, book20_bid_proxy_usdt=273576, book20_ask_proxy_usdt=160550, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=71612300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=3.928000, depth_time=2026-11-03T13:15:15+00:00, book20_bid_proxy_usdt=5637453, book20_ask_proxy_usdt=4475624, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=78670591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=0.449000, depth_time=2026-11-03T13:15:17+00:00, book20_bid_proxy_usdt=328214, book20_ask_proxy_usdt=429879, funding_indicative=0.000021, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=13303892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T13:15:02+00:00, last15m_closed_end=2026-11-03T13:15+00:00, prior8high=0.065540, depth_time=2026-11-03T13:15:13+00:00, book20_bid_proxy_usdt=403289, book20_ask_proxy_usdt=453934, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.02%, turnover=11591716. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
