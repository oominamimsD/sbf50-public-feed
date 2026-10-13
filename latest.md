# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T19:15:16Z**
- feed_generated_utc: 2026-10-13T19:15:19+00:00
- source_sha256: `7b2affd4aa1f7391f2c02fcfe8cfc1936389765479fb96903f0615a66c55017d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T19:15+00:00, close=83157.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T19:00+00:00, close=83113.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.358960|-3.44|-3.40|-3.16|5829573|1.11|
|DOS_USDT|0.208300|-3.25|-3.34|-2.97|9500625|4.80|
|W_USDT|0.016460|-2.04|13.42|-1.76|10325395|7.29|
|RLC_USDT|0.906700|-1.78|10.60|-1.50|5734519|1.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.358960|0.356760|0.358930|0.34|N|Y/N|N/N|Y|N|
|DOS_USDT|0.208300|0.206400|0.208400|0.87|N|Y/Y|Y/Y|Y|N|
|RLC_USDT|0.906700|0.874600|0.906700|0.85|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.016460|0.015938|0.016459|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T19:15:03+00:00, last15m_closed_end=2026-10-13T19:15+00:00, prior8high=0.378050, depth_time=2026-10-13T19:15:07+00:00, book20_bid_proxy_usdt=8190, book20_ask_proxy_usdt=10645, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=5829573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T19:15:03+00:00, last15m_closed_end=2026-10-13T19:15+00:00, prior8high=0.215800, depth_time=2026-10-13T19:15:11+00:00, book20_bid_proxy_usdt=103275, book20_ask_proxy_usdt=99118, funding_indicative=-0.000054, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=9500625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T19:15:03+00:00, last15m_closed_end=2026-10-13T19:15+00:00, prior8high=0.925900, depth_time=2026-10-13T19:15:14+00:00, book20_bid_proxy_usdt=74211, book20_ask_proxy_usdt=64177, funding_indicative=-0.000610, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=5734519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T19:15:03+00:00, last15m_closed_end=2026-10-13T19:15+00:00, prior8high=0.016788, depth_time=2026-10-13T19:15:13+00:00, book20_bid_proxy_usdt=33831, book20_ask_proxy_usdt=37988, funding_indicative=-0.000305, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=10325395. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
