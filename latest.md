# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T02:15:28Z**
- feed_generated_utc: 2026-11-01T02:15:31+00:00
- source_sha256: `e31895872d661d7cc19cbae682a3b56736eb1c372fa2d33d1d62547ac36451c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T02:15+00:00, close=77710.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T02:00+00:00, close=77680, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.232660|-21.44|38.55|-21.63|29498061|1.72|
|BLESS_USDT|0.009318|-11.79|14.85|-11.98|7465348|2.15|
|ENA_USDT|0.188020|-3.08|0.65|-3.27|44081428|0.53|
|ZEC_USDT|1253.670000|-2.40|9.47|-2.59|980332798|0.08|
|BTW_USDT|1.096600|-2.25|-37.02|-2.44|5455169|4.56|
|XLM_USDT|0.168890|-1.65|0.28|-1.84|20130280|0.59|
|FET_USDT|0.160700|-1.59|-6.73|-1.78|5326443|6.22|
|FARTCOIN_USDT|0.120070|-1.57|-1.56|-1.76|6158185|0.83|
|TRX_USDT|0.309020|-1.05|-6.05|-1.24|11095224|0.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009318|0.009355|0.009311|1.25|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.096600|1.049300|1.096600|1.38|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188020|0.187870|0.187990|0.79|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120070|0.119930|0.120070|0.90|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160700|0.159300|0.160700|0.50|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.232660|0.231920|0.232270|0.63|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.309020|0.301240|0.309020|1.55|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168890|0.168450|0.168880|1.20|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1253.670000|1248.040000|1253.810000|1.18|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.009626, depth_time=2026-11-01T02:15:10+00:00, book20_bid_proxy_usdt=9380, book20_ask_proxy_usdt=14168, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.79%, turnover=7465348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=1.108100, depth_time=2026-11-01T02:15:18+00:00, book20_bid_proxy_usdt=12500, book20_ask_proxy_usdt=18235, funding_indicative=-0.000375, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=5455169. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.190060, depth_time=2026-11-01T02:15:13+00:00, book20_bid_proxy_usdt=280397, book20_ask_proxy_usdt=132339, funding_indicative=0.000048, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=44081428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.120850, depth_time=2026-11-01T02:15:25+00:00, book20_bid_proxy_usdt=129359, book20_ask_proxy_usdt=88355, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=6158185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.161600, depth_time=2026-11-01T02:15:21+00:00, book20_bid_proxy_usdt=1245956, book20_ask_proxy_usdt=850819, funding_indicative=-0.000243, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=5326443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.253830, depth_time=2026-11-01T02:15:08+00:00, book20_bid_proxy_usdt=8501, book20_ask_proxy_usdt=7673, funding_indicative=-0.001389, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.44%, turnover=29498061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.309890, depth_time=2026-11-01T02:15:27+00:00, book20_bid_proxy_usdt=100106, book20_ask_proxy_usdt=71168, funding_indicative=-0.001684, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=11095224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=0.169810, depth_time=2026-11-01T02:15:21+00:00, book20_bid_proxy_usdt=179485, book20_ask_proxy_usdt=204729, funding_indicative=-0.000031, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=20130280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T02:15:03+00:00, last15m_closed_end=2026-11-01T02:15+00:00, prior8high=1263.460000, depth_time=2026-11-01T02:15:15+00:00, book20_bid_proxy_usdt=287923, book20_ask_proxy_usdt=864648, funding_indicative=-0.000106, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=980332798. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
