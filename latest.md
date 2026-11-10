# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T09:00:31Z**
- feed_generated_utc: 2026-11-10T09:00:33+00:00
- source_sha256: `36b7de29ed36f65c68285489757dc4ca768361815b848b85559f4a21181c5ae0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T09:00+00:00, close=74699.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T09:00+00:00, close=74699.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002453|-48.36|-55.41|-47.29|15193295|8.16|
|JCT_USDT|0.006505|-35.79|50.68|-34.72|24505934|1.54|
|ARB_USDT|0.168260|-6.67|5.60|-5.60|36598068|1.19|
|ZEC_USDT|1146.500000|-6.46|-8.57|-5.39|2279184089|0.09|
|QNT_USDT|189.660000|-5.18|-6.31|-4.11|32137591|0.53|
|AAVE_USDT|125.670000|-5.16|-3.74|-4.09|12172017|2.39|
|DOT_USDT|0.854700|-3.51|-8.50|-2.44|7907098|1.17|
|PUMPFUN_USDT|0.003549|-3.48|-13.52|-2.41|7064229|2.82|
|DASH_USDT|46.140000|-2.47|-2.24|-1.40|10283460|2.17|
|LIT_USDT|3.170800|-2.19|2.05|-1.12|10024679|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.670000|125.650000|125.670000|0.80|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002453|0.002421|0.002453|0.58|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.168260|0.166250|0.168240|0.37|N|Y/Y|Y/N|Y|N|
|DASH_USDT|46.140000|45.390000|46.140000|0.56|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.854700|0.854200|0.854700|1.52|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006505|0.005560|0.006515|1.74|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.170800|3.138800|3.170800|0.83|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003549|0.003532|0.003549|0.67|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.660000|189.130000|189.680000|0.45|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.500000|1134.630000|1146.970000|0.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=127.890000, depth_time=2026-11-10T09:00:20+00:00, book20_bid_proxy_usdt=438682, book20_ask_proxy_usdt=337600, funding_indicative=0.000070, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=12172017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=0.002555, depth_time=2026-11-10T09:00:08+00:00, book20_bid_proxy_usdt=51151, book20_ask_proxy_usdt=73348, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-48.36%, turnover=15193295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=0.171740, depth_time=2026-11-10T09:00:13+00:00, book20_bid_proxy_usdt=237267, book20_ask_proxy_usdt=91916, funding_indicative=-0.000119, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.67%, turnover=36598068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=45.950000, depth_time=2026-11-10T09:00:28+00:00, book20_bid_proxy_usdt=764387, book20_ask_proxy_usdt=556466, funding_indicative=0.000022, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=10283460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=0.862700, depth_time=2026-11-10T09:00:23+00:00, book20_bid_proxy_usdt=563658, book20_ask_proxy_usdt=420090, funding_indicative=-0.000030, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.51%, turnover=7907098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=0.006849, depth_time=2026-11-10T09:00:10+00:00, book20_bid_proxy_usdt=42067, book20_ask_proxy_usdt=14651, funding_indicative=0.000110, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-35.79%, turnover=24505934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=3.179500, depth_time=2026-11-10T09:00:28+00:00, book20_bid_proxy_usdt=31982, book20_ask_proxy_usdt=24002, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=10024679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=0.003602, depth_time=2026-11-10T09:00:25+00:00, book20_bid_proxy_usdt=3128909, book20_ask_proxy_usdt=2970906, funding_indicative=0.000040, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=7064229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=192.140000, depth_time=2026-11-10T09:00:17+00:00, book20_bid_proxy_usdt=89274, book20_ask_proxy_usdt=69634, funding_indicative=-0.000172, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.18%, turnover=32137591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T09:00:01+00:00, last15m_closed_end=2026-11-10T09:00+00:00, prior8high=1159.070000, depth_time=2026-11-10T09:00:16+00:00, book20_bid_proxy_usdt=88806, book20_ask_proxy_usdt=187347, funding_indicative=0.000047, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.46%, turnover=2279184089. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
