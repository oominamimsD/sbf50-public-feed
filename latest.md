# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T22:45:26Z**
- feed_generated_utc: 2026-11-05T22:45:28+00:00
- source_sha256: `3775ef51b32d633109104c4cf6427f03418d0880c26a46420776efc06cf8f2dc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T22:45+00:00, close=75814.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T22:00+00:00, close=75826.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002270|-12.01|-89.22|-11.75|19601384|4.41|
|ATOM_USDT|1.382000|-2.67|-15.26|-2.41|5367230|7.23|
|BCH_USDT|272.620000|-2.32|-5.43|-2.06|8908290|2.57|
|HYPE_USDT|77.095000|-2.03|-17.92|-1.77|89880224|0.13|
|XRP_USDT|1.219600|-2.00|-6.86|-1.74|438525102|0.82|
|QNT_USDT|188.780000|-1.58|-5.01|-1.32|43543940|0.53|
|ZRO_USDT|1.597800|-1.50|-9.43|-1.24|7095430|1.25|
|ONDO_USDT|0.367300|-1.39|-14.54|-1.13|30347799|2.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002270|0.002103|0.002272|0.16|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.382000|1.378000|1.382000|1.40|N|Y/Y|Y/N|Y|N|
|BCH_USDT|272.620000|270.070000|272.620000|0.61|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|77.095000|76.900000|77.095000|0.74|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.367300|0.366800|0.367400|1.69|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.780000|187.390000|188.730000|0.74|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.219600|1.217300|1.219400|0.53|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.597800|1.594300|1.597800|0.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=0.002275, depth_time=2026-11-05T22:45:07+00:00, book20_bid_proxy_usdt=35376, book20_ask_proxy_usdt=44873, funding_indicative=-0.000793, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.01%, turnover=19601384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=1.443000, depth_time=2026-11-05T22:45:08+00:00, book20_bid_proxy_usdt=1895130, book20_ask_proxy_usdt=1424049, funding_indicative=-0.000071, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=5367230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=278.230000, depth_time=2026-11-05T22:45:11+00:00, book20_bid_proxy_usdt=50789, book20_ask_proxy_usdt=51188, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=8908290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=78.964000, depth_time=2026-11-05T22:45:15+00:00, book20_bid_proxy_usdt=128174, book20_ask_proxy_usdt=88933, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=89880224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=0.375900, depth_time=2026-11-05T22:45:24+00:00, book20_bid_proxy_usdt=1404678, book20_ask_proxy_usdt=1508986, funding_indicative=-0.000024, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=30347799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=191.110000, depth_time=2026-11-05T22:45:19+00:00, book20_bid_proxy_usdt=93555, book20_ask_proxy_usdt=74583, funding_indicative=-0.000004, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=43543940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=1.243800, depth_time=2026-11-05T22:45:17+00:00, book20_bid_proxy_usdt=3885251, book20_ask_proxy_usdt=3416824, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=438525102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T22:45:02+00:00, last15m_closed_end=2026-11-05T22:45+00:00, prior8high=1.647400, depth_time=2026-11-05T22:45:22+00:00, book20_bid_proxy_usdt=32301, book20_ask_proxy_usdt=66258, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=7095430. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
