# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T03:15:25Z**
- feed_generated_utc: 2026-10-23T03:15:27+00:00
- source_sha256: `55372ca7992e7082f6a5c8a0bd1a34bb9423148f31d29fc679950dee85377ccc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T03:15+00:00, close=81850.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T03:00+00:00, close=81942.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004363|-5.31|119.79|-5.55|9388533|9.17|
|PHA_USDT|0.060170|-3.02|19.10|-3.26|8132327|6.65|
|LIT_USDT|3.507000|-2.96|13.44|-3.20|11044930|0.28|
|STRK_USDT|0.052850|-2.77|-45.15|-3.01|11901287|3.78|
|SILVER_USDT|54.030000|-2.22|-5.44|-2.46|370137572|1.85|
|TIA_USDT|0.561100|-1.28|-6.87|-1.52|23327196|1.78|
|XAU_USDT|4023.810000|-0.88|-3.18|-1.12|763064739|0.03|
|XAUT_USDT|4022.430000|-0.78|-2.95|-1.02|286852581|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004363|0.004284|0.004363|1.40|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.507000|3.385300|3.504300|2.95|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.060170|0.059190|0.060150|0.15|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.030000|53.570000|54.020000|0.95|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052850|0.052520|0.052850|1.74|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.561100|0.554300|0.561100|0.74|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4022.430000|3994.260000|4022.430000|1.03|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4023.810000|3989.000000|4023.440000|1.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=0.004509, depth_time=2026-10-23T03:15:08+00:00, book20_bid_proxy_usdt=35713, book20_ask_proxy_usdt=33652, funding_indicative=0.000089, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.31%, turnover=9388533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=3.544400, depth_time=2026-10-23T03:15:12+00:00, book20_bid_proxy_usdt=26143, book20_ask_proxy_usdt=24658, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=11044930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=0.061050, depth_time=2026-10-23T03:15:09+00:00, book20_bid_proxy_usdt=68875, book20_ask_proxy_usdt=63847, funding_indicative=-0.000481, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=8132327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=54.790000, depth_time=2026-10-23T03:15:17+00:00, book20_bid_proxy_usdt=35279238, book20_ask_proxy_usdt=24590170, funding_indicative=0.000084, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=370137572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=0.053500, depth_time=2026-10-23T03:15:15+00:00, book20_bid_proxy_usdt=554957, book20_ask_proxy_usdt=671488, funding_indicative=0.000029, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=11901287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=0.567500, depth_time=2026-10-23T03:15:20+00:00, book20_bid_proxy_usdt=349367, book20_ask_proxy_usdt=383526, funding_indicative=-0.000003, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=23327196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=4037.000000, depth_time=2026-10-23T03:15:25+00:00, book20_bid_proxy_usdt=68112, book20_ask_proxy_usdt=275293, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=286852581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T03:15:02+00:00, last15m_closed_end=2026-10-23T03:15+00:00, prior8high=4039.110000, depth_time=2026-10-23T03:15:22+00:00, book20_bid_proxy_usdt=155983, book20_ask_proxy_usdt=994596, funding_indicative=0.000090, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=763064739. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
