# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T06:00:38Z**
- feed_generated_utc: 2026-10-21T06:00:41+00:00
- source_sha256: `3f3320347d78062dee82e22fec71cab3251d98d3b31a2dea69a2e347caef429c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T06:00+00:00, close=82635.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T06:00+00:00, close=82635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.182990|-15.19|3.16|-15.25|10771433|0.55|
|BR_USDT|0.589050|-12.33|36.03|-12.39|33214843|1.53|
|XMR_USDT|578.680000|-6.74|9.61|-6.80|21073552|0.17|
|PHA_USDT|0.056450|-6.27|2.58|-6.33|6773359|5.32|
|ARB_USDT|0.187650|-4.52|1.62|-4.58|63619109|2.66|
|FILECOIN_USDT|1.023000|-3.85|-9.71|-3.91|9733445|0.98|
|SEI_USDT|0.060790|-3.78|-2.53|-3.84|6058210|1.65|
|TIA_USDT|0.618000|-3.57|7.05|-3.63|46438830|1.62|
|AGT_USDT|0.061722|-3.06|281.54|-3.12|6278605|2.44|
|STRK_USDT|0.055670|-3.03|-35.95|-3.09|17110915|1.80|
|DOT_USDT|1.148900|-2.97|-0.69|-3.03|12851353|0.87|
|HBAR_USDT|0.083090|-2.86|-4.21|-2.92|19361550|1.20|
|INJ_USDT|8.748000|-1.77|11.62|-1.83|61855981|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061722|0.060783|0.061722|1.17|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.187650|0.188390|0.187690|1.16|N|Y/Y|N/Y|N|N|
|BAT_USDT|0.182990|0.183100|0.182980|1.80|Y|Y/Y|Y/N|N|N|
|BR_USDT|0.589050|0.580080|0.589050|1.21|N|Y/Y|N/N|N|N|
|DOT_USDT|1.148900|1.146900|1.148900|2.77|N|Y/N|N/N|N|N|
|FILECOIN_USDT|1.023000|1.022600|1.023000|0.43|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.083090|0.082850|0.083090|1.21|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.748000|8.680000|8.748000|0.95|N|Y/N|N/N|N|N|
|PHA_USDT|0.056450|0.055950|0.056450|0.37|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060790|0.060800|0.060790|0.58|N|Y/Y|N/Y|N|N|
|STRK_USDT|0.055670|0.055600|0.055670|0.25|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.618000|0.610500|0.618000|2.16|N|Y/Y|Y/Y|N|N|
|XMR_USDT|578.680000|575.180000|578.680000|0.75|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T06:00:00+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.063305, depth_time=2026-10-21T06:00:26+00:00, book20_bid_proxy_usdt=9246, book20_ask_proxy_usdt=8587, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=6278605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-21T06:00:00+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.192540, depth_time=2026-10-21T06:00:18+00:00, book20_bid_proxy_usdt=87490, book20_ask_proxy_usdt=111934, funding_indicative=-0.000082, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.52%, turnover=63619109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.187530, depth_time=2026-10-21T06:00:07+00:00, book20_bid_proxy_usdt=26933, book20_ask_proxy_usdt=20967, funding_indicative=-0.000077, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-15.19%, turnover=10771433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T06:00:00+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.623210, depth_time=2026-10-21T06:00:10+00:00, book20_bid_proxy_usdt=2504, book20_ask_proxy_usdt=3485, funding_indicative=0.000050, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.33%, turnover=33214843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=1.168900, depth_time=2026-10-21T06:00:30+00:00, book20_bid_proxy_usdt=332491, book20_ask_proxy_usdt=294686, funding_indicative=-0.000116, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=12851353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=1.039400, depth_time=2026-10-21T06:00:20+00:00, book20_bid_proxy_usdt=621306, book20_ask_proxy_usdt=923486, funding_indicative=-0.000015, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=9733445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.083530, depth_time=2026-10-21T06:00:33+00:00, book20_bid_proxy_usdt=856040, book20_ask_proxy_usdt=792433, funding_indicative=0.000035, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=19361550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T06:00:00+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=9.071000, depth_time=2026-10-21T06:00:36+00:00, book20_bid_proxy_usdt=302609, book20_ask_proxy_usdt=311362, funding_indicative=0.000107, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=61855981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T06:00:00+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.057890, depth_time=2026-10-21T06:00:15+00:00, book20_bid_proxy_usdt=94599, book20_ask_proxy_usdt=91269, funding_indicative=-0.000022, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.27%, turnover=6773359. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.061440, depth_time=2026-10-21T06:00:21+00:00, book20_bid_proxy_usdt=270354, book20_ask_proxy_usdt=398534, funding_indicative=-0.000061, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=6058210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.057790, depth_time=2026-10-21T06:00:29+00:00, book20_bid_proxy_usdt=648336, book20_ask_proxy_usdt=762108, funding_indicative=0.000022, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=17110915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=0.621800, depth_time=2026-10-21T06:00:23+00:00, book20_bid_proxy_usdt=233931, book20_ask_proxy_usdt=200496, funding_indicative=-0.000078, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=46438830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T06:00:01+00:00, last15m_closed_end=2026-10-21T06:00+00:00, prior8high=581.680000, depth_time=2026-10-21T06:00:13+00:00, book20_bid_proxy_usdt=16525, book20_ask_proxy_usdt=11603, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.74%, turnover=21073552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
