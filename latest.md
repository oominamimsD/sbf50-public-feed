# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T17:15:17Z**
- feed_generated_utc: 2026-11-08T17:15:19+00:00
- source_sha256: `da2b2387f419005721c3450a02d1680520940263112ebd82556526d67dbb6564`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T17:15+00:00, close=75653.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T17:00+00:00, close=75741.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001754|-10.39|50.65|-9.90|18975394|0.57|
|NEAR_USDT|3.592000|-2.94|-17.06|-2.45|30466884|2.79|
|ZEC_USDT|1239.830000|-2.42|0.15|-1.93|1358359655|0.08|
|PUMPFUN_USDT|0.003652|-2.27|-13.41|-1.78|10394268|2.74|
|INJ_USDT|7.952000|-2.20|10.56|-1.71|18098368|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|INJ_USDT|7.952000|8.034000|7.952000|5.04|Y|Y/Y|N/N|Y|N|
|NEAR_USDT|3.592000|3.587000|3.587000|1.99|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001754|0.001693|0.001754|1.33|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003652|0.003635|0.003652|1.03|N|Y/N|Y/Y|Y|N|
|ZEC_USDT|1239.830000|1246.140000|1239.600000|1.39|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- INJ_USDT: quote_utc=2026-11-08T17:15:01+00:00, last15m_closed_end=2026-11-08T17:15+00:00, prior8high=8.160000, depth_time=2026-11-08T17:15:15+00:00, book20_bid_proxy_usdt=97354, book20_ask_proxy_usdt=304676, funding_indicative=-0.000061, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=18098368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T17:15:01+00:00, last15m_closed_end=2026-11-08T17:15+00:00, prior8high=3.725000, depth_time=2026-11-08T17:15:07+00:00, book20_bid_proxy_usdt=4655773, book20_ask_proxy_usdt=5195394, funding_indicative=0.000031, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=30466884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T17:15:01+00:00, last15m_closed_end=2026-11-08T17:15+00:00, prior8high=0.001987, depth_time=2026-11-08T17:15:07+00:00, book20_bid_proxy_usdt=13026, book20_ask_proxy_usdt=12964, funding_indicative=-0.001405, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.39%, turnover=18975394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T17:15:01+00:00, last15m_closed_end=2026-11-08T17:15+00:00, prior8high=0.003770, depth_time=2026-11-08T17:15:14+00:00, book20_bid_proxy_usdt=2188222, book20_ask_proxy_usdt=1951165, funding_indicative=0.000011, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=10394268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T17:15:01+00:00, last15m_closed_end=2026-11-08T17:15+00:00, prior8high=1276.700000, depth_time=2026-11-08T17:15:12+00:00, book20_bid_proxy_usdt=132472, book20_ask_proxy_usdt=256139, funding_indicative=0.000018, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=1358359655. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
