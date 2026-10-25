# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T11:30:40Z**
- feed_generated_utc: 2026-10-25T11:30:44+00:00
- source_sha256: `808f667ac1eca93b24c9a478577ca50c2d389c466962ea1540911dc0c4c311a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T11:30+00:00, close=80377.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T11:00+00:00, close=80246.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.048050|-28.70|55.25|-29.46|9649636|4.16|
|IRYS_USDT|0.034900|-24.21|173.51|-24.97|29258139|2.87|
|BTW_USDT|1.667300|-4.24|-26.53|-5.00|11386951|0.60|
|STRK_USDT|0.044940|-3.83|-32.06|-4.59|9293056|2.23|
|WLD_USDT|0.444800|-3.72|-10.25|-4.48|93903091|2.25|
|DOT_USDT|1.016600|-2.16|-9.02|-2.92|12280281|0.98|
|APT_USDT|0.691500|-1.48|-13.29|-2.24|5942122|1.45|
|SUI_USDT|0.911900|-1.41|-7.11|-2.17|67856681|1.10|
|ARB_USDT|0.163910|-1.10|-10.87|-1.86|15926334|0.61|
|PENGU_USDT|0.007363|-1.07|-1.20|-1.83|5713167|1.36|
|SEI_USDT|0.052340|-1.02|-15.59|-1.78|7793979|1.91|
|ONDO_USDT|0.399900|-0.37|-9.03|-1.13|15333149|2.50|
|LINK_USDT|11.343000|-0.34|-4.72|-1.10|47471778|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.691500|0.687600|0.691600|0.98|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.163910|0.163130|0.163910|1.37|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.667300|1.610600|1.666900|0.66|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.016600|1.011600|1.016600|1.86|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034900|0.034380|0.034870|0.72|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.343000|11.255000|11.343000|0.83|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.399900|0.396800|0.399900|0.98|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.048050|0.048920|0.048050|1.36|Y|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007363|0.007294|0.007364|3.05|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052340|0.051870|0.052340|0.64|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044940|0.044950|0.044940|2.85|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.911900|0.903500|0.911900|0.65|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.444800|0.441100|0.444800|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T11:30:01+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.695500, depth_time=2026-10-25T11:30:24+00:00, book20_bid_proxy_usdt=141980, book20_ask_proxy_usdt=134286, funding_indicative=-0.000127, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=5942122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.165000, depth_time=2026-10-25T11:30:29+00:00, book20_bid_proxy_usdt=69335, book20_ask_proxy_usdt=109637, funding_indicative=0.000057, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=15926334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=1.695000, depth_time=2026-10-25T11:30:14+00:00, book20_bid_proxy_usdt=7996, book20_ask_proxy_usdt=9344, funding_indicative=-0.017630, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=11386951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=1.026000, depth_time=2026-10-25T11:30:21+00:00, book20_bid_proxy_usdt=339068, book20_ask_proxy_usdt=369716, funding_indicative=-0.000054, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=12280281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.036280, depth_time=2026-10-25T11:30:11+00:00, book20_bid_proxy_usdt=70767, book20_ask_proxy_usdt=38134, funding_indicative=-0.000609, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=1, 24h_change=-24.21%, turnover=29258139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=11.356000, depth_time=2026-10-25T11:30:40+00:00, book20_bid_proxy_usdt=581463, book20_ask_proxy_usdt=487062, funding_indicative=-0.000017, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.34%, turnover=47471778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.401400, depth_time=2026-10-25T11:30:35+00:00, book20_bid_proxy_usdt=3468628, book20_ask_proxy_usdt=2188349, funding_indicative=0.000008, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.37%, turnover=15333149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.053130, depth_time=2026-10-25T11:30:08+00:00, book20_bid_proxy_usdt=68052, book20_ask_proxy_usdt=126679, funding_indicative=-0.001529, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=1, 24h_change=-28.70%, turnover=9649636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T11:30:01+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.007392, depth_time=2026-10-25T11:30:30+00:00, book20_bid_proxy_usdt=248008, book20_ask_proxy_usdt=194002, funding_indicative=-0.000068, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.07%, turnover=5713167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T11:30:01+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.052560, depth_time=2026-10-25T11:30:34+00:00, book20_bid_proxy_usdt=372429, book20_ask_proxy_usdt=297371, funding_indicative=-0.000118, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=7793979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T11:30:01+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.045550, depth_time=2026-10-25T11:30:16+00:00, book20_bid_proxy_usdt=918199, book20_ask_proxy_usdt=869129, funding_indicative=0.000046, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=9293056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.913700, depth_time=2026-10-25T11:30:27+00:00, book20_bid_proxy_usdt=2006988, book20_ask_proxy_usdt=1129553, funding_indicative=-0.000004, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=67856681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T11:30:00+00:00, last15m_closed_end=2026-10-25T11:30+00:00, prior8high=0.447500, depth_time=2026-10-25T11:30:19+00:00, book20_bid_proxy_usdt=1984407, book20_ask_proxy_usdt=1736984, funding_indicative=0.000002, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=93903091. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
