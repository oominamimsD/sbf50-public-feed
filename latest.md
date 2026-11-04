# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T09:00:16Z**
- feed_generated_utc: 2026-11-04T09:00:17+00:00
- source_sha256: `6bd39e8ad4d119ce72e3204673d7e58d33d65e37670e7a6193f82a5315d74254`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T09:00+00:00, close=78473.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T09:00+00:00, close=78473.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.034630|-33.51|-27.12|-34.55|10447368|5.77|
|AKE_USDT|0.002936|-29.35|-86.10|-30.39|11875169|3.40|
|TRUMPOFFICIAL_USDT|1.496000|-6.84|-11.37|-7.88|10048721|6.69|
|Q_USDT|0.027910|-1.27|-56.10|-2.31|7188563|7.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.034630|0.034150|0.034630|0.77|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.002936|0.002981|0.002936|1.65|Y|Y/Y|Y/Y|N|Y|
|Q_USDT|0.027910|0.027670|0.027910|2.79|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.496000|1.495000|1.496000|2.23|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T09:00:00+00:00, last15m_closed_end=2026-11-04T09:00+00:00, prior8high=0.038390, depth_time=2026-11-04T09:00:06+00:00, book20_bid_proxy_usdt=33918, book20_ask_proxy_usdt=34576, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-33.51%, turnover=10447368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T09:00:00+00:00, last15m_closed_end=2026-11-04T09:00+00:00, prior8high=0.003235, depth_time=2026-11-04T09:00:09+00:00, book20_bid_proxy_usdt=93888, book20_ask_proxy_usdt=102834, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.35%, turnover=11875169. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T09:00:00+00:00, last15m_closed_end=2026-11-04T09:00+00:00, prior8high=0.028570, depth_time=2026-11-04T09:00:15+00:00, book20_bid_proxy_usdt=66961, book20_ask_proxy_usdt=77706, funding_indicative=-0.000451, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=7188563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T09:00:01+00:00, last15m_closed_end=2026-11-04T09:00+00:00, prior8high=1.526000, depth_time=2026-11-04T09:00:12+00:00, book20_bid_proxy_usdt=2475718, book20_ask_proxy_usdt=2205484, funding_indicative=-0.000067, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.84%, turnover=10048721. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
