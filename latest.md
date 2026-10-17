# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T06:30:38Z**
- feed_generated_utc: 2026-10-17T06:30:40+00:00
- source_sha256: `f9928f2a1c832993e8ffa71b6d74ee918cfa767f7c1d30ae4b46398dd527a8cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T06:30+00:00, close=81581.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T06:00+00:00, close=81542.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.968000|-6.34|-3.37|-6.65|13983274|0.51|
|STRK_USDT|0.070710|-4.38|-6.10|-4.69|21645430|1.41|
|BAT_USDT|0.197110|-3.86|62.01|-4.17|14288524|3.55|
|ARB_USDT|0.188820|-3.13|4.43|-3.44|32340100|0.53|
|FET_USDT|0.194500|-2.55|-10.36|-2.86|12085096|5.14|
|APT_USDT|0.836700|-2.26|4.52|-2.57|11886541|1.20|
|OP_USDT|0.136900|-2.21|11.10|-2.52|14705702|0.73|
|ZEC_USDT|1162.090000|-2.18|-4.62|-2.49|1362216586|0.09|
|TAO_USDT|275.000000|-2.00|0.12|-2.31|70468244|0.73|
|SUI_USDT|1.009700|-1.05|-4.52|-1.36|93183150|0.99|
|AVAX_USDT|9.981000|-1.01|-2.07|-1.32|116599410|1.00|
|ICP_USDT|3.016000|-0.72|-0.09|-1.03|8996513|3.32|
|AAVE_USDT|156.160000|-0.71|-8.05|-1.02|27724649|0.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|156.160000|155.510000|156.160000|1.28|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.836700|0.838300|0.836800|1.91|Y|Y/Y|N/N|Y|N|
|ARB_USDT|0.188820|0.189400|0.188840|0.52|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.981000|9.972000|9.985000|0.83|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.197110|0.194790|0.197110|1.37|N|Y/N|N/N|Y|N|
|FET_USDT|0.194500|0.193700|0.194500|0.95|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.016000|3.010000|3.016000|1.17|N|N/N|Y/Y|Y|N|
|OP_USDT|0.136900|0.136620|0.136910|1.58|N|Y/N|Y/Y|Y|N|
|STRK_USDT|0.070710|0.070440|0.070710|0.63|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.009700|1.008500|1.009900|1.09|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.000000|274.400000|275.040000|1.18|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1162.090000|1151.950000|1162.440000|0.77|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.968000|1.960500|1.968000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=156.680000, depth_time=2026-10-17T06:30:35+00:00, book20_bid_proxy_usdt=351364, book20_ask_proxy_usdt=366836, funding_indicative=0.000045, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=27724649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=0.856200, depth_time=2026-10-17T06:30:20+00:00, book20_bid_proxy_usdt=102062, book20_ask_proxy_usdt=149834, funding_indicative=0.000072, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=11886541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=0.192330, depth_time=2026-10-17T06:30:15+00:00, book20_bid_proxy_usdt=72981, book20_ask_proxy_usdt=41416, funding_indicative=-0.000035, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=32340100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=10.037000, depth_time=2026-10-17T06:30:31+00:00, book20_bid_proxy_usdt=892083, book20_ask_proxy_usdt=485789, funding_indicative=0.000041, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=116599410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=0.201780, depth_time=2026-10-17T06:30:13+00:00, book20_bid_proxy_usdt=18650, book20_ask_proxy_usdt=26605, funding_indicative=-0.000040, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=14288524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=0.196300, depth_time=2026-10-17T06:30:17+00:00, book20_bid_proxy_usdt=1787504, book20_ask_proxy_usdt=1029959, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=12085096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=3.062000, depth_time=2026-10-17T06:30:35+00:00, book20_bid_proxy_usdt=866639, book20_ask_proxy_usdt=1270929, funding_indicative=0.000032, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.72%, turnover=8996513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=0.140730, depth_time=2026-10-17T06:30:23+00:00, book20_bid_proxy_usdt=39882, book20_ask_proxy_usdt=39918, funding_indicative=-0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=14705702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=0.072130, depth_time=2026-10-17T06:30:11+00:00, book20_bid_proxy_usdt=301591, book20_ask_proxy_usdt=363545, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=21645430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=1.019400, depth_time=2026-10-17T06:30:30+00:00, book20_bid_proxy_usdt=885812, book20_ask_proxy_usdt=819084, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=93183150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=277.150000, depth_time=2026-10-17T06:30:27+00:00, book20_bid_proxy_usdt=63861, book20_ask_proxy_usdt=63590, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=70468244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=1168.180000, depth_time=2026-10-17T06:30:25+00:00, book20_bid_proxy_usdt=522610, book20_ask_proxy_usdt=234471, funding_indicative=0.000008, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=1362216586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T06:30:01+00:00, last15m_closed_end=2026-10-17T06:30+00:00, prior8high=1.992900, depth_time=2026-10-17T06:30:07+00:00, book20_bid_proxy_usdt=57002, book20_ask_proxy_usdt=33535, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=13983274. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
