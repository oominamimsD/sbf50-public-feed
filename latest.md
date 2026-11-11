# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T05:30:12Z**
- feed_generated_utc: 2026-11-11T05:30:13+00:00
- source_sha256: `f29cbc6590af0958375151d336462800ddc331a17f2022f68db60d89691d337a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T05:30+00:00, close=73737, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T05:00+00:00, close=73703.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1012.200000|-7.42|-15.91|-8.18|2169702659|0.10|
|UNI_USDT|6.644000|-2.72|-9.64|-3.48|36445674|1.50|
|VVV_USDT|19.111000|-0.66|-14.53|-1.42|5371419|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|UNI_USDT|6.644000|6.629000|6.644000|0.72|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.111000|19.006000|19.111000|0.80|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1012.200000|1002.510000|1012.290000|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- UNI_USDT: quote_utc=2026-11-11T05:30:01+00:00, last15m_closed_end=2026-11-11T05:30+00:00, prior8high=6.768000, depth_time=2026-11-11T05:30:08+00:00, book20_bid_proxy_usdt=3092532, book20_ask_proxy_usdt=2140160, funding_indicative=0.000041, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=36445674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T05:30:01+00:00, last15m_closed_end=2026-11-11T05:30+00:00, prior8high=19.529000, depth_time=2026-11-11T05:30:10+00:00, book20_bid_proxy_usdt=20551, book20_ask_proxy_usdt=41686, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.66%, turnover=5371419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T05:30:01+00:00, last15m_closed_end=2026-11-11T05:30+00:00, prior8high=1038.490000, depth_time=2026-11-11T05:30:07+00:00, book20_bid_proxy_usdt=331628, book20_ask_proxy_usdt=201040, funding_indicative=0.000095, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.42%, turnover=2169702659. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
