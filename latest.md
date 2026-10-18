# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T08:00:42Z**
- feed_generated_utc: 2026-10-18T08:00:45+00:00
- source_sha256: `43fadc74995926cca674a26105171b50b505041688f680bcfeb01287164583a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063620|-6.60|-31.90|-6.71|14048743|1.57|
|PUMPFUN_USDT|0.004276|-5.37|-25.31|-5.48|23295820|2.34|
|FILECOIN_USDT|1.050600|-5.34|-6.84|-5.45|19373059|0.95|
|EIGEN_USDT|0.247100|-4.85|4.88|-4.96|7283899|4.05|
|QNT_USDT|193.900000|-4.29|-20.89|-4.40|67789364|1.55|
|TIA_USDT|0.634600|-3.96|23.70|-4.07|57631588|1.58|
|ZRO_USDT|1.832400|-3.52|-9.31|-3.63|7030153|0.55|
|ZEC_USDT|1127.590000|-2.99|-8.45|-3.10|1165098602|0.09|
|ENA_USDT|0.187430|-2.95|-15.58|-3.06|27712835|1.60|
|OP_USDT|0.126270|-2.89|-8.86|-3.00|9098357|1.58|
|XPL_USDT|0.078430|-2.89|-9.60|-3.00|5344043|1.27|
|DOT_USDT|1.104200|-2.79|-12.14|-2.90|16180664|0.91|
|APT_USDT|0.790200|-2.32|-4.42|-2.43|9818441|1.27|
|FARTCOIN_USDT|0.146760|-2.26|-10.46|-2.37|5682330|0.68|
|WLD_USDT|0.489000|-1.94|-12.52|-2.05|58031263|2.04|
|PEPE_USDT|0.000004|-1.89|-4.22|-2.00|56817693|0.26|
|ONDO_USDT|0.436900|-1.79|-11.66|-1.90|21843599|2.29|
|AAVE_USDT|151.900000|-1.75|-11.37|-1.86|15441299|0.66|
|ICP_USDT|2.916000|-1.38|-7.39|-1.49|6086078|3.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.790200|0.780900|0.790200|1.02|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.104200|1.090000|1.104200|0.44|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.247100|0.244200|0.247100|0.19|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187430|0.186180|0.187450|0.40|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.146760|0.146450|0.146760|4.56|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.050600|1.040400|1.050600|0.21|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126270|0.125060|0.126270|2.13|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004276|0.004250|0.004276|0.92|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.900000|192.710000|193.900000|0.83|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063620|0.062200|0.063620|1.97|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.634600|0.622800|0.634600|2.18|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.489000|0.483600|0.489000|0.51|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078430|0.077690|0.078430|5.37|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1127.590000|1125.640000|1127.590000|0.76|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.832400|1.827900|1.832400|0.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T08:00:01+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.792800, depth_time=2026-10-18T08:00:36+00:00, book20_bid_proxy_usdt=141276, book20_ask_proxy_usdt=125478, funding_indicative=-0.000070, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=9818441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=1.107500, depth_time=2026-10-18T08:00:34+00:00, book20_bid_proxy_usdt=299873, book20_ask_proxy_usdt=217210, funding_indicative=-0.000066, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=16180664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T08:00:01+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.249000, depth_time=2026-10-18T08:00:15+00:00, book20_bid_proxy_usdt=635874, book20_ask_proxy_usdt=418932, funding_indicative=-0.000005, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.85%, turnover=7283899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.188860, depth_time=2026-10-18T08:00:27+00:00, book20_bid_proxy_usdt=150589, book20_ask_proxy_usdt=197911, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=27712835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-18T08:00:01+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.148100, depth_time=2026-10-18T08:00:38+00:00, book20_bid_proxy_usdt=46320, book20_ask_proxy_usdt=35871, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=5682330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=1.056500, depth_time=2026-10-18T08:00:12+00:00, book20_bid_proxy_usdt=594582, book20_ask_proxy_usdt=615546, funding_indicative=-0.000066, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.34%, turnover=19373059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.127350, depth_time=2026-10-18T08:00:28+00:00, book20_bid_proxy_usdt=96093, book20_ask_proxy_usdt=113247, funding_indicative=-0.000169, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=9098357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.004309, depth_time=2026-10-18T08:00:10+00:00, book20_bid_proxy_usdt=2192893, book20_ask_proxy_usdt=1641070, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.37%, turnover=23295820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=196.100000, depth_time=2026-10-18T08:00:16+00:00, book20_bid_proxy_usdt=77740, book20_ask_proxy_usdt=74622, funding_indicative=-0.000051, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=67789364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.063440, depth_time=2026-10-18T08:00:07+00:00, book20_bid_proxy_usdt=311393, book20_ask_proxy_usdt=151374, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.60%, turnover=14048743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.633300, depth_time=2026-10-18T08:00:19+00:00, book20_bid_proxy_usdt=142768, book20_ask_proxy_usdt=137688, funding_indicative=-0.000061, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.96%, turnover=57631588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.494400, depth_time=2026-10-18T08:00:42+00:00, book20_bid_proxy_usdt=1968657, book20_ask_proxy_usdt=1609633, funding_indicative=-0.000106, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=58031263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T08:00:01+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=0.078880, depth_time=2026-10-18T08:00:30+00:00, book20_bid_proxy_usdt=626916, book20_ask_proxy_usdt=504163, funding_indicative=0.000034, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=5344043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T08:00:00+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=1142.650000, depth_time=2026-10-18T08:00:24+00:00, book20_bid_proxy_usdt=448402, book20_ask_proxy_usdt=1571500, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=1165098602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T08:00:01+00:00, last15m_closed_end=2026-10-18T08:00+00:00, prior8high=1.853200, depth_time=2026-10-18T08:00:22+00:00, book20_bid_proxy_usdt=45101, book20_ask_proxy_usdt=51587, funding_indicative=0.000038, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=7030153. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
