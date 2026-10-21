# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T23:15:43Z**
- feed_generated_utc: 2026-10-21T23:15:47+00:00
- source_sha256: `623e04c4ce9e75d68b0eb781e2e255a48bfa7c8a39e06cd35c7fca34336ec6a4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T23:15+00:00, close=84341.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T23:00+00:00, close=84408, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.001185|-19.04|48.09|-18.86|14525261|2.53|
|DOOD_USDT|0.002352|-17.29|65.86|-17.11|9123486|8.51|
|BR_USDT|0.484720|-10.49|18.87|-10.31|14576823|1.24|
|AKE_USDT|0.024264|-9.08|-6.24|-8.90|10774627|0.41|
|STRK_USDT|0.057700|-6.89|-25.23|-6.71|23861982|1.73|
|ZRO_USDT|1.952900|-6.88|3.11|-6.70|7237382|1.54|
|JCT_USDT|0.004070|-4.25|93.71|-4.07|13146229|9.83|
|TIA_USDT|0.607800|-3.90|13.92|-3.72|38998484|1.65|
|ARB_USDT|0.188920|-3.90|3.72|-3.72|33161975|0.53|
|DOT_USDT|1.151100|-2.44|2.36|-2.26|16030646|0.87|
|LDO_USDT|0.406100|-2.19|0.07|-2.01|5208251|2.46|
|OP_USDT|0.129060|-2.15|-6.70|-1.97|6851396|0.78|
|ICP_USDT|2.904000|-2.09|-3.10|-1.91|5611442|3.44|
|AVAX_USDT|9.710000|-2.07|-1.08|-1.89|155401595|1.03|
|TAO_USDT|272.500000|-1.81|1.69|-1.63|60859020|1.10|
|AAVE_USDT|155.930000|-1.62|0.02|-1.44|130959314|1.28|
|DOGE_USDT|0.082090|-1.62|0.13|-1.44|83003837|1.22|
|APT_USDT|0.822300|-1.59|3.99|-1.41|8161504|1.22|
|UNI_USDT|7.503000|-1.53|5.02|-1.35|26113069|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.024264|0.024305|0.024264|1.74|Y|Y/Y|Y/Y|N|Y|
|ARB_USDT|0.188920|0.190680|0.188940|2.83|Y|Y/N|N/N|N|N|
|AVAX_USDT|9.710000|9.698000|9.710000|1.98|N|Y/N|N/N|N|N|
|BR_USDT|0.484720|0.479170|0.484720|0.57|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002352|0.002280|0.002366|0.63|N|Y/Y|N/N|N|N|
|DOT_USDT|1.151100|1.149600|1.151200|1.65|N|Y/Y|N/N|N|N|
|ICP_USDT|2.904000|2.905000|2.904000|1.54|Y|Y/Y|N/N|N|N|
|IOST_USDT|0.001185|0.001132|0.001185|2.57|N|Y/N|N/N|N|N|
|JCT_USDT|0.004070|0.004087|0.004072|0.97|N|Y/Y|N/N|N|N|
|LDO_USDT|0.406100|0.404800|0.406200|0.90|N|Y/Y|N/N|N|N|
|OP_USDT|0.129060|0.128880|0.129070|2.52|N|Y/Y|N/N|N|N|
|STRK_USDT|0.057700|0.058100|0.057700|1.30|Y|Y/N|N/N|N|N|
|TAO_USDT|272.500000|272.570000|272.540000|2.05|Y|Y/N|N/N|N|N|
|TIA_USDT|0.607800|0.607500|0.607800|0.81|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.952900|1.932700|1.952900|1.64|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.025663, depth_time=2026-10-21T23:15:15+00:00, book20_bid_proxy_usdt=19262, book20_ask_proxy_usdt=12461, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.08%, turnover=10774627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.195580, depth_time=2026-10-21T23:15:28+00:00, book20_bid_proxy_usdt=38150, book20_ask_proxy_usdt=90983, funding_indicative=0.000097, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=33161975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=9.877000, depth_time=2026-10-21T23:15:39+00:00, book20_bid_proxy_usdt=954562, book20_ask_proxy_usdt=2048530, funding_indicative=0.000065, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=155401595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.504950, depth_time=2026-10-21T23:15:13+00:00, book20_bid_proxy_usdt=4860, book20_ask_proxy_usdt=3293, funding_indicative=-0.000182, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.49%, turnover=14576823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.002525, depth_time=2026-10-21T23:15:09+00:00, book20_bid_proxy_usdt=198560, book20_ask_proxy_usdt=153588, funding_indicative=-0.000044, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=1, 24h_change=-17.29%, turnover=9123486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=1.173500, depth_time=2026-10-21T23:15:30+00:00, book20_bid_proxy_usdt=259182, book20_ask_proxy_usdt=439049, funding_indicative=-0.000128, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=16030646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=2.959000, depth_time=2026-10-21T23:15:38+00:00, book20_bid_proxy_usdt=890660, book20_ask_proxy_usdt=933444, funding_indicative=0.000003, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=5611442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.001571, depth_time=2026-10-21T23:15:08+00:00, book20_bid_proxy_usdt=8936, book20_ask_proxy_usdt=6823, funding_indicative=-0.014619, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=1, 24h_change=-19.04%, turnover=14525261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.004284, depth_time=2026-10-21T23:15:23+00:00, book20_bid_proxy_usdt=48323, book20_ask_proxy_usdt=41912, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=13146229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.412100, depth_time=2026-10-21T23:15:33+00:00, book20_bid_proxy_usdt=556125, book20_ask_proxy_usdt=603228, funding_indicative=0.000006, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=5208251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.132370, depth_time=2026-10-21T23:15:36+00:00, book20_bid_proxy_usdt=43564, book20_ask_proxy_usdt=126172, funding_indicative=0.000000, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=6851396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.061590, depth_time=2026-10-21T23:15:18+00:00, book20_bid_proxy_usdt=485614, book20_ask_proxy_usdt=602409, funding_indicative=-0.000028, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.89%, turnover=23861982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=277.510000, depth_time=2026-10-21T23:15:43+00:00, book20_bid_proxy_usdt=88035, book20_ask_proxy_usdt=162844, funding_indicative=0.000018, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=60859020. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=0.625800, depth_time=2026-10-21T23:15:26+00:00, book20_bid_proxy_usdt=224328, book20_ask_proxy_usdt=340204, funding_indicative=-0.000135, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=38998484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T23:15:03+00:00, last15m_closed_end=2026-10-21T23:15+00:00, prior8high=2.012100, depth_time=2026-10-21T23:15:20+00:00, book20_bid_proxy_usdt=109068, book20_ask_proxy_usdt=69485, funding_indicative=-0.000021, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.88%, turnover=7237382. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
