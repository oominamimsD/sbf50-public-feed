# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T07:45:30Z**
- feed_generated_utc: 2026-10-20T07:45:33+00:00
- source_sha256: `c47d25f53d11587361e54fabb2c468082846118cf3ae3890038476f781e5eea0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T07:45+00:00, close=81528.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T07:00+00:00, close=81779.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.077016|-11.51|362.22|-11.03|11276067|2.99|
|CT_USDT|0.312230|-5.41|-8.73|-4.93|5490472|2.88|
|BTW_USDT|1.665500|-4.93|-5.14|-4.45|30709242|0.60|
|Q_USDT|0.119928|-4.80|289.49|-4.32|7791666|4.08|
|SAND_USDT|0.056700|-4.12|-8.68|-3.64|7656838|3.53|
|NEAR_USDT|4.782000|-2.48|-13.82|-2.00|169570628|2.09|
|ATOM_USDT|1.741000|-1.97|-4.75|-1.49|5426928|5.75|
|QNT_USDT|191.990000|-1.89|-15.93|-1.41|81972723|0.52|
|ARB_USDT|0.192400|-1.65|2.08|-1.17|94580233|0.52|
|TAO_USDT|263.910000|-1.63|-7.81|-1.15|56392290|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.077016|0.075754|0.077016|0.87|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192400|0.192880|0.192480|2.22|Y|N/N|N/N|Y|N|
|ATOM_USDT|1.741000|1.737000|1.740000|1.40|N|N/N|N/N|Y|N|
|BTW_USDT|1.665500|1.660000|1.665500|1.47|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.312230|0.301550|0.312230|0.34|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.782000|4.749000|4.782000|0.81|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.990000|191.100000|191.950000|0.38|N|Y/Y|N/Y|Y|N|
|Q_USDT|0.119928|0.110142|0.120122|0.67|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056700|0.056700|0.056700|1.93|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.910000|263.780000|263.910000|4.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=0.090417, depth_time=2026-10-20T07:45:07+00:00, book20_bid_proxy_usdt=14109, book20_ask_proxy_usdt=4099, funding_indicative=0.000277, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.51%, turnover=11276067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=0.200580, depth_time=2026-10-20T07:45:26+00:00, book20_bid_proxy_usdt=86862, book20_ask_proxy_usdt=129250, funding_indicative=-0.000084, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=94580233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T07:45:01+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=1.763000, depth_time=2026-10-20T07:45:22+00:00, book20_bid_proxy_usdt=1185625, book20_ask_proxy_usdt=1015941, funding_indicative=0.000100, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=5426928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=1.799100, depth_time=2026-10-20T07:45:12+00:00, book20_bid_proxy_usdt=12264, book20_ask_proxy_usdt=12281, funding_indicative=-0.004418, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=30709242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=0.313200, depth_time=2026-10-20T07:45:09+00:00, book20_bid_proxy_usdt=10749, book20_ask_proxy_usdt=14498, funding_indicative=-0.002400, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.41%, turnover=5490472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=4.811000, depth_time=2026-10-20T07:45:19+00:00, book20_bid_proxy_usdt=3899250, book20_ask_proxy_usdt=3087230, funding_indicative=-0.000018, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=169570628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=194.330000, depth_time=2026-10-20T07:45:23+00:00, book20_bid_proxy_usdt=105295, book20_ask_proxy_usdt=81919, funding_indicative=0.000023, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=81972723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=0.124516, depth_time=2026-10-20T07:45:15+00:00, book20_bid_proxy_usdt=13641, book20_ask_proxy_usdt=17065, funding_indicative=0.000003, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.80%, turnover=7791666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T07:45:01+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=0.057320, depth_time=2026-10-20T07:45:17+00:00, book20_bid_proxy_usdt=852751, book20_ask_proxy_usdt=801742, funding_indicative=-0.001419, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.12%, turnover=7656838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T07:45:00+00:00, last15m_closed_end=2026-10-20T07:45+00:00, prior8high=266.580000, depth_time=2026-10-20T07:45:29+00:00, book20_bid_proxy_usdt=90737, book20_ask_proxy_usdt=94755, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=56392290. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
