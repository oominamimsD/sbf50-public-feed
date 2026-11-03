# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T19:30:13Z**
- feed_generated_utc: 2026-11-03T19:30:15+00:00
- source_sha256: `5c92d2156e5fa451acc052af33fce693648ebebe91d052bb473b47a999c2c4fe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T19:30+00:00, close=77582.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T19:00+00:00, close=77569.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003979|-4.25|-81.16|-4.14|13353413|7.54|
|QNT_USDT|190.740000|-2.39|-3.61|-2.28|57355992|1.05|
|XPL_USDT|0.063300|-1.17|-14.25|-1.06|9734984|1.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003979|0.003757|0.003979|0.39|N|Y/Y|Y/Y|N|N|
|QNT_USDT|190.740000|190.860000|190.580000|1.83|Y|Y/Y|Y/Y|N|Y|
|XPL_USDT|0.063300|0.063150|0.063300|0.97|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T19:30:01+00:00, last15m_closed_end=2026-11-03T19:30+00:00, prior8high=0.004095, depth_time=2026-11-03T19:30:08+00:00, book20_bid_proxy_usdt=81277, book20_ask_proxy_usdt=43334, funding_indicative=-0.000511, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=13353413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T19:30:01+00:00, last15m_closed_end=2026-11-03T19:30+00:00, prior8high=195.660000, depth_time=2026-11-03T19:30:10+00:00, book20_bid_proxy_usdt=109571, book20_ask_proxy_usdt=78869, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=57355992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T19:30:01+00:00, last15m_closed_end=2026-11-03T19:30+00:00, prior8high=0.064140, depth_time=2026-11-03T19:30:13+00:00, book20_bid_proxy_usdt=388948, book20_ask_proxy_usdt=426717, funding_indicative=0.000050, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=9734984. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
