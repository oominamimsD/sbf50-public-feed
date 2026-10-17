# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T03:30:39Z**
- feed_generated_utc: 2026-10-17T03:30:41+00:00
- source_sha256: `25e4a8056624fdf91bb59ee305846ca8450e1af7ca5c76d77cc03e653f6ed277`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T03:30+00:00, close=81559, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T03:00+00:00, close=81449.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.961900|-6.63|-3.67|-6.92|15418812|0.51|
|STRK_USDT|0.070300|-4.93|-6.65|-5.22|22228043|1.42|
|RIVER_USDT|1.082000|-3.90|-8.46|-4.19|5239811|9.24|
|BAT_USDT|0.198320|-3.27|63.01|-3.56|14512346|2.52|
|ARB_USDT|0.188920|-3.08|4.49|-3.37|33320992|0.53|
|ZEC_USDT|1153.610000|-2.89|-5.31|-3.18|1392901275|0.09|
|FET_USDT|0.195400|-2.10|-9.95|-2.39|11609446|5.12|
|TAO_USDT|275.630000|-1.77|0.34|-2.06|79291852|1.09|
|APT_USDT|0.845700|-1.21|5.64|-1.50|12604562|1.18|
|SUI_USDT|1.010400|-0.98|-4.46|-1.27|96644124|0.99|
|AAVE_USDT|155.740000|-0.97|-8.30|-1.26|29961160|1.28|
|AVAX_USDT|9.987000|-0.95|-2.01|-1.24|123113270|2.00|
|FARTCOIN_USDT|0.153380|-0.86|-6.11|-1.15|7216091|1.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.740000|154.400000|155.740000|0.74|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.845700|0.833600|0.845700|3.07|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188920|0.187590|0.188920|1.42|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.987000|9.881000|9.986000|1.45|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.198320|0.196790|0.198340|1.21|N|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.153380|0.152200|0.153380|5.16|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195400|0.194100|0.195400|1.77|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.082000|1.074000|1.082000|2.20|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.070300|0.070090|0.070290|3.10|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.010400|1.001200|1.010400|0.82|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.630000|273.080000|275.630000|2.25|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1153.610000|1140.370000|1153.610000|0.99|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.961900|1.943800|1.961900|0.62|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=155.480000, depth_time=2026-10-17T03:30:32+00:00, book20_bid_proxy_usdt=373720, book20_ask_proxy_usdt=243710, funding_indicative=0.000052, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=29961160. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=0.848700, depth_time=2026-10-17T03:30:28+00:00, book20_bid_proxy_usdt=136601, book20_ask_proxy_usdt=150505, funding_indicative=0.000063, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=12604562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=0.190730, depth_time=2026-10-17T03:30:17+00:00, book20_bid_proxy_usdt=104110, book20_ask_proxy_usdt=64902, funding_indicative=-0.000078, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=33320992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=9.991000, depth_time=2026-10-17T03:30:36+00:00, book20_bid_proxy_usdt=680369, book20_ask_proxy_usdt=531015, funding_indicative=0.000088, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=123113270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T03:30:00+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=0.201540, depth_time=2026-10-17T03:30:15+00:00, book20_bid_proxy_usdt=20084, book20_ask_proxy_usdt=22308, funding_indicative=-0.000018, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=14512346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=0.153930, depth_time=2026-10-17T03:30:38+00:00, book20_bid_proxy_usdt=65313, book20_ask_proxy_usdt=37315, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.86%, turnover=7216091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=0.196500, depth_time=2026-10-17T03:30:23+00:00, book20_bid_proxy_usdt=1733822, book20_ask_proxy_usdt=1213104, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=11609446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=1.091000, depth_time=2026-10-17T03:30:12+00:00, book20_bid_proxy_usdt=384225, book20_ask_proxy_usdt=445513, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=5239811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=0.074750, depth_time=2026-10-17T03:30:10+00:00, book20_bid_proxy_usdt=293007, book20_ask_proxy_usdt=326191, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=22228043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=1.010200, depth_time=2026-10-17T03:30:30+00:00, book20_bid_proxy_usdt=576348, book20_ask_proxy_usdt=1372079, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=96644124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T03:30:01+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=275.350000, depth_time=2026-10-17T03:30:26+00:00, book20_bid_proxy_usdt=76156, book20_ask_proxy_usdt=94799, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=79291852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T03:30:00+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=1157.920000, depth_time=2026-10-17T03:30:20+00:00, book20_bid_proxy_usdt=178691, book20_ask_proxy_usdt=163430, funding_indicative=0.000065, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=1392901275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T03:30:00+00:00, last15m_closed_end=2026-10-17T03:30+00:00, prior8high=1.972200, depth_time=2026-10-17T03:30:07+00:00, book20_bid_proxy_usdt=67442, book20_ask_proxy_usdt=36350, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.63%, turnover=15418812. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
