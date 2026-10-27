# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T13:45:38Z**
- feed_generated_utc: 2026-10-27T13:45:41+00:00
- source_sha256: `8e906755ed013cd55813cbfc754b70decacc0e0d7f90703979c6262d245698c6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T13:45+00:00, close=80202.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T13:00+00:00, close=80337, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.094080|-36.90|30.63|-36.66|10998805|7.44|
|IRYS_USDT|0.025010|-9.31|103.66|-9.07|7075088|4.00|
|QNT_USDT|198.260000|-5.71|1.30|-5.47|106732578|1.01|
|AAVE_USDT|131.950000|-3.49|-10.37|-3.25|28769453|0.76|
|DOT_USDT|0.990100|-3.17|-13.66|-2.93|11283308|1.01|
|WLD_USDT|0.431800|-2.96|-14.71|-2.72|72089560|2.31|
|FILECOIN_USDT|0.893700|-2.93|-11.68|-2.69|6746611|1.12|
|AVAX_USDT|8.806000|-2.12|-7.90|-1.88|24848826|1.14|
|TIA_USDT|0.525900|-1.82|-13.57|-1.58|17868800|1.90|
|ICP_USDT|2.584000|-1.74|-9.42|-1.50|5356824|3.87|
|HBAR_USDT|0.076150|-1.56|-6.98|-1.32|10561279|1.31|
|LINK_USDT|11.366000|-1.40|-4.83|-1.16|136116207|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.950000|130.520000|131.950000|1.09|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.806000|8.732000|8.806000|12.50|N|N/Y|Y/Y|Y|N|
|BULLA_USDT|0.094080|0.060490|0.094120|1.15|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.990100|0.982200|0.990100|3.07|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.893700|0.887200|0.893700|0.76|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076150|0.075590|0.076160|1.47|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.584000|2.565000|2.584000|1.31|N|N/Y|Y/Y|Y|N|
|IRYS_USDT|0.025010|0.024590|0.025010|1.28|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.366000|11.290000|11.366000|1.78|N|N/Y|Y/Y|Y|N|
|QNT_USDT|198.260000|197.350000|198.160000|1.20|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.525900|0.520600|0.525900|1.53|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.431800|0.428900|0.431800|4.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=133.100000, depth_time=2026-10-27T13:45:16+00:00, book20_bid_proxy_usdt=397661, book20_ask_proxy_usdt=337961, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=28769453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=8.864000, depth_time=2026-10-27T13:45:27+00:00, book20_bid_proxy_usdt=1071756, book20_ask_proxy_usdt=1838713, funding_indicative=0.000052, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=24848826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.091160, depth_time=2026-10-27T13:45:09+00:00, book20_bid_proxy_usdt=3908, book20_ask_proxy_usdt=7634, funding_indicative=-0.005126, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-36.90%, turnover=10998805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.996900, depth_time=2026-10-27T13:45:20+00:00, book20_bid_proxy_usdt=481234, book20_ask_proxy_usdt=340314, funding_indicative=-0.000194, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=11283308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.902000, depth_time=2026-10-27T13:45:21+00:00, book20_bid_proxy_usdt=965564, book20_ask_proxy_usdt=1380846, funding_indicative=0.000057, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=6746611. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.076600, depth_time=2026-10-27T13:45:35+00:00, book20_bid_proxy_usdt=791423, book20_ask_proxy_usdt=1113289, funding_indicative=0.000083, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=10561279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=2.608000, depth_time=2026-10-27T13:45:32+00:00, book20_bid_proxy_usdt=1145093, book20_ask_proxy_usdt=1006903, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=5356824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.025210, depth_time=2026-10-27T13:45:11+00:00, book20_bid_proxy_usdt=116146, book20_ask_proxy_usdt=127783, funding_indicative=-0.000243, next_funding_utc=2026-10-27T14:00:00+00:00, funding_cycle_h=1, 24h_change=-9.31%, turnover=7075088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=11.453000, depth_time=2026-10-27T13:45:37+00:00, book20_bid_proxy_usdt=480622, book20_ask_proxy_usdt=426060, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=136116207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=203.620000, depth_time=2026-10-27T13:45:14+00:00, book20_bid_proxy_usdt=90384, book20_ask_proxy_usdt=98797, funding_indicative=-0.000247, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.71%, turnover=106732578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.531400, depth_time=2026-10-27T13:45:30+00:00, book20_bid_proxy_usdt=383657, book20_ask_proxy_usdt=467541, funding_indicative=0.000019, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=17868800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T13:45:01+00:00, last15m_closed_end=2026-10-27T13:45+00:00, prior8high=0.438400, depth_time=2026-10-27T13:45:22+00:00, book20_bid_proxy_usdt=2641020, book20_ask_proxy_usdt=4278795, funding_indicative=-0.000046, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=72089560. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
