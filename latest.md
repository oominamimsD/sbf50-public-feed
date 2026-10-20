# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T10:00:40Z**
- feed_generated_utc: 2026-10-20T10:00:42+00:00
- source_sha256: `47301af4332c799bd4a29dcd520b18e103a55ce8744504f68c37c04269c59e16`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T10:00+00:00, close=81450, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T10:00+00:00, close=81450, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.067312|-21.13|303.98|-20.58|9345068|3.12|
|BTW_USDT|1.660000|-13.22|-5.45|-12.67|33553505|3.62|
|Q_USDT|0.117322|-5.08|281.02|-4.53|6296379|2.39|
|SAND_USDT|0.056670|-4.85|-8.72|-4.30|5496763|1.76|
|NEAR_USDT|4.704000|-4.54|-15.22|-3.99|169107434|2.13|
|ARB_USDT|0.189460|-4.15|0.52|-3.60|95137385|0.53|
|ATOM_USDT|1.720000|-2.93|-5.90|-2.38|5190545|5.82|
|TAO_USDT|262.690000|-2.72|-8.24|-2.17|58381920|1.14|
|AVAX_USDT|9.427000|-2.69|-11.74|-2.14|140823716|1.06|
|UNI_USDT|7.127000|-2.20|-3.92|-1.65|10236249|1.40|
|PUMPFUN_USDT|0.004399|-1.85|-17.14|-1.30|29114098|2.27|
|FILECOIN_USDT|1.004800|-1.81|-13.55|-1.26|7209470|0.99|
|FARTCOIN_USDT|0.141160|-1.56|-14.02|-1.01|6128619|0.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067312|0.066550|0.067270|1.70|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189460|0.188850|0.189460|0.84|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.720000|1.714000|1.720000|2.30|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.427000|9.402000|9.427000|0.90|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.660000|1.486000|1.660000|1.66|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.141160|0.140730|0.141160|0.53|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.004800|1.000600|1.004800|1.91|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.704000|4.700000|4.704000|2.22|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004399|0.004402|0.004399|1.04|N|Y/N|N/N|Y|N|
|Q_USDT|0.117322|0.118441|0.117322|1.66|Y|Y/Y|N/N|Y|N|
|SAND_USDT|0.056670|0.056320|0.056670|0.28|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|262.690000|261.880000|262.690000|0.89|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.127000|7.099000|7.121000|3.05|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=0.077973, depth_time=2026-10-20T10:00:08+00:00, book20_bid_proxy_usdt=6684, book20_ask_proxy_usdt=4642, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.13%, turnover=9345068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=0.193280, depth_time=2026-10-20T10:00:19+00:00, book20_bid_proxy_usdt=76558, book20_ask_proxy_usdt=98727, funding_indicative=0.000084, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=95137385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T10:00:01+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=1.742000, depth_time=2026-10-20T10:00:22+00:00, book20_bid_proxy_usdt=1464668, book20_ask_proxy_usdt=1310660, funding_indicative=0.000089, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=5190545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=9.507000, depth_time=2026-10-20T10:00:28+00:00, book20_bid_proxy_usdt=1252798, book20_ask_proxy_usdt=1119016, funding_indicative=0.000003, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=140823716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=1.673600, depth_time=2026-10-20T10:00:11+00:00, book20_bid_proxy_usdt=18690, book20_ask_proxy_usdt=21698, funding_indicative=-0.004085, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.22%, turnover=33553505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-20T10:00:01+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=0.142190, depth_time=2026-10-20T10:00:38+00:00, book20_bid_proxy_usdt=55574, book20_ask_proxy_usdt=55937, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=6128619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-20T10:00:01+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=1.012000, depth_time=2026-10-20T10:00:36+00:00, book20_bid_proxy_usdt=464635, book20_ask_proxy_usdt=797385, funding_indicative=-0.000022, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=7209470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=4.792000, depth_time=2026-10-20T10:00:18+00:00, book20_bid_proxy_usdt=4012660, book20_ask_proxy_usdt=2850918, funding_indicative=0.000053, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.54%, turnover=169107434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=0.004464, depth_time=2026-10-20T10:00:32+00:00, book20_bid_proxy_usdt=1678310, book20_ask_proxy_usdt=1495291, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=29114098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=0.129136, depth_time=2026-10-20T10:00:13+00:00, book20_bid_proxy_usdt=16459, book20_ask_proxy_usdt=15695, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.08%, turnover=6296379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T10:00:01+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=0.056910, depth_time=2026-10-20T10:00:15+00:00, book20_bid_proxy_usdt=742129, book20_ask_proxy_usdt=1001733, funding_indicative=-0.001563, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.85%, turnover=5496763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T10:00:00+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=264.550000, depth_time=2026-10-20T10:00:25+00:00, book20_bid_proxy_usdt=80138, book20_ask_proxy_usdt=100000, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=58381920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T10:00:01+00:00, last15m_closed_end=2026-10-20T10:00+00:00, prior8high=7.187000, depth_time=2026-10-20T10:00:31+00:00, book20_bid_proxy_usdt=1635168, book20_ask_proxy_usdt=1835179, funding_indicative=0.000082, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=10236249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
