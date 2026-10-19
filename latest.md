# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T00:45:17Z**
- feed_generated_utc: 2026-10-19T00:45:19+00:00
- source_sha256: `f0a4873d701d763fd84c39a7a09bb0029e0300ef5f1ed89456e4cf616675b1fd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T00:45+00:00, close=82385.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.109825|-9.96|287.77|-11.49|9981086|1.46|
|AGT_USDT|0.061541|-8.86|247.98|-10.39|10123587|1.14|
|STRK_USDT|0.060320|-2.01|-49.42|-3.54|16621483|3.32|
|SAND_USDT|0.058780|0.03|-11.52|-1.50|33962261|1.70|
|BTW_USDT|2.314600|0.39|37.59|-1.14|23510324|0.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061541|0.060544|0.061541|1.31|N|Y/Y|N/N|N|N|
|BTW_USDT|2.314600|2.338900|2.313700|1.18|N|N/N|N/N|N|N|
|Q_USDT|0.109825|0.109117|0.109825|0.84|N|Y/Y|N/N|N|N|
|SAND_USDT|0.058780|0.057420|0.058780|0.36|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060320|0.059380|0.060320|2.15|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T00:44:59+00:00, last15m_closed_end=2026-10-19T00:45+00:00, prior8high=0.068584, depth_time=2026-10-19T00:45:09+00:00, book20_bid_proxy_usdt=4359, book20_ask_proxy_usdt=4039, funding_indicative=0.000171, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.86%, turnover=10123587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T00:44:59+00:00, last15m_closed_end=2026-10-19T00:45+00:00, prior8high=2.489400, depth_time=2026-10-19T00:45:17+00:00, book20_bid_proxy_usdt=10422, book20_ask_proxy_usdt=10199, funding_indicative=-0.000463, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.39%, turnover=23510324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T00:44:59+00:00, last15m_closed_end=2026-10-19T00:45+00:00, prior8high=0.121020, depth_time=2026-10-19T00:45:07+00:00, book20_bid_proxy_usdt=7612, book20_ask_proxy_usdt=14569, funding_indicative=0.000107, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.96%, turnover=9981086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T00:44:59+00:00, last15m_closed_end=2026-10-19T00:45+00:00, prior8high=0.058910, depth_time=2026-10-19T00:45:14+00:00, book20_bid_proxy_usdt=610703, book20_ask_proxy_usdt=717274, funding_indicative=-0.003512, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.03%, turnover=33962261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T00:44:59+00:00, last15m_closed_end=2026-10-19T00:45+00:00, prior8high=0.060690, depth_time=2026-10-19T00:45:12+00:00, book20_bid_proxy_usdt=330950, book20_ask_proxy_usdt=255446, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=16621483. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
