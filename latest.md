# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T03:00:29Z**
- feed_generated_utc: 2026-11-08T03:00:31+00:00
- source_sha256: `4aeebe592041fe58db95995e975766f986ed6d35941c4e69366c494c9e455a54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T03:00+00:00, close=75758, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T03:00+00:00, close=75758, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005040|-15.76|-54.74|-15.80|50493751|3.96|
|AIN_USDT|0.142180|-8.73|-38.75|-8.77|9593526|1.41|
|IDOL_USDT|0.031186|-6.33|77.99|-6.37|16032291|3.84|
|ONE_USDT|0.001935|-5.00|64.77|-5.04|26946758|0.52|
|QNT_USDT|194.400000|-2.23|-3.30|-2.27|43914254|0.51|
|ENA_USDT|0.154730|-2.18|-20.24|-2.22|28447003|0.65|
|WLD_USDT|0.330400|-1.54|-18.29|-1.58|26075947|3.03|
|PEPE_USDT|0.000005|-1.44|-3.12|-1.48|39673863|0.21|
|TIA_USDT|0.435900|-1.29|-11.05|-1.33|7243328|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.142180|0.141520|0.142180|0.97|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005040|0.004987|0.005040|1.06|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.154730|0.153930|0.154730|1.97|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.031186|0.032556|0.031186|2.47|Y|Y/N|N/N|Y|N|
|ONE_USDT|0.001935|0.001906|0.001935|0.79|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.08|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.400000|193.390000|194.400000|1.01|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.435900|0.435200|0.435900|2.26|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.330400|0.329500|0.330400|2.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.146520, depth_time=2026-11-08T03:00:10+00:00, book20_bid_proxy_usdt=6925, book20_ask_proxy_usdt=10220, funding_indicative=0.000302, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.73%, turnover=9593526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.005762, depth_time=2026-11-08T03:00:07+00:00, book20_bid_proxy_usdt=25196, book20_ask_proxy_usdt=35778, funding_indicative=-0.000062, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.76%, turnover=50493751. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.157740, depth_time=2026-11-08T03:00:21+00:00, book20_bid_proxy_usdt=154461, book20_ask_proxy_usdt=267353, funding_indicative=-0.000054, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=28447003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.034607, depth_time=2026-11-08T03:00:13+00:00, book20_bid_proxy_usdt=4798, book20_ask_proxy_usdt=5044, funding_indicative=0.000644, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.33%, turnover=16032291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.002107, depth_time=2026-11-08T03:00:16+00:00, book20_bid_proxy_usdt=16163, book20_ask_proxy_usdt=14576, funding_indicative=-0.000077, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.00%, turnover=26946758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.000005, depth_time=2026-11-08T03:00:26+00:00, book20_bid_proxy_usdt=52685, book20_ask_proxy_usdt=43947, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=39673863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=195.930000, depth_time=2026-11-08T03:00:18+00:00, book20_bid_proxy_usdt=89279, book20_ask_proxy_usdt=74107, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=43914254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.438500, depth_time=2026-11-08T03:00:29+00:00, book20_bid_proxy_usdt=344386, book20_ask_proxy_usdt=257791, funding_indicative=0.000019, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=7243328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T02:59:59+00:00, last15m_closed_end=2026-11-08T03:00+00:00, prior8high=0.332400, depth_time=2026-11-08T03:00:24+00:00, book20_bid_proxy_usdt=3288838, book20_ask_proxy_usdt=3723340, funding_indicative=-0.000108, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=26075947. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
