# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T20:00:39Z**
- feed_generated_utc: 2026-11-05T20:00:40+00:00
- source_sha256: `69e0e91c3d7859601ddff0d73ea40b40bb6f8afd3ce43dc4e6c883e9b123765f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002244|-12.61|-89.34|-10.15|18614727|8.89|
|JCT_USDT|0.003093|-10.00|-46.23|-7.54|11940665|3.23|
|FLUID_USDT|2.402000|-7.18|16.37|-4.72|8569168|4.16|
|ETHFI_USDT|0.535300|-5.88|-21.22|-3.42|5310003|1.87|
|XPL_USDT|0.059740|-5.12|-24.31|-2.66|11156778|1.68|
|ENA_USDT|0.165030|-4.94|-22.85|-2.48|49538324|0.61|
|PENGU_USDT|0.006570|-4.87|-19.19|-2.41|6119712|1.52|
|UNI_USDT|6.849000|-4.46|-7.35|-2.00|93382618|1.46|
|ONDO_USDT|0.372300|-4.29|-13.37|-1.83|29047388|2.69|
|NEAR_USDT|3.712000|-4.03|-20.15|-1.57|67513595|5.39|
|DASH_USDT|45.770000|-4.02|-11.10|-1.56|15175962|2.19|
|WLD_USDT|0.344000|-3.88|-21.15|-1.42|77627553|2.91|
|QNT_USDT|192.290000|-3.68|-3.24|-1.22|42700588|1.04|
|ETH_USDT|2260.990000|-3.49|-4.51|-1.03|2136327794|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002244|0.001878|0.002244|0.85|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.770000|43.950000|45.770000|0.47|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.165030|0.159850|0.165010|0.42|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.535300|0.517700|0.535300|0.32|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2260.990000|2242.200000|2260.990000|0.60|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.402000|2.359000|2.402000|0.09|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.003093|0.002969|0.003093|0.32|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.712000|3.638000|3.712000|0.42|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.372300|0.359500|0.372300|0.42|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.006570|0.006345|0.006570|0.33|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.290000|187.630000|192.290000|0.54|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.849000|6.762000|6.849000|0.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.344000|0.336100|0.344000|0.28|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.059740|0.057570|0.059740|0.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.002510, depth_time=2026-11-05T20:00:06+00:00, book20_bid_proxy_usdt=35884, book20_ask_proxy_usdt=17466, funding_indicative=-0.008362, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.61%, turnover=18614727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=45.950000, depth_time=2026-11-05T20:00:30+00:00, book20_bid_proxy_usdt=682398, book20_ask_proxy_usdt=596551, funding_indicative=-0.000012, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=15175962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.165740, depth_time=2026-11-05T20:00:18+00:00, book20_bid_proxy_usdt=100506, book20_ask_proxy_usdt=118059, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.94%, turnover=49538324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.536800, depth_time=2026-11-05T20:00:10+00:00, book20_bid_proxy_usdt=253518, book20_ask_proxy_usdt=176188, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.88%, turnover=5310003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=2265.400000, depth_time=2026-11-05T20:00:38+00:00, book20_bid_proxy_usdt=2153216, book20_ask_proxy_usdt=4750259, funding_indicative=0.000082, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=2136327794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=2.446000, depth_time=2026-11-05T20:00:09+00:00, book20_bid_proxy_usdt=199111, book20_ask_proxy_usdt=144896, funding_indicative=0.000070, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.18%, turnover=8569168. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.003139, depth_time=2026-11-05T20:00:09+00:00, book20_bid_proxy_usdt=119348, book20_ask_proxy_usdt=68328, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.00%, turnover=11940665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=3.733000, depth_time=2026-11-05T20:00:28+00:00, book20_bid_proxy_usdt=786609, book20_ask_proxy_usdt=3855456, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=67513595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.373500, depth_time=2026-11-05T20:00:25+00:00, book20_bid_proxy_usdt=1359335, book20_ask_proxy_usdt=2022010, funding_indicative=-0.000047, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=29047388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.006564, depth_time=2026-11-05T20:00:20+00:00, book20_bid_proxy_usdt=202662, book20_ask_proxy_usdt=146862, funding_indicative=0.000017, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=6119712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=192.450000, depth_time=2026-11-05T20:00:35+00:00, book20_bid_proxy_usdt=69990, book20_ask_proxy_usdt=64707, funding_indicative=0.000061, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=42700588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=6.902000, depth_time=2026-11-05T20:00:23+00:00, book20_bid_proxy_usdt=2053021, book20_ask_proxy_usdt=1590746, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=93382618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.346300, depth_time=2026-11-05T20:00:33+00:00, book20_bid_proxy_usdt=2722146, book20_ask_proxy_usdt=3114722, funding_indicative=-0.000626, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=77627553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-05T20:00:00+00:00, last15m_closed_end=2026-11-05T20:00+00:00, prior8high=0.060150, depth_time=2026-11-05T20:00:15+00:00, book20_bid_proxy_usdt=366796, book20_ask_proxy_usdt=343017, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.12%, turnover=11156778. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
