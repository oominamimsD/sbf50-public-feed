# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T21:15:24Z**
- feed_generated_utc: 2026-11-04T21:15:26+00:00
- source_sha256: `35bb0a1a9969086dfdbdb7d2c03fe3a28ca3f33a54ffb336101438f3ecc201e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T21:15+00:00, close=80232.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T21:00+00:00, close=80098.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.275000|-10.46|-25.39|-10.42|25438279|7.85|
|IDOL_USDT|0.021217|-9.59|145.08|-9.55|6351670|4.24|
|AKE_USDT|0.002555|-9.07|-87.28|-9.03|16851744|7.83|
|BTW_USDT|1.038200|-5.53|-40.26|-5.49|6373953|2.89|
|PUMPFUN_USDT|0.004228|-4.98|0.49|-4.94|19106853|2.37|
|ZRO_USDT|1.803300|-3.29|5.33|-3.25|11164932|0.56|
|HYPE_USDT|83.322000|-3.00|4.33|-2.96|91154418|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002555|0.002455|0.002571|1.66|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.038200|1.030900|1.038200|1.03|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.322000|83.096000|83.350000|1.88|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021217|0.021058|0.021217|1.37|N|Y/N|N/N|N|N|
|PUMPFUN_USDT|0.004228|0.004138|0.004228|0.29|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.275000|1.274000|1.275000|0.76|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.803300|1.757900|1.803300|0.34|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=0.002657, depth_time=2026-11-04T21:15:13+00:00, book20_bid_proxy_usdt=78373, book20_ask_proxy_usdt=84468, funding_indicative=-0.000668, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.07%, turnover=16851744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=1.079200, depth_time=2026-11-04T21:15:15+00:00, book20_bid_proxy_usdt=16571, book20_ask_proxy_usdt=12764, funding_indicative=0.000030, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.53%, turnover=6373953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=84.880000, depth_time=2026-11-04T21:15:23+00:00, book20_bid_proxy_usdt=206285, book20_ask_proxy_usdt=71932, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=91154418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=0.023103, depth_time=2026-11-04T21:15:10+00:00, book20_bid_proxy_usdt=4341, book20_ask_proxy_usdt=4491, funding_indicative=0.000174, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.59%, turnover=6351670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=0.004240, depth_time=2026-11-04T21:15:18+00:00, book20_bid_proxy_usdt=2358904, book20_ask_proxy_usdt=1996482, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.98%, turnover=19106853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=1.308000, depth_time=2026-11-04T21:15:08+00:00, book20_bid_proxy_usdt=1087216, book20_ask_proxy_usdt=967170, funding_indicative=-0.000219, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=25438279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T21:15:03+00:00, last15m_closed_end=2026-11-04T21:15+00:00, prior8high=1.805800, depth_time=2026-11-04T21:15:20+00:00, book20_bid_proxy_usdt=191969, book20_ask_proxy_usdt=34148, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=11164932. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
