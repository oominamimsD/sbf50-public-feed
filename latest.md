# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T01:00:42Z**
- feed_generated_utc: 2026-11-07T01:00:43+00:00
- source_sha256: `8c7b71ef0525c7caa8a52a9bcad54aff878494e1671401680a3ca32b06ec0a54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T01:00+00:00, close=75871, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T01:00+00:00, close=75871, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CYBER_USDT|0.325400|-8.07|19.10|-8.12|6671488|3.07|
|ANTHROPIC_USDT|1338.410000|-7.92|-20.16|-7.97|7264050|2.47|
|PUMPFUN_USDT|0.003928|-4.19|-4.35|-4.24|12453555|2.55|
|TRUMPOFFICIAL_USDT|1.204000|-3.98|-23.40|-4.03|11589440|8.31|
|ENA_USDT|0.163830|-3.33|-13.71|-3.38|31322602|0.61|
|DOT_USDT|0.907900|-3.11|-6.32|-3.16|6732766|1.10|
|ARB_USDT|0.164970|-2.62|1.75|-2.67|26294737|0.61|
|APT_USDT|0.603500|-2.07|-3.85|-2.12|5028342|1.66|
|UNI_USDT|6.906000|-1.98|-0.59|-2.03|29317262|1.45|
|ADA_USDT|0.184300|-1.91|-4.30|-1.96|27379414|5.42|
|FARTCOIN_USDT|0.118390|-1.91|-1.58|-1.96|12656202|1.69|
|WLD_USDT|0.343300|-1.63|-16.65|-1.68|30679585|2.91|
|ONDO_USDT|0.371300|-1.32|-7.03|-1.37|10904627|2.69|
|LIT_USDT|3.356600|-1.05|18.85|-1.10|8833886|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184300|0.183700|0.184300|0.17|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1338.410000|1322.000000|1338.410000|0.13|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.603500|0.603200|0.603500|2.31|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164970|0.164290|0.164970|0.67|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.325400|0.326000|0.325700|1.32|Y|Y/Y|N/N|Y|N|
|DOT_USDT|0.907900|0.909000|0.908000|2.30|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.163830|0.163260|0.163840|0.53|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118390|0.117630|0.118390|0.57|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.356600|3.292600|3.357400|1.40|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.371300|0.369900|0.371300|0.16|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003928|0.003882|0.003928|0.35|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.204000|1.196000|1.204000|1.39|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.906000|6.871000|6.906000|0.54|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.343300|0.342300|0.343300|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.185700, depth_time=2026-11-07T01:00:31+00:00, book20_bid_proxy_usdt=9095363, book20_ask_proxy_usdt=7467895, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=27379414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=1348.560000, depth_time=2026-11-07T01:00:10+00:00, book20_bid_proxy_usdt=16701, book20_ask_proxy_usdt=16167, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.92%, turnover=7264050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.609500, depth_time=2026-11-07T01:00:25+00:00, book20_bid_proxy_usdt=227293, book20_ask_proxy_usdt=177582, funding_indicative=0.000041, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=5028342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.165910, depth_time=2026-11-07T01:00:21+00:00, book20_bid_proxy_usdt=108426, book20_ask_proxy_usdt=89647, funding_indicative=0.000041, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=26294737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.345000, depth_time=2026-11-07T01:00:06+00:00, book20_bid_proxy_usdt=118049, book20_ask_proxy_usdt=148176, funding_indicative=-0.002298, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.07%, turnover=6671488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.919000, depth_time=2026-11-07T01:00:18+00:00, book20_bid_proxy_usdt=512406, book20_ask_proxy_usdt=412651, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=6732766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.164720, depth_time=2026-11-07T01:00:17+00:00, book20_bid_proxy_usdt=190559, book20_ask_proxy_usdt=312544, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=31322602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.118900, depth_time=2026-11-07T01:00:32+00:00, book20_bid_proxy_usdt=79742, book20_ask_proxy_usdt=82193, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=12656202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=3.347700, depth_time=2026-11-07T01:00:38+00:00, book20_bid_proxy_usdt=24716, book20_ask_proxy_usdt=27578, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=8833886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.372000, depth_time=2026-11-07T01:00:37+00:00, book20_bid_proxy_usdt=1520491, book20_ask_proxy_usdt=1639145, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=10904627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.003958, depth_time=2026-11-07T01:00:11+00:00, book20_bid_proxy_usdt=2191389, book20_ask_proxy_usdt=2260920, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=12453555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=1.219000, depth_time=2026-11-07T01:00:12+00:00, book20_bid_proxy_usdt=1590946, book20_ask_proxy_usdt=1073604, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=11589440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=6.925000, depth_time=2026-11-07T01:00:28+00:00, book20_bid_proxy_usdt=2352725, book20_ask_proxy_usdt=2332366, funding_indicative=0.000080, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=29317262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T01:00:02+00:00, last15m_closed_end=2026-11-07T01:00+00:00, prior8high=0.344700, depth_time=2026-11-07T01:00:30+00:00, book20_bid_proxy_usdt=3090675, book20_ask_proxy_usdt=2877432, funding_indicative=-0.000251, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=30679585. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
