# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T18:30:28Z**
- feed_generated_utc: 2026-11-10T18:30:29+00:00
- source_sha256: `1e4edad96397be559adb2a748a1ae19d5290e529ceee27dbe96dba4814ef6961`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T18:30+00:00, close=73300.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T18:00+00:00, close=73253.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.838300|-9.26|56.39|-9.42|8926631|2.72|
|ZEC_USDT|1031.990000|-5.61|-14.27|-5.77|2344606554|0.10|
|DASH_USDT|43.390000|-3.87|-5.96|-4.03|13776056|2.30|
|JCT_USDT|0.005105|-3.22|22.18|-3.38|22560664|5.87|
|ARB_USDT|0.158240|-1.94|-1.02|-2.10|35879762|0.63|
|ANTHROPIC_USDT|1293.190000|-1.84|-22.74|-2.00|7898393|1.08|
|UNI_USDT|6.707000|-1.80|-8.78|-1.96|28083167|1.49|
|ONDO_USDT|0.361700|-1.12|-7.06|-1.28|15125364|2.77|
|HYPE_USDT|71.169000|-0.84|-18.52|-1.00|41491334|0.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1293.190000|1286.420000|1293.190000|0.19|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158240|0.155570|0.158240|0.33|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.390000|42.350000|43.390000|0.45|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|71.169000|70.375000|71.176000|0.35|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005105|0.005014|0.005105|0.38|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.361700|0.355900|0.361700|0.26|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.838300|1.808000|1.834500|0.68|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.707000|6.608000|6.707000|0.85|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1031.990000|993.710000|1031.990000|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=1325.380000, depth_time=2026-11-10T18:30:19+00:00, book20_bid_proxy_usdt=9594, book20_ask_proxy_usdt=21343, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=7898393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=0.160870, depth_time=2026-11-10T18:30:17+00:00, book20_bid_proxy_usdt=77484, book20_ask_proxy_usdt=25120, funding_indicative=-0.000169, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=35879762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=45.460000, depth_time=2026-11-10T18:30:12+00:00, book20_bid_proxy_usdt=795906, book20_ask_proxy_usdt=750507, funding_indicative=-0.000130, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=13776056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=72.358000, depth_time=2026-11-10T18:30:27+00:00, book20_bid_proxy_usdt=111627, book20_ask_proxy_usdt=108110, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=41491334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=0.005498, depth_time=2026-11-10T18:30:15+00:00, book20_bid_proxy_usdt=42130, book20_ask_proxy_usdt=49290, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.22%, turnover=22560664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=0.370400, depth_time=2026-11-10T18:30:20+00:00, book20_bid_proxy_usdt=1969811, book20_ask_proxy_usdt=2285696, funding_indicative=-0.000027, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=15125364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=2.052900, depth_time=2026-11-10T18:30:07+00:00, book20_bid_proxy_usdt=12478, book20_ask_proxy_usdt=22061, funding_indicative=0.000120, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.26%, turnover=8926631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=6.851000, depth_time=2026-11-10T18:30:20+00:00, book20_bid_proxy_usdt=2956693, book20_ask_proxy_usdt=1674858, funding_indicative=-0.000011, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=28083167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T18:30:00+00:00, last15m_closed_end=2026-11-10T18:30+00:00, prior8high=1097.000000, depth_time=2026-11-10T18:30:09+00:00, book20_bid_proxy_usdt=461391, book20_ask_proxy_usdt=902913, funding_indicative=-0.000035, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.61%, turnover=2344606554. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
