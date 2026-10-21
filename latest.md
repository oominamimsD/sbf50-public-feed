# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T03:00:21Z**
- feed_generated_utc: 2026-10-21T03:00:23+00:00
- source_sha256: `e18cdae7b4e468dd1e25f111227e45e434b4e2bf47c9d33177454968b6ab9790`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T03:00+00:00, close=82770, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T03:00+00:00, close=82770, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186560|-14.57|5.17|-14.79|10385489|2.15|
|Q_USDT|0.116992|-9.33|184.46|-9.55|5030886|0.09|
|XMR_USDT|576.400000|-7.11|9.18|-7.33|20094857|0.87|
|TIA_USDT|0.614600|-4.10|6.46|-4.32|48424173|1.63|
|AGT_USDT|0.061890|-2.80|282.58|-3.02|6887188|1.94|
|SILVER_USDT|57.590000|-1.16|-3.03|-1.38|224147014|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061890|0.061689|0.061890|1.21|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186560|0.186500|0.186560|0.83|N|Y/Y|N/N|N|N|
|Q_USDT|0.116992|0.117713|0.116992|2.44|Y|Y/Y|N/N|N|N|
|SILVER_USDT|57.590000|57.520000|57.590000|1.71|N|Y/Y|N/N|N|N|
|TIA_USDT|0.614600|0.605800|0.614600|0.14|N|Y/Y|Y/Y|N|N|
|XMR_USDT|576.400000|572.610000|576.400000|0.44|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T03:00:01+00:00, last15m_closed_end=2026-10-21T03:00+00:00, prior8high=0.067294, depth_time=2026-10-21T03:00:17+00:00, book20_bid_proxy_usdt=5056, book20_ask_proxy_usdt=10967, funding_indicative=0.000051, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.80%, turnover=6887188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T03:00:01+00:00, last15m_closed_end=2026-10-21T03:00+00:00, prior8high=0.192480, depth_time=2026-10-21T03:00:08+00:00, book20_bid_proxy_usdt=16661, book20_ask_proxy_usdt=35265, funding_indicative=0.000051, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.57%, turnover=10385489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T03:00:01+00:00, last15m_closed_end=2026-10-21T03:00+00:00, prior8high=0.123452, depth_time=2026-10-21T03:00:09+00:00, book20_bid_proxy_usdt=21950, book20_ask_proxy_usdt=16603, funding_indicative=-0.000145, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.33%, turnover=5030886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T03:00:01+00:00, last15m_closed_end=2026-10-21T03:00+00:00, prior8high=58.060000, depth_time=2026-10-21T03:00:19+00:00, book20_bid_proxy_usdt=41072389, book20_ask_proxy_usdt=39640520, funding_indicative=0.000017, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=224147014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T03:00:01+00:00, last15m_closed_end=2026-10-21T03:00+00:00, prior8high=0.619700, depth_time=2026-10-21T03:00:15+00:00, book20_bid_proxy_usdt=429793, book20_ask_proxy_usdt=251760, funding_indicative=-0.000042, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=48424173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T03:00:01+00:00, last15m_closed_end=2026-10-21T03:00+00:00, prior8high=601.630000, depth_time=2026-10-21T03:00:11+00:00, book20_bid_proxy_usdt=15372, book20_ask_proxy_usdt=12292, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.11%, turnover=20094857. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
