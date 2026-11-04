# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T14:00:20Z**
- feed_generated_utc: 2026-11-04T14:00:22+00:00
- source_sha256: `9b64cb61a2c30c47fedf27fac9a46f03320c369f424f9151eca09d5969860047`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T14:00+00:00, close=78338.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T14:00+00:00, close=78338.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.034930|-32.94|-26.49|-33.80|7559610|5.75|
|AKE_USDT|0.003094|-25.55|-85.35|-26.41|14059720|3.23|
|TRUMPOFFICIAL_USDT|1.412000|-12.07|-16.35|-12.93|12745959|7.08|
|HOT_USDT|0.000483|-10.21|39.95|-11.07|5153672|8.28|
|ZRO_USDT|1.850600|-2.30|9.78|-3.16|10859189|0.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.034930|0.032170|0.034930|1.20|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.003094|0.002758|0.003089|1.47|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000483|0.000472|0.000483|1.55|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.412000|1.407000|1.412000|1.62|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.850600|1.841900|1.850500|0.86|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T14:00:02+00:00, last15m_closed_end=2026-11-04T14:00+00:00, prior8high=0.034410, depth_time=2026-11-04T14:00:09+00:00, book20_bid_proxy_usdt=20478, book20_ask_proxy_usdt=25255, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.94%, turnover=7559610. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T14:00:02+00:00, last15m_closed_end=2026-11-04T14:00+00:00, prior8high=0.003257, depth_time=2026-11-04T14:00:11+00:00, book20_bid_proxy_usdt=31790, book20_ask_proxy_usdt=45617, funding_indicative=-0.000061, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.55%, turnover=14059720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T14:00:02+00:00, last15m_closed_end=2026-11-04T14:00+00:00, prior8high=0.000500, depth_time=2026-11-04T14:00:16+00:00, book20_bid_proxy_usdt=80412, book20_ask_proxy_usdt=103528, funding_indicative=-0.000145, next_funding_utc=2026-11-04T15:00:00+00:00, funding_cycle_h=1, 24h_change=-10.21%, turnover=5153672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T14:00:03+00:00, last15m_closed_end=2026-11-04T14:00+00:00, prior8high=1.475000, depth_time=2026-11-04T14:00:14+00:00, book20_bid_proxy_usdt=2581359, book20_ask_proxy_usdt=2313498, funding_indicative=-0.000394, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.07%, turnover=12745959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T14:00:03+00:00, last15m_closed_end=2026-11-04T14:00+00:00, prior8high=1.907900, depth_time=2026-11-04T14:00:19+00:00, book20_bid_proxy_usdt=37188, book20_ask_proxy_usdt=34549, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=10859189. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
