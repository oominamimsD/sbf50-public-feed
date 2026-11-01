# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T01:00:28Z**
- feed_generated_utc: 2026-11-01T01:00:30+00:00
- source_sha256: `e45475f144026d5262ff8fcf8278688a03eb66780ff70ede28b5cc19e054cc6a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T01:00+00:00, close=77641.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T01:00+00:00, close=77641.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.237760|-20.56|41.59|-20.89|29174924|4.20|
|BLESS_USDT|0.009561|-10.32|17.84|-10.65|7643648|2.09|
|IDOL_USDT|0.018395|-7.76|132.84|-8.09|5390433|0.54|
|BTW_USDT|1.057900|-7.31|-39.24|-7.64|5326367|0.94|
|Q_USDT|0.031090|-5.98|-60.61|-6.31|9834541|3.21|
|TRX_USDT|0.306520|-2.77|-6.81|-3.10|10860833|0.33|
|ZEC_USDT|1255.000000|-1.74|9.58|-2.07|995942893|0.64|
|ENA_USDT|0.188700|-1.53|1.02|-1.86|43814435|0.53|
|FET_USDT|0.160100|-1.23|-7.08|-1.56|5393599|6.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009561|0.009300|0.009561|0.61|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.057900|1.049300|1.057900|0.74|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188700|0.187820|0.188700|0.44|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160100|0.159200|0.160100|0.07|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.018395|0.016831|0.018395|1.09|N|Y/Y|N/N|Y|N|
|LSK_USDT|0.237760|0.241380|0.237760|1.72|Y|Y/Y|N/N|Y|N|
|Q_USDT|0.031090|0.030800|0.031090|0.46|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.306520|0.300760|0.306520|3.19|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1255.000000|1243.100000|1254.960000|0.72|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.009626, depth_time=2026-11-01T01:00:10+00:00, book20_bid_proxy_usdt=13988, book20_ask_proxy_usdt=11382, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.32%, turnover=7643648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=1.111500, depth_time=2026-11-01T01:00:15+00:00, book20_bid_proxy_usdt=15345, book20_ask_proxy_usdt=20568, funding_indicative=-0.000416, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.31%, turnover=5326367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.189790, depth_time=2026-11-01T01:00:25+00:00, book20_bid_proxy_usdt=237770, book20_ask_proxy_usdt=135420, funding_indicative=0.000026, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=43814435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.160100, depth_time=2026-11-01T01:00:26+00:00, book20_bid_proxy_usdt=1401807, book20_ask_proxy_usdt=838368, funding_indicative=-0.000142, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=5393599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.018859, depth_time=2026-11-01T01:00:12+00:00, book20_bid_proxy_usdt=5361, book20_ask_proxy_usdt=3506, funding_indicative=0.000154, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.76%, turnover=5390433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.253830, depth_time=2026-11-01T01:00:08+00:00, book20_bid_proxy_usdt=3834, book20_ask_proxy_usdt=10964, funding_indicative=-0.001677, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-20.56%, turnover=29174924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.031740, depth_time=2026-11-01T01:00:17+00:00, book20_bid_proxy_usdt=69036, book20_ask_proxy_usdt=54740, funding_indicative=-0.000957, next_funding_utc=2026-11-01T02:00:00+00:00, funding_cycle_h=1, 24h_change=-5.98%, turnover=9834541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=0.308350, depth_time=2026-11-01T01:00:19+00:00, book20_bid_proxy_usdt=46613, book20_ask_proxy_usdt=69822, funding_indicative=-0.001788, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=10860833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T01:00:00+00:00, last15m_closed_end=2026-11-01T01:00+00:00, prior8high=1271.840000, depth_time=2026-11-01T01:00:22+00:00, book20_bid_proxy_usdt=516657, book20_ask_proxy_usdt=388417, funding_indicative=-0.000076, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=995942893. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
