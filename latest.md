# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T17:00:20Z**
- feed_generated_utc: 2026-11-08T17:00:21+00:00
- source_sha256: `1648fa61dc79eb2f10f1914721038aa08e9bee52a43b48f897288eb9275ad5fa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T17:00+00:00, close=75741.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T17:00+00:00, close=75741.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001739|-8.04|49.36|-7.64|18859540|4.60|
|NEAR_USDT|3.603000|-3.04|-16.80|-2.64|29911118|2.78|
|PUMPFUN_USDT|0.003657|-2.06|-13.30|-1.66|10347774|2.74|
|WLD_USDT|0.322500|-1.55|-18.49|-1.15|23652728|3.10|
|LIT_USDT|3.179700|-1.53|-1.56|-1.13|7528781|0.31|
|ZEC_USDT|1251.470000|-1.51|1.09|-1.11|1331578799|0.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.179700|3.181800|3.179700|1.54|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|3.603000|3.681000|3.603000|9.38|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001739|0.001739|0.001739|2.35|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003657|0.003664|0.003657|1.85|Y|Y/N|Y/Y|Y|N|
|WLD_USDT|0.322500|0.322800|0.322500|2.25|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1251.470000|1252.460000|1251.720000|1.59|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-11-08T17:00:01+00:00, last15m_closed_end=2026-11-08T17:00+00:00, prior8high=3.247100, depth_time=2026-11-08T17:00:16+00:00, book20_bid_proxy_usdt=22011, book20_ask_proxy_usdt=29350, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=7528781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T17:00:01+00:00, last15m_closed_end=2026-11-08T17:00+00:00, prior8high=3.725000, depth_time=2026-11-08T17:00:09+00:00, book20_bid_proxy_usdt=2522936, book20_ask_proxy_usdt=2993921, funding_indicative=0.000020, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=29911118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T17:00:00+00:00, last15m_closed_end=2026-11-08T17:00+00:00, prior8high=0.001987, depth_time=2026-11-08T17:00:07+00:00, book20_bid_proxy_usdt=11863, book20_ask_proxy_usdt=13969, funding_indicative=-0.001425, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.04%, turnover=18859540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T17:00:01+00:00, last15m_closed_end=2026-11-08T17:00+00:00, prior8high=0.003770, depth_time=2026-11-08T17:00:11+00:00, book20_bid_proxy_usdt=1961239, book20_ask_proxy_usdt=1947470, funding_indicative=0.000016, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=10347774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T17:00:01+00:00, last15m_closed_end=2026-11-08T17:00+00:00, prior8high=0.328300, depth_time=2026-11-08T17:00:11+00:00, book20_bid_proxy_usdt=4019088, book20_ask_proxy_usdt=3530735, funding_indicative=-0.000201, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=23652728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T17:00:01+00:00, last15m_closed_end=2026-11-08T17:00+00:00, prior8high=1277.770000, depth_time=2026-11-08T17:00:19+00:00, book20_bid_proxy_usdt=328256, book20_ask_proxy_usdt=286912, funding_indicative=0.000007, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=1331578799. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
