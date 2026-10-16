# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T07:15:15Z**
- feed_generated_utc: 2026-10-16T07:15:16+00:00
- source_sha256: `1b84804bb76368716585602ce3313b0239e6220051ab7194dd5c6df2957c652e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T07:15+00:00, close=82167, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T07:00+00:00, close=82146.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.043316|-15.55|57.75|-15.30|6752169|3.91|
|BTW_USDT|1.831300|-3.98|31.90|-3.73|20459889|2.73|
|AKE_USDT|0.030648|-3.02|5.59|-2.77|20996886|1.63|
|NIL_USDT|0.085470|-1.62|-1.29|-1.37|9079217|3.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030648|0.030300|0.030648|1.41|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.831300|1.873900|1.831600|2.60|Y|Y/N|Y/Y|Y|N|
|NIL_USDT|0.085470|0.085330|0.085440|0.78|N|Y/N|N/N|Y|N|
|ZEREBRO_USDT|0.043316|0.038862|0.043316|0.89|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T07:15:00+00:00, last15m_closed_end=2026-10-16T07:15+00:00, prior8high=0.033159, depth_time=2026-10-16T07:15:12+00:00, book20_bid_proxy_usdt=12022, book20_ask_proxy_usdt=12799, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=20996886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T07:15:00+00:00, last15m_closed_end=2026-10-16T07:15+00:00, prior8high=2.047500, depth_time=2026-10-16T07:15:10+00:00, book20_bid_proxy_usdt=8082, book20_ask_proxy_usdt=22067, funding_indicative=0.000014, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=20459889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T07:15:00+00:00, last15m_closed_end=2026-10-16T07:15+00:00, prior8high=0.088060, depth_time=2026-10-16T07:15:14+00:00, book20_bid_proxy_usdt=43841, book20_ask_proxy_usdt=22039, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=9079217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T07:15:00+00:00, last15m_closed_end=2026-10-16T07:15+00:00, prior8high=0.044404, depth_time=2026-10-16T07:15:06+00:00, book20_bid_proxy_usdt=5014, book20_ask_proxy_usdt=25643, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.55%, turnover=6752169. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
