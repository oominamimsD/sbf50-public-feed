# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T11:15:19Z**
- feed_generated_utc: 2026-10-21T11:15:21+00:00
- source_sha256: `0ddbead5a51b19caf774f1dcc82734c2da8a87a01f0734e5f82e53faec7f7d68`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T11:15+00:00, close=83401.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T11:00+00:00, close=83362.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.046125|-28.63|185.12|-29.62|6602810|3.04|
|BAT_USDT|0.182020|-15.64|2.61|-16.63|10601663|1.10|
|BR_USDT|0.574830|-11.65|32.75|-12.64|22922395|1.74|
|BTW_USDT|1.722200|-6.88|-11.79|-7.87|24980848|1.74|
|Q_USDT|0.118943|-3.10|189.20|-4.09|5347193|1.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.046125|0.043233|0.046125|0.55|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.182020|0.181440|0.181970|0.61|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.574830|0.566870|0.574860|0.89|N|Y/Y|N/N|N|N|
|BTW_USDT|1.722200|1.665600|1.722600|1.21|N|Y/N|N/N|N|N|
|Q_USDT|0.118943|0.117302|0.118943|0.58|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T11:15:01+00:00, last15m_closed_end=2026-10-21T11:15+00:00, prior8high=0.051865, depth_time=2026-10-21T11:15:07+00:00, book20_bid_proxy_usdt=8890, book20_ask_proxy_usdt=7387, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-28.63%, turnover=6602810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T11:15:01+00:00, last15m_closed_end=2026-10-21T11:15+00:00, prior8high=0.185160, depth_time=2026-10-21T11:15:11+00:00, book20_bid_proxy_usdt=31104, book20_ask_proxy_usdt=22494, funding_indicative=-0.000125, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.64%, turnover=10601663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T11:15:01+00:00, last15m_closed_end=2026-10-21T11:15+00:00, prior8high=0.608980, depth_time=2026-10-21T11:15:13+00:00, book20_bid_proxy_usdt=3414, book20_ask_proxy_usdt=2792, funding_indicative=-0.000095, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.65%, turnover=22922395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T11:15:01+00:00, last15m_closed_end=2026-10-21T11:15+00:00, prior8high=2.142500, depth_time=2026-10-21T11:15:16+00:00, book20_bid_proxy_usdt=7289, book20_ask_proxy_usdt=11120, funding_indicative=-0.002863, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.88%, turnover=24980848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T11:15:01+00:00, last15m_closed_end=2026-10-21T11:15+00:00, prior8high=0.124375, depth_time=2026-10-21T11:15:17+00:00, book20_bid_proxy_usdt=17740, book20_ask_proxy_usdt=19053, funding_indicative=0.000021, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.10%, turnover=5347193. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
