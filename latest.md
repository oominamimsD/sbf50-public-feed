# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T21:15:27Z**
- feed_generated_utc: 2026-10-31T21:15:29+00:00
- source_sha256: `11550b4297757bc883658cda688ae50b48f15235b09bccc95f8c006adbaeaec1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T21:15+00:00, close=77427.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T21:00+00:00, close=77523.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244810|-17.33|45.78|-17.16|27298560|3.27|
|BLESS_USDT|0.009375|-11.25|15.55|-11.08|8027017|5.33|
|IDOL_USDT|0.016575|-5.39|109.81|-5.22|7001199|4.23|
|INJ_USDT|7.211000|-3.67|-4.03|-3.50|21936134|1.39|
|TRX_USDT|0.303720|-2.75|-7.66|-2.58|9329307|0.33|
|ENA_USDT|0.188830|-2.66|1.09|-2.49|47589728|0.53|
|WLD_USDT|0.396100|-2.05|-14.26|-1.88|34116384|2.52|
|FET_USDT|0.160300|-1.83|-6.96|-1.66|5697181|6.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009375|0.009406|0.009375|3.44|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.188830|0.188540|0.188740|1.81|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160300|0.160100|0.160300|6.36|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.016575|0.016495|0.016575|1.11|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.211000|7.207000|7.211000|0.88|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.244810|0.237140|0.244810|0.75|N|Y/N|N/N|Y|N|
|TRX_USDT|0.303720|0.302520|0.303720|1.48|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396100|0.395100|0.396100|0.41|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.010415, depth_time=2026-10-31T21:15:10+00:00, book20_bid_proxy_usdt=11106, book20_ask_proxy_usdt=11997, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.25%, turnover=8027017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.191510, depth_time=2026-10-31T21:15:21+00:00, book20_bid_proxy_usdt=148311, book20_ask_proxy_usdt=198369, funding_indicative=-0.000011, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=47589728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.161800, depth_time=2026-10-31T21:15:24+00:00, book20_bid_proxy_usdt=1643467, book20_ask_proxy_usdt=974845, funding_indicative=-0.000157, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=5697181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.018263, depth_time=2026-10-31T21:15:13+00:00, book20_bid_proxy_usdt=6305, book20_ask_proxy_usdt=7676, funding_indicative=0.000053, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.39%, turnover=7001199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=7.358000, depth_time=2026-10-31T21:15:14+00:00, book20_bid_proxy_usdt=344368, book20_ask_proxy_usdt=325868, funding_indicative=0.000191, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=21936134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.284740, depth_time=2026-10-31T21:15:08+00:00, book20_bid_proxy_usdt=4720, book20_ask_proxy_usdt=6372, funding_indicative=-0.000858, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.33%, turnover=27298560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.308970, depth_time=2026-10-31T21:15:19+00:00, book20_bid_proxy_usdt=53178, book20_ask_proxy_usdt=179677, funding_indicative=-0.000510, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=9329307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T21:15:01+00:00, last15m_closed_end=2026-10-31T21:15+00:00, prior8high=0.398800, depth_time=2026-10-31T21:15:24+00:00, book20_bid_proxy_usdt=2609678, book20_ask_proxy_usdt=2978716, funding_indicative=0.000045, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=34116384. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
