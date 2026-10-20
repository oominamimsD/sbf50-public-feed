# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T09:00:33Z**
- feed_generated_utc: 2026-10-20T09:00:35+00:00
- source_sha256: `3955a53eeccf043af34b9531a5c8b90fca76f1637e68c0873fc4d6253085a6d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T09:00+00:00, close=81498.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T09:00+00:00, close=81498.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.511100|-21.00|-13.93|-20.49|32402136|4.64|
|AGT_USDT|0.069379|-18.71|316.39|-18.20|9351792|0.14|
|SAND_USDT|0.056700|-4.80|-8.68|-4.29|5749098|1.76|
|ARB_USDT|0.190060|-3.85|0.84|-3.34|95338043|1.58|
|NEAR_USDT|4.746000|-3.22|-14.47|-2.71|162117315|2.11|
|QNT_USDT|192.130000|-2.72|-15.87|-2.21|79585471|0.52|
|ATOM_USDT|1.725000|-2.65|-5.63|-2.14|5060646|5.79|
|TAO_USDT|263.090000|-2.58|-8.10|-2.07|57516440|1.14|
|UNI_USDT|7.140000|-2.03|-3.74|-1.52|10207634|1.40|
|SEI_USDT|0.059770|-1.88|-9.94|-1.37|6704721|1.67|
|Q_USDT|0.124000|-1.57|302.71|-1.06|6289749|0.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.069379|0.068168|0.069364|3.60|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.190060|0.189290|0.190060|1.01|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.725000|1.723000|1.725000|0.93|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.511100|1.489000|1.509600|1.82|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.746000|4.727000|4.747000|1.77|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.130000|189.730000|192.130000|0.47|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.124000|0.116790|0.124690|1.48|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056700|0.056480|0.056700|2.70|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059770|0.059640|0.059770|1.59|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.090000|262.690000|263.090000|2.45|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.140000|7.134000|7.143000|5.75|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=0.083943, depth_time=2026-10-20T09:00:11+00:00, book20_bid_proxy_usdt=9277, book20_ask_proxy_usdt=7192, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.71%, turnover=9351792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=0.198460, depth_time=2026-10-20T09:00:15+00:00, book20_bid_proxy_usdt=74687, book20_ask_proxy_usdt=74820, funding_indicative=0.000013, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=95338043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=1.756000, depth_time=2026-10-20T09:00:20+00:00, book20_bid_proxy_usdt=1248796, book20_ask_proxy_usdt=1436859, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=5060646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=1.727900, depth_time=2026-10-20T09:00:08+00:00, book20_bid_proxy_usdt=12726, book20_ask_proxy_usdt=10049, funding_indicative=-0.004668, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.00%, turnover=32402136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=4.806000, depth_time=2026-10-20T09:00:17+00:00, book20_bid_proxy_usdt=1272067, book20_ask_proxy_usdt=2925355, funding_indicative=0.000017, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=162117315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=194.060000, depth_time=2026-10-20T09:00:19+00:00, book20_bid_proxy_usdt=98150, book20_ask_proxy_usdt=81971, funding_indicative=0.000018, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=79585471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=0.122612, depth_time=2026-10-20T09:00:32+00:00, book20_bid_proxy_usdt=18490, book20_ask_proxy_usdt=19810, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=6289749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=0.057280, depth_time=2026-10-20T09:00:12+00:00, book20_bid_proxy_usdt=838531, book20_ask_proxy_usdt=949317, funding_indicative=-0.001439, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.80%, turnover=5749098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=0.060420, depth_time=2026-10-20T09:00:30+00:00, book20_bid_proxy_usdt=182210, book20_ask_proxy_usdt=226573, funding_indicative=0.000026, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=6704721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=266.060000, depth_time=2026-10-20T09:00:25+00:00, book20_bid_proxy_usdt=98413, book20_ask_proxy_usdt=64100, funding_indicative=0.000049, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=57516440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T09:00:02+00:00, last15m_closed_end=2026-10-20T09:00+00:00, prior8high=7.207000, depth_time=2026-10-20T09:00:27+00:00, book20_bid_proxy_usdt=1433169, book20_ask_proxy_usdt=2337755, funding_indicative=0.000063, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=10207634. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
