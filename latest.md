# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T06:30:21Z**
- feed_generated_utc: 2026-10-21T06:30:24+00:00
- source_sha256: `1db9d4b098d2be5b4b2cc0c69b6954468560374aca2f9018183c16d1e3b45e78`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T06:30+00:00, close=82687.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T06:00+00:00, close=82635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.047861|-25.94|195.85|-26.06|6503545|7.09|
|BAT_USDT|0.182950|-15.21|3.14|-15.33|10899408|1.09|
|BR_USDT|0.588830|-9.50|35.98|-9.62|33364072|0.17|
|XMR_USDT|579.310000|-6.59|9.73|-6.71|21207845|0.52|
|PHA_USDT|0.056880|-1.62|3.36|-1.74|6787352|1.76|
|SILVER_USDT|57.320000|-1.08|-3.48|-1.20|225789001|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.047861|0.054922|0.047608|7.44|Y|Y/Y|Y/Y|N|Y|
|BAT_USDT|0.182950|0.182340|0.182950|1.27|N|Y/Y|Y/N|N|N|
|BR_USDT|0.588830|0.580080|0.588830|0.48|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056880|0.055950|0.056880|0.26|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.320000|57.320000|57.320000|1.47|N|Y/Y|Y/N|N|N|
|XMR_USDT|579.310000|575.320000|579.310000|0.41|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T06:30:00+00:00, last15m_closed_end=2026-10-21T06:30+00:00, prior8high=0.063305, depth_time=2026-10-21T06:30:09+00:00, book20_bid_proxy_usdt=4122, book20_ask_proxy_usdt=7533, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-25.94%, turnover=6503545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T06:30:00+00:00, last15m_closed_end=2026-10-21T06:30+00:00, prior8high=0.187220, depth_time=2026-10-21T06:30:10+00:00, book20_bid_proxy_usdt=27974, book20_ask_proxy_usdt=22951, funding_indicative=-0.000110, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-15.21%, turnover=10899408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T06:30:00+00:00, last15m_closed_end=2026-10-21T06:30+00:00, prior8high=0.621040, depth_time=2026-10-21T06:30:13+00:00, book20_bid_proxy_usdt=4283, book20_ask_proxy_usdt=16721, funding_indicative=0.000045, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.50%, turnover=33364072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T06:30:00+00:00, last15m_closed_end=2026-10-21T06:30+00:00, prior8high=0.057320, depth_time=2026-10-21T06:30:17+00:00, book20_bid_proxy_usdt=82435, book20_ask_proxy_usdt=74942, funding_indicative=-0.000020, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=6787352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T06:30:00+00:00, last15m_closed_end=2026-10-21T06:30+00:00, prior8high=57.780000, depth_time=2026-10-21T06:30:20+00:00, book20_bid_proxy_usdt=41021729, book20_ask_proxy_usdt=44078542, funding_indicative=0.000036, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=225789001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T06:30:00+00:00, last15m_closed_end=2026-10-21T06:30+00:00, prior8high=581.680000, depth_time=2026-10-21T06:30:15+00:00, book20_bid_proxy_usdt=19290, book20_ask_proxy_usdt=7171, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.59%, turnover=21207845. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
