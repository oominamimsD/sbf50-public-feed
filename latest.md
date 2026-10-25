# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T13:15:35Z**
- feed_generated_utc: 2026-10-25T13:15:38+00:00
- source_sha256: `ef595383e3e0ef0b087e4e9fa1bd3de49e2a78b312f38d9962656ce8b93925bd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T13:15+00:00, close=80382.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T13:00+00:00, close=80419.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.046580|-30.89|50.50|-31.66|6696590|4.30|
|IRYS_USDT|0.034970|-24.06|174.05|-24.83|25505490|2.86|
|STRK_USDT|0.045400|-2.84|-31.36|-3.61|10132120|2.20|
|BTW_USDT|1.694200|-2.70|-25.34|-3.47|12430630|1.77|
|DOT_USDT|1.025800|-1.27|-8.19|-2.04|12533866|0.97|
|SEI_USDT|0.052350|-1.00|-15.57|-1.77|7689082|1.91|
|SUI_USDT|0.917500|-0.81|-6.54|-1.58|69567271|1.09|
|APT_USDT|0.696300|-0.79|-12.68|-1.56|6078153|2.87|
|PENGU_USDT|0.007398|-0.60|-0.73|-1.37|5865865|1.35|
|TIA_USDT|0.523000|-0.51|-20.51|-1.28|20212962|1.91|
|ARB_USDT|0.165270|-0.28|-10.14|-1.05|15877028|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.696300|0.689400|0.696300|0.30|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165270|0.163860|0.165270|0.41|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.694200|1.638700|1.694200|1.90|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.025800|1.013200|1.025800|0.49|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034970|0.033220|0.034760|1.90|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.046580|0.045450|0.046580|1.24|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007398|0.007338|0.007395|0.61|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052350|0.052260|0.052350|2.82|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045400|0.044870|0.045400|0.82|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.917500|0.909200|0.917500|0.76|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.523000|0.523600|0.523000|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.698900, depth_time=2026-10-25T13:15:26+00:00, book20_bid_proxy_usdt=142120, book20_ask_proxy_usdt=172528, funding_indicative=-0.000131, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=6078153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.166330, depth_time=2026-10-25T13:15:33+00:00, book20_bid_proxy_usdt=80454, book20_ask_proxy_usdt=67788, funding_indicative=0.000054, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.28%, turnover=15877028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=1.699100, depth_time=2026-10-25T13:15:14+00:00, book20_bid_proxy_usdt=11525, book20_ask_proxy_usdt=25898, funding_indicative=-0.011482, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=12430630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=1.028700, depth_time=2026-10-25T13:15:18+00:00, book20_bid_proxy_usdt=267384, book20_ask_proxy_usdt=398634, funding_indicative=-0.000061, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=12533866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T13:15:01+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.036110, depth_time=2026-10-25T13:15:11+00:00, book20_bid_proxy_usdt=56791, book20_ask_proxy_usdt=26278, funding_indicative=0.000012, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-24.06%, turnover=25505490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T13:15:01+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.050170, depth_time=2026-10-25T13:15:08+00:00, book20_bid_proxy_usdt=90691, book20_ask_proxy_usdt=67134, funding_indicative=-0.000907, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-30.89%, turnover=6696590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.007422, depth_time=2026-10-25T13:15:27+00:00, book20_bid_proxy_usdt=182621, book20_ask_proxy_usdt=254475, funding_indicative=-0.000061, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.60%, turnover=5865865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.052880, depth_time=2026-10-25T13:15:19+00:00, book20_bid_proxy_usdt=201396, book20_ask_proxy_usdt=393471, funding_indicative=-0.000070, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=7689082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.046180, depth_time=2026-10-25T13:15:12+00:00, book20_bid_proxy_usdt=774781, book20_ask_proxy_usdt=737709, funding_indicative=0.000001, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=10132120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T13:15:01+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.920400, depth_time=2026-10-25T13:15:24+00:00, book20_bid_proxy_usdt=797080, book20_ask_proxy_usdt=1751456, funding_indicative=-0.000031, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=69567271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T13:15:02+00:00, last15m_closed_end=2026-10-25T13:15+00:00, prior8high=0.532800, depth_time=2026-10-25T13:15:31+00:00, book20_bid_proxy_usdt=417578, book20_ask_proxy_usdt=339817, funding_indicative=-0.000029, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.51%, turnover=20212962. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
