# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T04:30:20Z**
- feed_generated_utc: 2026-11-11T04:30:21+00:00
- source_sha256: `f2c7a4e2a1c27581738fb3bf76ac40d0632aa92e73e17984926b7857f31b88fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T04:30+00:00, close=73650.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002673|-8.27|-35.68|-8.92|9756436|3.74|
|ZEC_USDT|1022.220000|-6.50|-15.08|-7.15|2171393793|0.10|
|DASH_USDT|43.960000|-2.61|-4.72|-3.26|14491514|2.28|
|UNI_USDT|6.712000|-1.72|-8.71|-2.37|36147674|1.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002673|0.002606|0.002672|0.97|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.960000|42.750000|43.960000|0.83|N|N/Y|Y/Y|Y|N|
|UNI_USDT|6.712000|6.626000|6.712000|0.89|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1022.220000|1007.730000|1022.290000|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T04:30:01+00:00, last15m_closed_end=2026-11-11T04:30+00:00, prior8high=0.003032, depth_time=2026-11-11T04:30:06+00:00, book20_bid_proxy_usdt=43599, book20_ask_proxy_usdt=45571, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.27%, turnover=9756436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T04:30:02+00:00, last15m_closed_end=2026-11-11T04:30+00:00, prior8high=44.810000, depth_time=2026-11-11T04:30:15+00:00, book20_bid_proxy_usdt=458966, book20_ask_proxy_usdt=567213, funding_indicative=-0.000117, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=14491514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T04:30:02+00:00, last15m_closed_end=2026-11-11T04:30+00:00, prior8high=6.768000, depth_time=2026-11-11T04:30:17+00:00, book20_bid_proxy_usdt=2918431, book20_ask_proxy_usdt=2195232, funding_indicative=0.000054, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=36147674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T04:30:01+00:00, last15m_closed_end=2026-11-11T04:30+00:00, prior8high=1038.490000, depth_time=2026-11-11T04:30:10+00:00, book20_bid_proxy_usdt=466147, book20_ask_proxy_usdt=159942, funding_indicative=0.000097, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.50%, turnover=2171393793. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
