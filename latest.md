# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T16:15:15Z**
- feed_generated_utc: 2026-11-04T16:15:16+00:00
- source_sha256: `40f5cc0fce6588ec9af1c3923d6d042a818ec1388deadb53ad16c3c17ab5af5b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T16:15+00:00, close=80516.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002700|-3.91|-86.56|-4.20|16656145|3.70|
|Q_USDT|0.028460|-0.73|-54.29|-1.02|7266665|3.51|
|AGT_USDT|0.035640|-0.72|-20.95|-1.01|6265796|2.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035640|0.033650|0.035640|1.07|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002700|0.002739|0.002689|1.52|Y|Y/Y|Y/Y|N|Y|
|Q_USDT|0.028460|0.028130|0.028460|1.79|N|N/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T16:15:01+00:00, last15m_closed_end=2026-11-04T16:15+00:00, prior8high=0.037650, depth_time=2026-11-04T16:15:14+00:00, book20_bid_proxy_usdt=23708, book20_ask_proxy_usdt=18806, funding_indicative=0.000063, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.72%, turnover=6265796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T16:15:01+00:00, last15m_closed_end=2026-11-04T16:15+00:00, prior8high=0.003487, depth_time=2026-11-04T16:15:08+00:00, book20_bid_proxy_usdt=113397, book20_ask_proxy_usdt=65249, funding_indicative=-0.000293, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.91%, turnover=16656145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T16:15:01+00:00, last15m_closed_end=2026-11-04T16:15+00:00, prior8high=0.029770, depth_time=2026-11-04T16:15:11+00:00, book20_bid_proxy_usdt=98081, book20_ask_proxy_usdt=63077, funding_indicative=-0.000083, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.73%, turnover=7266665. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
