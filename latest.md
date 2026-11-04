# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T12:00:13Z**
- feed_generated_utc: 2026-11-04T12:00:15+00:00
- source_sha256: `09837c681c1572dbeec357c29e08215155bffbe25e7d956bf44f15e6c4b6bf5c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002888|-30.51|-86.32|-31.52|13401292|3.46|
|TRUMPOFFICIAL_USDT|1.457000|-9.27|-13.68|-10.28|10756170|6.86|
|HOT_USDT|0.000498|-7.50|44.18|-8.51|8900924|4.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002888|0.002807|0.002888|1.30|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000498|0.000494|0.000498|1.05|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.457000|1.471000|1.457000|2.94|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T11:59:59+00:00, last15m_closed_end=2026-11-04T12:00+00:00, prior8high=0.003007, depth_time=2026-11-04T12:00:06+00:00, book20_bid_proxy_usdt=97421, book20_ask_proxy_usdt=96281, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-30.51%, turnover=13401292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T11:59:59+00:00, last15m_closed_end=2026-11-04T12:00+00:00, prior8high=0.000534, depth_time=2026-11-04T12:00:12+00:00, book20_bid_proxy_usdt=145538, book20_ask_proxy_usdt=70814, funding_indicative=-0.000082, next_funding_utc=2026-11-04T13:00:00+00:00, funding_cycle_h=1, 24h_change=-7.50%, turnover=8900924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T12:00:00+00:00, last15m_closed_end=2026-11-04T12:00+00:00, prior8high=1.497000, depth_time=2026-11-04T12:00:10+00:00, book20_bid_proxy_usdt=1558438, book20_ask_proxy_usdt=2371006, funding_indicative=-0.000267, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=10756170. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
