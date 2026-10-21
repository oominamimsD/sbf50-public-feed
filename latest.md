# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T07:45:20Z**
- feed_generated_utc: 2026-10-21T07:45:23+00:00
- source_sha256: `15545e9aa0195c835300acb6efa1650178f7d94af278e7c9157f81d2f29813b3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T07:45+00:00, close=83127.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T07:00+00:00, close=82752, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.042954|-33.53|165.52|-34.18|7151581|5.33|
|BAT_USDT|0.188240|-12.75|6.12|-13.40|11041970|0.53|
|BR_USDT|0.576820|-11.34|33.21|-11.99|30377953|1.04|
|XMR_USDT|584.890000|-5.69|10.79|-6.34|21732212|0.17|
|PHA_USDT|0.056760|-1.83|3.14|-2.48|5915311|1.76|
|SILVER_USDT|57.470000|-0.82|-3.23|-1.47|222183345|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.042954|0.038698|0.042954|3.76|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.188240|0.181950|0.188360|1.56|N|Y/Y|Y/N|N|N|
|BR_USDT|0.576820|0.577040|0.576820|0.56|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056760|0.056090|0.056760|1.21|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.470000|57.210000|57.470000|0.59|N|Y/Y|Y/N|N|N|
|XMR_USDT|584.890000|576.030000|584.890000|0.53|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T07:45:01+00:00, last15m_closed_end=2026-10-21T07:45+00:00, prior8high=0.062194, depth_time=2026-10-21T07:45:07+00:00, book20_bid_proxy_usdt=6219, book20_ask_proxy_usdt=5730, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-33.53%, turnover=7151581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T07:45:01+00:00, last15m_closed_end=2026-10-21T07:45+00:00, prior8high=0.188580, depth_time=2026-10-21T07:45:10+00:00, book20_bid_proxy_usdt=29927, book20_ask_proxy_usdt=17335, funding_indicative=-0.000132, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-12.75%, turnover=11041970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T07:45:01+00:00, last15m_closed_end=2026-10-21T07:45+00:00, prior8high=0.595790, depth_time=2026-10-21T07:45:12+00:00, book20_bid_proxy_usdt=4842, book20_ask_proxy_usdt=3648, funding_indicative=0.000050, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.34%, turnover=30377953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T07:45:01+00:00, last15m_closed_end=2026-10-21T07:45+00:00, prior8high=0.057160, depth_time=2026-10-21T07:45:17+00:00, book20_bid_proxy_usdt=99042, book20_ask_proxy_usdt=63873, funding_indicative=-0.000024, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=5915311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T07:45:01+00:00, last15m_closed_end=2026-10-21T07:45+00:00, prior8high=57.780000, depth_time=2026-10-21T07:45:19+00:00, book20_bid_proxy_usdt=38291152, book20_ask_proxy_usdt=36024187, funding_indicative=0.000026, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=222183345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T07:45:01+00:00, last15m_closed_end=2026-10-21T07:45+00:00, prior8high=588.220000, depth_time=2026-10-21T07:45:14+00:00, book20_bid_proxy_usdt=12042, book20_ask_proxy_usdt=15274, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.69%, turnover=21732212. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
