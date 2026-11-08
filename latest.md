# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T06:00:19Z**
- feed_generated_utc: 2026-11-08T06:00:20+00:00
- source_sha256: `cd3fe1a0b04a0a9bb4bf4ff4718c2b1791410874291f0579c79339f1db2eab25`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T06:00+00:00, close=75800, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T06:00+00:00, close=75800, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001940|-4.74|65.23|-4.80|26632611|0.52|
|ENA_USDT|0.154750|-2.16|-20.23|-2.22|28564173|0.65|
|TIA_USDT|0.432600|-2.03|-11.73|-2.09|7441778|2.31|
|QNT_USDT|195.400000|-1.73|-2.81|-1.79|46345065|1.54|
|WLD_USDT|0.330600|-1.48|-18.24|-1.54|24024596|3.02|
|ONDO_USDT|0.358900|-1.15|-12.97|-1.21|8866668|2.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.154750|0.153230|0.154750|1.00|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358900|0.357400|0.358900|0.43|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001940|0.001804|0.001940|1.45|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.400000|193.770000|195.400000|0.55|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.432600|0.432300|0.432500|1.47|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330600|0.329900|0.330600|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T05:59:59+00:00, last15m_closed_end=2026-11-08T06:00+00:00, prior8high=0.154970, depth_time=2026-11-08T06:00:09+00:00, book20_bid_proxy_usdt=227323, book20_ask_proxy_usdt=244915, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=28564173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T05:59:59+00:00, last15m_closed_end=2026-11-08T06:00+00:00, prior8high=0.361500, depth_time=2026-11-08T06:00:18+00:00, book20_bid_proxy_usdt=1450027, book20_ask_proxy_usdt=1802792, funding_indicative=-0.000003, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=8866668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T05:59:59+00:00, last15m_closed_end=2026-11-08T06:00+00:00, prior8high=0.001977, depth_time=2026-11-08T06:00:06+00:00, book20_bid_proxy_usdt=11402, book20_ask_proxy_usdt=20552, funding_indicative=-0.000032, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.74%, turnover=26632611. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T05:59:59+00:00, last15m_closed_end=2026-11-08T06:00+00:00, prior8high=196.790000, depth_time=2026-11-08T06:00:13+00:00, book20_bid_proxy_usdt=154229, book20_ask_proxy_usdt=78463, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=46345065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T05:59:59+00:00, last15m_closed_end=2026-11-08T06:00+00:00, prior8high=0.438300, depth_time=2026-11-08T06:00:11+00:00, book20_bid_proxy_usdt=370634, book20_ask_proxy_usdt=302342, funding_indicative=0.000016, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=7441778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T05:59:59+00:00, last15m_closed_end=2026-11-08T06:00+00:00, prior8high=0.332600, depth_time=2026-11-08T06:00:16+00:00, book20_bid_proxy_usdt=3601132, book20_ask_proxy_usdt=3143154, funding_indicative=-0.000163, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=24024596. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
