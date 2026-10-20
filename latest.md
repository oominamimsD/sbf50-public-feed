# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T19:30:27Z**
- feed_generated_utc: 2026-10-20T19:30:30+00:00
- source_sha256: `2a3ee31ac714f17e904c96e1549f99affac1bd3b6938b4ce3297c6ee33fdd1ff`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T19:30+00:00, close=82399.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T19:00+00:00, close=82503.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.689500|-8.65|-13.46|-8.43|30822037|1.77|
|AGT_USDT|0.059042|-8.64|264.97|-8.42|7437272|3.73|
|FILECOIN_USDT|1.021100|-1.81|-9.88|-1.59|6571227|0.98|
|AKE_USDT|0.030534|-1.79|21.80|-1.57|6546511|0.33|
|SEI_USDT|0.060650|-1.59|-2.75|-1.37|6309921|4.95|
|FET_USDT|0.192300|-1.43|-9.29|-1.21|11747639|5.20|
|INJ_USDT|8.491000|-1.26|8.34|-1.04|43480050|1.18|
|DASH_USDT|49.310000|-1.26|-0.70|-1.04|9966713|2.03|
|AAVE_USDT|150.160000|-1.25|-5.45|-1.03|84355071|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|150.160000|150.910000|150.150000|0.93|N|N/N|N/Y|N|N|
|AGT_USDT|0.059042|0.061234|0.058864|3.03|Y|Y/Y|Y/Y|N|Y|
|AKE_USDT|0.030534|0.030637|0.030534|0.37|N|Y/N|N/N|N|N|
|BTW_USDT|1.689500|1.665000|1.689500|0.85|N|Y/Y|Y/Y|N|N|
|DASH_USDT|49.310000|49.530000|49.310000|0.66|N|Y/N|N/N|N|N|
|FET_USDT|0.192300|0.193200|0.192400|0.41|N|N/N|N/Y|N|N|
|FILECOIN_USDT|1.021100|1.026500|1.021100|1.53|Y|N/N|Y/Y|N|N|
|INJ_USDT|8.491000|8.489000|8.494000|0.88|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060650|0.060930|0.060620|0.91|N|N/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=153.580000, depth_time=2026-10-20T19:30:26+00:00, book20_bid_proxy_usdt=320196, book20_ask_proxy_usdt=431425, funding_indicative=-0.000036, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=84355071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AGT_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=0.063379, depth_time=2026-10-20T19:30:09+00:00, book20_bid_proxy_usdt=11965, book20_ask_proxy_usdt=19435, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.64%, turnover=7437272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=0.031294, depth_time=2026-10-20T19:30:15+00:00, book20_bid_proxy_usdt=17689, book20_ask_proxy_usdt=10634, funding_indicative=0.000050, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=6546511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=1.812200, depth_time=2026-10-20T19:30:07+00:00, book20_bid_proxy_usdt=12517, book20_ask_proxy_usdt=9484, funding_indicative=-0.002419, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.65%, turnover=30822037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=50.090000, depth_time=2026-10-20T19:30:23+00:00, book20_bid_proxy_usdt=971981, book20_ask_proxy_usdt=731440, funding_indicative=-0.000091, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=9966713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=0.196300, depth_time=2026-10-20T19:30:19+00:00, book20_bid_proxy_usdt=1543504, book20_ask_proxy_usdt=1350051, funding_indicative=-0.000220, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=11747639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=1.041600, depth_time=2026-10-20T19:30:12+00:00, book20_bid_proxy_usdt=719967, book20_ask_proxy_usdt=686624, funding_indicative=0.000055, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=6571227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=8.590000, depth_time=2026-10-20T19:30:21+00:00, book20_bid_proxy_usdt=234594, book20_ask_proxy_usdt=169672, funding_indicative=0.000093, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=43480050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T19:30:02+00:00, last15m_closed_end=2026-10-20T19:30+00:00, prior8high=0.061830, depth_time=2026-10-20T19:30:15+00:00, book20_bid_proxy_usdt=378809, book20_ask_proxy_usdt=173305, funding_indicative=0.000035, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=6309921. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
