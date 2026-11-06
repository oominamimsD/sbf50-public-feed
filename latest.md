# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T05:15:15Z**
- feed_generated_utc: 2026-11-06T05:15:16+00:00
- source_sha256: `46972716afd8a4b8d69c34c4e6f4766ad7e9ade4244eb0fd70617b2e1292adce`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T05:15+00:00, close=75543.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T05:00+00:00, close=75744, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.076650|-5.54|2.61|-4.93|6227803|5.21|
|XRP_USDT|1.196500|-3.86|-8.62|-3.25|431458661|0.84|
|XPL_USDT|0.056910|-2.85|-27.89|-2.24|12476178|1.76|
|ZRO_USDT|1.587100|-2.16|-10.04|-1.55|7381075|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.076650|0.077150|0.076650|1.28|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.056910|0.056370|0.056950|1.56|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.196500|1.199900|1.196200|2.84|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.587100|1.572400|1.586800|0.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T05:15:03+00:00, last15m_closed_end=2026-11-06T05:15+00:00, prior8high=0.079970, depth_time=2026-11-06T05:15:06+00:00, book20_bid_proxy_usdt=34630, book20_ask_proxy_usdt=26194, funding_indicative=0.000097, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=6227803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T05:15:03+00:00, last15m_closed_end=2026-11-06T05:15+00:00, prior8high=0.057880, depth_time=2026-11-06T05:15:11+00:00, book20_bid_proxy_usdt=412272, book20_ask_proxy_usdt=445856, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=12476178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T05:15:02+00:00, last15m_closed_end=2026-11-06T05:15+00:00, prior8high=1.216900, depth_time=2026-11-06T05:15:09+00:00, book20_bid_proxy_usdt=3369642, book20_ask_proxy_usdt=3505621, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=431458661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T05:15:03+00:00, last15m_closed_end=2026-11-06T05:15+00:00, prior8high=1.615700, depth_time=2026-11-06T05:15:13+00:00, book20_bid_proxy_usdt=60170, book20_ask_proxy_usdt=20758, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=7381075. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
