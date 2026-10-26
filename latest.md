# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T10:00:26Z**
- feed_generated_utc: 2026-10-26T10:00:29+00:00
- source_sha256: `739e2d274b3807708edeadff8ec903975a133fd2175a50600e5e5348e3558655`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T10:00+00:00, close=80507.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T10:00+00:00, close=80507.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.029350|-23.64|140.57|-23.53|12541095|6.81|
|CAP_USDT|0.084500|-21.38|27.06|-21.27|7228303|1.18|
|APR_USDT|0.035250|-13.43|29.40|-13.32|8902111|8.51|
|BTW_USDT|1.521800|-8.87|-33.98|-8.76|10920619|0.66|
|WLD_USDT|0.439800|-3.67|-7.66|-3.56|61947783|2.27|
|XMR_USDT|589.970000|-3.01|1.28|-2.90|5817473|0.17|
|LIT_USDT|3.099500|-2.17|5.77|-2.06|5528282|0.32|
|DOT_USDT|1.019600|-1.88|-4.65|-1.77|9837996|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035250|0.035240|0.035250|5.39|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.521800|1.440500|1.521800|0.86|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.084500|0.074320|0.084240|0.75|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.019600|1.002700|1.019600|0.47|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.029350|0.028610|0.029370|0.75|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.099500|3.052200|3.099500|0.74|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439800|0.434300|0.439900|0.46|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.970000|583.530000|589.970000|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=0.039060, depth_time=2026-10-26T10:00:12+00:00, book20_bid_proxy_usdt=53738, book20_ask_proxy_usdt=61117, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.43%, turnover=8902111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=1.610000, depth_time=2026-10-26T10:00:15+00:00, book20_bid_proxy_usdt=11410, book20_ask_proxy_usdt=11119, funding_indicative=-0.010353, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.87%, turnover=10920619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=0.090920, depth_time=2026-10-26T10:00:10+00:00, book20_bid_proxy_usdt=53487, book20_ask_proxy_usdt=56594, funding_indicative=0.000066, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.38%, turnover=7228303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=1.025400, depth_time=2026-10-26T10:00:25+00:00, book20_bid_proxy_usdt=521222, book20_ask_proxy_usdt=266166, funding_indicative=-0.000033, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=9837996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=0.030570, depth_time=2026-10-26T10:00:07+00:00, book20_bid_proxy_usdt=53212, book20_ask_proxy_usdt=101070, funding_indicative=-0.000354, next_funding_utc=2026-10-26T11:00:00+00:00, funding_cycle_h=1, 24h_change=-23.64%, turnover=12541095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=3.121700, depth_time=2026-10-26T10:00:22+00:00, book20_bid_proxy_usdt=18813, book20_ask_proxy_usdt=16423, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=5528282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=0.444800, depth_time=2026-10-26T10:00:18+00:00, book20_bid_proxy_usdt=2830598, book20_ask_proxy_usdt=2799906, funding_indicative=-0.000121, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=61947783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T10:00:00+00:00, last15m_closed_end=2026-10-26T10:00+00:00, prior8high=592.000000, depth_time=2026-10-26T10:00:20+00:00, book20_bid_proxy_usdt=26166, book20_ask_proxy_usdt=16579, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=5817473. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
