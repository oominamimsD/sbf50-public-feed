# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T00:30:19Z**
- feed_generated_utc: 2026-10-19T00:30:20+00:00
- source_sha256: `c9e020671b35b4af7674ca3cfdcfad6bde7413a54f9662038320378005900551`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T00:30+00:00, close=82144.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.109117|-10.54|285.27|-11.78|9956893|1.38|
|STRK_USDT|0.059930|-2.64|-49.75|-3.88|16297122|1.67|
|AGT_USDT|0.066057|-2.17|273.51|-3.41|10075804|0.76|
|HBAR_USDT|0.084680|-1.28|-9.70|-2.52|50201083|1.18|
|SAND_USDT|0.058280|-0.81|-12.28|-2.05|33934481|3.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066057|0.060544|0.066057|0.92|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084680|0.084530|0.084680|0.77|N|N/Y|N/Y|N|N|
|Q_USDT|0.109117|0.110288|0.109117|1.18|N|Y/Y|N/N|N|N|
|SAND_USDT|0.058280|0.057420|0.058280|0.25|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.059930|0.059380|0.059930|0.49|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T00:29:59+00:00, last15m_closed_end=2026-10-19T00:30+00:00, prior8high=0.068584, depth_time=2026-10-19T00:30:13+00:00, book20_bid_proxy_usdt=2739, book20_ask_proxy_usdt=2545, funding_indicative=0.000199, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=10075804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T00:29:59+00:00, last15m_closed_end=2026-10-19T00:30+00:00, prior8high=0.085750, depth_time=2026-10-19T00:30:15+00:00, book20_bid_proxy_usdt=722167, book20_ask_proxy_usdt=1098500, funding_indicative=-0.000019, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=50201083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T00:29:59+00:00, last15m_closed_end=2026-10-19T00:30+00:00, prior8high=0.121020, depth_time=2026-10-19T00:30:07+00:00, book20_bid_proxy_usdt=7591, book20_ask_proxy_usdt=7777, funding_indicative=0.000106, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.54%, turnover=9956893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T00:29:59+00:00, last15m_closed_end=2026-10-19T00:30+00:00, prior8high=0.058910, depth_time=2026-10-19T00:30:18+00:00, book20_bid_proxy_usdt=478708, book20_ask_proxy_usdt=997855, funding_indicative=-0.003217, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=33934481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T00:29:59+00:00, last15m_closed_end=2026-10-19T00:30+00:00, prior8high=0.060690, depth_time=2026-10-19T00:30:10+00:00, book20_bid_proxy_usdt=588890, book20_ask_proxy_usdt=422751, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=16297122. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
