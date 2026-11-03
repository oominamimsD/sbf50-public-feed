# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T09:30:45Z**
- feed_generated_utc: 2026-11-03T09:30:48+00:00
- source_sha256: `16878d3aa389fdc5c88fe3f5e7278984db9459e48d15b574fe41923659277806`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T09:30+00:00, close=76879.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T09:00+00:00, close=76610, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.907700|-17.24|-24.08|-16.47|10268070|3.30|
|AKE_USDT|0.004566|-17.01|-85.16|-16.24|13707209|6.56|
|ZEC_USDT|1138.600000|-9.20|-8.74|-8.43|1783052527|0.09|
|XPL_USDT|0.064240|-7.67|-13.52|-6.90|11928074|1.56|
|NEAR_USDT|3.806000|-5.08|-16.77|-4.31|77187161|2.63|
|SILVER_USDT|48.930000|-4.17|-9.77|-3.40|443605374|2.04|
|TIA_USDT|0.438100|-4.11|-18.21|-3.34|12605218|2.28|
|QNT_USDT|195.040000|-3.66|-7.24|-2.89|48138534|0.51|
|OP_USDT|0.108540|-3.45|-2.82|-2.68|10861925|0.92|
|XLM_USDT|0.161820|-3.44|-4.58|-2.67|33925294|1.24|
|WLD_USDT|0.368300|-3.38|-17.23|-2.61|50752687|2.72|
|ENA_USDT|0.169260|-3.30|-19.54|-2.53|69950594|0.59|
|TRUMPOFFICIAL_USDT|1.584000|-3.17|-6.21|-2.40|9261931|6.32|
|DASH_USDT|45.810000|-2.94|-12.27|-2.17|9131353|2.19|
|ARB_USDT|0.154660|-2.93|-9.01|-2.16|14496344|0.65|
|PUMPFUN_USDT|0.003990|-2.77|-7.80|-2.00|10338707|2.51|
|FARTCOIN_USDT|0.116120|-2.63|-9.51|-1.86|9843392|1.72|
|APT_USDT|0.612500|-2.32|-12.74|-1.55|5387976|1.63|
|TAO_USDT|222.180000|-2.18|-12.35|-1.41|40192522|1.35|
|HYPE_USDT|84.155000|-1.81|7.28|-1.04|81121243|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004566|0.004340|0.004563|1.21|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.154660|0.152230|0.154660|1.22|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.907700|0.916600|0.908200|0.90|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.810000|45.380000|45.810000|0.24|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.169260|0.166740|0.169350|1.12|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.806000|3.743000|3.806000|1.06|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.108540|0.107010|0.108540|0.75|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.040000|192.510000|195.040000|0.70|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|48.930000|48.730000|48.930000|0.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.438100|0.434300|0.438400|1.03|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.584000|1.557000|1.584000|2.28|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.368300|0.363300|0.368400|0.60|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.161820|0.160590|0.161880|0.80|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064240|0.063220|0.064260|3.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1138.600000|1124.290000|1139.260000|0.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.004760, depth_time=2026-11-03T09:30:10+00:00, book20_bid_proxy_usdt=29776, book20_ask_proxy_usdt=28736, funding_indicative=-0.000913, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.01%, turnover=13707209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.154500, depth_time=2026-11-03T09:30:44+00:00, book20_bid_proxy_usdt=99311, book20_ask_proxy_usdt=100509, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=14496344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.937100, depth_time=2026-11-03T09:30:07+00:00, book20_bid_proxy_usdt=30998, book20_ask_proxy_usdt=33144, funding_indicative=-0.000085, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.24%, turnover=10268070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=45.800000, depth_time=2026-11-03T09:30:40+00:00, book20_bid_proxy_usdt=714504, book20_ask_proxy_usdt=680266, funding_indicative=0.000095, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=9131353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.169650, depth_time=2026-11-03T09:30:36+00:00, book20_bid_proxy_usdt=249066, book20_ask_proxy_usdt=242788, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=69950594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=3.814000, depth_time=2026-11-03T09:30:17+00:00, book20_bid_proxy_usdt=5717353, book20_ask_proxy_usdt=4627677, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.08%, turnover=77187161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.108290, depth_time=2026-11-03T09:30:27+00:00, book20_bid_proxy_usdt=166376, book20_ask_proxy_usdt=100245, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=10861925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=196.360000, depth_time=2026-11-03T09:30:25+00:00, book20_bid_proxy_usdt=76800, book20_ask_proxy_usdt=70952, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=48138534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=49.300000, depth_time=2026-11-03T09:30:18+00:00, book20_bid_proxy_usdt=48278076, book20_ask_proxy_usdt=58104072, funding_indicative=0.000000, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=443605374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.441000, depth_time=2026-11-03T09:30:22+00:00, book20_bid_proxy_usdt=334176, book20_ask_proxy_usdt=387265, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.11%, turnover=12605218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=1.580000, depth_time=2026-11-03T09:30:37+00:00, book20_bid_proxy_usdt=1920961, book20_ask_proxy_usdt=2380383, funding_indicative=0.000039, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=9261931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.368500, depth_time=2026-11-03T09:30:33+00:00, book20_bid_proxy_usdt=4348207, book20_ask_proxy_usdt=4113766, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=50752687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.161960, depth_time=2026-11-03T09:30:31+00:00, book20_bid_proxy_usdt=191051, book20_ask_proxy_usdt=226704, funding_indicative=0.000090, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=33925294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=0.064270, depth_time=2026-11-03T09:30:14+00:00, book20_bid_proxy_usdt=419199, book20_ask_proxy_usdt=381562, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.67%, turnover=11928074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T09:30:04+00:00, last15m_closed_end=2026-11-03T09:30+00:00, prior8high=1144.000000, depth_time=2026-11-03T09:30:12+00:00, book20_bid_proxy_usdt=416626, book20_ask_proxy_usdt=806231, funding_indicative=0.000077, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.20%, turnover=1783052527. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
