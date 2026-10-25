# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T12:15:33Z**
- feed_generated_utc: 2026-10-25T12:15:36+00:00
- source_sha256: `a734723da5820de82fdda1f104b961fc7e37fddf49b01f545090096efe9bd56a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T12:15+00:00, close=80434, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.033580|-27.07|163.16|-27.91|27060767|5.95|
|BTW_USDT|1.658100|-4.77|-26.93|-5.61|12320911|1.21|
|STRK_USDT|0.045800|-1.99|-30.76|-2.83|10244509|2.18|
|DOT_USDT|1.024800|-1.37|-8.28|-2.21|12463025|0.98|
|PENGU_USDT|0.007371|-0.96|-1.10|-1.80|5869377|1.36|
|APT_USDT|0.695600|-0.89|-12.77|-1.73|6148907|1.44|
|SUI_USDT|0.917100|-0.85|-6.58|-1.69|69367247|1.09|
|SEI_USDT|0.052570|-0.58|-15.22|-1.42|7542609|1.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.695600|0.689400|0.695600|1.22|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.658100|1.610600|1.658100|10.13|N|N/Y|Y/Y|Y|N|
|DOT_USDT|1.024800|1.013200|1.024800|1.42|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033580|0.033770|0.033580|1.25|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007371|0.007333|0.007371|0.42|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052570|0.052220|0.052570|0.34|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045800|0.044870|0.045820|1.89|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.917100|0.907500|0.917100|2.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=0.698100, depth_time=2026-10-25T12:15:24+00:00, book20_bid_proxy_usdt=168499, book20_ask_proxy_usdt=162191, funding_indicative=-0.000123, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=6148907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=1.699100, depth_time=2026-10-25T12:15:16+00:00, book20_bid_proxy_usdt=7628, book20_ask_proxy_usdt=15784, funding_indicative=-0.014705, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.77%, turnover=12320911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=1.026100, depth_time=2026-10-25T12:15:21+00:00, book20_bid_proxy_usdt=555555, book20_ask_proxy_usdt=293399, funding_indicative=-0.000037, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=12463025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=0.036110, depth_time=2026-10-25T12:15:09+00:00, book20_bid_proxy_usdt=134615, book20_ask_proxy_usdt=72252, funding_indicative=-0.000089, next_funding_utc=2026-10-25T13:00:00+00:00, funding_cycle_h=1, 24h_change=-27.07%, turnover=27060767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=0.007422, depth_time=2026-10-25T12:15:24+00:00, book20_bid_proxy_usdt=318418, book20_ask_proxy_usdt=175602, funding_indicative=-0.000072, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=5869377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=0.052880, depth_time=2026-10-25T12:15:31+00:00, book20_bid_proxy_usdt=254965, book20_ask_proxy_usdt=322516, funding_indicative=-0.000092, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.58%, turnover=7542609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=0.046180, depth_time=2026-10-25T12:15:19+00:00, book20_bid_proxy_usdt=989167, book20_ask_proxy_usdt=761374, funding_indicative=0.000020, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=10244509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T12:15:02+00:00, last15m_closed_end=2026-10-25T12:15+00:00, prior8high=0.920400, depth_time=2026-10-25T12:15:29+00:00, book20_bid_proxy_usdt=1433813, book20_ask_proxy_usdt=1559259, funding_indicative=-0.000038, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=69367247. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
