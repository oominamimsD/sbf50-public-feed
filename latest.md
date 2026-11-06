# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T01:15:23Z**
- feed_generated_utc: 2026-11-06T01:15:24+00:00
- source_sha256: `b1f1dae7b6bb094602517fa9ef2881462e46ec90a50d5f184a5c75120e1e18c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T01:15+00:00, close=76292.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T01:00+00:00, close=76300, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002130|-17.44|-89.88|-17.78|19699904|4.70|
|FLUID_USDT|2.433000|-3.90|17.87|-4.24|7115314|4.11|
|XPL_USDT|0.057230|-2.30|-27.49|-2.64|12572978|1.75|
|XRP_USDT|1.221500|-1.85|-6.72|-2.19|433187332|0.82|
|HYPE_USDT|77.541000|-1.47|-17.45|-1.81|87147830|0.13|
|ATOM_USDT|1.399000|-1.47|-14.22|-1.81|6405323|7.15|
|ZRO_USDT|1.599000|-1.43|-9.36|-1.77|7155561|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002130|0.002077|0.002125|0.90|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.399000|1.345000|1.399000|1.07|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.433000|2.362000|2.433000|0.16|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.541000|76.284000|77.539000|0.90|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057230|0.056610|0.057230|0.73|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.221500|1.199300|1.221500|1.21|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.599000|1.568700|1.599000|1.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=0.002257, depth_time=2026-11-06T01:15:07+00:00, book20_bid_proxy_usdt=38890, book20_ask_proxy_usdt=13562, funding_indicative=-0.000998, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.44%, turnover=19699904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=1.401000, depth_time=2026-11-06T01:15:18+00:00, book20_bid_proxy_usdt=2033936, book20_ask_proxy_usdt=1335600, funding_indicative=-0.000054, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=6405323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=2.470000, depth_time=2026-11-06T01:15:09+00:00, book20_bid_proxy_usdt=207354, book20_ask_proxy_usdt=172714, funding_indicative=0.000591, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=7115314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=77.905000, depth_time=2026-11-06T01:15:17+00:00, book20_bid_proxy_usdt=76375, book20_ask_proxy_usdt=108999, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=87147830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=0.058600, depth_time=2026-11-06T01:15:12+00:00, book20_bid_proxy_usdt=326391, book20_ask_proxy_usdt=420307, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=12572978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=1.222700, depth_time=2026-11-06T01:15:15+00:00, book20_bid_proxy_usdt=3132888, book20_ask_proxy_usdt=2787405, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=433187332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T01:15:02+00:00, last15m_closed_end=2026-11-06T01:15+00:00, prior8high=1.618800, depth_time=2026-11-06T01:15:22+00:00, book20_bid_proxy_usdt=48766, book20_ask_proxy_usdt=23989, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=7155561. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
