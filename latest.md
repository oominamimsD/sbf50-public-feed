# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T02:00:15Z**
- feed_generated_utc: 2026-10-19T02:00:16+00:00
- source_sha256: `9a43307fb2084a6143ac5bff9cf169f3541ff53c8462fa5edac3db2c5fc02495`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T02:00+00:00, close=82415, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T02:00+00:00, close=82415, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.108725|-10.86|283.88|-12.43|9834365|5.99|
|AGT_USDT|0.062820|-6.97|255.21|-8.54|9830108|6.84|
|HBAR_USDT|0.084010|-2.06|-10.41|-3.63|51457696|1.19|
|ICNT_USDT|0.179400|0.00|69.24|-1.57|7775004|5.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062820|0.061150|0.062798|0.70|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084010|0.084150|0.084010|2.61|Y|Y/Y|N/Y|N|N|
|ICNT_USDT|0.179400|0.175900|0.179400|1.18|N|Y/Y|N/N|N|N|
|Q_USDT|0.108725|0.107553|0.108719|1.79|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T01:59:59+00:00, last15m_closed_end=2026-10-19T02:00+00:00, prior8high=0.067881, depth_time=2026-10-19T02:00:09+00:00, book20_bid_proxy_usdt=2698, book20_ask_proxy_usdt=3339, funding_indicative=0.000166, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=9830108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T01:59:59+00:00, last15m_closed_end=2026-10-19T02:00+00:00, prior8high=0.085440, depth_time=2026-10-19T02:00:09+00:00, book20_bid_proxy_usdt=431363, book20_ask_proxy_usdt=977836, funding_indicative=-0.000026, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=51457696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T01:59:59+00:00, last15m_closed_end=2026-10-19T02:00+00:00, prior8high=0.192000, depth_time=2026-10-19T02:00:12+00:00, book20_bid_proxy_usdt=188129, book20_ask_proxy_usdt=70478, funding_indicative=-0.000006, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.00%, turnover=7775004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T01:59:59+00:00, last15m_closed_end=2026-10-19T02:00+00:00, prior8high=0.118711, depth_time=2026-10-19T02:00:07+00:00, book20_bid_proxy_usdt=9500, book20_ask_proxy_usdt=11118, funding_indicative=0.000053, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.86%, turnover=9834365. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
