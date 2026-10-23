# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T15:15:36Z**
- feed_generated_utc: 2026-10-23T15:15:38+00:00
- source_sha256: `fb2b7bd107e5aa24d2c5df99d76de9290244889c017256b4c289eeb507cd019d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T15:15+00:00, close=81453.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T15:00+00:00, close=81750, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.321300|-8.10|7.43|-7.86|8767865|0.30|
|QNT_USDT|178.860000|-6.21|-13.97|-5.97|59232663|1.68|
|TIA_USDT|0.543000|-4.46|-9.87|-4.22|25148271|1.84|
|STRK_USDT|0.052070|-4.21|-45.96|-3.97|11525625|1.92|
|ARB_USDT|0.178290|-2.91|-6.13|-2.67|26999090|0.56|
|PUMPFUN_USDT|0.004553|-2.69|0.59|-2.45|35080695|2.20|
|APT_USDT|0.755200|-2.20|-8.64|-1.96|7826212|1.32|
|OP_USDT|0.117530|-1.93|-15.36|-1.69|6585021|0.85|
|NEAR_USDT|4.859000|-1.71|-5.07|-1.47|119879774|2.06|
|XAU_USDT|4004.260000|-1.36|-3.65|-1.12|633665717|0.03|
|XAUT_USDT|3998.940000|-1.36|-3.52|-1.12|231069979|0.07|
|HBAR_USDT|0.079040|-1.33|-5.39|-1.09|19629960|1.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.755200|0.740700|0.755200|2.60|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.178290|0.175900|0.178380|3.40|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.079040|0.078580|0.079050|1.57|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.321300|3.279300|3.321400|1.09|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.859000|4.788000|4.859000|1.00|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.117530|0.115530|0.117610|1.15|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004553|0.004485|0.004553|1.89|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|178.860000|177.480000|178.900000|1.65|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052070|0.051770|0.052070|0.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.543000|0.535200|0.543000|1.28|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|3998.940000|3978.250000|3999.350000|1.24|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4004.260000|3985.020000|4004.260000|2.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.769200, depth_time=2026-10-23T15:15:23+00:00, book20_bid_proxy_usdt=95975, book20_ask_proxy_usdt=103249, funding_indicative=0.000022, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=7826212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.182320, depth_time=2026-10-23T15:15:17+00:00, book20_bid_proxy_usdt=69670, book20_ask_proxy_usdt=60547, funding_indicative=-0.000004, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=26999090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.080450, depth_time=2026-10-23T15:15:33+00:00, book20_bid_proxy_usdt=450973, book20_ask_proxy_usdt=1149503, funding_indicative=0.000030, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=19629960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=3.409500, depth_time=2026-10-23T15:15:07+00:00, book20_bid_proxy_usdt=23834, book20_ask_proxy_usdt=20086, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.10%, turnover=8767865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T15:15:01+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=4.980000, depth_time=2026-10-23T15:15:27+00:00, book20_bid_proxy_usdt=379306, book20_ask_proxy_usdt=437268, funding_indicative=0.000025, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=119879774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.118860, depth_time=2026-10-23T15:15:25+00:00, book20_bid_proxy_usdt=93776, book20_ask_proxy_usdt=101044, funding_indicative=-0.000041, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=6585021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.004677, depth_time=2026-10-23T15:15:20+00:00, book20_bid_proxy_usdt=1082169, book20_ask_proxy_usdt=1509316, funding_indicative=0.000028, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=35080695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=183.630000, depth_time=2026-10-23T15:15:10+00:00, book20_bid_proxy_usdt=76225, book20_ask_proxy_usdt=86925, funding_indicative=-0.000180, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.21%, turnover=59232663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.053090, depth_time=2026-10-23T15:15:15+00:00, book20_bid_proxy_usdt=613912, book20_ask_proxy_usdt=633995, funding_indicative=0.000001, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.21%, turnover=11525625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=0.552300, depth_time=2026-10-23T15:15:12+00:00, book20_bid_proxy_usdt=382480, book20_ask_proxy_usdt=349772, funding_indicative=-0.000012, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=25148271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T15:15:02+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=4035.760000, depth_time=2026-10-23T15:15:32+00:00, book20_bid_proxy_usdt=287895, book20_ask_proxy_usdt=116360, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=231069979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T15:15:01+00:00, last15m_closed_end=2026-10-23T15:15+00:00, prior8high=4042.750000, depth_time=2026-10-23T15:15:30+00:00, book20_bid_proxy_usdt=1344585, book20_ask_proxy_usdt=2596820, funding_indicative=0.000180, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=633665717. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
