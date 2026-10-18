# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T00:30:36Z**
- feed_generated_utc: 2026-10-18T00:30:38+00:00
- source_sha256: `124524d552326101f1946c15577e8d01facc01b76c94f1ae6062adfd3531b0f8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T00:30+00:00, close=81418, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.171700|-7.28|73.25|-7.39|14770548|5.83|
|STRK_USDT|0.063940|-3.34|-31.56|-3.45|16172885|3.13|
|EIGEN_USDT|0.249000|-2.84|5.68|-2.95|10791220|4.02|
|QNT_USDT|195.000000|-2.69|-20.45|-2.80|66980640|0.51|
|FILECOIN_USDT|1.060200|-2.50|-5.99|-2.61|20861328|0.94|
|TIA_USDT|0.643300|-2.23|25.39|-2.34|73950543|1.55|
|PUMPFUN_USDT|0.004323|-2.01|-24.48|-2.12|24680177|2.31|
|XPL_USDT|0.078590|-1.92|-9.41|-2.03|5099667|1.27|
|ZEC_USDT|1122.160000|-1.67|-8.89|-1.78|1157000146|2.05|
|ARB_USDT|0.181040|-1.56|-3.01|-1.67|30647478|1.10|
|WLD_USDT|0.488700|-1.39|-12.57|-1.50|66186790|2.05|
|NEAR_USDT|4.830000|-1.12|-9.97|-1.23|124721437|2.07|
|DOT_USDT|1.106600|-0.96|-11.95|-1.07|16936788|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181040|0.179180|0.181110|0.48|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.106600|1.100800|1.106600|0.73|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.249000|0.247100|0.249000|0.05|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.060200|1.050300|1.060200|1.40|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.171700|0.163200|0.171700|0.66|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.830000|4.804000|4.829000|0.39|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004323|0.004297|0.004323|0.11|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.000000|193.740000|195.020000|0.80|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063940|0.064020|0.063940|0.13|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.643300|0.639600|0.643300|0.23|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.488700|0.484300|0.488700|1.55|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078590|0.078200|0.078600|1.33|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1122.160000|1113.720000|1122.020000|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.181720, depth_time=2026-10-18T00:30:28+00:00, book20_bid_proxy_usdt=80897, book20_ask_proxy_usdt=49665, funding_indicative=0.000042, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=30647478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T00:30:01+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=1.117400, depth_time=2026-10-18T00:30:34+00:00, book20_bid_proxy_usdt=282066, book20_ask_proxy_usdt=284399, funding_indicative=-0.000028, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=16936788. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.252000, depth_time=2026-10-18T00:30:10+00:00, book20_bid_proxy_usdt=628955, book20_ask_proxy_usdt=307998, funding_indicative=0.000013, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=10791220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=1.066900, depth_time=2026-10-18T00:30:16+00:00, book20_bid_proxy_usdt=685107, book20_ask_proxy_usdt=645882, funding_indicative=-0.000035, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=20861328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.174400, depth_time=2026-10-18T00:30:04+00:00, book20_bid_proxy_usdt=284794, book20_ask_proxy_usdt=115336, funding_indicative=-0.000063, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.28%, turnover=14770548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=4.910000, depth_time=2026-10-18T00:30:30+00:00, book20_bid_proxy_usdt=2326558, book20_ask_proxy_usdt=2853722, funding_indicative=-0.000003, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=124721437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.004372, depth_time=2026-10-18T00:30:20+00:00, book20_bid_proxy_usdt=2090295, book20_ask_proxy_usdt=1619077, funding_indicative=0.000028, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=24680177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=196.940000, depth_time=2026-10-18T00:30:12+00:00, book20_bid_proxy_usdt=68535, book20_ask_proxy_usdt=88171, funding_indicative=-0.000051, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=66980640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.065060, depth_time=2026-10-18T00:30:09+00:00, book20_bid_proxy_usdt=482248, book20_ask_proxy_usdt=337569, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=16172885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.651200, depth_time=2026-10-18T00:30:16+00:00, book20_bid_proxy_usdt=232439, book20_ask_proxy_usdt=178100, funding_indicative=0.000001, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=73950543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.492900, depth_time=2026-10-18T00:30:30+00:00, book20_bid_proxy_usdt=1655523, book20_ask_proxy_usdt=1652989, funding_indicative=-0.000120, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=66186790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T00:30:01+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=0.078920, depth_time=2026-10-18T00:30:23+00:00, book20_bid_proxy_usdt=344663, book20_ask_proxy_usdt=366630, funding_indicative=0.000034, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=5099667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T00:30:00+00:00, last15m_closed_end=2026-10-18T00:30+00:00, prior8high=1131.290000, depth_time=2026-10-18T00:30:25+00:00, book20_bid_proxy_usdt=122251, book20_ask_proxy_usdt=622622, funding_indicative=0.000054, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=1157000146. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
