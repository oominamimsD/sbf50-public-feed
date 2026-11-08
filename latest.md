# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T06:30:26Z**
- feed_generated_utc: 2026-11-08T06:30:27+00:00
- source_sha256: `b7554f210114f11b1e43a951c6a6fb46c13b494ecdf70d6c391939edbeec8072`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T06:30+00:00, close=75819.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T06:00+00:00, close=75800, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005094|-14.85|-54.26|-14.97|40529701|3.93|
|ONE_USDT|0.001968|-3.36|67.61|-3.48|26183427|0.51|
|ENA_USDT|0.154660|-2.22|-20.28|-2.34|28421149|0.65|
|TIA_USDT|0.433100|-1.92|-11.63|-2.04|7547230|2.31|
|WLD_USDT|0.329800|-1.72|-18.44|-1.84|23468520|3.03|
|QNT_USDT|195.540000|-1.66|-2.74|-1.78|46080660|0.51|
|ONDO_USDT|0.358600|-1.23|-13.04|-1.35|8626570|2.79|
|AAVE_USDT|130.620000|-1.21|-3.60|-1.33|10802887|0.77|
|LINK_USDT|10.735000|-1.00|-7.22|-1.12|67000464|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.620000|130.350000|130.620000|8.49|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.005094|0.005077|0.005094|0.34|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.154660|0.153230|0.154660|0.19|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.735000|10.736000|10.735000|0.82|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358600|0.357400|0.358600|0.29|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001968|0.001804|0.001968|0.77|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.540000|193.770000|195.540000|0.49|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.433100|0.431800|0.433100|2.10|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.329800|0.329900|0.329800|0.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=131.600000, depth_time=2026-11-08T06:30:23+00:00, book20_bid_proxy_usdt=445901, book20_ask_proxy_usdt=627460, funding_indicative=0.000019, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=10802887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=0.005418, depth_time=2026-11-08T06:30:07+00:00, book20_bid_proxy_usdt=49601, book20_ask_proxy_usdt=90502, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.85%, turnover=40529701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=0.155060, depth_time=2026-11-08T06:30:11+00:00, book20_bid_proxy_usdt=480542, book20_ask_proxy_usdt=210703, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=28421149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=10.783000, depth_time=2026-11-08T06:30:21+00:00, book20_bid_proxy_usdt=908986, book20_ask_proxy_usdt=504699, funding_indicative=0.000074, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=67000464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=0.360500, depth_time=2026-11-08T06:30:19+00:00, book20_bid_proxy_usdt=1168799, book20_ask_proxy_usdt=2067214, funding_indicative=-0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=8626570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=0.002018, depth_time=2026-11-08T06:30:09+00:00, book20_bid_proxy_usdt=15520, book20_ask_proxy_usdt=12158, funding_indicative=-0.000139, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=26183427. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=196.790000, depth_time=2026-11-08T06:30:18+00:00, book20_bid_proxy_usdt=49083, book20_ask_proxy_usdt=54441, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=46080660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=0.437200, depth_time=2026-11-08T06:30:13+00:00, book20_bid_proxy_usdt=333310, book20_ask_proxy_usdt=264940, funding_indicative=0.000030, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=7547230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T06:29:59+00:00, last15m_closed_end=2026-11-08T06:30+00:00, prior8high=0.332600, depth_time=2026-11-08T06:30:13+00:00, book20_bid_proxy_usdt=4246619, book20_ask_proxy_usdt=3751936, funding_indicative=-0.000165, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=23468520. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
