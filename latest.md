# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T11:15:36Z**
- feed_generated_utc: 2026-11-03T11:15:38+00:00
- source_sha256: `cfb95cc4f5b3208d54baa45169891108aed9c5254ccf283f9e73ee9714668a20`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T11:15+00:00, close=77171.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T11:00+00:00, close=77103.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.884300|-19.37|-26.04|-18.97|10218071|2.26|
|XPL_USDT|0.064450|-7.37|-13.24|-6.97|11311455|1.55|
|ZEC_USDT|1171.100000|-6.61|-6.14|-6.21|1780731567|0.09|
|NEAR_USDT|3.852000|-3.94|-15.76|-3.54|76985292|2.60|
|SILVER_USDT|49.190000|-3.66|-9.29|-3.26|431375388|2.03|
|TIA_USDT|0.440400|-3.61|-17.78|-3.21|12682865|2.27|
|XLM_USDT|0.162860|-2.82|-3.96|-2.42|34179323|0.61|
|DASH_USDT|45.950000|-2.64|-12.00|-2.24|9032821|2.18|
|ENA_USDT|0.170580|-2.54|-18.91|-2.14|67929773|0.59|
|OP_USDT|0.109820|-2.32|-1.68|-1.92|10351961|1.82|
|FARTCOIN_USDT|0.117070|-1.83|-8.77|-1.43|9799395|0.85|
|APT_USDT|0.616700|-1.65|-12.15|-1.25|5230461|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.616700|0.611100|0.616700|2.58|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.884300|0.887500|0.882600|4.29|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|45.950000|45.610000|45.950000|3.76|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170580|0.168610|0.170580|1.68|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117070|0.115250|0.117070|2.92|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.852000|3.782000|3.852000|1.11|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109820|0.107580|0.109820|1.60|N|N/Y|Y/Y|Y|N|
|SILVER_USDT|49.190000|48.730000|49.200000|0.51|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.440400|0.436200|0.440400|2.64|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162860|0.161080|0.162860|1.77|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064450|0.063400|0.064430|3.96|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1171.100000|1126.070000|1171.320000|2.09|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.616100, depth_time=2026-11-03T11:15:35+00:00, book20_bid_proxy_usdt=203867, book20_ask_proxy_usdt=206423, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=5230461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.930000, depth_time=2026-11-03T11:15:08+00:00, book20_bid_proxy_usdt=39787, book20_ask_proxy_usdt=21483, funding_indicative=-0.000336, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.37%, turnover=10218071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=45.880000, depth_time=2026-11-03T11:15:25+00:00, book20_bid_proxy_usdt=721228, book20_ask_proxy_usdt=635661, funding_indicative=0.000098, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=9032821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T11:15:02+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.170450, depth_time=2026-11-03T11:15:29+00:00, book20_bid_proxy_usdt=215794, book20_ask_proxy_usdt=165808, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=67929773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.116620, depth_time=2026-11-03T11:15:32+00:00, book20_bid_proxy_usdt=90814, book20_ask_proxy_usdt=76163, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=9799395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T11:15:02+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=3.849000, depth_time=2026-11-03T11:15:17+00:00, book20_bid_proxy_usdt=4977754, book20_ask_proxy_usdt=4351166, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=76985292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.109550, depth_time=2026-11-03T11:15:31+00:00, book20_bid_proxy_usdt=190392, book20_ask_proxy_usdt=172417, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=10351961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T11:15:02+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=49.150000, depth_time=2026-11-03T11:15:19+00:00, book20_bid_proxy_usdt=50891580, book20_ask_proxy_usdt=52261594, funding_indicative=0.000046, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=431375388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.440000, depth_time=2026-11-03T11:15:21+00:00, book20_bid_proxy_usdt=347677, book20_ask_proxy_usdt=394388, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.61%, turnover=12682865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.162210, depth_time=2026-11-03T11:15:21+00:00, book20_bid_proxy_usdt=272823, book20_ask_proxy_usdt=192042, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=34179323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T11:15:03+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=0.064320, depth_time=2026-11-03T11:15:10+00:00, book20_bid_proxy_usdt=513402, book20_ask_proxy_usdt=359324, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.37%, turnover=11311455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T11:15:02+00:00, last15m_closed_end=2026-11-03T11:15+00:00, prior8high=1163.710000, depth_time=2026-11-03T11:15:14+00:00, book20_bid_proxy_usdt=221112, book20_ask_proxy_usdt=736214, funding_indicative=0.000028, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.61%, turnover=1780731567. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
