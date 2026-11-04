# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T13:30:18Z**
- feed_generated_utc: 2026-11-04T13:30:20+00:00
- source_sha256: `0002a5608e6f46d7274e22b0e3238515716675429f8e4db73e3e50af5608d55a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T13:30+00:00, close=78428.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T13:00+00:00, close=78272, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.034150|-36.53|-28.13|-37.51|9534219|5.86|
|AKE_USDT|0.002998|-27.86|-85.80|-28.84|14359782|3.34|
|HOT_USDT|0.000473|-12.12|36.97|-13.10|6011002|2.11|
|TRUMPOFFICIAL_USDT|1.431000|-11.00|-15.22|-11.98|12725463|6.99|
|ZRO_USDT|1.853200|-2.16|9.93|-3.14|11550884|1.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.034150|0.032170|0.034150|1.75|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002998|0.002758|0.002998|1.40|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000473|0.000479|0.000473|0.70|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.431000|1.408000|1.431000|2.20|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.853200|1.841900|1.853200|1.69|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T13:30:00+00:00, last15m_closed_end=2026-11-04T13:30+00:00, prior8high=0.033790, depth_time=2026-11-04T13:30:07+00:00, book20_bid_proxy_usdt=37550, book20_ask_proxy_usdt=42503, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-36.53%, turnover=9534219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T13:30:00+00:00, last15m_closed_end=2026-11-04T13:30+00:00, prior8high=0.003257, depth_time=2026-11-04T13:30:10+00:00, book20_bid_proxy_usdt=30068, book20_ask_proxy_usdt=109642, funding_indicative=-0.000032, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-27.86%, turnover=14359782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T13:30:00+00:00, last15m_closed_end=2026-11-04T13:30+00:00, prior8high=0.000507, depth_time=2026-11-04T13:30:13+00:00, book20_bid_proxy_usdt=85923, book20_ask_proxy_usdt=73088, funding_indicative=-0.000124, next_funding_utc=2026-11-04T14:00:00+00:00, funding_cycle_h=1, 24h_change=-12.12%, turnover=6011002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T13:30:00+00:00, last15m_closed_end=2026-11-04T13:30+00:00, prior8high=1.490000, depth_time=2026-11-04T13:30:13+00:00, book20_bid_proxy_usdt=2444505, book20_ask_proxy_usdt=2517364, funding_indicative=-0.000351, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.00%, turnover=12725463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T13:30:00+00:00, last15m_closed_end=2026-11-04T13:30+00:00, prior8high=1.909000, depth_time=2026-11-04T13:30:17+00:00, book20_bid_proxy_usdt=33231, book20_ask_proxy_usdt=40506, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=11550884. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
