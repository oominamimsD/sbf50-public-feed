# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T08:15:11Z**
- feed_generated_utc: 2026-10-28T08:15:13+00:00
- source_sha256: `1971b1b103028ce789f605f1699ae65ebaf1314244de5c9912aa6b91dfd6d04b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T08:15+00:00, close=81136.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.059440|-6.51|-51.57|-7.26|29492380|1.68|
|AKE_USDT|0.020538|-2.77|-33.94|-3.52|5827181|8.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020538|0.020384|0.020494|1.51|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.059440|0.051476|0.059440|0.34|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T08:15:01+00:00, last15m_closed_end=2026-10-28T08:15+00:00, prior8high=0.021607, depth_time=2026-10-28T08:15:09+00:00, book20_bid_proxy_usdt=5172, book20_ask_proxy_usdt=6721, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=5827181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T08:15:01+00:00, last15m_closed_end=2026-10-28T08:15+00:00, prior8high=0.074627, depth_time=2026-10-28T08:15:07+00:00, book20_bid_proxy_usdt=41767, book20_ask_proxy_usdt=22501, funding_indicative=-0.001020, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=29492380. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
