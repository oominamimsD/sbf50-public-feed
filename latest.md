# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T10:00:17Z**
- feed_generated_utc: 2026-10-28T10:00:20+00:00
- source_sha256: `7e58d81ec96b9e7de75180cfcfed77e353c76ef91d70df145ae4d36c72dec49c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T10:00+00:00, close=81515.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T10:00+00:00, close=81515.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.059240|-10.22|-51.74|-11.44|22845777|3.38|
|BULLA_USDT|0.064310|-6.93|-8.66|-8.15|10196677|1.56|
|AKE_USDT|0.020564|-2.65|-33.85|-3.87|6007651|2.92|
|DASH_USDT|54.060000|-0.01|8.24|-1.23|15063730|1.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020564|0.020071|0.020648|1.28|N|Y/Y|Y/Y|N|N|
|BULLA_USDT|0.064310|0.063520|0.064310|0.49|N|Y/Y|Y/Y|N|N|
|DASH_USDT|54.060000|53.960000|54.060000|5.09|N|Y/Y|N/N|N|N|
|Q_USDT|0.059240|0.056930|0.059260|0.51|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T10:00:01+00:00, last15m_closed_end=2026-10-28T10:00+00:00, prior8high=0.021005, depth_time=2026-10-28T10:00:13+00:00, book20_bid_proxy_usdt=10814, book20_ask_proxy_usdt=5161, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=6007651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T10:00:01+00:00, last15m_closed_end=2026-10-28T10:00+00:00, prior8high=0.070500, depth_time=2026-10-28T10:00:10+00:00, book20_bid_proxy_usdt=11435, book20_ask_proxy_usdt=8781, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.93%, turnover=10196677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T10:00:01+00:00, last15m_closed_end=2026-10-28T10:00+00:00, prior8high=54.730000, depth_time=2026-10-28T10:00:11+00:00, book20_bid_proxy_usdt=678127, book20_ask_proxy_usdt=526597, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.01%, turnover=15063730. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T10:00:00+00:00, last15m_closed_end=2026-10-28T10:00+00:00, prior8high=0.061020, depth_time=2026-10-28T10:00:08+00:00, book20_bid_proxy_usdt=17002, book20_ask_proxy_usdt=16226, funding_indicative=-0.000434, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=22845777. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
