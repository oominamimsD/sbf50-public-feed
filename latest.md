# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T11:00:20Z**
- feed_generated_utc: 2026-10-19T11:00:21+00:00
- source_sha256: `16ff286500732a5ce7a681c67b9a520b5340eba1123ac46d4e0f57486d1ccbd3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T11:00+00:00, close=82379.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T11:00+00:00, close=82379.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.134400|-9.10|26.88|-10.63|20593524|0.47|
|HBAR_USDT|0.083330|-4.54|-11.14|-6.07|43203854|1.20|
|SAND_USDT|0.058070|-3.58|-12.59|-5.11|15097742|1.72|
|STRK_USDT|0.058700|-3.48|-50.78|-5.01|17748607|1.71|
|TIA_USDT|0.611200|-1.08|3.82|-2.61|50819969|3.27|
|SEI_USDT|0.059900|-0.21|-15.50|-1.74|8785693|1.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.134400|2.104100|2.134400|0.83|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.083330|0.083140|0.083330|3.09|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.058070|0.057570|0.058070|0.10|N|Y/Y|N/N|N|N|
|SEI_USDT|0.059900|0.059590|0.059900|3.84|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058700|0.057600|0.058670|2.18|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.611200|0.602400|0.611200|0.75|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T11:00:01+00:00, last15m_closed_end=2026-10-19T11:00+00:00, prior8high=2.310800, depth_time=2026-10-19T11:00:07+00:00, book20_bid_proxy_usdt=8533, book20_ask_proxy_usdt=6405, funding_indicative=-0.000580, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.10%, turnover=20593524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T11:00:01+00:00, last15m_closed_end=2026-10-19T11:00+00:00, prior8high=0.084860, depth_time=2026-10-19T11:00:10+00:00, book20_bid_proxy_usdt=633636, book20_ask_proxy_usdt=731619, funding_indicative=-0.000023, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.54%, turnover=43203854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T11:00:01+00:00, last15m_closed_end=2026-10-19T11:00+00:00, prior8high=0.059280, depth_time=2026-10-19T11:00:11+00:00, book20_bid_proxy_usdt=356138, book20_ask_proxy_usdt=704372, funding_indicative=-0.003099, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=15097742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T11:00:01+00:00, last15m_closed_end=2026-10-19T11:00+00:00, prior8high=0.061400, depth_time=2026-10-19T11:00:19+00:00, book20_bid_proxy_usdt=186741, book20_ask_proxy_usdt=274669, funding_indicative=0.000027, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.21%, turnover=8785693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T11:00:01+00:00, last15m_closed_end=2026-10-19T11:00+00:00, prior8high=0.060310, depth_time=2026-10-19T11:00:14+00:00, book20_bid_proxy_usdt=598392, book20_ask_proxy_usdt=570053, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=17748607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T11:00:01+00:00, last15m_closed_end=2026-10-19T11:00+00:00, prior8high=0.614100, depth_time=2026-10-19T11:00:17+00:00, book20_bid_proxy_usdt=206089, book20_ask_proxy_usdt=180359, funding_indicative=0.000002, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=50819969. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
