# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T02:00:41Z**
- feed_generated_utc: 2026-10-23T02:00:43+00:00
- source_sha256: `382de3486c62cd633816803f63e20f351bc3d6b8011b6eb27a30764e60c80bfd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T02:00+00:00, close=81311.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T02:00+00:00, close=81311.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004351|-13.15|119.19|-12.74|9573396|9.19|
|LIT_USDT|3.425700|-5.89|10.81|-5.48|11389627|0.29|
|PHA_USDT|0.059930|-4.31|18.62|-3.90|8237127|1.67|
|STRK_USDT|0.052650|-4.16|-45.36|-3.75|12179128|3.80|
|SILVER_USDT|53.680000|-3.10|-6.05|-2.69|375955329|1.86|
|TIA_USDT|0.561900|-2.39|-6.73|-1.98|23063454|1.78|
|QNT_USDT|188.690000|-2.18|-9.24|-1.77|54549123|1.59|
|ARB_USDT|0.180210|-2.04|-5.12|-1.63|30177228|0.56|
|PUMPFUN_USDT|0.004612|-1.89|1.90|-1.48|35904555|2.17|
|XMR_USDT|608.830000|-1.88|11.92|-1.47|26904305|0.16|
|APT_USDT|0.763200|-1.64|-7.68|-1.23|9199194|1.31|
|XAUT_USDT|3998.420000|-1.56|-3.53|-1.15|290101691|0.07|
|XPL_USDT|0.076290|-1.56|-9.97|-1.15|5640650|1.31|
|XAU_USDT|4000.660000|-1.45|-3.74|-1.04|721788486|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.763200|0.748700|0.763200|0.36|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.180210|0.178680|0.180210|1.04|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004351|0.004335|0.004351|1.58|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.425700|3.363100|3.425700|2.59|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.059930|0.059760|0.059930|1.69|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004612|0.004531|0.004612|0.64|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.690000|185.950000|188.690000|1.51|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.680000|54.110000|53.680000|6.53|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.052650|0.052330|0.052650|2.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.561900|0.554300|0.561900|2.27|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|3998.420000|4016.140000|3998.420000|8.87|Y|Y/Y|Y/Y|Y|Y|
|XAU_USDT|4000.660000|4018.000000|4000.980000|9.80|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|608.830000|593.340000|608.830000|0.65|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.076290|0.075130|0.076350|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.765000, depth_time=2026-10-23T02:00:33+00:00, book20_bid_proxy_usdt=158020, book20_ask_proxy_usdt=89189, funding_indicative=-0.000060, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=9199194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.181100, depth_time=2026-10-23T02:00:24+00:00, book20_bid_proxy_usdt=253514, book20_ask_proxy_usdt=79046, funding_indicative=-0.000112, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=30177228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.004606, depth_time=2026-10-23T02:00:08+00:00, book20_bid_proxy_usdt=46000, book20_ask_proxy_usdt=38760, funding_indicative=0.000097, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.15%, turnover=9573396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=3.456400, depth_time=2026-10-23T02:00:10+00:00, book20_bid_proxy_usdt=23972, book20_ask_proxy_usdt=23140, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=11389627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.061510, depth_time=2026-10-23T02:00:12+00:00, book20_bid_proxy_usdt=60808, book20_ask_proxy_usdt=74121, funding_indicative=-0.000583, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=8237127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.004646, depth_time=2026-10-23T02:00:27+00:00, book20_bid_proxy_usdt=2261981, book20_ask_proxy_usdt=881614, funding_indicative=0.000024, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=35904555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=189.130000, depth_time=2026-10-23T02:00:22+00:00, book20_bid_proxy_usdt=55477, book20_ask_proxy_usdt=53717, funding_indicative=-0.000169, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=54549123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=54.870000, depth_time=2026-10-23T02:00:17+00:00, book20_bid_proxy_usdt=31795470, book20_ask_proxy_usdt=28914488, funding_indicative=0.000110, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.10%, turnover=375955329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.053350, depth_time=2026-10-23T02:00:15+00:00, book20_bid_proxy_usdt=761010, book20_ask_proxy_usdt=595254, funding_indicative=0.000031, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=12179128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.564100, depth_time=2026-10-23T02:00:20+00:00, book20_bid_proxy_usdt=437711, book20_ask_proxy_usdt=285434, funding_indicative=-0.000004, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=23063454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=4038.080000, depth_time=2026-10-23T02:00:35+00:00, book20_bid_proxy_usdt=77192, book20_ask_proxy_usdt=281454, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=290101691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=4040.120000, depth_time=2026-10-23T02:00:40+00:00, book20_bid_proxy_usdt=141133, book20_ask_proxy_usdt=1646594, funding_indicative=0.000106, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=721788486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T02:00:00+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=609.360000, depth_time=2026-10-23T02:00:30+00:00, book20_bid_proxy_usdt=16362, book20_ask_proxy_usdt=11182, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=26904305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T02:00:01+00:00, last15m_closed_end=2026-10-23T02:00+00:00, prior8high=0.076380, depth_time=2026-10-23T02:00:37+00:00, book20_bid_proxy_usdt=497102, book20_ask_proxy_usdt=473020, funding_indicative=0.000025, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=5640650. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
