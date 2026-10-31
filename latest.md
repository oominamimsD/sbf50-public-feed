# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T09:00:38Z**
- feed_generated_utc: 2026-10-31T09:00:40+00:00
- source_sha256: `237a40a1abaa0b85f7f0a2cdb60e0a774de5696b2a07ae2dc8327d2e8d58bb86`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T09:00+00:00, close=77320.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T09:00+00:00, close=77320.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010689|-44.40|-69.45|-44.07|9864624|8.44|
|Q_USDT|0.032790|-30.93|-72.29|-30.60|15215167|3.05|
|BLESS_USDT|0.010095|-25.24|23.69|-24.91|13201456|3.96|
|BEAT_USDT|0.098680|-6.66|35.94|-6.33|8001478|1.01|
|BTW_USDT|1.148400|-5.66|-32.54|-5.33|9084615|5.23|
|HYPE_USDT|87.625000|-5.52|11.76|-5.19|102306809|0.11|
|TRX_USDT|0.318710|-5.26|-3.22|-4.93|5947296|0.31|
|EVAA_USDT|1.228100|-4.79|133.96|-4.46|5319016|3.26|
|DASH_USDT|47.730000|-2.92|-11.36|-2.59|13263522|2.10|
|FET_USDT|0.161700|-2.05|-13.66|-1.72|5818100|6.18|
|LTC_USDT|54.670000|-1.70|-6.46|-1.37|6385298|3.66|
|WLD_USDT|0.397000|-1.61|-25.43|-1.28|48041047|2.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010689|0.009146|0.010689|1.94|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098680|0.096500|0.098680|0.60|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.010095|0.009788|0.010095|0.71|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.148400|1.128400|1.148400|0.88|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.730000|47.610000|47.730000|1.28|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.228100|1.185800|1.228100|0.77|N|N/N|N/N|Y|N|
|FET_USDT|0.161700|0.161500|0.161700|0.91|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.625000|86.343000|87.625000|2.72|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.670000|54.520000|54.670000|1.43|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.032790|0.031580|0.032860|0.52|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318710|0.319560|0.318710|3.24|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.397000|0.394600|0.397000|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.013245, depth_time=2026-10-31T09:00:08+00:00, book20_bid_proxy_usdt=4673, book20_ask_proxy_usdt=8024, funding_indicative=-0.001301, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-44.40%, turnover=9864624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.098520, depth_time=2026-10-31T09:00:15+00:00, book20_bid_proxy_usdt=13131, book20_ask_proxy_usdt=10098, funding_indicative=0.000175, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.66%, turnover=8001478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.010163, depth_time=2026-10-31T09:00:13+00:00, book20_bid_proxy_usdt=18059, book20_ask_proxy_usdt=13671, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-25.24%, turnover=13201456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=1.181700, depth_time=2026-10-31T09:00:18+00:00, book20_bid_proxy_usdt=11141, book20_ask_proxy_usdt=20023, funding_indicative=-0.000250, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=9084615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=48.110000, depth_time=2026-10-31T09:00:28+00:00, book20_bid_proxy_usdt=734312, book20_ask_proxy_usdt=780632, funding_indicative=0.000042, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=13263522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=1.226600, depth_time=2026-10-31T09:00:25+00:00, book20_bid_proxy_usdt=6762, book20_ask_proxy_usdt=3501, funding_indicative=0.000258, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.79%, turnover=5319016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.164200, depth_time=2026-10-31T09:00:32+00:00, book20_bid_proxy_usdt=1203178, book20_ask_proxy_usdt=927206, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=5818100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T09:00:01+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=88.891000, depth_time=2026-10-31T09:00:20+00:00, book20_bid_proxy_usdt=520864, book20_ask_proxy_usdt=94966, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.52%, turnover=102306809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=55.350000, depth_time=2026-10-31T09:00:34+00:00, book20_bid_proxy_usdt=1375207, book20_ask_proxy_usdt=1195608, funding_indicative=0.000019, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=6385298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.033340, depth_time=2026-10-31T09:00:11+00:00, book20_bid_proxy_usdt=37660, book20_ask_proxy_usdt=57176, funding_indicative=-0.000678, next_funding_utc=2026-10-31T10:00:00+00:00, funding_cycle_h=1, 24h_change=-30.93%, turnover=15215167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.324750, depth_time=2026-10-31T09:00:20+00:00, book20_bid_proxy_usdt=758723, book20_ask_proxy_usdt=108685, funding_indicative=-0.000424, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.26%, turnover=5947296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T09:00:02+00:00, last15m_closed_end=2026-10-31T09:00+00:00, prior8high=0.401700, depth_time=2026-10-31T09:00:37+00:00, book20_bid_proxy_usdt=3117625, book20_ask_proxy_usdt=4253394, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=48041047. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
