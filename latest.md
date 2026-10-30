# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T22:30:18Z**
- feed_generated_utc: 2026-10-30T22:30:19+00:00
- source_sha256: `b6bedf82d6bf3b19fb774f558a3baf9ddac8c4bd85c07e259274ca08120131f9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T22:30+00:00, close=76847.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T22:00+00:00, close=76670.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013449|-28.92|-61.57|-27.98|5169327|5.21|
|EVAA_USDT|1.109400|-13.47|111.35|-12.53|6700478|2.71|
|LIT_USDT|2.723000|-3.58|-18.08|-2.64|9494157|0.37|
|HYPE_USDT|89.536000|-3.04|14.19|-2.10|154611993|0.11|
|BTW_USDT|1.167400|-2.67|-31.42|-1.73|10400043|0.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013449|0.013039|0.013432|1.36|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.167400|1.144800|1.167400|0.74|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.109400|1.082800|1.109400|0.47|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.536000|89.002000|89.536000|0.63|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.723000|2.686200|2.723000|0.41|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T22:30:00+00:00, last15m_closed_end=2026-10-30T22:30+00:00, prior8high=0.014049, depth_time=2026-10-30T22:30:08+00:00, book20_bid_proxy_usdt=4634, book20_ask_proxy_usdt=32241, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-28.92%, turnover=5169327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T22:30:00+00:00, last15m_closed_end=2026-10-30T22:30+00:00, prior8high=1.262200, depth_time=2026-10-30T22:30:16+00:00, book20_bid_proxy_usdt=25015, book20_ask_proxy_usdt=18297, funding_indicative=-0.000260, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=10400043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T22:30:00+00:00, last15m_closed_end=2026-10-30T22:30+00:00, prior8high=1.132500, depth_time=2026-10-30T22:30:10+00:00, book20_bid_proxy_usdt=10943, book20_ask_proxy_usdt=13830, funding_indicative=0.000119, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.47%, turnover=6700478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T22:30:00+00:00, last15m_closed_end=2026-10-30T22:30+00:00, prior8high=90.590000, depth_time=2026-10-30T22:30:14+00:00, book20_bid_proxy_usdt=177702, book20_ask_proxy_usdt=28348, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=154611993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T22:30:00+00:00, last15m_closed_end=2026-10-30T22:30+00:00, prior8high=2.764300, depth_time=2026-10-30T22:30:11+00:00, book20_bid_proxy_usdt=26235, book20_ask_proxy_usdt=17495, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=9494157. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
