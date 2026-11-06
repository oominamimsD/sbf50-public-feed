# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T19:30:12Z**
- feed_generated_utc: 2026-11-06T19:30:13+00:00
- source_sha256: `0616f88e6d0c6c8e1cce5afee21706a3f34706d9832fd57a561aaf3ebfff93f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T19:30+00:00, close=75677.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T19:00+00:00, close=75764.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.126400|-33.47|-52.40|-33.27|29523424|7.88|
|ANTHROPIC_USDT|1329.770000|-7.08|-20.67|-6.88|5601429|1.96|
|LIT_USDT|3.281300|-3.27|16.18|-3.07|12036153|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1329.770000|1326.270000|1329.770000|5.16|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.281300|3.301900|3.281300|1.19|N|Y/Y|N/N|Y|N|
|UAI_USDT|0.126400|0.105200|0.126400|0.89|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T19:30:00+00:00, last15m_closed_end=2026-11-06T19:30+00:00, prior8high=1385.470000, depth_time=2026-11-06T19:30:09+00:00, book20_bid_proxy_usdt=29845, book20_ask_proxy_usdt=18318, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.08%, turnover=5601429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T19:30:00+00:00, last15m_closed_end=2026-11-06T19:30+00:00, prior8high=3.455000, depth_time=2026-11-06T19:30:09+00:00, book20_bid_proxy_usdt=44663, book20_ask_proxy_usdt=33260, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=12036153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T19:30:00+00:00, last15m_closed_end=2026-11-06T19:30+00:00, prior8high=0.249200, depth_time=2026-11-06T19:30:06+00:00, book20_bid_proxy_usdt=75017, book20_ask_proxy_usdt=175700, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-33.47%, turnover=29523424. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
