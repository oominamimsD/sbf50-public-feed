# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T17:15:31Z**
- feed_generated_utc: 2026-11-02T17:15:34+00:00
- source_sha256: `e5283db5ad99429d81e298961a8e50fde1225432d2e8b591ef5aa5f5b3d7e494`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T17:15+00:00, close=77400, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T17:00+00:00, close=77464.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.127800|-3.69|-48.63|-3.58|7089132|7.83|
|ZRO_USDT|1.721200|-2.65|0.82|-2.54|7125085|0.58|
|ENA_USDT|0.170490|-2.59|-18.95|-2.48|66504001|0.59|
|ZEC_USDT|1224.240000|-2.38|-1.88|-2.27|1575905735|0.08|
|PUMPFUN_USDT|0.004006|-2.38|-7.43|-2.27|9993098|2.50|
|LIT_USDT|3.044800|-1.99|-2.35|-1.88|11825317|0.33|
|XPL_USDT|0.068490|-1.56|-7.80|-1.45|9544071|1.46|
|QNT_USDT|199.380000|-1.51|-5.18|-1.40|46438835|0.50|
|Q_USDT|0.025670|-1.42|-56.53|-1.31|7054712|3.90|
|HYPE_USDT|84.533000|-1.37|7.76|-1.26|95434335|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.170490|0.170670|0.170490|1.57|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|84.533000|85.331000|84.533000|3.68|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.044800|3.075500|3.044800|0.97|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004006|0.004041|0.004005|3.28|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|199.380000|199.120000|199.380000|1.41|N|Y/N|N/N|Y|N|
|Q_USDT|0.025670|0.025090|0.025670|0.95|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.127800|0.127300|0.128000|1.21|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.068490|0.068800|0.068490|2.17|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1224.240000|1227.170000|1224.880000|0.76|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|1.721200|1.742000|1.726400|2.71|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=0.178750, depth_time=2026-11-02T17:15:13+00:00, book20_bid_proxy_usdt=135344, book20_ask_proxy_usdt=202060, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=66504001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-02T17:15:02+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=86.541000, depth_time=2026-11-02T17:15:30+00:00, book20_bid_proxy_usdt=364671, book20_ask_proxy_usdt=158288, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=95434335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=3.175600, depth_time=2026-11-02T17:15:20+00:00, book20_bid_proxy_usdt=23776, book20_ask_proxy_usdt=31937, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=11825317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=0.004222, depth_time=2026-11-02T17:15:17+00:00, book20_bid_proxy_usdt=2063368, book20_ask_proxy_usdt=2102989, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=9993098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=204.870000, depth_time=2026-11-02T17:15:25+00:00, book20_bid_proxy_usdt=111539, book20_ask_proxy_usdt=86805, funding_indicative=0.000059, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=46438835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=0.026880, depth_time=2026-11-02T17:15:28+00:00, book20_bid_proxy_usdt=75379, book20_ask_proxy_usdt=41790, funding_indicative=-0.000324, next_funding_utc=2026-11-02T18:00:00+00:00, funding_cycle_h=1, 24h_change=-1.42%, turnover=7054712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=0.136800, depth_time=2026-11-02T17:15:08+00:00, book20_bid_proxy_usdt=154830, book20_ask_proxy_usdt=143348, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.69%, turnover=7089132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=0.070990, depth_time=2026-11-02T17:15:22+00:00, book20_bid_proxy_usdt=358821, book20_ask_proxy_usdt=440172, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=9544071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T17:15:02+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=1273.110000, depth_time=2026-11-02T17:15:16+00:00, book20_bid_proxy_usdt=918054, book20_ask_proxy_usdt=206324, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=1575905735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T17:15:03+00:00, last15m_closed_end=2026-11-02T17:15+00:00, prior8high=1.801200, depth_time=2026-11-02T17:15:10+00:00, book20_bid_proxy_usdt=25035, book20_ask_proxy_usdt=57391, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=7125085. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
