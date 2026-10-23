# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T05:15:24Z**
- feed_generated_utc: 2026-10-23T05:15:26+00:00
- source_sha256: `69cbef35fb405f6cbcc31b1b7850ff48a09af0332955e8e3862610cc0af753d3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T05:15+00:00, close=81820.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T05:00+00:00, close=81561.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004167|-9.57|109.92|-9.78|8871979|9.62|
|LIT_USDT|3.469700|-3.99|12.23|-4.20|10414149|0.29|
|STRK_USDT|0.052870|-2.74|-45.13|-2.95|11429653|1.89|
|SILVER_USDT|54.210000|-1.90|-5.12|-2.11|356786453|1.84|
|TIA_USDT|0.561300|-1.24|-6.83|-1.45|23208149|1.78|
|XAU_USDT|4024.020000|-0.87|-3.17|-1.08|731208660|0.03|
|XAUT_USDT|4022.110000|-0.79|-2.96|-1.00|283075182|0.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004167|0.004168|0.004167|2.20|Y|Y/Y|N/N|Y|N|
|LIT_USDT|3.469700|3.428400|3.469700|0.26|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.210000|53.720000|54.210000|0.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052870|0.052780|0.052870|0.41|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.561300|0.557400|0.561300|1.54|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4022.110000|4008.190000|4022.000000|0.73|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4024.020000|4010.840000|4024.020000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T05:14:59+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=0.004422, depth_time=2026-10-23T05:15:08+00:00, book20_bid_proxy_usdt=26512, book20_ask_proxy_usdt=42946, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.57%, turnover=8871979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T05:15:00+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=3.531100, depth_time=2026-10-23T05:15:11+00:00, book20_bid_proxy_usdt=17060, book20_ask_proxy_usdt=21151, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=10414149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T05:14:59+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=54.190000, depth_time=2026-10-23T05:15:15+00:00, book20_bid_proxy_usdt=32377612, book20_ask_proxy_usdt=35116300, funding_indicative=0.000146, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=356786453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T05:14:59+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=0.053370, depth_time=2026-10-23T05:15:13+00:00, book20_bid_proxy_usdt=451476, book20_ask_proxy_usdt=589158, funding_indicative=0.000015, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=11429653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T05:14:59+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=0.565900, depth_time=2026-10-23T05:15:18+00:00, book20_bid_proxy_usdt=415965, book20_ask_proxy_usdt=381548, funding_indicative=0.000023, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=23208149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T05:14:59+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=4026.540000, depth_time=2026-10-23T05:15:23+00:00, book20_bid_proxy_usdt=100465, book20_ask_proxy_usdt=121441, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=283075182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T05:14:59+00:00, last15m_closed_end=2026-10-23T05:15+00:00, prior8high=4028.080000, depth_time=2026-10-23T05:15:20+00:00, book20_bid_proxy_usdt=1588493, book20_ask_proxy_usdt=3163724, funding_indicative=0.000097, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=731208660. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
