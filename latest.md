# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T16:00:25Z**
- feed_generated_utc: 2026-10-18T16:00:27+00:00
- source_sha256: `ad8883473d17ea7e31a110c377756c28ecb5cbebef8abd2a88ea19917de2faf6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.179400|-2.50|69.24|-2.59|12383879|5.57|
|AGT_USDT|0.067525|-2.43|281.82|-2.52|11059738|7.26|
|BTW_USDT|2.306000|-1.80|37.08|-1.89|27711368|0.43|
|BAT_USDT|0.175380|-1.58|5.24|-1.67|10903542|0.57|
|XPL_USDT|0.075940|-1.28|-14.91|-1.37|6322116|1.32|
|LTC_USDT|58.120000|-1.20|-9.89|-1.29|8994548|1.72|
|ZEC_USDT|1085.220000|-1.11|-13.72|-1.20|1250729531|0.09|
|PUMPFUN_USDT|0.004195|-0.99|-27.35|-1.08|27631043|2.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067525|0.062242|0.067529|0.92|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.175380|0.175250|0.175380|0.72|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|2.306000|2.292900|2.305400|1.26|N|Y/Y|N/N|Y|N|
|ICNT_USDT|0.179400|0.176300|0.179400|0.32|N|Y/Y|N/N|Y|N|
|LTC_USDT|58.120000|58.050000|58.120000|1.27|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004195|0.004146|0.004195|2.67|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.075940|0.075520|0.075940|3.06|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1085.220000|1076.100000|1085.220000|1.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=0.075811, depth_time=2026-10-18T16:00:10+00:00, book20_bid_proxy_usdt=6737, book20_ask_proxy_usdt=9350, funding_indicative=0.000238, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=11059738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=0.181050, depth_time=2026-10-18T16:00:15+00:00, book20_bid_proxy_usdt=25863, book20_ask_proxy_usdt=20172, funding_indicative=-0.000031, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=10903542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=2.424600, depth_time=2026-10-18T16:00:12+00:00, book20_bid_proxy_usdt=12214, book20_ask_proxy_usdt=15229, funding_indicative=-0.000265, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=27711368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=0.189500, depth_time=2026-10-18T16:00:08+00:00, book20_bid_proxy_usdt=171223, book20_ask_proxy_usdt=154501, funding_indicative=-0.000150, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=12383879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=59.830000, depth_time=2026-10-18T16:00:18+00:00, book20_bid_proxy_usdt=1146748, book20_ask_proxy_usdt=1217310, funding_indicative=0.000023, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=8994548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=0.004275, depth_time=2026-10-18T16:00:24+00:00, book20_bid_proxy_usdt=1637338, book20_ask_proxy_usdt=1427639, funding_indicative=0.000005, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=27631043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=0.077800, depth_time=2026-10-18T16:00:15+00:00, book20_bid_proxy_usdt=393514, book20_ask_proxy_usdt=446674, funding_indicative=0.000023, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=6322116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T16:00:01+00:00, last15m_closed_end=2026-10-18T16:00+00:00, prior8high=1119.150000, depth_time=2026-10-18T16:00:21+00:00, book20_bid_proxy_usdt=197422, book20_ask_proxy_usdt=576188, funding_indicative=0.000084, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=1250729531. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
