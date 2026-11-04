# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T21:30:31Z**
- feed_generated_utc: 2026-11-04T21:30:33+00:00
- source_sha256: `765be0efaefdc95e1ec2f623973152becc41ad1b76696cb3f0237e7b5974f997`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T21:30+00:00, close=80077.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T21:00+00:00, close=80098.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.266000|-11.09|-25.92|-10.85|25622529|7.90|
|IDOL_USDT|0.021227|-9.54|145.20|-9.30|6376827|1.42|
|AKE_USDT|0.002556|-9.03|-87.28|-8.79|16957901|3.91|
|BTW_USDT|1.035200|-5.80|-40.43|-5.56|6405301|1.93|
|PUMPFUN_USDT|0.004206|-5.48|-0.02|-5.24|19294805|2.38|
|PEPE_USDT|0.000005|-4.48|1.87|-4.24|145506953|0.20|
|WLD_USDT|0.375500|-4.23|-13.23|-3.99|77356134|2.66|
|OP_USDT|0.109450|-4.15|-1.46|-3.91|11747244|0.91|
|ZRO_USDT|1.799600|-3.49|5.11|-3.25|11172342|0.56|
|HYPE_USDT|83.010000|-3.37|3.94|-3.13|91817113|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002556|0.002455|0.002556|0.90|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.035200|1.030900|1.035200|1.17|N|Y/Y|Y/N|N|N|
|HYPE_USDT|83.010000|83.096000|83.010000|1.19|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021227|0.021030|0.021240|0.72|N|Y/N|N/N|N|N|
|OP_USDT|0.109450|0.108620|0.109440|0.76|N|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.63|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004206|0.004163|0.004206|1.03|N|Y/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.266000|1.272000|1.267000|0.64|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.375500|0.370800|0.375500|0.51|N|Y/Y|Y/N|N|N|
|ZRO_USDT|1.799600|1.757900|1.799600|0.10|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=0.002701, depth_time=2026-11-04T21:30:13+00:00, book20_bid_proxy_usdt=107791, book20_ask_proxy_usdt=114830, funding_indicative=-0.000727, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.03%, turnover=16957901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=1.079200, depth_time=2026-11-04T21:30:14+00:00, book20_bid_proxy_usdt=24198, book20_ask_proxy_usdt=19172, funding_indicative=0.000009, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.80%, turnover=6405301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=84.688000, depth_time=2026-11-04T21:30:30+00:00, book20_bid_proxy_usdt=113610, book20_ask_proxy_usdt=190599, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=91817113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=0.023103, depth_time=2026-11-04T21:30:09+00:00, book20_bid_proxy_usdt=6215, book20_ask_proxy_usdt=6696, funding_indicative=0.000125, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.54%, turnover=6376827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=0.110610, depth_time=2026-11-04T21:30:25+00:00, book20_bid_proxy_usdt=142060, book20_ask_proxy_usdt=126622, funding_indicative=0.000010, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=11747244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=0.000005, depth_time=2026-11-04T21:30:20+00:00, book20_bid_proxy_usdt=54940, book20_ask_proxy_usdt=70682, funding_indicative=0.000100, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.48%, turnover=145506953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=0.004240, depth_time=2026-11-04T21:30:17+00:00, book20_bid_proxy_usdt=2614245, book20_ask_proxy_usdt=2382474, funding_indicative=0.000043, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.48%, turnover=19294805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=1.308000, depth_time=2026-11-04T21:30:06+00:00, book20_bid_proxy_usdt=1170421, book20_ask_proxy_usdt=1184586, funding_indicative=-0.000193, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.09%, turnover=25622529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=0.378500, depth_time=2026-11-04T21:30:22+00:00, book20_bid_proxy_usdt=2543809, book20_ask_proxy_usdt=2328443, funding_indicative=-0.000525, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=77356134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T21:30:03+00:00, last15m_closed_end=2026-11-04T21:30+00:00, prior8high=1.813900, depth_time=2026-11-04T21:30:28+00:00, book20_bid_proxy_usdt=69792, book20_ask_proxy_usdt=23299, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.49%, turnover=11172342. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
