# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T20:45:18Z**
- feed_generated_utc: 2026-10-21T20:45:20+00:00
- source_sha256: `80a0740b0e1f5c17a8547f8c620a14488ef4e08a5c4c508b67221350b6d6c5e1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T20:45+00:00, close=84670.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002491|-12.41|75.66|-12.61|9121133|4.01|
|BR_USDT|0.476790|-11.95|16.93|-12.15|15098617|5.03|
|AKE_USDT|0.025794|-3.35|-0.33|-3.55|10283500|0.39|
|TIA_USDT|0.620100|-1.96|16.23|-2.16|39877222|3.23|
|INJ_USDT|8.643000|-1.31|13.14|-1.51|57863922|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025794|0.025195|0.025794|0.39|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.476790|0.478000|0.477000|1.38|Y|Y/Y|Y/Y|N|Y|
|DOOD_USDT|0.002491|0.002237|0.002491|0.55|N|Y/Y|N/N|N|N|
|INJ_USDT|8.643000|8.474000|8.643000|2.97|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.620100|0.614400|0.620100|0.46|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T20:45:00+00:00, last15m_closed_end=2026-10-21T20:45+00:00, prior8high=0.026156, depth_time=2026-10-21T20:45:12+00:00, book20_bid_proxy_usdt=10289, book20_ask_proxy_usdt=17884, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=10283500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T20:45:00+00:00, last15m_closed_end=2026-10-21T20:45+00:00, prior8high=0.528660, depth_time=2026-10-21T20:45:09+00:00, book20_bid_proxy_usdt=4198, book20_ask_proxy_usdt=4840, funding_indicative=-0.000101, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.95%, turnover=15098617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T20:45:00+00:00, last15m_closed_end=2026-10-21T20:45+00:00, prior8high=0.002549, depth_time=2026-10-21T20:45:08+00:00, book20_bid_proxy_usdt=126371, book20_ask_proxy_usdt=149813, funding_indicative=0.000012, next_funding_utc=2026-10-21T21:00:00+00:00, funding_cycle_h=1, 24h_change=-12.41%, turnover=9121133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T20:45:00+00:00, last15m_closed_end=2026-10-21T20:45+00:00, prior8high=8.672000, depth_time=2026-10-21T20:45:17+00:00, book20_bid_proxy_usdt=341901, book20_ask_proxy_usdt=177849, funding_indicative=0.000106, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=57863922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T20:45:00+00:00, last15m_closed_end=2026-10-21T20:45+00:00, prior8high=0.635600, depth_time=2026-10-21T20:45:15+00:00, book20_bid_proxy_usdt=320687, book20_ask_proxy_usdt=240014, funding_indicative=-0.000084, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=39877222. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
