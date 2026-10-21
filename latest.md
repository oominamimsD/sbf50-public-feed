# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T17:00:17Z**
- feed_generated_utc: 2026-10-21T17:00:19+00:00
- source_sha256: `302c629ab7a5c9a6a2d699679e561febc92ea6819ca48eb93bbd93c046700304`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T17:00+00:00, close=84506.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T17:00+00:00, close=84506.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002303|-19.02|62.41|-19.02|9066095|4.34|
|BR_USDT|0.527360|-8.95|29.33|-8.95|15617339|0.76|
|ICNT_USDT|0.186000|-4.37|70.01|-4.37|5740858|5.38|
|AKE_USDT|0.026016|-2.52|0.52|-2.52|9932124|2.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026016|0.026170|0.025995|1.59|Y|Y/Y|Y/Y|N|Y|
|BR_USDT|0.527360|0.523420|0.527360|0.57|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002303|0.002128|0.002300|0.74|N|Y/Y|N/N|N|N|
|ICNT_USDT|0.186000|0.185500|0.186000|0.36|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T17:00:03+00:00, last15m_closed_end=2026-10-21T17:00+00:00, prior8high=0.027884, depth_time=2026-10-21T17:00:16+00:00, book20_bid_proxy_usdt=13580, book20_ask_proxy_usdt=8770, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=9932124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T17:00:03+00:00, last15m_closed_end=2026-10-21T17:00+00:00, prior8high=0.587770, depth_time=2026-10-21T17:00:11+00:00, book20_bid_proxy_usdt=3496, book20_ask_proxy_usdt=3146, funding_indicative=-0.000101, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.95%, turnover=15617339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T17:00:03+00:00, last15m_closed_end=2026-10-21T17:00+00:00, prior8high=0.004584, depth_time=2026-10-21T17:00:09+00:00, book20_bid_proxy_usdt=132966, book20_ask_proxy_usdt=133859, funding_indicative=-0.003392, next_funding_utc=2026-10-21T18:00:00+00:00, funding_cycle_h=1, 24h_change=-19.02%, turnover=9066095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-21T17:00:03+00:00, last15m_closed_end=2026-10-21T17:00+00:00, prior8high=0.195900, depth_time=2026-10-21T17:00:13+00:00, book20_bid_proxy_usdt=195527, book20_ask_proxy_usdt=102339, funding_indicative=-0.000040, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=5740858. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
