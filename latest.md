# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T13:00:35Z**
- feed_generated_utc: 2026-11-08T13:00:36+00:00
- source_sha256: `aea9dcd786f4a88046b8245ffc61862cf6dc87fb29c29c88a88d37c8ddb80339`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T13:00+00:00, close=75946.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T13:00+00:00, close=75946.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001894|-7.00|61.31|-7.29|24513439|0.53|
|TIA_USDT|0.422000|-4.43|-13.89|-4.72|6873003|2.37|
|ENA_USDT|0.153570|-4.16|-20.84|-4.45|29227173|0.65|
|WLD_USDT|0.326000|-2.86|-19.38|-3.15|22864191|3.07|
|ADA_USDT|0.180100|-1.36|-6.97|-1.65|9055979|5.55|
|IDOL_USDT|0.029921|-1.25|70.77|-1.54|15814438|2.00|
|LINK_USDT|10.723000|-1.11|-7.32|-1.40|61708892|1.86|
|AAVE_USDT|130.280000|-1.11|-3.85|-1.40|9309037|0.77|
|SUI_USDT|0.852000|-1.02|-5.54|-1.31|21794798|1.17|
|AVAX_USDT|8.174000|-0.95|-4.22|-1.24|8046463|1.22|
|LIT_USDT|3.215400|-0.77|10.16|-1.06|8004825|0.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.280000|129.980000|130.280000|1.36|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180100|0.179600|0.180100|0.36|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.174000|8.152000|8.174000|0.93|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153570|0.152500|0.153580|0.92|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.029921|0.027111|0.029921|0.71|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.723000|10.706000|10.723000|1.60|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.215400|3.212500|3.215400|1.12|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001894|0.001872|0.001894|0.23|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.852000|0.847200|0.852000|1.21|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.422000|0.421400|0.422000|1.62|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.326000|0.324800|0.325900|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=131.250000, depth_time=2026-11-08T13:00:23+00:00, book20_bid_proxy_usdt=720977, book20_ask_proxy_usdt=346976, funding_indicative=0.000067, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=9309037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.181000, depth_time=2026-11-08T13:00:19+00:00, book20_bid_proxy_usdt=9843441, book20_ask_proxy_usdt=8156253, funding_indicative=-0.000026, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=9055979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=8.207000, depth_time=2026-11-08T13:00:29+00:00, book20_bid_proxy_usdt=1641826, book20_ask_proxy_usdt=2141782, funding_indicative=0.000052, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=8046463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.155490, depth_time=2026-11-08T13:00:12+00:00, book20_bid_proxy_usdt=284385, book20_ask_proxy_usdt=208139, funding_indicative=-0.000024, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=29227173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.033952, depth_time=2026-11-08T13:00:21+00:00, book20_bid_proxy_usdt=4392, book20_ask_proxy_usdt=3359, funding_indicative=0.000748, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=15814438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=10.807000, depth_time=2026-11-08T13:00:21+00:00, book20_bid_proxy_usdt=1398250, book20_ask_proxy_usdt=577480, funding_indicative=0.000002, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=61708892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=3.312400, depth_time=2026-11-08T13:00:34+00:00, book20_bid_proxy_usdt=35706, book20_ask_proxy_usdt=19367, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.77%, turnover=8004825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.001986, depth_time=2026-11-08T13:00:08+00:00, book20_bid_proxy_usdt=9944, book20_ask_proxy_usdt=12364, funding_indicative=-0.000942, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.00%, turnover=24513439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.855800, depth_time=2026-11-08T13:00:28+00:00, book20_bid_proxy_usdt=1731162, book20_ask_proxy_usdt=1496539, funding_indicative=0.000044, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=21794798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.427700, depth_time=2026-11-08T13:00:09+00:00, book20_bid_proxy_usdt=391286, book20_ask_proxy_usdt=325159, funding_indicative=-0.000043, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=6873003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T13:00:03+00:00, last15m_closed_end=2026-11-08T13:00+00:00, prior8high=0.330100, depth_time=2026-11-08T13:00:15+00:00, book20_bid_proxy_usdt=4549140, book20_ask_proxy_usdt=3849304, funding_indicative=-0.000068, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=22864191. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
