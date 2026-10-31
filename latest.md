# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T02:15:26Z**
- feed_generated_utc: 2026-10-31T02:15:29+00:00
- source_sha256: `986b517fb03807b98352c128cb2fa5a454776c70abbb21df91f42d78a1a5a5e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T02:15+00:00, close=77379.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T02:00+00:00, close=77358.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011927|-36.96|-65.91|-36.71|6392698|0.84|
|Q_USDT|0.035180|-25.90|-70.27|-25.65|19459570|8.53|
|EVAA_USDT|1.164400|-9.18|121.83|-8.93|6496201|5.12|
|BEAT_USDT|0.097520|-7.25|34.34|-7.00|8651335|1.03|
|BLESS_USDT|0.009301|-5.58|13.96|-5.33|12336141|2.15|
|TRX_USDT|0.326050|-2.81|-0.99|-2.56|8074477|1.53|
|HYPE_USDT|89.857000|-2.69|14.60|-2.44|119410093|0.11|
|LIT_USDT|2.768900|-1.95|-16.69|-1.70|6168037|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011927|0.012234|0.011936|1.79|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097520|0.096630|0.097520|3.98|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009301|0.009223|0.009289|0.96|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.164400|1.106900|1.164400|0.91|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.857000|89.156000|89.857000|1.12|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.768900|2.749900|2.768900|1.27|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.035180|0.035540|0.035190|8.08|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.326050|0.321930|0.326040|5.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=0.014222, depth_time=2026-10-31T02:15:08+00:00, book20_bid_proxy_usdt=22848, book20_ask_proxy_usdt=8185, funding_indicative=-0.000058, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-36.96%, turnover=6392698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=0.106950, depth_time=2026-10-31T02:15:15+00:00, book20_bid_proxy_usdt=5758, book20_ask_proxy_usdt=13765, funding_indicative=0.000145, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.25%, turnover=8651335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=0.009963, depth_time=2026-10-31T02:15:18+00:00, book20_bid_proxy_usdt=17209, book20_ask_proxy_usdt=12093, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.58%, turnover=12336141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=1.176200, depth_time=2026-10-31T02:15:13+00:00, book20_bid_proxy_usdt=2814, book20_ask_proxy_usdt=8772, funding_indicative=0.000103, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.18%, turnover=6496201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=90.251000, depth_time=2026-10-31T02:15:23+00:00, book20_bid_proxy_usdt=103120, book20_ask_proxy_usdt=40269, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=119410093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T02:15:01+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=2.792300, depth_time=2026-10-31T02:15:23+00:00, book20_bid_proxy_usdt=25850, book20_ask_proxy_usdt=24650, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=6168037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=0.049970, depth_time=2026-10-31T02:15:10+00:00, book20_bid_proxy_usdt=16546, book20_ask_proxy_usdt=20925, funding_indicative=-0.001004, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-25.90%, turnover=19459570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T02:15:00+00:00, last15m_closed_end=2026-10-31T02:15+00:00, prior8high=0.328990, depth_time=2026-10-31T02:15:20+00:00, book20_bid_proxy_usdt=59809, book20_ask_proxy_usdt=56745, funding_indicative=-0.001442, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=8074477. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
