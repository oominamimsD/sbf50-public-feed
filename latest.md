# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T17:15:18Z**
- feed_generated_utc: 2026-10-21T17:15:21+00:00
- source_sha256: `d94b4838e0b412d762a04f4c2835166fbcc086151f685aaaba3e27d4ce1c0a41`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T17:15+00:00, close=84380, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T17:00+00:00, close=84506.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002239|-21.27|57.89|-21.12|9192793|4.47|
|JCT_USDT|0.004109|-3.34|95.57|-3.19|16625948|9.74|
|BR_USDT|0.524100|-3.22|28.53|-3.07|15770353|2.67|
|INJ_USDT|8.607000|-1.72|12.67|-1.57|55467525|1.16|
|AKE_USDT|0.026347|-1.28|1.80|-1.13|9987391|3.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026347|0.025666|0.026347|0.53|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.524100|0.521520|0.524310|1.15|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002239|0.002128|0.002240|0.84|N|Y/Y|N/N|N|N|
|INJ_USDT|8.607000|8.658000|8.609000|1.82|Y|Y/Y|N/N|N|N|
|JCT_USDT|0.004109|0.004016|0.004109|0.57|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T17:15:00+00:00, last15m_closed_end=2026-10-21T17:15+00:00, prior8high=0.027884, depth_time=2026-10-21T17:15:16+00:00, book20_bid_proxy_usdt=13086, book20_ask_proxy_usdt=10725, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=9987391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T17:15:00+00:00, last15m_closed_end=2026-10-21T17:15+00:00, prior8high=0.581620, depth_time=2026-10-21T17:15:13+00:00, book20_bid_proxy_usdt=3409, book20_ask_proxy_usdt=4528, funding_indicative=-0.000123, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.22%, turnover=15770353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T17:15:00+00:00, last15m_closed_end=2026-10-21T17:15+00:00, prior8high=0.004290, depth_time=2026-10-21T17:15:08+00:00, book20_bid_proxy_usdt=98709, book20_ask_proxy_usdt=67983, funding_indicative=-0.002423, next_funding_utc=2026-10-21T18:00:00+00:00, funding_cycle_h=1, 24h_change=-21.27%, turnover=9192793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T17:15:00+00:00, last15m_closed_end=2026-10-21T17:15+00:00, prior8high=8.817000, depth_time=2026-10-21T17:15:15+00:00, book20_bid_proxy_usdt=128517, book20_ask_proxy_usdt=212075, funding_indicative=0.000019, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=55467525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T17:15:00+00:00, last15m_closed_end=2026-10-21T17:15+00:00, prior8high=0.004408, depth_time=2026-10-21T17:15:10+00:00, book20_bid_proxy_usdt=51742, book20_ask_proxy_usdt=36940, funding_indicative=0.000059, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=16625948. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
