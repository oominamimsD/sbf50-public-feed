# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T07:00:16Z**
- feed_generated_utc: 2026-10-28T07:00:19+00:00
- source_sha256: `62743ebad61c3fdd0f78af15f8155e35a341f0086620112b99ce0ddf5aac151b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T07:00+00:00, close=80839.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T07:00+00:00, close=80839.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.020805|-29.62|-33.08|-30.00|5732251|1.44|
|Q_USDT|0.055800|-12.24|-54.54|-12.62|31439379|1.79|
|NIL_USDT|0.084290|-7.34|-5.14|-7.72|6059875|5.93|
|BULLA_USDT|0.064580|-6.54|-8.28|-6.92|10773072|7.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020805|0.020971|0.020805|2.02|Y|Y/Y|Y/Y|N|Y|
|BULLA_USDT|0.064580|0.057000|0.064580|0.93|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.084290|0.081520|0.084290|0.69|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.055800|0.047660|0.056010|2.06|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T07:00:01+00:00, last15m_closed_end=2026-10-28T07:00+00:00, prior8high=0.022222, depth_time=2026-10-28T07:00:08+00:00, book20_bid_proxy_usdt=4786, book20_ask_proxy_usdt=4749, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-29.62%, turnover=5732251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T07:00:01+00:00, last15m_closed_end=2026-10-28T07:00+00:00, prior8high=0.082140, depth_time=2026-10-28T07:00:15+00:00, book20_bid_proxy_usdt=10707, book20_ask_proxy_usdt=8513, funding_indicative=-0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.54%, turnover=10773072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T07:00:01+00:00, last15m_closed_end=2026-10-28T07:00+00:00, prior8high=0.085350, depth_time=2026-10-28T07:00:12+00:00, book20_bid_proxy_usdt=2555, book20_ask_proxy_usdt=20596, funding_indicative=-0.000555, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.34%, turnover=6059875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T07:00:01+00:00, last15m_closed_end=2026-10-28T07:00+00:00, prior8high=0.074627, depth_time=2026-10-28T07:00:10+00:00, book20_bid_proxy_usdt=44925, book20_ask_proxy_usdt=22777, funding_indicative=-0.001093, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.24%, turnover=31439379. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
