# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T10:45:22Z**
- feed_generated_utc: 2026-10-21T10:45:24+00:00
- source_sha256: `022fec0d7e98c6833c32f98f36f6b906d75479819fcf0f1bb5c0af77c2681820`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T10:45+00:00, close=83450.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T10:00+00:00, close=83402.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.047763|-26.09|195.25|-27.14|6801405|0.84|
|BAT_USDT|0.182860|-15.25|3.08|-16.30|11101259|0.55|
|BR_USDT|0.582760|-10.43|34.58|-11.48|25216256|2.92|
|BTW_USDT|1.735500|-6.16|-11.11|-7.21|26450055|2.30|
|Q_USDT|0.118850|-3.18|188.98|-4.23|5735990|0.42|
|TIA_USDT|0.622500|-0.03|7.82|-1.08|47183781|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.047763|0.042549|0.047763|0.74|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.182860|0.181440|0.182860|0.27|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.582760|0.566870|0.582820|0.65|N|Y/Y|N/N|N|N|
|BTW_USDT|1.735500|1.665600|1.736600|1.97|N|N/N|N/N|N|N|
|Q_USDT|0.118850|0.117558|0.118856|0.74|N|Y/Y|N/N|N|N|
|TIA_USDT|0.622500|0.614700|0.622500|2.73|N|Y/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T10:45:01+00:00, last15m_closed_end=2026-10-21T10:45+00:00, prior8high=0.051865, depth_time=2026-10-21T10:45:09+00:00, book20_bid_proxy_usdt=8297, book20_ask_proxy_usdt=5248, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-26.09%, turnover=6801405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T10:45:01+00:00, last15m_closed_end=2026-10-21T10:45+00:00, prior8high=0.186870, depth_time=2026-10-21T10:45:12+00:00, book20_bid_proxy_usdt=26167, book20_ask_proxy_usdt=21214, funding_indicative=-0.000120, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.25%, turnover=11101259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T10:45:01+00:00, last15m_closed_end=2026-10-21T10:45+00:00, prior8high=0.627970, depth_time=2026-10-21T10:45:14+00:00, book20_bid_proxy_usdt=3568, book20_ask_proxy_usdt=2275, funding_indicative=-0.000058, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.43%, turnover=25216256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T10:45:01+00:00, last15m_closed_end=2026-10-21T10:45+00:00, prior8high=2.145300, depth_time=2026-10-21T10:45:17+00:00, book20_bid_proxy_usdt=9024, book20_ask_proxy_usdt=10950, funding_indicative=-0.001831, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.16%, turnover=26450055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T10:45:01+00:00, last15m_closed_end=2026-10-21T10:45+00:00, prior8high=0.125729, depth_time=2026-10-21T10:45:18+00:00, book20_bid_proxy_usdt=14088, book20_ask_proxy_usdt=27127, funding_indicative=0.000015, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=5735990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T10:45:01+00:00, last15m_closed_end=2026-10-21T10:45+00:00, prior8high=0.635900, depth_time=2026-10-21T10:45:21+00:00, book20_bid_proxy_usdt=246881, book20_ask_proxy_usdt=246140, funding_indicative=-0.000097, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.03%, turnover=47183781. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
