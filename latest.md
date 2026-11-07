# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T03:30:43Z**
- feed_generated_utc: 2026-11-07T03:30:45+00:00
- source_sha256: `f8266626463a4957bca669792d058c8865bbc9e8b0733828c5a653fef4304789`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T03:30+00:00, close=75967, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T03:00+00:00, close=76008, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.148500|-21.84|-44.08|-22.01|35246737|6.75|
|CYBER_USDT|0.319300|-9.80|16.87|-9.97|6250596|3.13|
|TRUMPOFFICIAL_USDT|1.189000|-4.26|-24.36|-4.43|11096409|8.41|
|DOT_USDT|0.906000|-3.31|-6.52|-3.48|6854524|1.10|
|PUMPFUN_USDT|0.003922|-3.04|-4.50|-3.21|12228132|2.55|
|OP_USDT|0.104530|-2.59|-3.40|-2.76|5765687|1.91|
|XRP_USDT|1.159800|-2.32|-7.54|-2.49|353694607|0.86|
|ADA_USDT|0.184000|-2.17|-4.46|-2.34|26804012|5.43|
|ARB_USDT|0.164600|-2.15|1.52|-2.32|26015049|0.61|
|ONDO_USDT|0.368500|-2.12|-7.73|-2.29|10988739|2.71|
|ENA_USDT|0.164170|-1.99|-13.54|-2.16|30561416|0.61|
|AAVE_USDT|129.500000|-1.89|3.07|-2.06|17604338|0.77|
|HBAR_USDT|0.067130|-1.85|-6.56|-2.02|5156207|1.49|
|XLM_USDT|0.152320|-1.77|-11.56|-1.94|23937784|0.66|
|BEAT_USDT|0.107430|-1.71|2.16|-1.88|8858791|3.72|
|LINK_USDT|10.775000|-1.70|-2.50|-1.87|120172189|0.93|
|FARTCOIN_USDT|0.118100|-1.60|-1.82|-1.77|12260525|0.85|
|AVAX_USDT|8.304000|-1.23|-0.52|-1.40|12356934|1.20|
|WLD_USDT|0.340900|-1.13|-17.23|-1.30|29814327|2.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.500000|129.380000|129.500000|1.92|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.184000|0.184000|0.184000|0.47|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164600|0.163930|0.164600|0.63|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.107430|0.106510|0.107430|0.40|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.319300|0.309500|0.319300|1.40|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.906000|0.902700|0.906000|0.19|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.164170|0.163570|0.164170|2.36|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067130|0.067080|0.067130|1.02|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.368500|0.368500|0.368500|3.10|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.104530|0.104030|0.104530|0.33|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003922|0.003912|0.003922|0.19|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.189000|1.192000|1.190000|5.86|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.148500|0.135500|0.148500|0.38|N|Y/Y|N/N|Y|N|
|XLM_USDT|0.152320|0.152120|0.152280|4.33|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.159800|1.161900|1.159800|5.50|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=131.010000, depth_time=2026-11-07T03:30:27+00:00, book20_bid_proxy_usdt=347684, book20_ask_proxy_usdt=319575, funding_indicative=0.000063, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=17604338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.185600, depth_time=2026-11-07T03:30:24+00:00, book20_bid_proxy_usdt=10714430, book20_ask_proxy_usdt=9541552, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=26804012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.165540, depth_time=2026-11-07T03:30:26+00:00, book20_bid_proxy_usdt=81627, book20_ask_proxy_usdt=105655, funding_indicative=-0.000044, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=26015049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.108970, depth_time=2026-11-07T03:30:42+00:00, book20_bid_proxy_usdt=9886, book20_ask_proxy_usdt=17780, funding_indicative=0.000086, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=8858791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.330900, depth_time=2026-11-07T03:30:09+00:00, book20_bid_proxy_usdt=135681, book20_ask_proxy_usdt=115389, funding_indicative=-0.001839, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.80%, turnover=6250596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.908600, depth_time=2026-11-07T03:30:12+00:00, book20_bid_proxy_usdt=593218, book20_ask_proxy_usdt=510216, funding_indicative=0.000091, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=6854524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.164840, depth_time=2026-11-07T03:30:32+00:00, book20_bid_proxy_usdt=221342, book20_ask_proxy_usdt=273193, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=30561416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.067850, depth_time=2026-11-07T03:30:35+00:00, book20_bid_proxy_usdt=781178, book20_ask_proxy_usdt=863545, funding_indicative=-0.000068, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=5156207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.372500, depth_time=2026-11-07T03:30:28+00:00, book20_bid_proxy_usdt=1601644, book20_ask_proxy_usdt=1730348, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=10988739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.105440, depth_time=2026-11-07T03:30:18+00:00, book20_bid_proxy_usdt=87772, book20_ask_proxy_usdt=126228, funding_indicative=0.000000, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=5765687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.003956, depth_time=2026-11-07T03:30:14+00:00, book20_bid_proxy_usdt=2064858, book20_ask_proxy_usdt=1976985, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=12228132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=1.204000, depth_time=2026-11-07T03:30:12+00:00, book20_bid_proxy_usdt=1181027, book20_ask_proxy_usdt=1659035, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=11096409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.152300, depth_time=2026-11-07T03:30:07+00:00, book20_bid_proxy_usdt=168425, book20_ask_proxy_usdt=119611, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.84%, turnover=35246737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=0.154170, depth_time=2026-11-07T03:30:39+00:00, book20_bid_proxy_usdt=173566, book20_ask_proxy_usdt=290338, funding_indicative=-0.000020, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=23937784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T03:30:01+00:00, last15m_closed_end=2026-11-07T03:30+00:00, prior8high=1.180500, depth_time=2026-11-07T03:30:22+00:00, book20_bid_proxy_usdt=3162917, book20_ask_proxy_usdt=3894726, funding_indicative=0.000059, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=353694607. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
