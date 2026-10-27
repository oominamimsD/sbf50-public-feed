# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T15:30:26Z**
- feed_generated_utc: 2026-10-27T15:30:29+00:00
- source_sha256: `e9fe2cd9fd1962fc54383bc4f6bf4711a0363dd8eeaf782e90e183889bc1132b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T15:30+00:00, close=80469.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T15:00+00:00, close=80328.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025240|-8.48|105.53|-8.55|6370085|3.96|
|QNT_USDT|197.910000|-5.88|1.12|-5.95|90702343|0.51|
|AAVE_USDT|132.300000|-3.23|-10.13|-3.30|26636807|0.76|
|DOT_USDT|0.992800|-2.91|-13.42|-2.98|11332638|1.01|
|FILECOIN_USDT|0.900800|-2.16|-10.98|-2.23|5328800|1.11|
|HBAR_USDT|0.076000|-1.75|-7.16|-1.82|10037181|1.32|
|ICP_USDT|2.590000|-1.52|-9.21|-1.59|5104542|3.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.300000|130.180000|132.370000|1.03|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.992800|0.977000|0.992900|1.56|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900800|0.880500|0.900900|0.83|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076000|0.075280|0.076000|2.63|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.590000|2.552000|2.590000|0.50|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025240|0.024620|0.025240|1.02|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.910000|196.560000|198.140000|1.21|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T15:30:03+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=132.490000, depth_time=2026-10-27T15:30:14+00:00, book20_bid_proxy_usdt=285226, book20_ask_proxy_usdt=326732, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=26636807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T15:30:03+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=0.992400, depth_time=2026-10-27T15:30:17+00:00, book20_bid_proxy_usdt=505304, book20_ask_proxy_usdt=280737, funding_indicative=-0.000140, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=11332638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T15:30:04+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=0.895500, depth_time=2026-10-27T15:30:19+00:00, book20_bid_proxy_usdt=1098294, book20_ask_proxy_usdt=1337140, funding_indicative=0.000023, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=5328800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T15:30:03+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=0.076230, depth_time=2026-10-27T15:30:22+00:00, book20_bid_proxy_usdt=1022238, book20_ask_proxy_usdt=1232973, funding_indicative=0.000072, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=10037181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T15:30:04+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=2.586000, depth_time=2026-10-27T15:30:25+00:00, book20_bid_proxy_usdt=1136414, book20_ask_proxy_usdt=1138570, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=5104542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T15:30:03+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=0.025580, depth_time=2026-10-27T15:30:09+00:00, book20_bid_proxy_usdt=103296, book20_ask_proxy_usdt=95557, funding_indicative=-0.000727, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=1, 24h_change=-8.48%, turnover=6370085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T15:30:03+00:00, last15m_closed_end=2026-10-27T15:30+00:00, prior8high=200.970000, depth_time=2026-10-27T15:30:12+00:00, book20_bid_proxy_usdt=57640, book20_ask_proxy_usdt=63673, funding_indicative=-0.000200, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.88%, turnover=90702343. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
