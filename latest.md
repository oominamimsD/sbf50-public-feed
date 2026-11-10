# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T19:15:35Z**
- feed_generated_utc: 2026-11-10T19:15:37+00:00
- source_sha256: `2a4c946611b0aea78f45a55d46f363ef5c87f29b3cede311d6f0e544de5cc915`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T19:15+00:00, close=73326.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T19:00+00:00, close=73455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.854900|-8.44|57.81|-8.64|7973727|1.08|
|ZEC_USDT|1027.780000|-5.99|-14.62|-6.19|2308472161|0.10|
|DASH_USDT|43.220000|-4.25|-6.32|-4.45|13277858|2.31|
|JCT_USDT|0.005147|-2.42|23.19|-2.62|21544613|1.95|
|UNI_USDT|6.666000|-2.40|-9.34|-2.60|28440079|1.50|
|AKE_USDT|0.002852|-2.12|-31.37|-2.32|15774656|3.51|
|ANTHROPIC_USDT|1296.490000|-1.59|-22.54|-1.79|8016544|3.39|
|ONDO_USDT|0.360200|-1.53|-7.45|-1.73|14889276|2.78|
|ARB_USDT|0.159290|-1.29|-0.36|-1.49|34131439|0.63|
|VVV_USDT|19.058000|-0.94|-14.77|-1.14|5032005|0.53|
|ENA_USDT|0.147810|-0.92|-14.15|-1.12|29258846|0.68|
|TIA_USDT|0.420900|-0.91|-3.41|-1.11|9484324|2.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002852|0.002739|0.002852|0.89|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1296.490000|1287.140000|1296.490000|0.41|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159290|0.155570|0.159290|0.31|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.220000|42.350000|43.220000|0.25|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.147810|0.146650|0.147800|1.10|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005147|0.005014|0.005147|0.74|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360200|0.355900|0.360200|0.30|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.854900|1.808000|1.854900|0.85|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.420900|0.412300|0.421100|1.34|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.666000|6.608000|6.666000|0.43|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.058000|18.330000|19.058000|1.13|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1027.780000|998.600000|1027.510000|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=0.002954, depth_time=2026-11-10T19:15:19+00:00, book20_bid_proxy_usdt=54527, book20_ask_proxy_usdt=23013, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=15774656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=1325.380000, depth_time=2026-11-10T19:15:23+00:00, book20_bid_proxy_usdt=11268, book20_ask_proxy_usdt=11454, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=8016544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=0.160280, depth_time=2026-11-10T19:15:27+00:00, book20_bid_proxy_usdt=99730, book20_ask_proxy_usdt=699168, funding_indicative=-0.000189, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=34131439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=43.750000, depth_time=2026-11-10T19:15:12+00:00, book20_bid_proxy_usdt=727248, book20_ask_proxy_usdt=681556, funding_indicative=-0.000141, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.25%, turnover=13277858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=0.150710, depth_time=2026-11-10T19:15:32+00:00, book20_bid_proxy_usdt=202279, book20_ask_proxy_usdt=153375, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=29258846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=0.005415, depth_time=2026-11-10T19:15:14+00:00, book20_bid_proxy_usdt=51616, book20_ask_proxy_usdt=48685, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=21544613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=0.364800, depth_time=2026-11-10T19:15:25+00:00, book20_bid_proxy_usdt=3211884, book20_ask_proxy_usdt=2493110, funding_indicative=-0.000011, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=14889276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=1.885500, depth_time=2026-11-10T19:15:05+00:00, book20_bid_proxy_usdt=17405, book20_ask_proxy_usdt=15720, funding_indicative=0.000116, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.44%, turnover=7973727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=0.426100, depth_time=2026-11-10T19:15:33+00:00, book20_bid_proxy_usdt=282576, book20_ask_proxy_usdt=400096, funding_indicative=0.000016, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=9484324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=6.745000, depth_time=2026-11-10T19:15:16+00:00, book20_bid_proxy_usdt=1602460, book20_ask_proxy_usdt=2801810, funding_indicative=-0.000025, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=28440079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=19.408000, depth_time=2026-11-10T19:15:28+00:00, book20_bid_proxy_usdt=24442, book20_ask_proxy_usdt=26785, funding_indicative=-0.000027, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=5032005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T19:15:02+00:00, last15m_closed_end=2026-11-10T19:15+00:00, prior8high=1045.180000, depth_time=2026-11-10T19:15:10+00:00, book20_bid_proxy_usdt=161355, book20_ask_proxy_usdt=68047, funding_indicative=-0.000033, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.99%, turnover=2308472161. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
