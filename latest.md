# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T15:30:30Z**
- feed_generated_utc: 2026-10-31T15:30:32+00:00
- source_sha256: `4645ebd67a117f7c5f61a028945a220105ffb1cbbb3196f132bb00bb0051b1fa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T15:30+00:00, close=77442.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T15:00+00:00, close=77382.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011129|-41.18|-68.20|-41.01|12255146|5.39|
|Q_USDT|0.032230|-32.11|-72.76|-31.94|11520676|3.10|
|TRX_USDT|0.313500|-6.55|-4.80|-6.38|6680434|1.28|
|BTW_USDT|1.126800|-6.06|-33.81|-5.89|8004540|2.66|
|BEAT_USDT|0.098830|-6.01|36.14|-5.84|6560206|1.01|
|HYPE_USDT|87.308000|-5.45|11.35|-5.28|93314180|0.11|
|IDOL_USDT|0.019400|-4.15|144.94|-3.98|15602349|8.25|
|FET_USDT|0.163000|-2.16|-12.97|-1.99|5781582|6.14|
|BCH_USDT|288.310000|-1.70|0.29|-1.53|5262892|9.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011129|0.010824|0.011129|0.53|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|288.310000|288.030000|288.310000|0.60|N|Y/N|N/N|Y|N|
|BEAT_USDT|0.098830|0.096930|0.098830|0.62|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.126800|1.095000|1.126800|0.63|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163000|0.160500|0.163000|9.74|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.308000|86.372000|87.308000|0.57|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019400|0.019232|0.019395|1.26|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032230|0.031650|0.032240|1.18|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.313500|0.314340|0.313500|4.95|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=0.011929, depth_time=2026-10-31T15:30:10+00:00, book20_bid_proxy_usdt=6297, book20_ask_proxy_usdt=13072, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-41.18%, turnover=12255146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=292.380000, depth_time=2026-10-31T15:30:27+00:00, book20_bid_proxy_usdt=39870, book20_ask_proxy_usdt=72505, funding_indicative=0.000052, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=5262892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=0.100370, depth_time=2026-10-31T15:30:19+00:00, book20_bid_proxy_usdt=11768, book20_ask_proxy_usdt=13492, funding_indicative=0.000143, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=6560206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=1.152900, depth_time=2026-10-31T15:30:17+00:00, book20_bid_proxy_usdt=16561, book20_ask_proxy_usdt=10945, funding_indicative=-0.000096, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.06%, turnover=8004540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=0.162400, depth_time=2026-10-31T15:30:25+00:00, book20_bid_proxy_usdt=1187491, book20_ask_proxy_usdt=955416, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=5781582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=87.815000, depth_time=2026-10-31T15:30:18+00:00, book20_bid_proxy_usdt=41417, book20_ask_proxy_usdt=167777, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=93314180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=0.020565, depth_time=2026-10-31T15:30:24+00:00, book20_bid_proxy_usdt=12511, book20_ask_proxy_usdt=7766, funding_indicative=0.000214, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=15602349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=0.033470, depth_time=2026-10-31T15:30:12+00:00, book20_bid_proxy_usdt=71667, book20_ask_proxy_usdt=51008, funding_indicative=-0.000551, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=1, 24h_change=-32.11%, turnover=11520676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T15:30:01+00:00, last15m_closed_end=2026-10-31T15:30+00:00, prior8high=0.319440, depth_time=2026-10-31T15:30:15+00:00, book20_bid_proxy_usdt=57239, book20_ask_proxy_usdt=642310, funding_indicative=-0.000579, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.55%, turnover=6680434. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
