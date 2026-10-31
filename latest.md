# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T16:30:11Z**
- feed_generated_utc: 2026-10-31T16:30:13+00:00
- source_sha256: `8628e291db928a79692c258f9ac001a014798f4acbae4fe41045226471df626a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T16:30+00:00, close=77574.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.031380|-2.18|-60.24|-2.19|11065580|3.19|
|IDOL_USDT|0.017183|-1.92|117.50|-1.93|15578991|7.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IDOL_USDT|0.017183|0.016785|0.017182|1.47|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031380|0.030480|0.031380|3.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IDOL_USDT: quote_utc=2026-10-31T16:30:01+00:00, last15m_closed_end=2026-10-31T16:30+00:00, prior8high=0.020565, depth_time=2026-10-31T16:30:11+00:00, book20_bid_proxy_usdt=5152, book20_ask_proxy_usdt=5799, funding_indicative=0.000158, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=15578991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T16:30:02+00:00, last15m_closed_end=2026-10-31T16:30+00:00, prior8high=0.033470, depth_time=2026-10-31T16:30:08+00:00, book20_bid_proxy_usdt=70242, book20_ask_proxy_usdt=44725, funding_indicative=-0.000627, next_funding_utc=2026-10-31T17:00:00+00:00, funding_cycle_h=1, 24h_change=-2.18%, turnover=11065580. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
