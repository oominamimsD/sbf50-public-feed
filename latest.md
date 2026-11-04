# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T18:00:25Z**
- feed_generated_utc: 2026-11-04T18:00:27+00:00
- source_sha256: `d4ea90bc2b28868b079d1b3def7e2ec0e71c2201f68407afc158a8902a23f81b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T18:00+00:00, close=80387.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T18:00+00:00, close=80387.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.246000|-12.62|-27.09|-12.76|22183424|8.03|
|AKE_USDT|0.002637|-6.15|-86.87|-6.29|17510191|7.58|
|PUMPFUN_USDT|0.004254|-3.90|1.11|-4.04|18083326|2.35|
|WLFI_USDT|0.047640|-3.79|-9.22|-3.93|5980924|2.10|
|AGT_USDT|0.033740|-3.73|-25.17|-3.87|5667377|2.96|
|ZRO_USDT|1.829400|-1.89|6.85|-2.03|11042496|0.55|
|XMR_USDT|630.820000|-1.43|4.42|-1.57|9681338|1.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033740|0.033090|0.033740|0.54|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002637|0.002421|0.002649|1.12|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004254|0.004278|0.004254|1.29|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.246000|1.241000|1.246000|3.82|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.047640|0.046430|0.047640|0.57|N|Y/Y|Y/Y|N|N|
|XMR_USDT|630.820000|633.500000|630.820000|2.02|Y|Y/Y|N/N|N|N|
|ZRO_USDT|1.829400|1.806000|1.830100|0.83|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T18:00:03+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=0.036320, depth_time=2026-11-04T18:00:19+00:00, book20_bid_proxy_usdt=29882, book20_ask_proxy_usdt=15434, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5667377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T18:00:03+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=0.002921, depth_time=2026-11-04T18:00:12+00:00, book20_bid_proxy_usdt=39826, book20_ask_proxy_usdt=215748, funding_indicative=-0.000214, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.15%, turnover=17510191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T18:00:04+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=0.004498, depth_time=2026-11-04T18:00:15+00:00, book20_bid_proxy_usdt=1274444, book20_ask_proxy_usdt=2103815, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=18083326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T18:00:04+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=1.441000, depth_time=2026-11-04T18:00:08+00:00, book20_bid_proxy_usdt=807087, book20_ask_proxy_usdt=930162, funding_indicative=-0.000444, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-12.62%, turnover=22183424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T18:00:04+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=0.049600, depth_time=2026-11-04T18:00:15+00:00, book20_bid_proxy_usdt=126267, book20_ask_proxy_usdt=313334, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=5980924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-04T18:00:04+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=643.000000, depth_time=2026-11-04T18:00:24+00:00, book20_bid_proxy_usdt=38986, book20_ask_proxy_usdt=16511, funding_indicative=0.000147, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=9681338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T18:00:04+00:00, last15m_closed_end=2026-11-04T18:00+00:00, prior8high=1.897900, depth_time=2026-11-04T18:00:22+00:00, book20_bid_proxy_usdt=23564, book20_ask_proxy_usdt=22756, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=11042496. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
