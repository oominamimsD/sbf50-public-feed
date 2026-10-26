# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T06:45:42Z**
- feed_generated_utc: 2026-10-26T06:45:45+00:00
- source_sha256: `14a58d7084b2f28908c8516b1e1db0b1b7f189a12e462b9063ec209178fda9b1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T06:45+00:00, close=79944.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T06:00+00:00, close=80234.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.031490|-18.08|158.11|-17.27|13809257|6.36|
|APR_USDT|0.035540|-13.96|30.46|-13.15|10452916|5.63|
|T_USDT|0.004800|-10.83|2.08|-10.02|5813562|4.17|
|WLD_USDT|0.437000|-4.29|-8.25|-3.48|72285970|2.29|
|BTW_USDT|1.593800|-3.92|-30.86|-3.11|12716373|1.88|
|XMR_USDT|585.700000|-3.55|0.54|-2.74|6444564|0.51|
|DOT_USDT|1.004000|-3.38|-6.11|-2.57|11359903|1.00|
|LIT_USDT|3.088000|-2.84|5.37|-2.03|6103230|0.32|
|TIA_USDT|0.522200|-2.77|-15.48|-1.96|18022463|3.83|
|PUMPFUN_USDT|0.004168|-2.73|-0.64|-1.92|16672174|2.40|
|DASH_USDT|51.080000|-2.53|6.68|-1.72|12189067|1.96|
|STRK_USDT|0.044680|-2.31|-27.42|-1.50|9625620|2.24|
|NEAR_USDT|4.442000|-2.24|-6.24|-1.43|132854244|2.25|
|INJ_USDT|7.536000|-2.18|-7.20|-1.37|25732925|1.33|
|APT_USDT|0.687700|-1.99|-10.52|-1.18|6238795|2.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035540|0.034230|0.035540|0.69|N|Y/Y|N/N|Y|N|
|APT_USDT|0.687700|0.686800|0.687700|1.58|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.593800|1.608600|1.593100|1.66|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|51.080000|50.650000|51.080000|0.51|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004000|1.002800|1.004300|0.95|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.536000|7.535000|7.536000|0.55|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.031490|0.030290|0.031490|1.26|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.088000|3.010300|3.088000|0.32|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.442000|4.451000|4.442000|1.05|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004168|0.004156|0.004168|0.33|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044680|0.044600|0.044680|8.48|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.522200|0.519000|0.522500|0.62|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004800|0.004814|0.004800|1.76|Y|Y/Y|Y/N|Y|N|
|WLD_USDT|0.437000|0.437400|0.436900|0.82|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|585.700000|587.680000|585.700000|1.59|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T06:45:00+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.037240, depth_time=2026-10-26T06:45:10+00:00, book20_bid_proxy_usdt=58246, book20_ask_proxy_usdt=76669, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.96%, turnover=10452916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.705000, depth_time=2026-10-26T06:45:41+00:00, book20_bid_proxy_usdt=141707, book20_ask_proxy_usdt=187391, funding_indicative=-0.000031, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=6238795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=1.667700, depth_time=2026-10-26T06:45:17+00:00, book20_bid_proxy_usdt=10857, book20_ask_proxy_usdt=14388, funding_indicative=-0.004026, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=12716373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=51.450000, depth_time=2026-10-26T06:45:24+00:00, book20_bid_proxy_usdt=905359, book20_ask_proxy_usdt=602048, funding_indicative=0.000059, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=12189067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=1.024300, depth_time=2026-10-26T06:45:22+00:00, book20_bid_proxy_usdt=276104, book20_ask_proxy_usdt=330140, funding_indicative=-0.000076, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=11359903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=7.718000, depth_time=2026-10-26T06:45:38+00:00, book20_bid_proxy_usdt=442176, book20_ask_proxy_usdt=455591, funding_indicative=0.000091, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=25732925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T06:45:00+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.035930, depth_time=2026-10-26T06:45:07+00:00, book20_bid_proxy_usdt=125389, book20_ask_proxy_usdt=53772, funding_indicative=-0.000502, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-18.08%, turnover=13809257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=3.121800, depth_time=2026-10-26T06:45:22+00:00, book20_bid_proxy_usdt=19973, book20_ask_proxy_usdt=16835, funding_indicative=0.000023, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=6103230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T06:45:00+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=4.541000, depth_time=2026-10-26T06:45:36+00:00, book20_bid_proxy_usdt=3140614, book20_ask_proxy_usdt=3582925, funding_indicative=0.000067, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=132854244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.004233, depth_time=2026-10-26T06:45:28+00:00, book20_bid_proxy_usdt=2554670, book20_ask_proxy_usdt=2226454, funding_indicative=-0.000011, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=16672174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.045380, depth_time=2026-10-26T06:45:34+00:00, book20_bid_proxy_usdt=932296, book20_ask_proxy_usdt=747957, funding_indicative=0.000004, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=9625620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.536500, depth_time=2026-10-26T06:45:27+00:00, book20_bid_proxy_usdt=281724, book20_ask_proxy_usdt=292618, funding_indicative=-0.000054, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=18022463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T06:45:00+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.004948, depth_time=2026-10-26T06:45:09+00:00, book20_bid_proxy_usdt=101432, book20_ask_proxy_usdt=82241, funding_indicative=-0.000721, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-10.83%, turnover=5813562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T06:45:00+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=0.446600, depth_time=2026-10-26T06:45:14+00:00, book20_bid_proxy_usdt=2277855, book20_ask_proxy_usdt=2684402, funding_indicative=-0.000051, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=72285970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T06:45:01+00:00, last15m_closed_end=2026-10-26T06:45+00:00, prior8high=593.530000, depth_time=2026-10-26T06:45:14+00:00, book20_bid_proxy_usdt=10394, book20_ask_proxy_usdt=24946, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=6444564. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
