# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T19:00:16Z**
- feed_generated_utc: 2026-10-27T19:00:19+00:00
- source_sha256: `e72f08bd10939c7fb751bd9a2a969deaaae90eb5d88490169dc5a30139df3bf1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T19:00+00:00, close=80582.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T19:00+00:00, close=80582.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.023173|-21.62|-25.46|-21.68|5139366|1.30|
|Q_USDT|0.054755|-17.02|-55.39|-17.08|56420906|2.19|
|BULLA_USDT|0.066150|-4.26|-6.05|-4.32|11258964|1.51|
|IRYS_USDT|0.024590|-2.84|88.86|-2.90|5781457|8.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.023173|0.022000|0.023173|0.35|N|Y/Y|Y/Y|N|N|
|BULLA_USDT|0.066150|0.050590|0.066150|0.18|N|Y/Y|Y/Y|N|N|
|IRYS_USDT|0.024590|0.024370|0.024590|0.74|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.054755|0.052960|0.054755|0.44|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-27T19:00:03+00:00, last15m_closed_end=2026-10-27T19:00+00:00, prior8high=0.025351, depth_time=2026-10-27T19:00:08+00:00, book20_bid_proxy_usdt=4684, book20_ask_proxy_usdt=3397, funding_indicative=0.000050, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-21.62%, turnover=5139366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T19:00:02+00:00, last15m_closed_end=2026-10-27T19:00+00:00, prior8high=0.085880, depth_time=2026-10-27T19:00:13+00:00, book20_bid_proxy_usdt=35823, book20_ask_proxy_usdt=6486, funding_indicative=-0.017405, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=11258964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T19:00:02+00:00, last15m_closed_end=2026-10-27T19:00+00:00, prior8high=0.024890, depth_time=2026-10-27T19:00:13+00:00, book20_bid_proxy_usdt=118050, book20_ask_proxy_usdt=82273, funding_indicative=-0.000349, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=1, 24h_change=-2.84%, turnover=5781457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T19:00:02+00:00, last15m_closed_end=2026-10-27T19:00+00:00, prior8high=0.057931, depth_time=2026-10-27T19:00:10+00:00, book20_bid_proxy_usdt=1643, book20_ask_proxy_usdt=2379, funding_indicative=0.000050, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-17.02%, turnover=56420906. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
