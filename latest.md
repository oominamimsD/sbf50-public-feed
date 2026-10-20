# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T15:30:26Z**
- feed_generated_utc: 2026-10-20T15:30:28+00:00
- source_sha256: `cb390bff7e22c77fe6222f4c0695fd074dbdcf1d8f3f67e92b12e90359c6c593`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T15:30+00:00, close=82446.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T15:00+00:00, close=83242.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.065320|-24.95|292.02|-25.59|8249521|0.61|
|ARB_USDT|0.188680|-3.55|0.11|-4.19|104678375|0.53|
|STRK_USDT|0.055660|-1.62|-38.61|-2.26|18438203|1.80|
|AKE_USDT|0.030272|-1.60|28.59|-2.24|6753135|0.66|
|Q_USDT|0.124440|-1.22|304.14|-1.86|7028084|0.40|
|UNI_USDT|7.261000|-0.37|-2.11|-1.01|12495024|2.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.065320|0.063039|0.065320|0.73|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030272|0.029930|0.030272|0.87|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188680|0.187280|0.188680|2.60|N|N/Y|Y/N|Y|N|
|Q_USDT|0.124440|0.119102|0.124520|0.67|N|N/N|N/N|Y|N|
|STRK_USDT|0.055660|0.055650|0.055660|5.03|N|N/N|Y/Y|Y|N|
|UNI_USDT|7.261000|7.125000|7.261000|7.16|N|N/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T15:30:01+00:00, last15m_closed_end=2026-10-20T15:30+00:00, prior8high=0.068775, depth_time=2026-10-20T15:30:10+00:00, book20_bid_proxy_usdt=8246, book20_ask_proxy_usdt=5707, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.95%, turnover=8249521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T15:30:01+00:00, last15m_closed_end=2026-10-20T15:30+00:00, prior8high=0.030823, depth_time=2026-10-20T15:30:19+00:00, book20_bid_proxy_usdt=14767, book20_ask_proxy_usdt=10621, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=6753135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T15:30:01+00:00, last15m_closed_end=2026-10-20T15:30+00:00, prior8high=0.198770, depth_time=2026-10-20T15:30:13+00:00, book20_bid_proxy_usdt=30270, book20_ask_proxy_usdt=43784, funding_indicative=-0.000023, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=104678375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T15:30:01+00:00, last15m_closed_end=2026-10-20T15:30+00:00, prior8high=0.131229, depth_time=2026-10-20T15:30:22+00:00, book20_bid_proxy_usdt=15731, book20_ask_proxy_usdt=16235, funding_indicative=0.000004, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=7028084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T15:30:01+00:00, last15m_closed_end=2026-10-20T15:30+00:00, prior8high=0.059770, depth_time=2026-10-20T15:30:17+00:00, book20_bid_proxy_usdt=482296, book20_ask_proxy_usdt=545183, funding_indicative=0.000000, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=18438203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T15:30:01+00:00, last15m_closed_end=2026-10-20T15:30+00:00, prior8high=7.570000, depth_time=2026-10-20T15:30:25+00:00, book20_bid_proxy_usdt=1142751, book20_ask_proxy_usdt=1514642, funding_indicative=0.000003, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.37%, turnover=12495024. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
