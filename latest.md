# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T18:15:20Z**
- feed_generated_utc: 2026-10-30T18:15:22+00:00
- source_sha256: `4bea010bdc4cf4ac15f9e49e2efb4ad6cf2a67d546822730da05d1a90bac7b7c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T18:15+00:00, close=77098.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T18:00+00:00, close=77152, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.045290|-4.61|-61.72|-3.99|24735046|2.21|
|EVAA_USDT|1.227200|-4.28|133.79|-3.66|6614575|0.81|
|LIT_USDT|2.741200|-2.93|-17.53|-2.31|12444571|0.36|
|PUMPFUN_USDT|0.004001|-2.58|-12.31|-1.96|25704748|2.50|
|HYPE_USDT|90.672000|-1.81|15.64|-1.19|212377126|0.11|
|ETHFI_USDT|0.590800|-1.63|-9.49|-1.01|6383311|1.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ETHFI_USDT|0.590800|0.591300|0.590900|0.47|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.227200|1.233800|1.227400|0.91|N|Y/N|N/N|Y|N|
|HYPE_USDT|90.672000|90.546000|90.672000|0.61|N|Y/N|N/N|Y|N|
|LIT_USDT|2.741200|2.725000|2.741200|0.26|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004001|0.004001|0.004001|0.43|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045290|0.045730|0.045380|1.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ETHFI_USDT: quote_utc=2026-10-30T18:15:00+00:00, last15m_closed_end=2026-10-30T18:15+00:00, prior8high=0.603200, depth_time=2026-10-30T18:15:17+00:00, book20_bid_proxy_usdt=278842, book20_ask_proxy_usdt=183584, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=6383311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T18:15:00+00:00, last15m_closed_end=2026-10-30T18:15+00:00, prior8high=1.335900, depth_time=2026-10-30T18:15:10+00:00, book20_bid_proxy_usdt=9001, book20_ask_proxy_usdt=4615, funding_indicative=0.000218, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.28%, turnover=6614575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T18:15:00+00:00, last15m_closed_end=2026-10-30T18:15+00:00, prior8high=92.513000, depth_time=2026-10-30T18:15:17+00:00, book20_bid_proxy_usdt=51969, book20_ask_proxy_usdt=50394, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=212377126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T18:15:00+00:00, last15m_closed_end=2026-10-30T18:15+00:00, prior8high=2.835500, depth_time=2026-10-30T18:15:12+00:00, book20_bid_proxy_usdt=16573, book20_ask_proxy_usdt=34127, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=12444571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T18:15:00+00:00, last15m_closed_end=2026-10-30T18:15+00:00, prior8high=0.004120, depth_time=2026-10-30T18:15:14+00:00, book20_bid_proxy_usdt=627306, book20_ask_proxy_usdt=922906, funding_indicative=0.000007, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=25704748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T18:15:00+00:00, last15m_closed_end=2026-10-30T18:15+00:00, prior8high=0.049120, depth_time=2026-10-30T18:15:07+00:00, book20_bid_proxy_usdt=18002, book20_ask_proxy_usdt=21716, funding_indicative=0.000054, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.61%, turnover=24735046. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
