# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T17:45:25Z**
- feed_generated_utc: 2026-11-05T17:45:27+00:00
- source_sha256: `d46b7ed581537eb0fa91f6220e6152b4a76c90c05e3434cc2877226187ea7a03`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T17:45+00:00, close=75959.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T17:00+00:00, close=76361, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.381000|-5.96|15.35|-5.89|8863998|8.39|
|AKE_USDT|0.002460|-4.65|-88.31|-4.58|16470778|4.07|
|TRUMPOFFICIAL_USDT|1.122000|-3.85|-35.06|-3.78|33640263|8.90|
|PENGU_USDT|0.006355|-2.35|-21.84|-2.28|6313721|1.57|
|BCH_USDT|274.250000|-1.74|-4.86|-1.67|9982713|2.55|
|QNT_USDT|189.330000|-1.29|-4.73|-1.22|48313340|0.53|
|ENA_USDT|0.160800|-1.13|-24.83|-1.06|57143283|0.62|
|WLD_USDT|0.337200|-1.08|-22.71|-1.01|84874671|2.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002460|0.002466|0.002460|3.53|Y|N/N|Y/Y|Y|N|
|BCH_USDT|274.250000|273.260000|274.250000|2.04|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.160800|0.159750|0.160810|0.85|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.381000|2.364000|2.381000|0.09|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.006355|0.006351|0.006355|4.76|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.330000|189.170000|189.330000|0.96|N|Y/Y|Y/N|Y|N|
|TRUMPOFFICIAL_USDT|1.122000|1.114000|1.122000|0.78|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.337200|0.333700|0.337200|0.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T17:44:59+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=0.003465, depth_time=2026-11-05T17:45:09+00:00, book20_bid_proxy_usdt=21989, book20_ask_proxy_usdt=67399, funding_indicative=-0.003196, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=16470778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T17:45:00+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=284.120000, depth_time=2026-11-05T17:45:17+00:00, book20_bid_proxy_usdt=68602, book20_ask_proxy_usdt=51149, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=9982713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T17:44:59+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=0.167400, depth_time=2026-11-05T17:45:22+00:00, book20_bid_proxy_usdt=100932, book20_ask_proxy_usdt=99553, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=57143283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T17:44:59+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=2.611000, depth_time=2026-11-05T17:45:06+00:00, book20_bid_proxy_usdt=200150, book20_ask_proxy_usdt=208697, funding_indicative=0.000272, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=8863998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T17:45:00+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=0.006695, depth_time=2026-11-05T17:45:14+00:00, book20_bid_proxy_usdt=169572, book20_ask_proxy_usdt=136643, funding_indicative=-0.000030, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=6313721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T17:44:59+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=195.990000, depth_time=2026-11-05T17:45:19+00:00, book20_bid_proxy_usdt=98352, book20_ask_proxy_usdt=45844, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=48313340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T17:44:59+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=1.204000, depth_time=2026-11-05T17:45:09+00:00, book20_bid_proxy_usdt=2049753, book20_ask_proxy_usdt=1564147, funding_indicative=-0.000061, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=33640263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T17:44:59+00:00, last15m_closed_end=2026-11-05T17:45+00:00, prior8high=0.349400, depth_time=2026-11-05T17:45:24+00:00, book20_bid_proxy_usdt=3426346, book20_ask_proxy_usdt=2668264, funding_indicative=-0.000622, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=84874671. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
