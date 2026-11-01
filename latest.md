# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T07:15:28Z**
- feed_generated_utc: 2026-11-01T07:15:30+00:00
- source_sha256: `a8cc86c8abc018fa306a8644971645589c17080b3f836f7a5dc8db900854a42e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T07:15+00:00, close=77873, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T07:00+00:00, close=77974.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.231750|-21.74|38.01|-22.14|31165386|0.43|
|AKE_USDT|0.009361|-15.95|-67.97|-16.35|11514301|4.28|
|BLESS_USDT|0.009438|-10.65|16.33|-11.05|6234778|5.30|
|XPL_USDT|0.073440|-9.67|1.70|-10.07|5751527|2.73|
|ZEC_USDT|1242.550000|-3.26|8.49|-3.66|936910613|0.08|
|ENA_USDT|0.187720|-3.24|0.49|-3.64|42641377|0.53|
|NEAR_USDT|4.360000|-2.59|-0.95|-2.99|53793237|2.29|
|XLM_USDT|0.168950|-1.62|0.32|-2.02|19985975|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009361|0.009269|0.009361|0.68|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009438|0.009421|0.009434|0.85|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187720|0.187160|0.187620|0.45|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.231750|0.231890|0.231700|1.03|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.360000|4.363000|4.360000|1.66|Y|Y/Y|N/N|Y|N|
|XLM_USDT|0.168950|0.168360|0.168950|0.85|N|N/Y|Y/N|Y|N|
|XPL_USDT|0.073440|0.070520|0.073430|1.22|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1242.550000|1241.440000|1242.550000|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T07:15:00+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=0.010385, depth_time=2026-11-01T07:15:10+00:00, book20_bid_proxy_usdt=4684, book20_ask_proxy_usdt=9807, funding_indicative=-0.001918, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.95%, turnover=11514301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T07:15:00+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=0.009785, depth_time=2026-11-01T07:15:13+00:00, book20_bid_proxy_usdt=22614, book20_ask_proxy_usdt=17442, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.65%, turnover=6234778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T07:14:59+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=0.190760, depth_time=2026-11-01T07:15:22+00:00, book20_bid_proxy_usdt=172184, book20_ask_proxy_usdt=60965, funding_indicative=-0.000012, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=42641377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T07:15:03+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=0.247730, depth_time=2026-11-01T07:15:08+00:00, book20_bid_proxy_usdt=8279, book20_ask_proxy_usdt=3533, funding_indicative=-0.002309, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-21.74%, turnover=31165386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T07:15:03+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=4.410000, depth_time=2026-11-01T07:15:24+00:00, book20_bid_proxy_usdt=4767705, book20_ask_proxy_usdt=3256020, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=53793237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T07:15:00+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=0.169690, depth_time=2026-11-01T07:15:25+00:00, book20_bid_proxy_usdt=166668, book20_ask_proxy_usdt=158699, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=19985975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T07:15:00+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=0.074870, depth_time=2026-11-01T07:15:16+00:00, book20_bid_proxy_usdt=371044, book20_ask_proxy_usdt=302608, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.67%, turnover=5751527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T07:15:00+00:00, last15m_closed_end=2026-11-01T07:15+00:00, prior8high=1254.820000, depth_time=2026-11-01T07:15:19+00:00, book20_bid_proxy_usdt=989204, book20_ask_proxy_usdt=200816, funding_indicative=-0.000114, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=936910613. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
