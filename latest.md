# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T19:15:19Z**
- feed_generated_utc: 2026-10-31T19:15:21+00:00
- source_sha256: `4d4b724de5eb50e35d43307d08c8299191a050006d10c6b5889adeca5cd74ff6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T19:15+00:00, close=77643, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T19:00+00:00, close=77582.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRX_USDT|0.307000|-1.70|-6.66|-1.80|8186025|0.33|
|WLD_USDT|0.398600|-1.43|-13.72|-1.53|36299249|2.51|
|FET_USDT|0.161600|-1.04|-6.21|-1.14|5286919|6.19|
|DASH_USDT|48.120000|-1.02|-2.78|-1.12|5034034|2.08|
|BTW_USDT|1.110800|-0.98|-36.20|-1.08|6897845|1.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.110800|1.083700|1.110800|1.16|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.120000|48.050000|48.120000|0.30|N|Y/N|Y/Y|Y|N|
|FET_USDT|0.161600|0.160900|0.161600|1.09|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.307000|0.305290|0.307000|5.14|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398600|0.397300|0.398600|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T19:15:00+00:00, last15m_closed_end=2026-10-31T19:15+00:00, prior8high=1.134700, depth_time=2026-10-31T19:15:18+00:00, book20_bid_proxy_usdt=21005, book20_ask_proxy_usdt=13473, funding_indicative=-0.000247, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.98%, turnover=6897845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T19:15:00+00:00, last15m_closed_end=2026-10-31T19:15+00:00, prior8high=48.510000, depth_time=2026-10-31T19:15:15+00:00, book20_bid_proxy_usdt=784795, book20_ask_proxy_usdt=470902, funding_indicative=0.000020, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=5034034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T19:15:00+00:00, last15m_closed_end=2026-10-31T19:15+00:00, prior8high=0.162400, depth_time=2026-10-31T19:15:12+00:00, book20_bid_proxy_usdt=1289084, book20_ask_proxy_usdt=736513, funding_indicative=-0.000064, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=5286919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T19:15:00+00:00, last15m_closed_end=2026-10-31T19:15+00:00, prior8high=0.311270, depth_time=2026-10-31T19:15:05+00:00, book20_bid_proxy_usdt=93466, book20_ask_proxy_usdt=61670, funding_indicative=-0.000458, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=8186025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T19:15:00+00:00, last15m_closed_end=2026-10-31T19:15+00:00, prior8high=0.400400, depth_time=2026-10-31T19:15:10+00:00, book20_bid_proxy_usdt=2425402, book20_ask_proxy_usdt=2454069, funding_indicative=-0.000029, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=36299249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
