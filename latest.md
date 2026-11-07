# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T21:15:20Z**
- feed_generated_utc: 2026-11-07T21:15:21+00:00
- source_sha256: `576b98a8d4f3d706443fb4c287880412133e1ce01d441e8bea28bb09f650f5e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T21:15+00:00, close=75586.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T21:00+00:00, close=75657.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AAVE_USDT|129.300000|-2.21|-4.58|-2.03|8883728|0.77|
|UAI_USDT|0.122000|-1.92|-60.73|-1.74|11171778|8.19|
|WLD_USDT|0.329600|-1.78|-18.49|-1.60|25690911|3.03|
|ZEC_USDT|1237.820000|-1.58|-3.63|-1.40|1815559233|0.08|
|TIA_USDT|0.435800|-1.31|-11.07|-1.13|6478091|2.29|
|PEPE_USDT|0.000005|-1.22|-2.90|-1.04|44306007|0.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.300000|129.490000|129.300000|7.24|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.36|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.435800|0.434600|0.435800|2.74|N|Y/N|N/N|Y|N|
|UAI_USDT|0.122000|0.121100|0.122000|0.40|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329600|0.327700|0.329400|2.70|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1237.820000|1240.790000|1237.840000|2.37|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T21:15:01+00:00, last15m_closed_end=2026-11-07T21:15+00:00, prior8high=132.080000, depth_time=2026-11-07T21:15:07+00:00, book20_bid_proxy_usdt=376694, book20_ask_proxy_usdt=413756, funding_indicative=0.000041, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=8883728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T21:15:01+00:00, last15m_closed_end=2026-11-07T21:15+00:00, prior8high=0.000005, depth_time=2026-11-07T21:15:19+00:00, book20_bid_proxy_usdt=43790, book20_ask_proxy_usdt=33678, funding_indicative=0.000048, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=44306007. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-07T21:15:01+00:00, last15m_closed_end=2026-11-07T21:15+00:00, prior8high=0.446800, depth_time=2026-11-07T21:15:16+00:00, book20_bid_proxy_usdt=266031, book20_ask_proxy_usdt=350258, funding_indicative=0.000012, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6478091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T21:15:01+00:00, last15m_closed_end=2026-11-07T21:15+00:00, prior8high=0.124500, depth_time=2026-11-07T21:15:08+00:00, book20_bid_proxy_usdt=193268, book20_ask_proxy_usdt=155566, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=11171778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T21:15:01+00:00, last15m_closed_end=2026-11-07T21:15+00:00, prior8high=0.336500, depth_time=2026-11-07T21:15:11+00:00, book20_bid_proxy_usdt=3260755, book20_ask_proxy_usdt=3479635, funding_indicative=-0.000210, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=25690911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T21:15:01+00:00, last15m_closed_end=2026-11-07T21:15+00:00, prior8high=1270.260000, depth_time=2026-11-07T21:15:15+00:00, book20_bid_proxy_usdt=207511, book20_ask_proxy_usdt=1352456, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=1815559233. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
