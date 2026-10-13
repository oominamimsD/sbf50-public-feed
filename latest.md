# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T18:30:21Z**
- feed_generated_utc: 2026-10-13T18:30:23+00:00
- source_sha256: `39a965bbf723d4fa07a42aaa35936c5400e347b0de9cb8036f4f22b4e155e504`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T18:30+00:00, close=83039.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T18:00+00:00, close=83063.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.016204|-3.56|11.65|-3.14|10663105|8.02|
|RLC_USDT|0.891700|-3.41|8.77|-2.99|5882777|1.12|
|DOS_USDT|0.209000|-2.92|-3.01|-2.50|9515621|4.78|
|CT_USDT|0.361640|-2.72|-2.68|-2.30|5884638|1.94|
|STX_USDT|0.412600|-2.01|9.93|-1.59|18697370|2.42|
|STRK_USDT|0.085330|-1.84|63.49|-1.42|46847415|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.361640|0.366310|0.361640|0.59|N|N/N|N/N|N|N|
|DOS_USDT|0.209000|0.210800|0.209000|1.16|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.891700|0.877700|0.891700|1.93|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085330|0.082420|0.085330|0.61|N|Y/Y|Y/Y|N|N|
|STX_USDT|0.412600|0.414200|0.412600|1.67|Y|Y/N|N/N|N|N|
|W_USDT|0.016204|0.016124|0.016208|0.59|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T18:30:00+00:00, last15m_closed_end=2026-10-13T18:30+00:00, prior8high=0.383340, depth_time=2026-10-13T18:30:15+00:00, book20_bid_proxy_usdt=12322, book20_ask_proxy_usdt=9995, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=5884638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T18:30:00+00:00, last15m_closed_end=2026-10-13T18:30+00:00, prior8high=0.218600, depth_time=2026-10-13T18:30:12+00:00, book20_bid_proxy_usdt=98270, book20_ask_proxy_usdt=102314, funding_indicative=-0.000059, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=9515621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T18:30:00+00:00, last15m_closed_end=2026-10-13T18:30+00:00, prior8high=0.926400, depth_time=2026-10-13T18:30:09+00:00, book20_bid_proxy_usdt=57648, book20_ask_proxy_usdt=66092, funding_indicative=-0.000657, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=5882777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T18:30:00+00:00, last15m_closed_end=2026-10-13T18:30+00:00, prior8high=0.086110, depth_time=2026-10-13T18:30:20+00:00, book20_bid_proxy_usdt=217833, book20_ask_proxy_usdt=269490, funding_indicative=0.000029, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=46847415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STX_USDT: quote_utc=2026-10-13T18:30:00+00:00, last15m_closed_end=2026-10-13T18:30+00:00, prior8high=0.437700, depth_time=2026-10-13T18:30:17+00:00, book20_bid_proxy_usdt=256100, book20_ask_proxy_usdt=152747, funding_indicative=-0.000184, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=18697370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T18:30:00+00:00, last15m_closed_end=2026-10-13T18:30+00:00, prior8high=0.017236, depth_time=2026-10-13T18:30:08+00:00, book20_bid_proxy_usdt=36496, book20_ask_proxy_usdt=30409, funding_indicative=-0.000349, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=10663105. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
