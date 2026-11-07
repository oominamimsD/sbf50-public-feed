# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T16:00:21Z**
- feed_generated_utc: 2026-11-07T16:00:22+00:00
- source_sha256: `e890590cc52ba7918d636c2719f8a4dcc79e5b63267d1c206a4ef618209f0883`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.003649|-2.48|-12.74|-2.48|13787939|2.74|
|UAI_USDT|0.124400|-1.89|-59.96|-1.89|21515860|8.04|
|LIT_USDT|3.186200|-1.67|9.16|-1.67|11066389|0.31|
|ENA_USDT|0.158180|-1.29|-18.46|-1.29|28316687|2.53|
|DASH_USDT|45.960000|-1.24|-5.47|-1.24|6503487|2.17|
|ZEC_USDT|1257.790000|-1.08|-2.08|-1.08|1983750551|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|45.960000|45.950000|45.960000|4.52|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.158180|0.157750|0.158180|1.81|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.186200|3.185300|3.186200|3.50|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003649|0.003632|0.003649|1.02|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.124400|0.119700|0.124400|1.50|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1257.790000|1251.240000|1257.790000|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-07T16:00:01+00:00, last15m_closed_end=2026-11-07T16:00+00:00, prior8high=46.700000, depth_time=2026-11-07T16:00:13+00:00, book20_bid_proxy_usdt=721990, book20_ask_proxy_usdt=788669, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=6503487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T16:00:01+00:00, last15m_closed_end=2026-11-07T16:00+00:00, prior8high=0.162680, depth_time=2026-11-07T16:00:14+00:00, book20_bid_proxy_usdt=142691, book20_ask_proxy_usdt=274670, funding_indicative=0.000050, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=28316687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T16:00:01+00:00, last15m_closed_end=2026-11-07T16:00+00:00, prior8high=3.266300, depth_time=2026-11-07T16:00:13+00:00, book20_bid_proxy_usdt=48455, book20_ask_proxy_usdt=29600, funding_indicative=0.000050, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=11066389. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T16:00:01+00:00, last15m_closed_end=2026-11-07T16:00+00:00, prior8high=0.003791, depth_time=2026-11-07T16:00:07+00:00, book20_bid_proxy_usdt=2553908, book20_ask_proxy_usdt=3106358, funding_indicative=-0.000007, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=13787939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T16:00:01+00:00, last15m_closed_end=2026-11-07T16:00+00:00, prior8high=0.128400, depth_time=2026-11-07T16:00:09+00:00, book20_bid_proxy_usdt=154792, book20_ask_proxy_usdt=172713, funding_indicative=-0.000105, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=21515860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T16:00:01+00:00, last15m_closed_end=2026-11-07T16:00+00:00, prior8high=1281.010000, depth_time=2026-11-07T16:00:20+00:00, book20_bid_proxy_usdt=437733, book20_ask_proxy_usdt=475610, funding_indicative=0.000186, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=1983750551. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
