# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T02:00:28Z**
- feed_generated_utc: 2026-11-10T02:00:29+00:00
- source_sha256: `25abaa8f4b64bd8b70697363531898205c8c4631ba7fb9e76a60526d8f31bfad`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T02:00+00:00, close=75046.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T02:00+00:00, close=75046.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002740|-42.32|-50.19|-41.72|13484108|3.66|
|ZEC_USDT|1165.600000|-4.90|-7.05|-4.30|2330310981|0.09|
|DOT_USDT|0.854400|-4.09|-8.53|-3.49|10363813|1.17|
|ARB_USDT|0.173540|-3.74|8.91|-3.14|30805095|0.58|
|QNT_USDT|194.450000|-2.74|-3.95|-2.14|37884031|0.51|
|PUMPFUN_USDT|0.003578|-2.69|-12.81|-2.09|8258289|2.79|
|WLD_USDT|0.315200|-2.38|-17.31|-1.78|25742484|3.17|
|INJ_USDT|7.999000|-2.17|14.12|-1.57|19228052|3.75|
|SOL_USDT|86.270000|-1.84|-7.74|-1.24|625262155|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002740|0.002154|0.002740|1.81|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.173540|0.173330|0.173540|0.30|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.854400|0.852500|0.853900|0.53|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.999000|8.011000|7.996000|0.74|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003578|0.003581|0.003578|2.89|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|194.450000|193.200000|194.450000|0.91|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.270000|86.250000|86.240000|1.80|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.315200|0.315900|0.315200|2.01|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1165.600000|1152.430000|1165.380000|0.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=0.003214, depth_time=2026-11-10T02:00:08+00:00, book20_bid_proxy_usdt=64696, book20_ask_proxy_usdt=23900, funding_indicative=-0.000263, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-42.32%, turnover=13484108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=0.176000, depth_time=2026-11-10T02:00:14+00:00, book20_bid_proxy_usdt=35026, book20_ask_proxy_usdt=35511, funding_indicative=-0.000028, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=30805095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=0.858500, depth_time=2026-11-10T02:00:11+00:00, book20_bid_proxy_usdt=535320, book20_ask_proxy_usdt=853458, funding_indicative=0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=10363813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=8.135000, depth_time=2026-11-10T02:00:24+00:00, book20_bid_proxy_usdt=277183, book20_ask_proxy_usdt=307124, funding_indicative=-0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=19228052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T02:00:02+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=0.003624, depth_time=2026-11-10T02:00:16+00:00, book20_bid_proxy_usdt=2533440, book20_ask_proxy_usdt=3233714, funding_indicative=0.000030, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=8258289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=195.180000, depth_time=2026-11-10T02:00:17+00:00, book20_bid_proxy_usdt=85721, book20_ask_proxy_usdt=101292, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=37884031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=86.790000, depth_time=2026-11-10T02:00:27+00:00, book20_bid_proxy_usdt=15643944, book20_ask_proxy_usdt=20600391, funding_indicative=0.000038, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=625262155. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=0.319600, depth_time=2026-11-10T02:00:19+00:00, book20_bid_proxy_usdt=5091091, book20_ask_proxy_usdt=6089947, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=25742484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T02:00:01+00:00, last15m_closed_end=2026-11-10T02:00+00:00, prior8high=1178.530000, depth_time=2026-11-10T02:00:10+00:00, book20_bid_proxy_usdt=208256, book20_ask_proxy_usdt=249483, funding_indicative=0.000091, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.90%, turnover=2330310981. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
