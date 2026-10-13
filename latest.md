# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T08:00:39Z**
- feed_generated_utc: 2026-10-13T08:00:42+00:00
- source_sha256: `f066867d0aa5a78bb8e4de8c88aa68563b2d5113088a3cfcaac043542284b6f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.227900|-23.11|6.99|-24.66|9372391|4.39|
|W_USDT|0.019287|-20.18|36.37|-21.73|30328618|7.78|
|ZRO_USDT|2.135600|-8.99|4.39|-10.54|25301081|0.47|
|RLC_USDT|0.938000|-8.63|71.16|-10.18|6649764|2.13|
|STRK_USDT|0.085260|-8.59|63.61|-10.14|60966071|1.17|
|NEAR_USDT|5.195000|-6.94|3.44|-8.49|269723431|1.93|
|PUMPFUN_USDT|0.005080|-6.37|-19.81|-7.92|31760693|1.97|
|LIT_USDT|3.429000|-5.26|-9.81|-6.81|10166664|0.29|
|PONS_USDT|0.291600|-2.54|-23.96|-4.09|6145010|3.43|
|HBAR_USDT|0.088170|-2.43|-12.44|-3.98|22397088|1.13|
|JUP_USDT|0.335500|-2.38|-0.71|-3.93|8552415|2.98|
|GRASS_USDT|0.752000|-2.36|6.63|-3.91|6419758|5.32|
|QNT_USDT|227.340000|-0.51|-11.46|-2.06|75348618|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.227900|0.228000|0.227900|1.17|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.752000|0.759600|0.752000|5.38|Y|Y/Y|N/N|N|N|
|HBAR_USDT|0.088170|0.087450|0.088170|1.46|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.335500|0.334000|0.335500|0.08|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.429000|3.407500|3.429000|1.64|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.195000|5.151000|5.195000|1.08|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.291600|0.287500|0.291600|0.84|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005080|0.005044|0.005080|0.93|N|Y/Y|Y/Y|N|N|
|QNT_USDT|227.340000|227.080000|227.340000|0.77|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.938000|0.917000|0.938000|2.32|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085260|0.083010|0.085260|0.89|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019287|0.019044|0.019287|0.46|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.135600|2.075100|2.135600|1.69|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.235200, depth_time=2026-10-13T08:00:07+00:00, book20_bid_proxy_usdt=94959, book20_ask_proxy_usdt=55806, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.11%, turnover=9372391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.794800, depth_time=2026-10-13T08:00:36+00:00, book20_bid_proxy_usdt=126091, book20_ask_proxy_usdt=97463, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=6419758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.088300, depth_time=2026-10-13T08:00:30+00:00, book20_bid_proxy_usdt=370152, book20_ask_proxy_usdt=651897, funding_indicative=-0.000017, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=22397088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T08:00:01+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.339200, depth_time=2026-10-13T08:00:33+00:00, book20_bid_proxy_usdt=612354, book20_ask_proxy_usdt=453778, funding_indicative=-0.000006, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=8552415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T08:00:01+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=3.465900, depth_time=2026-10-13T08:00:23+00:00, book20_bid_proxy_usdt=23662, book20_ask_proxy_usdt=27381, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.26%, turnover=10166664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=5.340000, depth_time=2026-10-13T08:00:19+00:00, book20_bid_proxy_usdt=2881292, book20_ask_proxy_usdt=1918382, funding_indicative=-0.000027, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.94%, turnover=269723431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.295200, depth_time=2026-10-13T08:00:27+00:00, book20_bid_proxy_usdt=217261, book20_ask_proxy_usdt=196467, funding_indicative=0.000060, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=6145010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.005142, depth_time=2026-10-13T08:00:22+00:00, book20_bid_proxy_usdt=1587001, book20_ask_proxy_usdt=1067910, funding_indicative=0.000005, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.37%, turnover=31760693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=231.390000, depth_time=2026-10-13T08:00:38+00:00, book20_bid_proxy_usdt=49672, book20_ask_proxy_usdt=63432, funding_indicative=0.000047, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=75348618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.963200, depth_time=2026-10-13T08:00:14+00:00, book20_bid_proxy_usdt=40510, book20_ask_proxy_usdt=48232, funding_indicative=-0.000875, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.63%, turnover=6649764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.088100, depth_time=2026-10-13T08:00:17+00:00, book20_bid_proxy_usdt=246207, book20_ask_proxy_usdt=152564, funding_indicative=0.000007, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.59%, turnover=60966071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=0.019841, depth_time=2026-10-13T08:00:09+00:00, book20_bid_proxy_usdt=10895, book20_ask_proxy_usdt=22645, funding_indicative=-0.000519, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.18%, turnover=30328618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T08:00:00+00:00, last15m_closed_end=2026-10-13T08:00+00:00, prior8high=2.157300, depth_time=2026-10-13T08:00:13+00:00, book20_bid_proxy_usdt=36587, book20_ask_proxy_usdt=25717, funding_indicative=-0.000039, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.99%, turnover=25301081. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
