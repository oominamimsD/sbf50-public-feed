# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T05:00:14Z**
- feed_generated_utc: 2026-10-28T05:00:17+00:00
- source_sha256: `4ab9e5e20d1e47fddbba170fbaccbed7a2ab3e771f9dcffd1d8bf78e89cd840a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T05:00+00:00, close=80965.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T05:00+00:00, close=80965.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.021967|-25.69|-29.34|-26.23|5587882|0.46|
|Q_USDT|0.049200|-22.62|-59.92|-23.16|34043713|1.42|
|NIL_USDT|0.082490|-9.32|-7.16|-9.86|5927288|6.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.021967|0.021404|0.021967|1.06|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.082490|0.082210|0.082490|0.64|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.049200|0.047916|0.049180|1.91|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T05:00:02+00:00, last15m_closed_end=2026-10-28T05:00+00:00, prior8high=0.022743, depth_time=2026-10-28T05:00:08+00:00, book20_bid_proxy_usdt=4301, book20_ask_proxy_usdt=2988, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-25.69%, turnover=5587882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T05:00:02+00:00, last15m_closed_end=2026-10-28T05:00+00:00, prior8high=0.085420, depth_time=2026-10-28T05:00:14+00:00, book20_bid_proxy_usdt=8423, book20_ask_proxy_usdt=10313, funding_indicative=-0.000123, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.32%, turnover=5927288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T05:00:02+00:00, last15m_closed_end=2026-10-28T05:00+00:00, prior8high=0.055430, depth_time=2026-10-28T05:00:11+00:00, book20_bid_proxy_usdt=32813, book20_ask_proxy_usdt=31854, funding_indicative=-0.000031, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.62%, turnover=34043713. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
