# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T18:30:15Z**
- feed_generated_utc: 2026-10-31T18:30:17+00:00
- source_sha256: `bb4f3ba67df7349b66ac5f87988c22aeaf434c109e298f6326a2703f30808276`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T18:30+00:00, close=77690.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T18:00+00:00, close=77664.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRX_USDT|0.307500|-1.54|-6.51|-1.70|7407434|0.33|
|WLD_USDT|0.400300|-1.01|-13.35|-1.17|38369908|2.50|
|BTW_USDT|1.111100|-0.96|-36.19|-1.12|7301009|0.90|
|DASH_USDT|48.160000|-0.94|-2.70|-1.10|5404955|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.111100|1.083700|1.111100|0.57|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.160000|48.050000|48.160000|1.02|N|Y/N|Y/Y|Y|N|
|TRX_USDT|0.307500|0.306760|0.307500|8.00|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.400300|0.397400|0.400300|0.59|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T18:30:01+00:00, last15m_closed_end=2026-10-31T18:30+00:00, prior8high=1.127400, depth_time=2026-10-31T18:30:09+00:00, book20_bid_proxy_usdt=13698, book20_ask_proxy_usdt=9146, funding_indicative=-0.000316, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=7301009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T18:30:01+00:00, last15m_closed_end=2026-10-31T18:30+00:00, prior8high=48.980000, depth_time=2026-10-31T18:30:10+00:00, book20_bid_proxy_usdt=804139, book20_ask_proxy_usdt=628574, funding_indicative=0.000029, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=5404955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T18:30:01+00:00, last15m_closed_end=2026-10-31T18:30+00:00, prior8high=0.312340, depth_time=2026-10-31T18:30:07+00:00, book20_bid_proxy_usdt=84258, book20_ask_proxy_usdt=51419, funding_indicative=-0.000537, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=7407434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T18:30:01+00:00, last15m_closed_end=2026-10-31T18:30+00:00, prior8high=0.403200, depth_time=2026-10-31T18:30:09+00:00, book20_bid_proxy_usdt=2315249, book20_ask_proxy_usdt=2798322, funding_indicative=0.000011, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=38369908. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
