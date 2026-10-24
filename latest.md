# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T16:00:20Z**
- feed_generated_utc: 2026-10-24T16:00:23+00:00
- source_sha256: `9d4d15715f616d7a553ccaab740a0633617f8fcf0e7200b34325a0f7319f0190`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.046050|-19.09|260.89|-19.09|86349662|6.49|
|AGT_USDT|0.066930|-5.90|-7.11|-5.90|10243972|4.48|
|FARTCOIN_USDT|0.121970|-1.72|-17.61|-1.72|10594379|0.82|
|DASH_USDT|49.500000|-1.68|2.33|-1.68|16506267|2.02|
|STRK_USDT|0.046730|-1.22|-29.35|-1.22|10021182|2.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066930|0.065630|0.066930|0.91|N|Y/Y|Y/N|Y|N|
|DASH_USDT|49.500000|48.890000|49.500000|1.66|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.121970|0.119180|0.121980|3.16|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.046050|0.047100|0.046050|1.09|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.046730|0.046470|0.046730|9.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T16:00:02+00:00, last15m_closed_end=2026-10-24T16:00+00:00, prior8high=0.077400, depth_time=2026-10-24T16:00:12+00:00, book20_bid_proxy_usdt=12808, book20_ask_proxy_usdt=6465, funding_indicative=0.000170, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.90%, turnover=10243972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-24T16:00:02+00:00, last15m_closed_end=2026-10-24T16:00+00:00, prior8high=50.900000, depth_time=2026-10-24T16:00:16+00:00, book20_bid_proxy_usdt=528871, book20_ask_proxy_usdt=505105, funding_indicative=-0.000002, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=16506267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-24T16:00:02+00:00, last15m_closed_end=2026-10-24T16:00+00:00, prior8high=0.132320, depth_time=2026-10-24T16:00:14+00:00, book20_bid_proxy_usdt=32767, book20_ask_proxy_usdt=44734, funding_indicative=-0.000324, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=10594379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T16:00:02+00:00, last15m_closed_end=2026-10-24T16:00+00:00, prior8high=0.061360, depth_time=2026-10-24T16:00:09+00:00, book20_bid_proxy_usdt=30676, book20_ask_proxy_usdt=43983, funding_indicative=0.000012, next_funding_utc=2026-10-24T17:00:00+00:00, funding_cycle_h=1, 24h_change=-19.09%, turnover=86349662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T16:00:02+00:00, last15m_closed_end=2026-10-24T16:00+00:00, prior8high=0.048070, depth_time=2026-10-24T16:00:19+00:00, book20_bid_proxy_usdt=878964, book20_ask_proxy_usdt=788966, funding_indicative=0.000025, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=10021182. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
