# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T18:15:24Z**
- feed_generated_utc: 2026-11-04T18:15:26+00:00
- source_sha256: `add333d2a964487e132e2863f144f2b482d592128a624e925b2dcbbd34be9533`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T18:15+00:00, close=80628.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T18:00+00:00, close=80387.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.285000|-9.76|-24.80|-10.20|22928706|7.78|
|AKE_USDT|0.002585|-8.00|-87.13|-8.44|17738892|3.87|
|AGT_USDT|0.033430|-6.88|-25.85|-7.32|5708988|2.99|
|PUMPFUN_USDT|0.004277|-3.88|1.66|-4.32|18340879|2.34|
|XMR_USDT|632.080000|-1.23|4.62|-1.67|9753967|0.16|
|ZRO_USDT|1.842000|-1.21|7.59|-1.65|11079363|0.54|
|WLFI_USDT|0.047440|-0.75|-9.60|-1.19|6005256|2.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033430|0.033090|0.033430|0.70|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002585|0.002421|0.002585|0.77|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004277|0.004248|0.004277|1.28|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.285000|1.215000|1.285000|2.06|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.047440|0.046430|0.047440|0.82|N|Y/Y|Y/Y|N|N|
|XMR_USDT|632.080000|630.810000|632.080000|0.94|N|Y/Y|N/N|N|N|
|ZRO_USDT|1.842000|1.806000|1.842000|0.36|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T18:14:59+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=0.036000, depth_time=2026-11-04T18:15:12+00:00, book20_bid_proxy_usdt=31274, book20_ask_proxy_usdt=27547, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.88%, turnover=5708988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T18:14:59+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=0.002842, depth_time=2026-11-04T18:15:10+00:00, book20_bid_proxy_usdt=179385, book20_ask_proxy_usdt=49005, funding_indicative=-0.000236, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.00%, turnover=17738892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T18:15:00+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=0.004498, depth_time=2026-11-04T18:15:16+00:00, book20_bid_proxy_usdt=1846325, book20_ask_proxy_usdt=1531187, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=18340879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T18:14:59+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=1.436000, depth_time=2026-11-04T18:15:07+00:00, book20_bid_proxy_usdt=736954, book20_ask_proxy_usdt=633614, funding_indicative=-0.000439, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=22928706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T18:15:00+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=0.048650, depth_time=2026-11-04T18:15:22+00:00, book20_bid_proxy_usdt=207186, book20_ask_proxy_usdt=187182, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.75%, turnover=6005256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-04T18:15:00+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=643.000000, depth_time=2026-11-04T18:15:18+00:00, book20_bid_proxy_usdt=7802, book20_ask_proxy_usdt=45833, funding_indicative=0.000144, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=9753967. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T18:15:00+00:00, last15m_closed_end=2026-11-04T18:15+00:00, prior8high=1.872200, depth_time=2026-11-04T18:15:21+00:00, book20_bid_proxy_usdt=36103, book20_ask_proxy_usdt=31623, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.21%, turnover=11079363. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
