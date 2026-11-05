# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T21:30:21Z**
- feed_generated_utc: 2026-11-05T21:30:22+00:00
- source_sha256: `8e8e2a95cb53619114f00d70d456ffa81da7d08f8c5274a368cccb2046502e05`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T21:30+00:00, close=75974.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T21:00+00:00, close=76205.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002231|-13.52|-89.40|-13.47|19594646|4.48|
|FLUID_USDT|2.388000|-5.68|15.69|-5.63|8294831|4.19|
|BCH_USDT|274.110000|-1.79|-4.91|-1.74|10274313|2.19|
|XRP_USDT|1.225200|-1.55|-6.43|-1.50|437062856|0.82|
|HYPE_USDT|77.699000|-1.27|-17.28|-1.22|88693058|0.13|
|QNT_USDT|189.740000|-1.08|-4.52|-1.03|43423462|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002231|0.002009|0.002231|0.33|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|274.110000|272.970000|274.110000|2.14|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.388000|2.355000|2.388000|0.80|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.699000|77.569000|77.720000|0.50|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.740000|188.050000|189.740000|1.90|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.225200|1.222200|1.225100|2.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T21:30:02+00:00, last15m_closed_end=2026-11-05T21:30+00:00, prior8high=0.002495, depth_time=2026-11-05T21:30:08+00:00, book20_bid_proxy_usdt=21623, book20_ask_proxy_usdt=44565, funding_indicative=-0.002251, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.52%, turnover=19594646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T21:30:02+00:00, last15m_closed_end=2026-11-05T21:30+00:00, prior8high=278.650000, depth_time=2026-11-05T21:30:13+00:00, book20_bid_proxy_usdt=63711, book20_ask_proxy_usdt=61437, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=10274313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T21:30:02+00:00, last15m_closed_end=2026-11-05T21:30+00:00, prior8high=2.424000, depth_time=2026-11-05T21:30:08+00:00, book20_bid_proxy_usdt=168342, book20_ask_proxy_usdt=213226, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.68%, turnover=8294831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T21:30:02+00:00, last15m_closed_end=2026-11-05T21:30+00:00, prior8high=78.939000, depth_time=2026-11-05T21:30:18+00:00, book20_bid_proxy_usdt=325064, book20_ask_proxy_usdt=139450, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=88693058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T21:30:02+00:00, last15m_closed_end=2026-11-05T21:30+00:00, prior8high=193.570000, depth_time=2026-11-05T21:30:21+00:00, book20_bid_proxy_usdt=40391, book20_ask_proxy_usdt=56609, funding_indicative=0.000006, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=43423462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T21:30:02+00:00, last15m_closed_end=2026-11-05T21:30+00:00, prior8high=1.245300, depth_time=2026-11-05T21:30:16+00:00, book20_bid_proxy_usdt=3081603, book20_ask_proxy_usdt=2982676, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=437062856. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
