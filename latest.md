# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T09:15:37Z**
- feed_generated_utc: 2026-10-31T09:15:39+00:00
- source_sha256: `0185d0e19a653c664fa053ecb115bf0ceac0a5fb30579096532654c7f74fc880`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T09:15+00:00, close=77390, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T09:00+00:00, close=77320.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010702|-43.43|-69.42|-43.19|9958635|2.80|
|Q_USDT|0.033280|-29.90|-71.87|-29.66|15312010|3.01|
|BTW_USDT|1.127900|-5.96|-33.74|-5.72|9141842|0.89|
|HYPE_USDT|87.524000|-5.21|11.63|-4.97|103155677|0.11|
|TRX_USDT|0.318840|-4.96|-3.18|-4.72|6387034|0.31|
|EVAA_USDT|1.221600|-4.71|132.73|-4.47|5346198|5.72|
|BEAT_USDT|0.100270|-4.64|38.13|-4.40|8126771|1.00|
|WLD_USDT|0.397200|-3.56|-25.39|-3.32|48294703|2.52|
|FET_USDT|0.162100|-2.70|-13.45|-2.46|5861227|6.17|
|IDOL_USDT|0.019707|-2.64|148.82|-2.40|15623577|6.09|
|DASH_USDT|47.790000|-2.54|-11.25|-2.30|13316394|2.09|
|LTC_USDT|54.730000|-1.77|-6.36|-1.53|6408218|3.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010702|0.009146|0.010747|1.06|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100270|0.096500|0.100270|1.76|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.127900|1.128400|1.127900|1.11|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.790000|47.590000|47.780000|0.96|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.221600|1.185800|1.221600|1.42|N|N/N|N/N|Y|N|
|FET_USDT|0.162100|0.161500|0.162100|1.80|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.524000|86.343000|87.537000|1.28|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019707|0.019151|0.019536|3.26|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.730000|54.520000|54.730000|1.58|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.033280|0.031580|0.033350|1.06|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318840|0.318590|0.318840|13.34|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397200|0.394600|0.397300|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.013245, depth_time=2026-10-31T09:15:08+00:00, book20_bid_proxy_usdt=8639, book20_ask_proxy_usdt=8756, funding_indicative=-0.001158, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-43.43%, turnover=9958635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.098880, depth_time=2026-10-31T09:15:24+00:00, book20_bid_proxy_usdt=8491, book20_ask_proxy_usdt=12531, funding_indicative=0.000176, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=8126771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=1.181700, depth_time=2026-10-31T09:15:13+00:00, book20_bid_proxy_usdt=13895, book20_ask_proxy_usdt=15503, funding_indicative=-0.000233, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=9141842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=48.110000, depth_time=2026-10-31T09:15:33+00:00, book20_bid_proxy_usdt=778278, book20_ask_proxy_usdt=621309, funding_indicative=0.000021, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=13316394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=1.230000, depth_time=2026-10-31T09:15:21+00:00, book20_bid_proxy_usdt=21539, book20_ask_proxy_usdt=5145, funding_indicative=0.000259, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.71%, turnover=5346198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.163700, depth_time=2026-10-31T09:15:27+00:00, book20_bid_proxy_usdt=1168490, book20_ask_proxy_usdt=916942, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=5861227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T09:15:02+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=88.750000, depth_time=2026-10-31T09:15:15+00:00, book20_bid_proxy_usdt=45338, book20_ask_proxy_usdt=104905, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=103155677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T09:15:02+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.023675, depth_time=2026-10-31T09:15:31+00:00, book20_bid_proxy_usdt=7068, book20_ask_proxy_usdt=8515, funding_indicative=0.000180, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=15623577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=55.210000, depth_time=2026-10-31T09:15:35+00:00, book20_bid_proxy_usdt=1738320, book20_ask_proxy_usdt=1220278, funding_indicative=0.000016, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=6408218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.033340, depth_time=2026-10-31T09:15:11+00:00, book20_bid_proxy_usdt=34098, book20_ask_proxy_usdt=56566, funding_indicative=-0.000623, next_funding_utc=2026-10-31T10:00:00+00:00, funding_cycle_h=1, 24h_change=-29.90%, turnover=15312010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.324270, depth_time=2026-10-31T09:15:18+00:00, book20_bid_proxy_usdt=61548, book20_ask_proxy_usdt=79276, funding_indicative=-0.000482, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.96%, turnover=6387034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T09:15:03+00:00, last15m_closed_end=2026-10-31T09:15+00:00, prior8high=0.400700, depth_time=2026-10-31T09:15:24+00:00, book20_bid_proxy_usdt=3202624, book20_ask_proxy_usdt=3377412, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=48294703. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
