# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T07:45:21Z**
- feed_generated_utc: 2026-10-14T07:45:23+00:00
- source_sha256: `484f3c9712588efe53c113f084065e62ed0c16732c420e7b3a6eaf6c91ded753`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T07:45+00:00, close=83413.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T07:00+00:00, close=83400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGIC_USDT|0.112430|-5.24|65.04|-5.26|5464445|3.56|
|STRK_USDT|0.082440|-5.16|57.96|-5.18|31261349|1.22|
|TIA_USDT|0.557500|-3.42|17.04|-3.44|42558772|1.79|
|W_USDT|0.016315|-2.90|12.42|-2.92|6889176|0.61|
|UNI_USDT|7.375000|-2.60|-14.88|-2.62|19454648|1.36|
|SILVER_USDT|58.760000|-1.06|-4.25|-1.08|253545157|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.112430|0.110660|0.112430|1.11|N|Y/Y|Y/N|N|N|
|SILVER_USDT|58.760000|58.510000|58.760000|0.62|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.082440|0.080270|0.082440|1.51|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.557500|0.547400|0.557400|1.01|N|Y/Y|N/N|N|N|
|UNI_USDT|7.375000|7.259000|7.375000|0.57|N|Y/Y|Y/N|N|N|
|W_USDT|0.016315|0.015869|0.016315|0.35|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T07:45:00+00:00, last15m_closed_end=2026-10-14T07:45+00:00, prior8high=0.115340, depth_time=2026-10-14T07:45:07+00:00, book20_bid_proxy_usdt=177122, book20_ask_proxy_usdt=179542, funding_indicative=-0.000006, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=5464445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T07:45:00+00:00, last15m_closed_end=2026-10-14T07:45+00:00, prior8high=59.330000, depth_time=2026-10-14T07:45:20+00:00, book20_bid_proxy_usdt=55786547, book20_ask_proxy_usdt=35965381, funding_indicative=0.000078, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=253545157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T07:45:00+00:00, last15m_closed_end=2026-10-14T07:45+00:00, prior8high=0.083840, depth_time=2026-10-14T07:45:12+00:00, book20_bid_proxy_usdt=306399, book20_ask_proxy_usdt=350491, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=31261349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T07:45:00+00:00, last15m_closed_end=2026-10-14T07:45+00:00, prior8high=0.571500, depth_time=2026-10-14T07:45:14+00:00, book20_bid_proxy_usdt=124164, book20_ask_proxy_usdt=179338, funding_indicative=0.000023, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=42558772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T07:45:00+00:00, last15m_closed_end=2026-10-14T07:45+00:00, prior8high=7.420000, depth_time=2026-10-14T07:45:18+00:00, book20_bid_proxy_usdt=1517496, book20_ask_proxy_usdt=1523620, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=19454648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T07:45:00+00:00, last15m_closed_end=2026-10-14T07:45+00:00, prior8high=0.016445, depth_time=2026-10-14T07:45:11+00:00, book20_bid_proxy_usdt=31245, book20_ask_proxy_usdt=20586, funding_indicative=-0.000216, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=6889176. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
