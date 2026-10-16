# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T07:45:21Z**
- feed_generated_utc: 2026-10-16T07:45:23+00:00
- source_sha256: `ed0ddb5730da8b0a77fc8548e1f815c1eec9f06737f995ed95205866dce0d630`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T07:45+00:00, close=82195.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T07:00+00:00, close=82146.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.080600|-16.35|33.97|-16.14|47785249|1.24|
|ZEREBRO_USDT|0.045967|-10.38|67.41|-10.17|6786044|4.57|
|AKE_USDT|0.030265|-4.23|4.27|-4.02|21111942|1.32|
|BTW_USDT|1.838000|-3.63|32.39|-3.42|21260599|0.54|
|NIL_USDT|0.083990|-3.32|-3.00|-3.11|9155745|3.58|
|CRV_USDT|0.347600|-1.89|2.50|-1.68|7983562|2.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030265|0.030300|0.030268|0.95|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.838000|1.766500|1.842200|2.28|N|Y/N|Y/Y|Y|N|
|CRV_USDT|0.347600|0.348800|0.347600|2.72|Y|Y/N|N/N|Y|N|
|NIL_USDT|0.083990|0.084700|0.083990|1.66|Y|Y/N|N/N|Y|N|
|STRK_USDT|0.080600|0.081180|0.080580|1.92|Y|Y/Y|N/N|Y|N|
|ZEREBRO_USDT|0.045967|0.038862|0.045967|0.72|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T07:45:01+00:00, last15m_closed_end=2026-10-16T07:45+00:00, prior8high=0.032366, depth_time=2026-10-16T07:45:13+00:00, book20_bid_proxy_usdt=20314, book20_ask_proxy_usdt=12856, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.23%, turnover=21111942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T07:45:01+00:00, last15m_closed_end=2026-10-16T07:45+00:00, prior8high=2.047500, depth_time=2026-10-16T07:45:16+00:00, book20_bid_proxy_usdt=9740, book20_ask_proxy_usdt=9199, funding_indicative=-0.000078, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=21260599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-16T07:45:02+00:00, last15m_closed_end=2026-10-16T07:45+00:00, prior8high=0.352700, depth_time=2026-10-16T07:45:20+00:00, book20_bid_proxy_usdt=223402, book20_ask_proxy_usdt=249308, funding_indicative=0.000100, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=7983562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T07:45:01+00:00, last15m_closed_end=2026-10-16T07:45+00:00, prior8high=0.087770, depth_time=2026-10-16T07:45:18+00:00, book20_bid_proxy_usdt=36463, book20_ask_proxy_usdt=32471, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.32%, turnover=9155745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T07:45:01+00:00, last15m_closed_end=2026-10-16T07:45+00:00, prior8high=0.084950, depth_time=2026-10-16T07:45:08+00:00, book20_bid_proxy_usdt=264245, book20_ask_proxy_usdt=396387, funding_indicative=-0.000031, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.35%, turnover=47785249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T07:45:01+00:00, last15m_closed_end=2026-10-16T07:45+00:00, prior8high=0.045687, depth_time=2026-10-16T07:45:10+00:00, book20_bid_proxy_usdt=48392, book20_ask_proxy_usdt=4473, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.38%, turnover=6786044. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
