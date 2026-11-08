# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T08:15:23Z**
- feed_generated_utc: 2026-11-08T08:15:24+00:00
- source_sha256: `b532f65f3b70f36231b76de3eb87fa3b1d4384df7c912df44fd998d1d0be20e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T08:15+00:00, close=75885.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.429400|-2.76|-12.38|-2.97|7396596|2.33|
|ENA_USDT|0.154240|-2.49|-20.49|-2.70|29212783|0.65|
|QNT_USDT|195.290000|-1.79|-2.86|-2.00|43773513|0.51|
|WLD_USDT|0.329800|-1.72|-18.44|-1.93|23508409|3.03|
|AAVE_USDT|130.550000|-1.27|-3.66|-1.48|10783508|0.77|
|LINK_USDT|10.720000|-1.14|-7.35|-1.35|66125531|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.550000|129.910000|130.550000|11.38|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.154240|0.153450|0.154240|0.74|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.720000|10.711000|10.721000|1.40|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.290000|194.160000|195.290000|0.54|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.429400|0.429800|0.429500|1.19|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329800|0.328600|0.329800|1.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T08:14:59+00:00, last15m_closed_end=2026-11-08T08:15+00:00, prior8high=131.110000, depth_time=2026-11-08T08:15:16+00:00, book20_bid_proxy_usdt=737144, book20_ask_proxy_usdt=323866, funding_indicative=0.000024, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=10783508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T08:14:59+00:00, last15m_closed_end=2026-11-08T08:15+00:00, prior8high=0.155160, depth_time=2026-11-08T08:15:10+00:00, book20_bid_proxy_usdt=427750, book20_ask_proxy_usdt=292655, funding_indicative=0.000028, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=29212783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T08:14:59+00:00, last15m_closed_end=2026-11-08T08:15+00:00, prior8high=10.755000, depth_time=2026-11-08T08:15:18+00:00, book20_bid_proxy_usdt=512468, book20_ask_proxy_usdt=514571, funding_indicative=0.000074, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=66125531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T08:14:59+00:00, last15m_closed_end=2026-11-08T08:15+00:00, prior8high=196.350000, depth_time=2026-11-08T08:15:13+00:00, book20_bid_proxy_usdt=63377, book20_ask_proxy_usdt=62080, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=43773513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T08:14:59+00:00, last15m_closed_end=2026-11-08T08:15+00:00, prior8high=0.434500, depth_time=2026-11-08T08:15:07+00:00, book20_bid_proxy_usdt=288686, book20_ask_proxy_usdt=303872, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=7396596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T08:14:59+00:00, last15m_closed_end=2026-11-08T08:15+00:00, prior8high=0.331200, depth_time=2026-11-08T08:15:16+00:00, book20_bid_proxy_usdt=4246019, book20_ask_proxy_usdt=3502856, funding_indicative=-0.000166, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=23508409. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
