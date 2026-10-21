# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T16:45:20Z**
- feed_generated_utc: 2026-10-21T16:45:22+00:00
- source_sha256: `836744cbe861e987e5c7efe323cde4088fadae5826124550e26827ed445cf4f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T16:45+00:00, close=84636.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002191|-22.96|54.51|-23.10|9300090|9.13|
|JCT_USDT|0.004071|-4.23|93.76|-4.37|17332324|2.46|
|BR_USDT|0.524830|-3.08|28.71|-3.22|17504128|1.52|
|AKE_USDT|0.026275|-1.55|1.52|-1.69|9943737|3.42|
|ICNT_USDT|0.186100|-1.27|70.10|-1.41|5752439|5.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026275|0.026170|0.026287|0.63|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.524830|0.523420|0.524830|1.12|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002191|0.002323|0.002174|1.55|Y|Y/N|N/N|N|N|
|ICNT_USDT|0.186100|0.185500|0.186000|0.48|N|Y/Y|N/N|N|N|
|JCT_USDT|0.004071|0.004074|0.004089|1.22|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T16:45:04+00:00, last15m_closed_end=2026-10-21T16:45+00:00, prior8high=0.027884, depth_time=2026-10-21T16:45:16+00:00, book20_bid_proxy_usdt=11242, book20_ask_proxy_usdt=9486, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=9943737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T16:45:03+00:00, last15m_closed_end=2026-10-21T16:45+00:00, prior8high=0.590800, depth_time=2026-10-21T16:45:14+00:00, book20_bid_proxy_usdt=6887, book20_ask_proxy_usdt=6739, funding_indicative=-0.000099, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=17504128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T16:45:03+00:00, last15m_closed_end=2026-10-21T16:45+00:00, prior8high=0.004584, depth_time=2026-10-21T16:45:09+00:00, book20_bid_proxy_usdt=58165, book20_ask_proxy_usdt=89321, funding_indicative=-0.004199, next_funding_utc=2026-10-21T17:00:00+00:00, funding_cycle_h=1, 24h_change=-22.96%, turnover=9300090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-21T16:45:03+00:00, last15m_closed_end=2026-10-21T16:45+00:00, prior8high=0.195900, depth_time=2026-10-21T16:45:17+00:00, book20_bid_proxy_usdt=188446, book20_ask_proxy_usdt=122811, funding_indicative=-0.000072, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=5752439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T16:45:03+00:00, last15m_closed_end=2026-10-21T16:45+00:00, prior8high=0.004499, depth_time=2026-10-21T16:45:11+00:00, book20_bid_proxy_usdt=55533, book20_ask_proxy_usdt=54024, funding_indicative=0.000087, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.23%, turnover=17332324. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
