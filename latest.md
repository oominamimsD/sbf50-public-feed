# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T00:45:20Z**
- feed_generated_utc: 2026-11-06T00:45:21+00:00
- source_sha256: `cf31f6fb2df256dcf52ebbe104988fa6299e101fb7a6cbb8470212a1a0fe9a29`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T00:45+00:00, close=76376.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002104|-18.44|-90.00|-18.91|19670030|4.75|
|FLUID_USDT|2.457000|-2.96|19.04|-3.43|7551107|4.06|
|XRP_USDT|1.222400|-1.78|-6.65|-2.25|436470562|0.82|
|ATOM_USDT|1.400000|-1.40|-14.16|-1.87|6300337|7.14|
|HYPE_USDT|77.720000|-1.24|-17.26|-1.71|88298532|0.13|
|XPL_USDT|0.058120|-0.78|-26.36|-1.25|12566011|1.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002104|0.002086|0.002104|1.25|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.400000|1.345000|1.400000|19.44|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.457000|2.362000|2.457000|1.63|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.720000|76.284000|77.720000|0.75|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.058120|0.056610|0.058120|0.20|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.222400|1.199300|1.222400|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T00:45:00+00:00, last15m_closed_end=2026-11-06T00:45+00:00, prior8high=0.002272, depth_time=2026-11-06T00:45:06+00:00, book20_bid_proxy_usdt=33892, book20_ask_proxy_usdt=42127, funding_indicative=-0.000853, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.44%, turnover=19670030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T00:45:00+00:00, last15m_closed_end=2026-11-06T00:45+00:00, prior8high=1.385000, depth_time=2026-11-06T00:45:14+00:00, book20_bid_proxy_usdt=1752475, book20_ask_proxy_usdt=2597749, funding_indicative=-0.000084, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=6300337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T00:45:00+00:00, last15m_closed_end=2026-11-06T00:45+00:00, prior8high=2.467000, depth_time=2026-11-06T00:45:09+00:00, book20_bid_proxy_usdt=201007, book20_ask_proxy_usdt=193508, funding_indicative=0.000751, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=7551107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T00:45:00+00:00, last15m_closed_end=2026-11-06T00:45+00:00, prior8high=77.692000, depth_time=2026-11-06T00:45:17+00:00, book20_bid_proxy_usdt=230620, book20_ask_proxy_usdt=89875, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=88298532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T00:45:00+00:00, last15m_closed_end=2026-11-06T00:45+00:00, prior8high=0.058820, depth_time=2026-11-06T00:45:19+00:00, book20_bid_proxy_usdt=409153, book20_ask_proxy_usdt=337983, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=12566011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T00:45:00+00:00, last15m_closed_end=2026-11-06T00:45+00:00, prior8high=1.223100, depth_time=2026-11-06T00:45:11+00:00, book20_bid_proxy_usdt=3444489, book20_ask_proxy_usdt=3371760, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=436470562. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
