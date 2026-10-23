# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T01:00:38Z**
- feed_generated_utc: 2026-10-23T01:00:40+00:00
- source_sha256: `0d57232bc9214e0371fbea031a1c4d685000e928c3633655be4839c752e03154`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T01:00+00:00, close=81431.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T01:00+00:00, close=81431.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.426800|-5.86|10.84|-5.60|12725750|0.29|
|STRK_USDT|0.052720|-3.01|-45.28|-2.75|13103360|1.90|
|XPL_USDT|0.076000|-2.70|-10.31|-2.44|5721803|1.32|
|XMR_USDT|600.870000|-1.96|10.46|-1.70|27511476|3.33|
|TIA_USDT|0.557600|-1.90|-7.45|-1.64|23607777|1.79|
|ARB_USDT|0.180230|-1.85|-5.11|-1.59|32397573|0.56|
|PHA_USDT|0.060910|-1.83|20.56|-1.57|8406887|1.64|
|SEI_USDT|0.057230|-1.73|-6.88|-1.47|9679283|1.75|
|PUMPFUN_USDT|0.004605|-1.58|1.74|-1.32|37605390|2.17|
|APT_USDT|0.760100|-1.56|-8.05|-1.30|9071704|1.32|
|QNT_USDT|188.110000|-1.36|-9.52|-1.10|58914000|1.59|
|OP_USDT|0.118320|-1.30|-14.79|-1.04|6735920|0.84|
|EIGEN_USDT|0.219400|-1.26|-11.53|-1.00|6248098|4.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.760100|0.748700|0.760100|0.32|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.180230|0.177500|0.180230|0.30|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.219400|0.216000|0.219400|2.35|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.426800|3.363100|3.426800|3.87|N|Y/Y|Y/N|Y|N|
|OP_USDT|0.118320|0.117250|0.118320|1.45|N|Y/Y|Y/Y|Y|N|
|PHA_USDT|0.060910|0.060560|0.060910|1.54|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004605|0.004525|0.004605|0.18|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.110000|185.530000|188.110000|0.55|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.057230|0.056780|0.057230|1.00|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052720|0.052330|0.052720|0.47|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.557600|0.555400|0.557600|0.41|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|600.870000|593.340000|600.870000|1.34|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.076000|0.075130|0.076000|1.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.760500, depth_time=2026-10-23T01:00:30+00:00, book20_bid_proxy_usdt=150709, book20_ask_proxy_usdt=168391, funding_indicative=-0.000048, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=9071704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.180530, depth_time=2026-10-23T01:00:20+00:00, book20_bid_proxy_usdt=57293, book20_ask_proxy_usdt=78142, funding_indicative=-0.000127, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=32397573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-23T01:00:00+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.219800, depth_time=2026-10-23T01:00:36+00:00, book20_bid_proxy_usdt=699445, book20_ask_proxy_usdt=510492, funding_indicative=-0.000055, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=6248098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T01:00:00+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=3.439800, depth_time=2026-10-23T01:00:08+00:00, book20_bid_proxy_usdt=25057, book20_ask_proxy_usdt=22551, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.86%, turnover=12725750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T01:00:00+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.118330, depth_time=2026-10-23T01:00:34+00:00, book20_bid_proxy_usdt=205596, book20_ask_proxy_usdt=84582, funding_indicative=-0.000195, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=6735920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.061540, depth_time=2026-10-23T01:00:21+00:00, book20_bid_proxy_usdt=91487, book20_ask_proxy_usdt=78358, funding_indicative=-0.000569, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=8406887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.004599, depth_time=2026-10-23T01:00:27+00:00, book20_bid_proxy_usdt=2328300, book20_ask_proxy_usdt=2067447, funding_indicative=0.000025, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=37605390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=187.920000, depth_time=2026-10-23T01:00:32+00:00, book20_bid_proxy_usdt=99255, book20_ask_proxy_usdt=68933, funding_indicative=-0.000144, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=58914000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-23T01:00:00+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.057220, depth_time=2026-10-23T01:00:25+00:00, book20_bid_proxy_usdt=323007, book20_ask_proxy_usdt=280712, funding_indicative=-0.000017, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=9679283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.053350, depth_time=2026-10-23T01:00:11+00:00, book20_bid_proxy_usdt=509042, book20_ask_proxy_usdt=717350, funding_indicative=0.000030, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=13103360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.560500, depth_time=2026-10-23T01:00:18+00:00, book20_bid_proxy_usdt=307133, book20_ask_proxy_usdt=432686, funding_indicative=-0.000019, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=23607777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T00:59:59+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=602.780000, depth_time=2026-10-23T01:00:15+00:00, book20_bid_proxy_usdt=22097, book20_ask_proxy_usdt=9129, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=27511476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-23T01:00:00+00:00, last15m_closed_end=2026-10-23T01:00+00:00, prior8high=0.075930, depth_time=2026-10-23T01:00:13+00:00, book20_bid_proxy_usdt=429346, book20_ask_proxy_usdt=597622, funding_indicative=-0.000003, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=5721803. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
