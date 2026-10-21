# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T19:15:19Z**
- feed_generated_utc: 2026-10-21T19:15:21+00:00
- source_sha256: `5634f9191faa2efc5297b9b78ae0cacf500b080fed60e2e9cabee7b422257302`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T19:15+00:00, close=84311.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T19:00+00:00, close=84374.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002397|-15.71|69.04|-15.49|9070193|4.17|
|BR_USDT|0.505250|-6.70|23.91|-6.48|14704856|1.98|
|AKE_USDT|0.025497|-4.46|-1.48|-4.24|10103777|3.53|
|INJ_USDT|8.499000|-2.95|11.25|-2.73|56783786|2.35|
|TIA_USDT|0.620700|-1.86|16.34|-1.64|39581424|3.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025497|0.025640|0.025497|2.06|Y|Y/Y|Y/Y|N|Y|
|BR_USDT|0.505250|0.513880|0.505220|1.94|Y|Y/Y|Y/Y|N|Y|
|DOOD_USDT|0.002397|0.002080|0.002397|0.36|N|Y/Y|N/N|N|N|
|INJ_USDT|8.499000|8.525000|8.498000|3.02|Y|Y/Y|N/N|N|N|
|TIA_USDT|0.620700|0.618400|0.620800|1.14|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T19:15:01+00:00, last15m_closed_end=2026-10-21T19:15+00:00, prior8high=0.026445, depth_time=2026-10-21T19:15:13+00:00, book20_bid_proxy_usdt=14541, book20_ask_proxy_usdt=11860, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=10103777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T19:15:01+00:00, last15m_closed_end=2026-10-21T19:15+00:00, prior8high=0.535870, depth_time=2026-10-21T19:15:11+00:00, book20_bid_proxy_usdt=3708, book20_ask_proxy_usdt=2349, funding_indicative=-0.000172, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.70%, turnover=14704856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T19:15:01+00:00, last15m_closed_end=2026-10-21T19:15+00:00, prior8high=0.002431, depth_time=2026-10-21T19:15:08+00:00, book20_bid_proxy_usdt=108286, book20_ask_proxy_usdt=80926, funding_indicative=0.000012, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=1, 24h_change=-15.71%, turnover=9070193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T19:15:01+00:00, last15m_closed_end=2026-10-21T19:15+00:00, prior8high=8.717000, depth_time=2026-10-21T19:15:15+00:00, book20_bid_proxy_usdt=211288, book20_ask_proxy_usdt=281594, funding_indicative=0.000052, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=56783786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T19:15:01+00:00, last15m_closed_end=2026-10-21T19:15+00:00, prior8high=0.636000, depth_time=2026-10-21T19:15:18+00:00, book20_bid_proxy_usdt=177101, book20_ask_proxy_usdt=300320, funding_indicative=-0.000092, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=39581424. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
