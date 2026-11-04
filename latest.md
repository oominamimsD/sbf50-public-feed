# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T22:00:29Z**
- feed_generated_utc: 2026-11-04T22:00:31+00:00
- source_sha256: `5b5b37a39e95394dbcd9f47d9010ece4972eb41be2b07e26e4ab0da72cbcbafe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T22:00+00:00, close=80198.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T22:00+00:00, close=80198.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.269000|-11.00|-25.74|-10.90|26050063|7.88|
|AKE_USDT|0.002550|-9.25|-87.31|-9.15|16477785|3.92|
|BTW_USDT|1.031600|-6.77|-40.64|-6.67|6194087|1.94|
|PUMPFUN_USDT|0.004237|-4.29|0.71|-4.19|18254147|2.36|
|WLD_USDT|0.377600|-3.69|-12.75|-3.59|73399091|2.65|
|IDOL_USDT|0.021414|-3.30|147.36|-3.20|6272873|2.80|
|HYPE_USDT|83.278000|-3.05|4.28|-2.95|90823961|0.12|
|ZRO_USDT|1.813900|-2.72|5.95|-2.62|11025987|0.55|
|PEPE_USDT|0.000005|-2.03|2.22|-1.93|142566614|0.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002550|0.002459|0.002550|0.38|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.031600|1.027600|1.031600|0.77|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.278000|82.778000|83.315000|1.36|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021414|0.020994|0.021414|1.36|N|Y/Y|N/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.95|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004237|0.004163|0.004237|0.37|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.269000|1.257000|1.269000|0.83|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377600|0.370800|0.377600|0.32|N|Y/Y|Y/N|N|N|
|ZRO_USDT|1.813900|1.757900|1.814000|1.17|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=0.002701, depth_time=2026-11-04T22:00:10+00:00, book20_bid_proxy_usdt=111041, book20_ask_proxy_usdt=81931, funding_indicative=-0.000787, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.25%, turnover=16477785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=1.065500, depth_time=2026-11-04T22:00:13+00:00, book20_bid_proxy_usdt=20304, book20_ask_proxy_usdt=23957, funding_indicative=0.000035, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.77%, turnover=6194087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=84.049000, depth_time=2026-11-04T22:00:23+00:00, book20_bid_proxy_usdt=260446, book20_ask_proxy_usdt=32181, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=90823961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=0.022500, depth_time=2026-11-04T22:00:18+00:00, book20_bid_proxy_usdt=7578, book20_ask_proxy_usdt=6440, funding_indicative=0.000068, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=6272873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=0.000005, depth_time=2026-11-04T22:00:28+00:00, book20_bid_proxy_usdt=38285, book20_ask_proxy_usdt=51884, funding_indicative=0.000100, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=142566614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=0.004240, depth_time=2026-11-04T22:00:15+00:00, book20_bid_proxy_usdt=2318989, book20_ask_proxy_usdt=2356624, funding_indicative=0.000044, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=18254147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=1.308000, depth_time=2026-11-04T22:00:05+00:00, book20_bid_proxy_usdt=728195, book20_ask_proxy_usdt=1044654, funding_indicative=-0.000133, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.00%, turnover=26050063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=0.378500, depth_time=2026-11-04T22:00:15+00:00, book20_bid_proxy_usdt=3016213, book20_ask_proxy_usdt=2750542, funding_indicative=-0.000535, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=73399091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T22:00:04+00:00, last15m_closed_end=2026-11-04T22:00+00:00, prior8high=1.815200, depth_time=2026-11-04T22:00:25+00:00, book20_bid_proxy_usdt=68827, book20_ask_proxy_usdt=40820, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=11025987. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
