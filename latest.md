# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T16:30:20Z**
- feed_generated_utc: 2026-11-10T16:30:21+00:00
- source_sha256: `580f2a22e446733e6bef87d97d401783bc280c6131ea9e3921b27e136577ec93`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T16:30+00:00, close=73231.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.932200|-4.63|64.38|-4.72|10597963|5.17|
|ZEC_USDT|1061.820000|-2.88|-11.79|-2.97|2352517966|0.75|
|PEPE_USDT|0.000005|-2.15|5.01|-2.24|76280357|0.20|
|DASH_USDT|44.220000|-2.03|-4.16|-2.12|13494729|2.26|
|ARB_USDT|0.158630|-1.70|-0.78|-1.79|40666385|0.63|
|ANTHROPIC_USDT|1301.530000|-1.21|-22.24|-1.30|7791103|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1301.530000|1280.200000|1302.100000|0.87|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158630|0.158930|0.158600|3.89|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|44.220000|44.570000|44.210000|1.72|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|1.50|Y|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.932200|1.952600|1.944400|2.89|Y|N/N|N/N|Y|N|
|ZEC_USDT|1061.820000|1074.930000|1060.630000|2.02|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-10T16:30:01+00:00, last15m_closed_end=2026-11-10T16:30+00:00, prior8high=1326.010000, depth_time=2026-11-10T16:30:19+00:00, book20_bid_proxy_usdt=12538, book20_ask_proxy_usdt=222874, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=7791103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T16:30:02+00:00, last15m_closed_end=2026-11-10T16:30+00:00, prior8high=0.166600, depth_time=2026-11-10T16:30:16+00:00, book20_bid_proxy_usdt=45903, book20_ask_proxy_usdt=74654, funding_indicative=-0.000096, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=40666385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T16:30:02+00:00, last15m_closed_end=2026-11-10T16:30+00:00, prior8high=47.390000, depth_time=2026-11-10T16:30:14+00:00, book20_bid_proxy_usdt=316036, book20_ask_proxy_usdt=469794, funding_indicative=0.000008, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=13494729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T16:30:02+00:00, last15m_closed_end=2026-11-10T16:30+00:00, prior8high=0.000006, depth_time=2026-11-10T16:30:12+00:00, book20_bid_proxy_usdt=40786, book20_ask_proxy_usdt=49684, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=76280357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T16:30:02+00:00, last15m_closed_end=2026-11-10T16:30+00:00, prior8high=2.085000, depth_time=2026-11-10T16:30:07+00:00, book20_bid_proxy_usdt=18716, book20_ask_proxy_usdt=13174, funding_indicative=0.000290, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.63%, turnover=10597963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T16:30:02+00:00, last15m_closed_end=2026-11-10T16:30+00:00, prior8high=1198.440000, depth_time=2026-11-10T16:30:08+00:00, book20_bid_proxy_usdt=248509, book20_ask_proxy_usdt=96593, funding_indicative=0.000001, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=2352517966. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
