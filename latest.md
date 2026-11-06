# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T07:45:20Z**
- feed_generated_utc: 2026-11-06T07:45:21+00:00
- source_sha256: `2e3a3c6ab9e42529466d8683f62d83846b10a58f46e038239796152229e58822`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T07:45+00:00, close=75679.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T07:00+00:00, close=75670, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.403000|-5.09|16.42|-4.65|5688489|4.16|
|XRP_USDT|1.181800|-5.04|-9.75|-4.60|467089810|0.85|
|BCH_USDT|265.470000|-4.89|-7.91|-4.45|7901583|4.89|
|XPL_USDT|0.057040|-2.62|-27.73|-2.18|12249520|1.75|
|QNT_USDT|188.200000|-1.88|-5.30|-1.44|37910895|2.12|
|HYPE_USDT|77.275000|-1.81|-17.73|-1.37|83702716|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|265.470000|265.120000|265.470000|22.98|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.403000|2.388000|2.403000|1.68|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.275000|77.281000|77.299000|3.56|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.200000|188.130000|188.200000|4.11|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057040|0.056460|0.057030|0.86|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.181800|1.180700|1.181800|2.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T07:45:02+00:00, last15m_closed_end=2026-11-06T07:45+00:00, prior8high=277.780000, depth_time=2026-11-06T07:45:12+00:00, book20_bid_proxy_usdt=38316, book20_ask_proxy_usdt=59559, funding_indicative=0.000044, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.89%, turnover=7901583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T07:45:02+00:00, last15m_closed_end=2026-11-06T07:45+00:00, prior8high=2.459000, depth_time=2026-11-06T07:45:07+00:00, book20_bid_proxy_usdt=163303, book20_ask_proxy_usdt=201092, funding_indicative=0.000175, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=5688489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T07:45:01+00:00, last15m_closed_end=2026-11-06T07:45+00:00, prior8high=77.912000, depth_time=2026-11-06T07:45:19+00:00, book20_bid_proxy_usdt=181029, book20_ask_proxy_usdt=40835, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=83702716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T07:45:02+00:00, last15m_closed_end=2026-11-06T07:45+00:00, prior8high=189.970000, depth_time=2026-11-06T07:45:17+00:00, book20_bid_proxy_usdt=86899, book20_ask_proxy_usdt=73871, funding_indicative=0.000005, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=37910895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T07:45:02+00:00, last15m_closed_end=2026-11-06T07:45+00:00, prior8high=0.057590, depth_time=2026-11-06T07:45:14+00:00, book20_bid_proxy_usdt=410822, book20_ask_proxy_usdt=396228, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=12249520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T07:45:01+00:00, last15m_closed_end=2026-11-06T07:45+00:00, prior8high=1.201600, depth_time=2026-11-06T07:45:10+00:00, book20_bid_proxy_usdt=3179693, book20_ask_proxy_usdt=3205091, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.04%, turnover=467089810. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
