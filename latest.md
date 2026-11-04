# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T11:30:18Z**
- feed_generated_utc: 2026-11-04T11:30:19+00:00
- source_sha256: `bf9b75349d46d2b0866478aa8e0125959b114d7231dd470f6ed5c3d37c4ed95d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T11:30+00:00, close=78644.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T11:00+00:00, close=78590.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032660|-39.30|-31.27|-40.56|10632355|9.19|
|AKE_USDT|0.002935|-29.37|-86.10|-30.63|12957582|3.41|
|HOT_USDT|0.000498|-7.52|44.15|-8.78|8801370|2.01|
|TRUMPOFFICIAL_USDT|1.488000|-7.46|-11.84|-8.72|10548993|6.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032660|0.032150|0.032660|0.97|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.002935|0.002807|0.002935|1.50|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000498|0.000507|0.000498|2.51|Y|N/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.488000|1.463000|1.488000|0.14|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T11:30:02+00:00, last15m_closed_end=2026-11-04T11:30+00:00, prior8high=0.034540, depth_time=2026-11-04T11:30:05+00:00, book20_bid_proxy_usdt=23460, book20_ask_proxy_usdt=35701, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.30%, turnover=10632355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T11:30:02+00:00, last15m_closed_end=2026-11-04T11:30+00:00, prior8high=0.003107, depth_time=2026-11-04T11:30:11+00:00, book20_bid_proxy_usdt=67054, book20_ask_proxy_usdt=76407, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.37%, turnover=12957582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T11:30:02+00:00, last15m_closed_end=2026-11-04T11:30+00:00, prior8high=0.000542, depth_time=2026-11-04T11:30:13+00:00, book20_bid_proxy_usdt=109757, book20_ask_proxy_usdt=90195, funding_indicative=-0.000266, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=1, 24h_change=-7.52%, turnover=8801370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T11:30:02+00:00, last15m_closed_end=2026-11-04T11:30+00:00, prior8high=1.497000, depth_time=2026-11-04T11:30:16+00:00, book20_bid_proxy_usdt=2160585, book20_ask_proxy_usdt=2175233, funding_indicative=-0.000197, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.46%, turnover=10548993. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
