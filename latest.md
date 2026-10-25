# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T04:15:20Z**
- feed_generated_utc: 2026-10-25T04:15:23+00:00
- source_sha256: `34880feb1b4069f6441a3b673b77567c548ff666bd3e788cec5fa44d7f924b68`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T04:15+00:00, close=80807.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.059530|-11.67|92.34|-12.97|13563136|3.35|
|BIRB_USDT|0.091370|-6.44|88.31|-7.74|8489285|3.29|
|BTW_USDT|1.707800|-1.92|-24.74|-3.22|9939216|2.34|
|DOT_USDT|1.042200|0.29|-6.72|-1.01|11394607|1.92|
|STRK_USDT|0.046870|0.29|-29.14|-1.01|8444206|2.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.091370|0.069430|0.091370|1.82|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.707800|1.695500|1.707800|1.84|N|Y/N|Y/Y|Y|N|
|DOT_USDT|1.042200|1.039200|1.042200|0.78|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.059530|0.050530|0.060270|1.32|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046870|0.046250|0.046870|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T04:15:03+00:00, last15m_closed_end=2026-10-25T04:15+00:00, prior8high=0.088490, depth_time=2026-10-25T04:15:11+00:00, book20_bid_proxy_usdt=9895, book20_ask_proxy_usdt=6606, funding_indicative=-0.008593, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.44%, turnover=8489285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T04:15:03+00:00, last15m_closed_end=2026-10-25T04:15+00:00, prior8high=1.754800, depth_time=2026-10-25T04:15:14+00:00, book20_bid_proxy_usdt=12800, book20_ask_proxy_usdt=7691, funding_indicative=-0.003721, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=9939216. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T04:15:03+00:00, last15m_closed_end=2026-10-25T04:15+00:00, prior8high=1.052900, depth_time=2026-10-25T04:15:14+00:00, book20_bid_proxy_usdt=409814, book20_ask_proxy_usdt=327533, funding_indicative=-0.000120, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.29%, turnover=11394607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T04:15:03+00:00, last15m_closed_end=2026-10-25T04:15+00:00, prior8high=0.058640, depth_time=2026-10-25T04:15:09+00:00, book20_bid_proxy_usdt=49917, book20_ask_proxy_usdt=52129, funding_indicative=-0.001147, next_funding_utc=2026-10-25T05:00:00+00:00, funding_cycle_h=1, 24h_change=-11.67%, turnover=13563136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T04:15:00+00:00, last15m_closed_end=2026-10-25T04:15+00:00, prior8high=0.047120, depth_time=2026-10-25T04:15:19+00:00, book20_bid_proxy_usdt=942031, book20_ask_proxy_usdt=691512, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.29%, turnover=8444206. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
