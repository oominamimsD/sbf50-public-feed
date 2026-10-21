# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T23:30:44Z**
- feed_generated_utc: 2026-10-21T23:30:48+00:00
- source_sha256: `f75765c7b327ef0b782d9663139a067ab0a663edd8392e0efaaab622f765a11e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 23; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T23:30+00:00, close=84251.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T23:00+00:00, close=84408, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002300|-19.12|62.20|-18.83|9131088|4.33|
|BR_USDT|0.483630|-10.69|18.60|-10.40|14639553|2.69|
|AKE_USDT|0.023890|-10.49|-7.69|-10.20|10845085|1.67|
|JCT_USDT|0.003927|-7.62|86.91|-7.33|13237264|7.64|
|STRK_USDT|0.057540|-7.14|-25.44|-6.85|24115556|1.74|
|ZRO_USDT|1.953500|-6.85|3.14|-6.56|7333868|0.51|
|TIA_USDT|0.600900|-4.99|12.63|-4.70|39683680|1.66|
|ARB_USDT|0.188080|-4.33|3.26|-4.04|33349677|0.53|
|DOT_USDT|1.145500|-2.91|1.86|-2.62|16853304|0.87|
|LDO_USDT|0.403400|-2.84|-0.59|-2.55|5219088|2.48|
|AVAX_USDT|9.660000|-2.58|-1.59|-2.29|156553614|2.07|
|ICP_USDT|2.890000|-2.56|-3.57|-2.27|5641440|3.46|
|FET_USDT|0.195500|-2.54|-4.11|-2.25|7613741|5.12|
|OP_USDT|0.128680|-2.44|-6.98|-2.15|6898804|2.33|
|TAO_USDT|271.200000|-2.28|1.20|-1.99|61291749|1.11|
|HBAR_USDT|0.083980|-2.28|-0.02|-1.99|14560519|1.19|
|AAVE_USDT|155.090000|-2.15|-0.51|-1.86|132095410|0.65|
|UNI_USDT|7.457000|-2.13|4.38|-1.84|26226539|1.34|
|DOGE_USDT|0.081770|-2.01|-0.25|-1.72|83511033|1.22|
|SUI_USDT|1.028700|-1.96|2.04|-1.67|65595105|0.97|
|APT_USDT|0.819600|-1.91|3.65|-1.62|8228330|1.22|
|INJ_USDT|8.603000|-1.76|12.61|-1.47|51168495|1.16|
|SOL_USDT|106.890000|-1.42|2.95|-1.13|757320918|0.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.023890|0.024063|0.023890|1.27|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.188080|0.188600|0.188070|0.98|N|Y/N|N/N|N|N|
|AVAX_USDT|9.660000|9.652000|9.661000|0.94|N|Y/N|N/N|N|N|
|BR_USDT|0.483630|0.482300|0.483770|0.45|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002300|0.002280|0.002300|0.43|N|Y/Y|N/N|N|N|
|DOT_USDT|1.145500|1.145500|1.145500|5.74|N|Y/Y|N/N|N|N|
|FET_USDT|0.195500|0.195000|0.195500|0.38|N|Y/N|N/N|N|N|
|ICP_USDT|2.890000|2.894000|2.891000|0.64|N|Y/Y|N/N|N|N|
|JCT_USDT|0.003927|0.004051|0.003927|2.59|Y|Y/Y|N/N|N|N|
|LDO_USDT|0.403400|0.403900|0.403400|0.23|N|Y/Y|N/N|N|N|
|OP_USDT|0.128680|0.128400|0.128640|0.82|N|Y/Y|N/N|N|N|
|STRK_USDT|0.057540|0.057230|0.057540|0.81|N|Y/N|N/N|N|N|
|TAO_USDT|271.200000|271.270000|271.200000|0.59|N|Y/N|N/N|N|N|
|TIA_USDT|0.600900|0.606500|0.600900|2.75|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.953500|1.932700|1.953500|1.51|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.025512, depth_time=2026-10-21T23:30:12+00:00, book20_bid_proxy_usdt=24804, book20_ask_proxy_usdt=18659, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.49%, turnover=10845085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.195530, depth_time=2026-10-21T23:30:25+00:00, book20_bid_proxy_usdt=36408, book20_ask_proxy_usdt=74618, funding_indicative=0.000080, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=33349677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=9.877000, depth_time=2026-10-21T23:30:31+00:00, book20_bid_proxy_usdt=1147184, book20_ask_proxy_usdt=1595504, funding_indicative=0.000056, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=156553614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.504950, depth_time=2026-10-21T23:30:10+00:00, book20_bid_proxy_usdt=3764, book20_ask_proxy_usdt=4929, funding_indicative=-0.000209, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.69%, turnover=14639553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.002525, depth_time=2026-10-21T23:30:08+00:00, book20_bid_proxy_usdt=142079, book20_ask_proxy_usdt=148530, funding_indicative=-0.000067, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=1, 24h_change=-19.12%, turnover=9131088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=1.173500, depth_time=2026-10-21T23:30:28+00:00, book20_bid_proxy_usdt=195598, book20_ask_proxy_usdt=367746, funding_indicative=-0.000117, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=16853304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.200300, depth_time=2026-10-21T23:30:38+00:00, book20_bid_proxy_usdt=1842676, book20_ask_proxy_usdt=1145039, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=7613741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=2.959000, depth_time=2026-10-21T23:30:36+00:00, book20_bid_proxy_usdt=776300, book20_ask_proxy_usdt=989073, funding_indicative=0.000004, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=5641440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.004284, depth_time=2026-10-21T23:30:15+00:00, book20_bid_proxy_usdt=53026, book20_ask_proxy_usdt=44285, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.62%, turnover=13237264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.411700, depth_time=2026-10-21T23:30:30+00:00, book20_bid_proxy_usdt=593320, book20_ask_proxy_usdt=624017, funding_indicative=0.000005, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=5219088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.132180, depth_time=2026-10-21T23:30:40+00:00, book20_bid_proxy_usdt=70047, book20_ask_proxy_usdt=112698, funding_indicative=-0.000010, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=6898804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.061150, depth_time=2026-10-21T23:30:15+00:00, book20_bid_proxy_usdt=556077, book20_ask_proxy_usdt=420804, funding_indicative=-0.000042, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.14%, turnover=24115556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=277.510000, depth_time=2026-10-21T23:30:43+00:00, book20_bid_proxy_usdt=127658, book20_ask_proxy_usdt=133765, funding_indicative=0.000031, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=61291749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=0.625800, depth_time=2026-10-21T23:30:22+00:00, book20_bid_proxy_usdt=288042, book20_ask_proxy_usdt=274354, funding_indicative=-0.000139, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=39683680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T23:30:01+00:00, last15m_closed_end=2026-10-21T23:30+00:00, prior8high=2.012100, depth_time=2026-10-21T23:30:20+00:00, book20_bid_proxy_usdt=72046, book20_ask_proxy_usdt=49611, funding_indicative=-0.000006, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.85%, turnover=7333868. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
