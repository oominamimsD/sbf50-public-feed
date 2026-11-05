# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T00:15:31Z**
- feed_generated_utc: 2026-11-05T00:15:33+00:00
- source_sha256: `fd362edf441d0d9363b8ce5511a7e7d0b9b32246efea724be86ebaa791de2aac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T00:15+00:00, close=80659.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002454|-12.66|-87.78|-13.13|16464422|4.08|
|TRUMPOFFICIAL_USDT|1.253000|-12.00|-26.68|-12.47|27146629|7.98|
|VVV_USDT|21.327000|-7.88|-10.45|-8.35|5080362|0.47|
|EVAA_USDT|1.539600|-5.99|3.67|-6.46|5036033|3.25|
|BTW_USDT|1.035900|-5.74|-40.39|-6.21|6069144|0.96|
|PUMPFUN_USDT|0.004252|-4.44|1.06|-4.91|17571700|2.35|
|OP_USDT|0.109630|-4.00|-1.30|-4.47|11312079|0.91|
|WLD_USDT|0.376600|-3.95|-12.98|-4.42|72369099|2.66|
|ZRO_USDT|1.813200|-2.76|5.91|-3.23|11084197|3.86|
|CLANKER_USDT|18.150000|-2.47|35.85|-2.94|19856790|5.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002454|0.002379|0.002455|1.41|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.035900|1.025200|1.035900|1.90|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|18.150000|17.160000|18.150000|0.37|N|Y/N|N/N|N|N|
|EVAA_USDT|1.539600|1.512800|1.539600|0.46|N|Y/Y|N/N|N|N|
|OP_USDT|0.109630|0.110190|0.109630|1.47|Y|Y/Y|Y/N|N|N|
|PUMPFUN_USDT|0.004252|0.004232|0.004253|0.44|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.253000|1.264000|1.253000|0.55|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.327000|21.519000|21.315000|4.45|Y|Y/Y|Y/Y|N|Y|
|WLD_USDT|0.376600|0.374400|0.376600|1.62|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.813200|1.813900|1.813200|0.35|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=0.002595, depth_time=2026-11-05T00:15:09+00:00, book20_bid_proxy_usdt=120695, book20_ask_proxy_usdt=92692, funding_indicative=-0.001021, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.66%, turnover=16464422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=1.044500, depth_time=2026-11-05T00:15:18+00:00, book20_bid_proxy_usdt=23974, book20_ask_proxy_usdt=16360, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.74%, turnover=6069144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T00:15:01+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=22.970000, depth_time=2026-11-05T00:15:31+00:00, book20_bid_proxy_usdt=144607, book20_ask_proxy_usdt=157048, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=19856790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=1.595600, depth_time=2026-11-05T00:15:16+00:00, book20_bid_proxy_usdt=11634, book20_ask_proxy_usdt=7463, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.99%, turnover=5036033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=0.112550, depth_time=2026-11-05T00:15:22+00:00, book20_bid_proxy_usdt=160809, book20_ask_proxy_usdt=121675, funding_indicative=0.000007, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=11312079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=0.004318, depth_time=2026-11-05T00:15:20+00:00, book20_bid_proxy_usdt=2083978, book20_ask_proxy_usdt=2490061, funding_indicative=0.000013, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=17571700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=1.286000, depth_time=2026-11-05T00:15:10+00:00, book20_bid_proxy_usdt=1192637, book20_ask_proxy_usdt=1208684, funding_indicative=-0.000388, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.00%, turnover=27146629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=22.501000, depth_time=2026-11-05T00:15:14+00:00, book20_bid_proxy_usdt=17008, book20_ask_proxy_usdt=39434, funding_indicative=-0.000306, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.88%, turnover=5080362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=0.384000, depth_time=2026-11-05T00:15:25+00:00, book20_bid_proxy_usdt=3127114, book20_ask_proxy_usdt=2590874, funding_indicative=-0.000430, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=72369099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T00:15:02+00:00, last15m_closed_end=2026-11-05T00:15+00:00, prior8high=1.856300, depth_time=2026-11-05T00:15:25+00:00, book20_bid_proxy_usdt=27013, book20_ask_proxy_usdt=39181, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=11084197. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
