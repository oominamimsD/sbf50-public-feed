# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T14:30:44Z**
- feed_generated_utc: 2026-10-28T14:30:48+00:00
- source_sha256: `eb453230037c4ee70f790eb292f83905b027dba7f224c6648e8dca458f241a3e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T14:30+00:00, close=80525.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T14:00+00:00, close=80713.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055710|-12.38|-54.61|-12.38|17888668|7.18|
|BEAT_USDT|0.080020|-12.15|7.10|-12.15|12289046|1.25|
|AKE_USDT|0.019246|-8.89|-38.09|-8.89|6714865|0.52|
|ENA_USDT|0.193880|-8.87|2.10|-8.87|83775520|0.52|
|INJ_USDT|7.765000|-5.21|-9.70|-5.21|25158558|1.29|
|ARB_USDT|0.163690|-2.85|-13.36|-2.85|17982362|0.61|
|QNT_USDT|192.890000|-2.52|-1.16|-2.52|67736742|0.52|
|PUMPFUN_USDT|0.004181|-2.42|-7.31|-2.42|13517036|2.39|
|DASH_USDT|52.870000|-2.39|5.86|-2.39|15896458|1.89|
|UNI_USDT|6.990000|-2.36|-3.86|-2.36|14219739|2.86|
|WLD_USDT|0.426900|-2.08|-24.14|-2.08|62301181|2.34|
|ADA_USDT|0.201700|-1.89|-8.89|-1.89|37330889|4.96|
|OP_USDT|0.109400|-1.72|-16.67|-1.72|6349576|0.91|
|ZEC_USDT|1272.870000|-1.53|6.86|-1.53|1586411252|0.08|
|ASTER_USDT|0.702100|-1.52|-1.66|-1.52|5119863|1.42|
|SILVER_USDT|53.830000|-1.48|-7.10|-1.48|254366491|1.86|
|APT_USDT|0.678000|-1.41|-15.00|-1.41|6442147|2.95|
|HBAR_USDT|0.075120|-1.31|-9.88|-1.31|10320128|1.33|
|AAVE_USDT|131.100000|-1.18|-13.78|-1.18|16695086|0.76|
|ONDO_USDT|0.412600|-1.10|-7.07|-1.10|17063652|2.42|
|STRK_USDT|0.045630|-1.06|-17.70|-1.06|5033191|2.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.201700|0.201400|0.201800|3.39|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.019246|0.019286|0.019248|1.42|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.163690|0.163580|0.163690|9.72|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.702100|0.701900|0.702200|1.17|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.080020|0.078520|0.080000|0.45|N|Y/Y|Y/N|Y|N|
|DASH_USDT|52.870000|52.880000|52.870000|1.74|Y|Y/Y|N/N|Y|N|
|ENA_USDT|0.193880|0.194520|0.193770|1.40|Y|Y/Y|Y/N|Y|N|
|INJ_USDT|7.765000|7.773000|7.766000|2.97|Y|Y/Y|N/N|Y|N|
|OP_USDT|0.109400|0.109440|0.109400|2.27|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004181|0.004181|0.004179|0.96|N|Y/Y|N/N|Y|N|
|QNT_USDT|192.890000|194.120000|192.890000|2.41|Y|Y/Y|N/N|Y|N|
|Q_USDT|0.055710|0.052780|0.055630|0.92|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.990000|6.983000|6.988000|1.17|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.426900|0.425300|0.426900|1.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1272.870000|1275.740000|1272.920000|1.68|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.204900, depth_time=2026-10-28T14:30:35+00:00, book20_bid_proxy_usdt=8357312, book20_ask_proxy_usdt=7666543, funding_indicative=-0.000076, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=37330889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.019953, depth_time=2026-10-28T14:30:11+00:00, book20_bid_proxy_usdt=4173, book20_ask_proxy_usdt=4718, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.89%, turnover=6714865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.166480, depth_time=2026-10-28T14:30:20+00:00, book20_bid_proxy_usdt=73828, book20_ask_proxy_usdt=103392, funding_indicative=-0.000097, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=17982362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.708100, depth_time=2026-10-28T14:30:42+00:00, book20_bid_proxy_usdt=830198, book20_ask_proxy_usdt=688327, funding_indicative=0.000025, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=5119863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.080810, depth_time=2026-10-28T14:30:10+00:00, book20_bid_proxy_usdt=11055, book20_ask_proxy_usdt=10169, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.15%, turnover=12289046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=53.670000, depth_time=2026-10-28T14:30:25+00:00, book20_bid_proxy_usdt=753394, book20_ask_proxy_usdt=706128, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=15896458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.202290, depth_time=2026-10-28T14:30:15+00:00, book20_bid_proxy_usdt=294660, book20_ask_proxy_usdt=179266, funding_indicative=-0.000036, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.87%, turnover=83775520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=7.895000, depth_time=2026-10-28T14:30:18+00:00, book20_bid_proxy_usdt=279701, book20_ask_proxy_usdt=586779, funding_indicative=0.000108, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.21%, turnover=25158558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.111470, depth_time=2026-10-28T14:30:38+00:00, book20_bid_proxy_usdt=78346, book20_ask_proxy_usdt=140483, funding_indicative=-0.000071, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=6349576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.004277, depth_time=2026-10-28T14:30:25+00:00, book20_bid_proxy_usdt=1629636, book20_ask_proxy_usdt=2833995, funding_indicative=0.000000, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=13517036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=198.250000, depth_time=2026-10-28T14:30:23+00:00, book20_bid_proxy_usdt=96093, book20_ask_proxy_usdt=80013, funding_indicative=-0.000293, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=67736742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.055880, depth_time=2026-10-28T14:30:07+00:00, book20_bid_proxy_usdt=25781, book20_ask_proxy_usdt=34832, funding_indicative=-0.000794, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.38%, turnover=17888668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=7.087000, depth_time=2026-10-28T14:30:30+00:00, book20_bid_proxy_usdt=1266064, book20_ask_proxy_usdt=2258116, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=14219739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=0.432900, depth_time=2026-10-28T14:30:33+00:00, book20_bid_proxy_usdt=3125266, book20_ask_proxy_usdt=3148306, funding_indicative=-0.000071, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=62301181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-28T14:30:03+00:00, last15m_closed_end=2026-10-28T14:30+00:00, prior8high=1298.660000, depth_time=2026-10-28T14:30:41+00:00, book20_bid_proxy_usdt=795603, book20_ask_proxy_usdt=253580, funding_indicative=0.000082, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=1586411252. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
