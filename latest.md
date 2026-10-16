# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T10:15:15Z**
- feed_generated_utc: 2026-10-16T10:15:17+00:00
- source_sha256: `f77f440cdecd5380d73b2b6254ee253a570252215a3e55824ff2e91413fd619c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T10:15+00:00, close=81881, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T10:00+00:00, close=81985.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.077790|-19.27|29.30|-18.68|43545841|1.29|
|AKE_USDT|0.030044|-4.93|3.51|-4.34|19904941|2.00|
|NIL_USDT|0.083770|-3.57|-3.25|-2.98|6195870|2.39|
|BTW_USDT|1.867300|-2.10|34.50|-1.51|21093198|4.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030044|0.028483|0.030031|1.21|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.867300|1.852800|1.874500|1.20|N|Y/N|Y/Y|Y|N|
|NIL_USDT|0.083770|0.081680|0.083770|0.52|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.077790|0.077970|0.077790|2.25|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T10:15:01+00:00, last15m_closed_end=2026-10-16T10:15+00:00, prior8high=0.031827, depth_time=2026-10-16T10:15:09+00:00, book20_bid_proxy_usdt=11380, book20_ask_proxy_usdt=17491, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=19904941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T10:15:01+00:00, last15m_closed_end=2026-10-16T10:15+00:00, prior8high=2.088200, depth_time=2026-10-16T10:15:14+00:00, book20_bid_proxy_usdt=8784, book20_ask_proxy_usdt=13287, funding_indicative=-0.000358, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=21093198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T10:15:01+00:00, last15m_closed_end=2026-10-16T10:15+00:00, prior8high=0.084370, depth_time=2026-10-16T10:15:12+00:00, book20_bid_proxy_usdt=26360, book20_ask_proxy_usdt=23643, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=6195870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T10:15:01+00:00, last15m_closed_end=2026-10-16T10:15+00:00, prior8high=0.079650, depth_time=2026-10-16T10:15:06+00:00, book20_bid_proxy_usdt=200759, book20_ask_proxy_usdt=334353, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.27%, turnover=43545841. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
