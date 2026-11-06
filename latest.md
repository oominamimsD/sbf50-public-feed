# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T03:15:20Z**
- feed_generated_utc: 2026-11-06T03:15:22+00:00
- source_sha256: `9a953251f9bde68a78f7de8ce37268c7099155f8fad4c587076a3581b87630ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T03:15+00:00, close=76109.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T03:00+00:00, close=76162.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.077930|-3.96|4.32|-4.08|6962614|6.41|
|FLUID_USDT|2.442000|-3.55|18.31|-3.67|6903872|8.19|
|XRP_USDT|1.213200|-2.52|-7.35|-2.64|419286936|1.65|
|XPL_USDT|0.057590|-1.68|-27.03|-1.80|12499186|3.48|
|HYPE_USDT|77.887000|-1.03|-17.08|-1.15|85700277|0.13|
|ZRO_USDT|1.607800|-0.88|-8.87|-1.00|7143534|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.077930|0.078610|0.077950|1.65|Y|Y/Y|N/N|Y|N|
|FLUID_USDT|2.442000|2.394000|2.442000|0.10|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.887000|77.111000|77.887000|0.68|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057590|0.056870|0.057590|0.47|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.213200|1.212100|1.213200|0.85|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.607800|1.590700|1.607800|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T03:14:59+00:00, last15m_closed_end=2026-11-06T03:15+00:00, prior8high=0.083830, depth_time=2026-11-06T03:15:05+00:00, book20_bid_proxy_usdt=19159, book20_ask_proxy_usdt=23374, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.96%, turnover=6962614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T03:14:59+00:00, last15m_closed_end=2026-11-06T03:15+00:00, prior8high=2.468000, depth_time=2026-11-06T03:15:06+00:00, book20_bid_proxy_usdt=237662, book20_ask_proxy_usdt=279332, funding_indicative=0.000236, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=6903872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T03:14:59+00:00, last15m_closed_end=2026-11-06T03:15+00:00, prior8high=78.260000, depth_time=2026-11-06T03:15:17+00:00, book20_bid_proxy_usdt=157725, book20_ask_proxy_usdt=72499, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=85700277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T03:15:00+00:00, last15m_closed_end=2026-11-06T03:15+00:00, prior8high=0.058050, depth_time=2026-11-06T03:15:15+00:00, book20_bid_proxy_usdt=422245, book20_ask_proxy_usdt=353186, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=12499186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T03:14:59+00:00, last15m_closed_end=2026-11-06T03:15+00:00, prior8high=1.222500, depth_time=2026-11-06T03:15:11+00:00, book20_bid_proxy_usdt=3673690, book20_ask_proxy_usdt=3530965, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=419286936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T03:15:00+00:00, last15m_closed_end=2026-11-06T03:15+00:00, prior8high=1.616700, depth_time=2026-11-06T03:15:19+00:00, book20_bid_proxy_usdt=37185, book20_ask_proxy_usdt=29968, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=7143534. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
