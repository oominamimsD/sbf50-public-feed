# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T13:15:22Z**
- feed_generated_utc: 2026-10-21T13:15:24+00:00
- source_sha256: `170669dfa3ecab4d5f8571710a979340edae1928361da58256aea48ada8376ad`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T13:15+00:00, close=83795, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T13:00+00:00, close=83471.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045539|-29.53|181.50|-30.99|6528797|3.51|
|BAT_USDT|0.179800|-16.67|1.36|-18.13|10481462|1.11|
|BTW_USDT|1.547100|-16.35|-20.76|-17.81|24352115|2.58|
|AKE_USDT|0.027212|-12.47|8.55|-13.93|9100727|5.52|
|BR_USDT|0.618350|-4.96|42.80|-6.42|19567529|1.46|
|TIA_USDT|0.621900|-0.12|7.72|-1.58|43322050|6.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045539|0.044727|0.045505|0.71|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027212|0.026106|0.027211|1.54|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.179800|0.179570|0.179900|0.64|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.618350|0.572580|0.618350|0.65|N|N/Y|N/N|N|N|
|BTW_USDT|1.547100|1.555200|1.549100|0.96|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.621900|0.615000|0.622200|1.07|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T13:15:01+00:00, last15m_closed_end=2026-10-21T13:15+00:00, prior8high=0.047381, depth_time=2026-10-21T13:15:08+00:00, book20_bid_proxy_usdt=7224, book20_ask_proxy_usdt=8551, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.53%, turnover=6528797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T13:15:01+00:00, last15m_closed_end=2026-10-21T13:15+00:00, prior8high=0.036371, depth_time=2026-10-21T13:15:16+00:00, book20_bid_proxy_usdt=10695, book20_ask_proxy_usdt=15912, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.47%, turnover=9100727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T13:15:01+00:00, last15m_closed_end=2026-10-21T13:15+00:00, prior8high=0.182790, depth_time=2026-10-21T13:15:11+00:00, book20_bid_proxy_usdt=22229, book20_ask_proxy_usdt=26312, funding_indicative=-0.000185, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.67%, turnover=10481462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T13:15:01+00:00, last15m_closed_end=2026-10-21T13:15+00:00, prior8high=0.623940, depth_time=2026-10-21T13:15:19+00:00, book20_bid_proxy_usdt=4262, book20_ask_proxy_usdt=3984, funding_indicative=-0.000005, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.96%, turnover=19567529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T13:15:01+00:00, last15m_closed_end=2026-10-21T13:15+00:00, prior8high=1.768800, depth_time=2026-10-21T13:15:13+00:00, book20_bid_proxy_usdt=9583, book20_ask_proxy_usdt=10526, funding_indicative=-0.005444, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.35%, turnover=24352115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T13:15:01+00:00, last15m_closed_end=2026-10-21T13:15+00:00, prior8high=0.626700, depth_time=2026-10-21T13:15:20+00:00, book20_bid_proxy_usdt=246321, book20_ask_proxy_usdt=265787, funding_indicative=-0.000081, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.12%, turnover=43322050. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
