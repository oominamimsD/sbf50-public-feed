# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T03:30:19Z**
- feed_generated_utc: 2026-11-08T03:30:21+00:00
- source_sha256: `80cb83ea9d9add4f1fb0fbe0bc6d72e484b88ab6b5cde0d1c2b61dde0030a6d3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T03:30+00:00, close=75841.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T03:00+00:00, close=75758, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.137290|-11.86|-40.86|-12.01|9462133|6.59|
|ONE_USDT|0.001875|-7.92|59.70|-8.07|26592256|0.53|
|QNT_USDT|193.970000|-2.45|-3.52|-2.60|43660296|0.52|
|ENA_USDT|0.154330|-2.43|-20.45|-2.58|28196204|0.65|
|WLD_USDT|0.330600|-1.48|-18.24|-1.63|24972914|3.02|
|TIA_USDT|0.436200|-1.22|-10.99|-1.37|7240130|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.137290|0.141520|0.137290|22.06|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.154330|0.153550|0.154330|1.06|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001875|0.001906|0.001875|1.27|N|Y/Y|N/N|Y|N|
|QNT_USDT|193.970000|193.120000|193.970000|0.47|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.436200|0.434500|0.436200|1.09|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.330600|0.329000|0.330600|0.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T03:29:59+00:00, last15m_closed_end=2026-11-08T03:30+00:00, prior8high=0.157480, depth_time=2026-11-08T03:30:07+00:00, book20_bid_proxy_usdt=6342, book20_ask_proxy_usdt=2947, funding_indicative=0.000286, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.86%, turnover=9462133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T03:29:59+00:00, last15m_closed_end=2026-11-08T03:30+00:00, prior8high=0.157380, depth_time=2026-11-08T03:30:13+00:00, book20_bid_proxy_usdt=229777, book20_ask_proxy_usdt=195395, funding_indicative=-0.000038, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=28196204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T03:29:59+00:00, last15m_closed_end=2026-11-08T03:30+00:00, prior8high=0.002086, depth_time=2026-11-08T03:30:08+00:00, book20_bid_proxy_usdt=12409, book20_ask_proxy_usdt=14136, funding_indicative=-0.000050, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.92%, turnover=26592256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T03:29:59+00:00, last15m_closed_end=2026-11-08T03:30+00:00, prior8high=195.340000, depth_time=2026-11-08T03:30:09+00:00, book20_bid_proxy_usdt=93059, book20_ask_proxy_usdt=68731, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=43660296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T03:29:59+00:00, last15m_closed_end=2026-11-08T03:30+00:00, prior8high=0.438500, depth_time=2026-11-08T03:30:12+00:00, book20_bid_proxy_usdt=381762, book20_ask_proxy_usdt=318384, funding_indicative=0.000033, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=7240130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T03:29:59+00:00, last15m_closed_end=2026-11-08T03:30+00:00, prior8high=0.332300, depth_time=2026-11-08T03:30:15+00:00, book20_bid_proxy_usdt=3667072, book20_ask_proxy_usdt=3913453, funding_indicative=-0.000080, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=24972914. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
