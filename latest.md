# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T02:00:29Z**
- feed_generated_utc: 2026-11-05T02:00:30+00:00
- source_sha256: `8c3f754c06900ccca187e352d518a0ab2ccabb35c9c38bb1153f2b79cf780ca8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T02:00+00:00, close=80640.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T02:00+00:00, close=80640.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.247000|-12.55|-27.03|-13.00|26948490|8.00|
|VVV_USDT|21.218000|-9.63|-10.91|-10.08|5010168|0.47|
|BTW_USDT|1.033300|-6.62|-40.54|-7.07|5907953|1.94|
|EVAA_USDT|1.533800|-6.35|3.28|-6.80|5037886|4.56|
|WLD_USDT|0.374200|-4.17|-13.53|-4.62|73283023|2.67|
|IDOL_USDT|0.021285|-3.88|145.87|-4.33|5885745|0.47|
|ZRO_USDT|1.817400|-3.82|6.15|-4.27|10388891|0.55|
|PUMPFUN_USDT|0.004274|-3.45|1.59|-3.90|15976518|2.34|
|CLANKER_USDT|16.720000|-2.79|25.14|-3.24|20255229|5.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.033300|1.003000|1.033300|1.52|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|16.720000|15.780000|16.720000|0.27|N|Y/Y|N/N|N|N|
|EVAA_USDT|1.533800|1.518600|1.533800|0.65|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021285|0.020956|0.021285|1.23|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004274|0.004224|0.004274|0.43|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.247000|1.233000|1.247000|0.28|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.218000|20.977000|21.218000|0.26|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374200|0.370800|0.374200|0.83|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.817400|1.807200|1.817400|0.25|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-11-05T02:00:01+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=1.036000, depth_time=2026-11-05T02:00:12+00:00, book20_bid_proxy_usdt=18217, book20_ask_proxy_usdt=15034, funding_indicative=0.000046, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.62%, turnover=5907953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T02:00:00+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=18.850000, depth_time=2026-11-05T02:00:28+00:00, book20_bid_proxy_usdt=134918, book20_ask_proxy_usdt=158602, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=20255229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-05T02:00:00+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=1.585200, depth_time=2026-11-05T02:00:14+00:00, book20_bid_proxy_usdt=9573, book20_ask_proxy_usdt=14497, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.35%, turnover=5037886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T02:00:00+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=0.022404, depth_time=2026-11-05T02:00:17+00:00, book20_bid_proxy_usdt=3867, book20_ask_proxy_usdt=6702, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=5885745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T02:00:01+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=0.004317, depth_time=2026-11-05T02:00:26+00:00, book20_bid_proxy_usdt=2668894, book20_ask_proxy_usdt=1767684, funding_indicative=0.000011, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=15976518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T02:00:00+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=1.284000, depth_time=2026-11-05T02:00:05+00:00, book20_bid_proxy_usdt=899827, book20_ask_proxy_usdt=1122175, funding_indicative=-0.000405, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.55%, turnover=26948490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T02:00:01+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=21.851000, depth_time=2026-11-05T02:00:07+00:00, book20_bid_proxy_usdt=28650, book20_ask_proxy_usdt=24519, funding_indicative=-0.000411, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.63%, turnover=5010168. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T02:00:00+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=0.381000, depth_time=2026-11-05T02:00:16+00:00, book20_bid_proxy_usdt=2221596, book20_ask_proxy_usdt=1787626, funding_indicative=-0.000357, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=73283023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T02:00:01+00:00, last15m_closed_end=2026-11-05T02:00+00:00, prior8high=1.831100, depth_time=2026-11-05T02:00:22+00:00, book20_bid_proxy_usdt=47857, book20_ask_proxy_usdt=22643, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=10388891. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
