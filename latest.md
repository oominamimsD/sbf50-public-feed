# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T12:00:33Z**
- feed_generated_utc: 2026-10-20T12:00:36+00:00
- source_sha256: `a4dc3cda7146be76b314776ba2b0826c8f5a64692408d19bef9bc61ad157d37a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.067660|-22.26|306.07|-21.72|8707789|3.10|
|SAND_USDT|0.056660|-4.86|-8.74|-4.32|5288010|3.53|
|NEAR_USDT|4.669000|-4.79|-15.85|-4.25|163607006|2.14|
|ARB_USDT|0.189310|-3.23|0.44|-2.69|95266656|0.53|
|STRK_USDT|0.055540|-2.95|-38.74|-2.41|18071975|1.80|
|UNI_USDT|7.127000|-2.90|-3.92|-2.36|9592064|1.40|
|LTC_USDT|58.540000|-2.28|-7.02|-1.74|12897658|3.42|
|QNT_USDT|193.270000|-2.15|-15.37|-1.61|71515607|1.55|
|TAO_USDT|262.890000|-2.01|-8.17|-1.47|56310966|0.76|
|FARTCOIN_USDT|0.140550|-1.99|-14.39|-1.45|5673647|0.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067660|0.066520|0.067626|0.42|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.189310|0.188340|0.189360|0.26|N|Y/Y|Y/N|Y|N|
|FARTCOIN_USDT|0.140550|0.140370|0.140550|1.14|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.540000|58.250000|58.540000|1.77|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.669000|4.630000|4.670000|2.80|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.270000|191.990000|193.270000|1.25|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056660|0.056330|0.056660|1.19|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.055540|0.055610|0.055540|2.66|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|262.890000|261.790000|262.870000|0.52|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.127000|7.093000|7.127000|0.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=0.071607, depth_time=2026-10-20T12:00:09+00:00, book20_bid_proxy_usdt=7933, book20_ask_proxy_usdt=8530, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.26%, turnover=8707789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=0.190320, depth_time=2026-10-20T12:00:16+00:00, book20_bid_proxy_usdt=73699, book20_ask_proxy_usdt=99789, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=95266656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=0.141660, depth_time=2026-10-20T12:00:33+00:00, book20_bid_proxy_usdt=68092, book20_ask_proxy_usdt=68827, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=5673647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=59.150000, depth_time=2026-10-20T12:00:25+00:00, book20_bid_proxy_usdt=1301058, book20_ask_proxy_usdt=1637643, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=12897658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=4.712000, depth_time=2026-10-20T12:00:14+00:00, book20_bid_proxy_usdt=3730118, book20_ask_proxy_usdt=3813970, funding_indicative=0.000057, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.79%, turnover=163607006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=194.600000, depth_time=2026-10-20T12:00:26+00:00, book20_bid_proxy_usdt=53338, book20_ask_proxy_usdt=71481, funding_indicative=0.000052, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=71515607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=0.057080, depth_time=2026-10-20T12:00:09+00:00, book20_bid_proxy_usdt=731660, book20_ask_proxy_usdt=903846, funding_indicative=-0.001863, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.86%, turnover=5288010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=0.056500, depth_time=2026-10-20T12:00:20+00:00, book20_bid_proxy_usdt=542336, book20_ask_proxy_usdt=695916, funding_indicative=0.000020, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=18071975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=264.440000, depth_time=2026-10-20T12:00:30+00:00, book20_bid_proxy_usdt=94856, book20_ask_proxy_usdt=102372, funding_indicative=0.000034, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=56310966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T12:00:02+00:00, last15m_closed_end=2026-10-20T12:00+00:00, prior8high=7.169000, depth_time=2026-10-20T12:00:22+00:00, book20_bid_proxy_usdt=1014898, book20_ask_proxy_usdt=3661776, funding_indicative=0.000060, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=9592064. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
