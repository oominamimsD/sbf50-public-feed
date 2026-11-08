# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T15:15:31Z**
- feed_generated_utc: 2026-11-08T15:15:32+00:00
- source_sha256: `4bcadfd8d8115631b2d59b3b60a96ddab39eb5a460dd5e34c54fc3307bffd503`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T15:15+00:00, close=75993.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T15:00+00:00, close=76006.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030888|-7.23|76.29|-7.58|15257859|2.91|
|ONE_USDT|0.001934|-5.03|64.72|-5.38|22131628|0.52|
|TIA_USDT|0.420900|-4.68|-14.11|-5.03|7021606|2.38|
|WLD_USDT|0.326300|-2.77|-19.31|-3.12|24373443|3.06|
|AAVE_USDT|129.230000|-2.26|-4.63|-2.61|9398849|0.77|
|ENA_USDT|0.154680|-2.21|-20.27|-2.56|24458825|0.65|
|LINK_USDT|10.715000|-1.18|-7.39|-1.53|58777533|0.93|
|SUI_USDT|0.849700|-0.86|-5.79|-1.21|24393537|1.18|
|ADA_USDT|0.180300|-0.71|-6.86|-1.06|11620578|5.54|
|ONDO_USDT|0.360700|-0.66|-12.53|-1.01|7203090|2.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.230000|128.470000|129.210000|0.37|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180300|0.179300|0.180300|5.46|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154680|0.152750|0.154600|1.13|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030888|0.029746|0.030888|0.68|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.715000|10.691000|10.716000|1.59|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360700|0.358800|0.360700|0.79|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001934|0.001818|0.001931|1.72|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.849700|0.845000|0.849900|1.29|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.420900|0.419200|0.420900|0.18|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.326300|0.323500|0.326300|0.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=131.400000, depth_time=2026-11-08T15:15:17+00:00, book20_bid_proxy_usdt=497215, book20_ask_proxy_usdt=527314, funding_indicative=0.000073, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=9398849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.181200, depth_time=2026-11-08T15:15:27+00:00, book20_bid_proxy_usdt=10393052, book20_ask_proxy_usdt=8208680, funding_indicative=-0.000012, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=11620578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.155690, depth_time=2026-11-08T15:15:20+00:00, book20_bid_proxy_usdt=204269, book20_ask_proxy_usdt=296046, funding_indicative=-0.000044, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=24458825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.031239, depth_time=2026-11-08T15:15:07+00:00, book20_bid_proxy_usdt=4567, book20_ask_proxy_usdt=4668, funding_indicative=0.001015, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.23%, turnover=15257859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=10.788000, depth_time=2026-11-08T15:15:19+00:00, book20_bid_proxy_usdt=451812, book20_ask_proxy_usdt=625285, funding_indicative=0.000011, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=58777533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.365700, depth_time=2026-11-08T15:15:28+00:00, book20_bid_proxy_usdt=2200412, book20_ask_proxy_usdt=2375705, funding_indicative=0.000038, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.66%, turnover=7203090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.001915, depth_time=2026-11-08T15:15:09+00:00, book20_bid_proxy_usdt=10113, book20_ask_proxy_usdt=10593, funding_indicative=-0.001098, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=22131628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.859000, depth_time=2026-11-08T15:15:23+00:00, book20_bid_proxy_usdt=1650086, book20_ask_proxy_usdt=1785456, funding_indicative=0.000042, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=24393537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.425000, depth_time=2026-11-08T15:15:11+00:00, book20_bid_proxy_usdt=300754, book20_ask_proxy_usdt=380905, funding_indicative=0.000026, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=7021606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T15:15:02+00:00, last15m_closed_end=2026-11-08T15:15+00:00, prior8high=0.328300, depth_time=2026-11-08T15:15:12+00:00, book20_bid_proxy_usdt=3918020, book20_ask_proxy_usdt=3882275, funding_indicative=-0.000062, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=24373443. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
