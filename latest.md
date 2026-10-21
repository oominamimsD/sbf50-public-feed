# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T10:00:38Z**
- feed_generated_utc: 2026-10-21T10:00:41+00:00
- source_sha256: `fbfdec38568c44cd5fbee54ab314a7b5623be915a241b567af2d4c2cc670a19f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T10:00+00:00, close=83402.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T10:00+00:00, close=83402.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.050314|-20.98|211.02|-21.97|6532086|0.99|
|BAT_USDT|0.181910|-15.69|2.55|-16.68|10834772|4.95|
|BR_USDT|0.573070|-14.71|32.34|-15.70|24910691|1.22|
|Q_USDT|0.120477|-6.63|192.93|-7.62|5576376|1.57|
|ARB_USDT|0.189400|-3.63|2.57|-4.62|55146432|0.53|
|TIA_USDT|0.619500|-3.33|7.30|-4.32|44674661|4.84|
|DOT_USDT|1.150900|-2.80|-0.51|-3.79|13687657|0.87|
|STRK_USDT|0.055990|-2.47|-35.59|-3.46|17956811|3.57|
|INJ_USDT|8.711000|-2.18|11.15|-3.17|65560747|1.15|
|SILVER_USDT|57.380000|-1.52|-3.38|-2.51|214539991|1.74|
|XAU_USDT|4126.390000|-0.59|-0.94|-1.58|378816231|0.02|
|XAUT_USDT|4118.720000|-0.49|-0.91|-1.48|146541491|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.050314|0.041474|0.050314|1.03|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.189400|0.188470|0.189400|1.40|N|Y/Y|N/Y|N|N|
|BAT_USDT|0.181910|0.182390|0.181740|1.72|Y|Y/Y|Y/Y|N|Y|
|BR_USDT|0.573070|0.575440|0.573070|2.09|Y|Y/Y|N/N|N|N|
|DOT_USDT|1.150900|1.152900|1.150300|1.18|N|Y/N|N/N|N|N|
|INJ_USDT|8.711000|8.701000|8.711000|0.59|N|Y/Y|N/N|N|N|
|Q_USDT|0.120477|0.120575|0.120477|0.90|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.380000|57.310000|57.380000|3.11|N|Y/Y|N/N|N|N|
|STRK_USDT|0.055990|0.055950|0.055990|0.51|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.619500|0.621500|0.619800|1.20|N|Y/N|N/Y|N|N|
|XAUT_USDT|4118.720000|4117.940000|4118.720000|1.39|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4126.390000|4125.700000|4126.390000|1.19|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.051537, depth_time=2026-10-21T10:00:09+00:00, book20_bid_proxy_usdt=10028, book20_ask_proxy_usdt=14042, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.98%, turnover=6532086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.191610, depth_time=2026-10-21T10:00:20+00:00, book20_bid_proxy_usdt=70860, book20_ask_proxy_usdt=73086, funding_indicative=-0.000170, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=55146432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.190510, depth_time=2026-10-21T10:00:11+00:00, book20_bid_proxy_usdt=21950, book20_ask_proxy_usdt=26091, funding_indicative=-0.000110, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.69%, turnover=10834772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.627970, depth_time=2026-10-21T10:00:14+00:00, book20_bid_proxy_usdt=2877, book20_ask_proxy_usdt=2192, funding_indicative=-0.000021, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.71%, turnover=24910691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=1.169700, depth_time=2026-10-21T10:00:24+00:00, book20_bid_proxy_usdt=386511, book20_ask_proxy_usdt=225610, funding_indicative=-0.000270, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=13687657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=8.836000, depth_time=2026-10-21T10:00:30+00:00, book20_bid_proxy_usdt=379930, book20_ask_proxy_usdt=236770, funding_indicative=0.000096, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=65560747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.146637, depth_time=2026-10-21T10:00:14+00:00, book20_bid_proxy_usdt=19815, book20_ask_proxy_usdt=16845, funding_indicative=0.000040, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.63%, turnover=5576376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=57.610000, depth_time=2026-10-21T10:00:32+00:00, book20_bid_proxy_usdt=37001136, book20_ask_proxy_usdt=35453107, funding_indicative=0.000032, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=214539991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.057240, depth_time=2026-10-21T10:00:26+00:00, book20_bid_proxy_usdt=749894, book20_ask_proxy_usdt=748841, funding_indicative=0.000014, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=17956811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=0.642000, depth_time=2026-10-21T10:00:21+00:00, book20_bid_proxy_usdt=213589, book20_ask_proxy_usdt=368901, funding_indicative=-0.000080, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=44674661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T10:00:01+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=4126.350000, depth_time=2026-10-21T10:00:36+00:00, book20_bid_proxy_usdt=144464, book20_ask_proxy_usdt=123754, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.49%, turnover=146541491. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T10:00:00+00:00, last15m_closed_end=2026-10-21T10:00+00:00, prior8high=4133.460000, depth_time=2026-10-21T10:00:35+00:00, book20_bid_proxy_usdt=744838, book20_ask_proxy_usdt=1827510, funding_indicative=0.000060, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.59%, turnover=378816231. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
