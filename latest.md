# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T17:30:17Z**
- feed_generated_utc: 2026-11-04T17:30:18+00:00
- source_sha256: `83bf85c71370f372ad31ac3c22511a7f871744336b04d2875609c19270b870bc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T17:30+00:00, close=80413.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T17:00+00:00, close=80491.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002547|-9.35|-87.32|-9.52|17363452|3.92|
|TRUMPOFFICIAL_USDT|1.320000|-7.30|-22.76|-7.47|19388315|7.57|
|AGT_USDT|0.033740|-6.01|-25.17|-6.18|6035695|5.92|
|ZRO_USDT|1.817300|-2.54|6.15|-2.71|11428951|1.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033740|0.034300|0.033740|1.23|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002547|0.002455|0.002547|0.92|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.320000|1.334000|1.319000|3.27|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.817300|1.818600|1.817300|0.98|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T17:30:02+00:00, last15m_closed_end=2026-11-04T17:30+00:00, prior8high=0.036850, depth_time=2026-11-04T17:30:13+00:00, book20_bid_proxy_usdt=29982, book20_ask_proxy_usdt=21238, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=6035695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T17:30:02+00:00, last15m_closed_end=2026-11-04T17:30+00:00, prior8high=0.003422, depth_time=2026-11-04T17:30:07+00:00, book20_bid_proxy_usdt=91765, book20_ask_proxy_usdt=66233, funding_indicative=-0.000327, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.35%, turnover=17363452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T17:30:03+00:00, last15m_closed_end=2026-11-04T17:30+00:00, prior8high=1.464000, depth_time=2026-11-04T17:30:10+00:00, book20_bid_proxy_usdt=1131760, book20_ask_proxy_usdt=1060254, funding_indicative=-0.000457, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.30%, turnover=19388315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T17:30:03+00:00, last15m_closed_end=2026-11-04T17:30+00:00, prior8high=1.911400, depth_time=2026-11-04T17:30:16+00:00, book20_bid_proxy_usdt=42934, book20_ask_proxy_usdt=80796, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=11428951. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
