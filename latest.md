# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T07:45:42Z**
- feed_generated_utc: 2026-10-18T07:45:45+00:00
- source_sha256: `b65caa692da006a883c089a756fac7f4b7bf263488352df853488818def73cb0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T07:45+00:00, close=81666.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T07:00+00:00, close=81687.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062790|-5.07|-32.79|-5.50|14236926|1.59|
|TIA_USDT|0.627600|-4.62|22.33|-5.05|60361301|1.59|
|FILECOIN_USDT|1.046900|-3.72|-7.17|-4.15|19689979|5.73|
|EIGEN_USDT|0.247000|-3.62|4.83|-4.05|7730153|4.05|
|QNT_USDT|193.550000|-3.42|-21.04|-3.85|69625833|1.03|
|PUMPFUN_USDT|0.004263|-3.37|-25.53|-3.80|23694987|2.35|
|ZRO_USDT|1.836400|-2.59|-9.11|-3.02|7212340|1.09|
|OP_USDT|0.125990|-2.33|-9.06|-2.76|9796133|0.79|
|XPL_USDT|0.078290|-2.29|-9.76|-2.72|5444625|1.28|
|WLD_USDT|0.488500|-1.43|-12.61|-1.86|59270278|2.05|
|DOT_USDT|1.101500|-1.42|-12.36|-1.85|16854147|0.91|
|ZEC_USDT|1126.810000|-1.27|-8.52|-1.70|1189396404|0.09|
|APT_USDT|0.787300|-1.27|-4.77|-1.70|10454972|1.27|
|ENA_USDT|0.187190|-1.04|-15.69|-1.47|28595992|0.53|
|FARTCOIN_USDT|0.146740|-0.88|-10.47|-1.31|5983053|0.68|
|PEPE_USDT|0.000004|-0.67|-4.26|-1.10|58983135|0.26|
|ONDO_USDT|0.437000|-0.59|-11.64|-1.02|22451034|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.787300|0.780900|0.787300|3.66|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.101500|1.089000|1.101500|0.88|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.247000|0.244000|0.247000|1.03|N|Y/Y|N/Y|N|N|
|ENA_USDT|0.187190|0.186180|0.187240|0.21|N|Y/Y|Y/Y|N|N|
|FARTCOIN_USDT|0.146740|0.146450|0.146740|0.70|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.046900|1.040400|1.046900|0.56|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.125990|0.124920|0.125990|1.33|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004263|0.004250|0.004263|1.47|N|Y/Y|Y/Y|N|N|
|QNT_USDT|193.550000|191.970000|193.550000|0.32|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.062790|0.062200|0.062790|0.25|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.627600|0.622800|0.627600|0.75|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.488500|0.483600|0.488500|0.71|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.078290|0.077620|0.078290|3.41|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1126.810000|1125.640000|1126.810000|1.01|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.836400|1.827700|1.836400|0.66|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.792800, depth_time=2026-10-18T07:45:37+00:00, book20_bid_proxy_usdt=150611, book20_ask_proxy_usdt=153706, funding_indicative=-0.000081, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=10454972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=1.107500, depth_time=2026-10-18T07:45:31+00:00, book20_bid_proxy_usdt=358080, book20_ask_proxy_usdt=290383, funding_indicative=-0.000087, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=16854147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.249000, depth_time=2026-10-18T07:45:15+00:00, book20_bid_proxy_usdt=463599, book20_ask_proxy_usdt=406539, funding_indicative=-0.000027, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=7730153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.188860, depth_time=2026-10-18T07:45:39+00:00, book20_bid_proxy_usdt=173155, book20_ask_proxy_usdt=86310, funding_indicative=0.000041, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=28595992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.148100, depth_time=2026-10-18T07:45:41+00:00, book20_bid_proxy_usdt=45308, book20_ask_proxy_usdt=42251, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=5983053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=1.056500, depth_time=2026-10-18T07:45:12+00:00, book20_bid_proxy_usdt=509938, book20_ask_proxy_usdt=570026, funding_indicative=-0.000073, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=19689979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.127350, depth_time=2026-10-18T07:45:24+00:00, book20_bid_proxy_usdt=107396, book20_ask_proxy_usdt=79285, funding_indicative=-0.000181, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=9796133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.004309, depth_time=2026-10-18T07:45:20+00:00, book20_bid_proxy_usdt=2989905, book20_ask_proxy_usdt=1746683, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=23694987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=196.100000, depth_time=2026-10-18T07:45:16+00:00, book20_bid_proxy_usdt=74759, book20_ask_proxy_usdt=107980, funding_indicative=-0.000060, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=69625833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.063440, depth_time=2026-10-18T07:45:08+00:00, book20_bid_proxy_usdt=659028, book20_ask_proxy_usdt=382807, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.07%, turnover=14236926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.633300, depth_time=2026-10-18T07:45:10+00:00, book20_bid_proxy_usdt=262523, book20_ask_proxy_usdt=302226, funding_indicative=-0.000066, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=60361301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.494400, depth_time=2026-10-18T07:45:30+00:00, book20_bid_proxy_usdt=1642131, book20_ask_proxy_usdt=1947002, funding_indicative=-0.000125, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=59270278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=0.078880, depth_time=2026-10-18T07:45:26+00:00, book20_bid_proxy_usdt=393790, book20_ask_proxy_usdt=391513, funding_indicative=0.000032, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=5444625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=1142.650000, depth_time=2026-10-18T07:45:34+00:00, book20_bid_proxy_usdt=346582, book20_ask_proxy_usdt=670184, funding_indicative=0.000100, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=1189396404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T07:45:01+00:00, last15m_closed_end=2026-10-18T07:45+00:00, prior8high=1.853200, depth_time=2026-10-18T07:45:21+00:00, book20_bid_proxy_usdt=50107, book20_ask_proxy_usdt=64977, funding_indicative=0.000032, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=7212340. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
