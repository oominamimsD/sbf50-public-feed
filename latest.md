# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T00:30:30Z**
- feed_generated_utc: 2026-11-05T00:30:33+00:00
- source_sha256: `b5f7c56c1c3f73cf6c2da6c17890e0d986e1feb7aacead9028130429137d7b20`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T00:30+00:00, close=80670.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002414|-14.09|-87.98|-14.58|16502995|4.14|
|TRUMPOFFICIAL_USDT|1.274000|-10.53|-25.45|-11.02|27611688|7.85|
|VVV_USDT|21.062000|-9.03|-11.56|-9.52|5178937|0.47|
|BTW_USDT|1.017300|-7.43|-41.46|-7.92|6123490|0.98|
|EVAA_USDT|1.527600|-6.72|2.86|-7.21|5047459|3.93|
|PUMPFUN_USDT|0.004274|-3.95|1.59|-4.44|17616627|2.34|
|OP_USDT|0.109770|-3.87|-1.17|-4.36|11324748|0.91|
|CLANKER_USDT|18.110000|-2.68|35.55|-3.17|19986143|5.53|
|ZRO_USDT|1.818100|-2.49|6.19|-2.98|11091288|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002414|0.002379|0.002415|0.58|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.017300|1.025200|1.017300|1.90|Y|Y/Y|Y/N|N|N|
|CLANKER_USDT|18.110000|17.160000|18.120000|0.42|N|Y/N|N/N|N|N|
|EVAA_USDT|1.527600|1.535200|1.527600|0.48|N|Y/Y|N/N|N|N|
|OP_USDT|0.109770|0.109240|0.109780|0.32|N|Y/Y|Y/N|N|N|
|PUMPFUN_USDT|0.004274|0.004236|0.004276|0.53|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.274000|1.248000|1.274000|2.55|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.062000|21.237000|21.062000|2.38|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.818100|1.812300|1.818100|0.20|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=0.002595, depth_time=2026-11-05T00:30:08+00:00, book20_bid_proxy_usdt=66708, book20_ask_proxy_usdt=69830, funding_indicative=-0.001031, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.09%, turnover=16502995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=1.044500, depth_time=2026-11-05T00:30:15+00:00, book20_bid_proxy_usdt=17056, book20_ask_proxy_usdt=22589, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.43%, turnover=6123490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=21.360000, depth_time=2026-11-05T00:30:26+00:00, book20_bid_proxy_usdt=143511, book20_ask_proxy_usdt=125430, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=19986143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=1.595600, depth_time=2026-11-05T00:30:17+00:00, book20_bid_proxy_usdt=21541, book20_ask_proxy_usdt=12053, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.72%, turnover=5047459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=0.112550, depth_time=2026-11-05T00:30:24+00:00, book20_bid_proxy_usdt=75847, book20_ask_proxy_usdt=118362, funding_indicative=0.000008, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=11324748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=0.004318, depth_time=2026-11-05T00:30:21+00:00, book20_bid_proxy_usdt=1823392, book20_ask_proxy_usdt=2384785, funding_indicative=0.000009, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.95%, turnover=17616627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=1.286000, depth_time=2026-11-05T00:30:12+00:00, book20_bid_proxy_usdt=1093816, book20_ask_proxy_usdt=1191511, funding_indicative=-0.000414, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.53%, turnover=27611688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=22.501000, depth_time=2026-11-05T00:30:14+00:00, book20_bid_proxy_usdt=20890, book20_ask_proxy_usdt=23113, funding_indicative=-0.000354, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.03%, turnover=5178937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T00:30:01+00:00, last15m_closed_end=2026-11-05T00:30+00:00, prior8high=1.856300, depth_time=2026-11-05T00:30:29+00:00, book20_bid_proxy_usdt=45606, book20_ask_proxy_usdt=36537, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=11091288. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
