# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T17:45:16Z**
- feed_generated_utc: 2026-10-13T17:45:19+00:00
- source_sha256: `7763284cab51f3c0dd42f8ddb77b4ffb285655110da11a206559352671600273`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T17:45+00:00, close=83166.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T17:00+00:00, close=83347, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083710|-3.70|60.39|-3.43|50516037|1.19|
|W_USDT|0.016254|-3.26|12.00|-2.99|11889080|9.83|
|RLC_USDT|0.899500|-2.56|9.72|-2.29|5936764|1.11|
|DOS_USDT|0.212500|-1.30|-1.39|-1.03|9507475|4.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.212500|0.212000|0.212500|0.71|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.899500|0.901200|0.899900|0.60|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.083710|0.082420|0.083710|0.97|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016254|0.016221|0.016254|0.71|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T17:45:03+00:00, last15m_closed_end=2026-10-13T17:45+00:00, prior8high=0.218600, depth_time=2026-10-13T17:45:13+00:00, book20_bid_proxy_usdt=125530, book20_ask_proxy_usdt=142133, funding_indicative=0.000004, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=9507475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T17:45:03+00:00, last15m_closed_end=2026-10-13T17:45+00:00, prior8high=0.949500, depth_time=2026-10-13T17:45:13+00:00, book20_bid_proxy_usdt=80871, book20_ask_proxy_usdt=71474, funding_indicative=-0.000690, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=5936764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T17:45:03+00:00, last15m_closed_end=2026-10-13T17:45+00:00, prior8high=0.087530, depth_time=2026-10-13T17:45:09+00:00, book20_bid_proxy_usdt=196557, book20_ask_proxy_usdt=216154, funding_indicative=0.000014, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=50516037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T17:45:03+00:00, last15m_closed_end=2026-10-13T17:45+00:00, prior8high=0.017867, depth_time=2026-10-13T17:45:11+00:00, book20_bid_proxy_usdt=23766, book20_ask_proxy_usdt=41759, funding_indicative=-0.000360, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=11889080. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
