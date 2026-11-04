# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T01:15:43Z**
- feed_generated_utc: 2026-11-04T01:15:46+00:00
- source_sha256: `a9fec8d3b01b7e3fa66add4615fbb289a598b3bc7e0c1580fd0d75bc160f4b52`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T01:15+00:00, close=76888, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T01:00+00:00, close=77225.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003789|-8.83|-82.06|-7.84|13359494|2.64|
|TRUMPOFFICIAL_USDT|1.513000|-5.90|-10.36|-4.91|6574970|6.61|
|STRK_USDT|0.041630|-5.66|-9.73|-4.67|5457403|4.80|
|HYPE_USDT|83.178000|-4.77|4.68|-3.78|67629690|0.12|
|XPL_USDT|0.061720|-3.63|-16.39|-2.64|7431025|3.24|
|XLM_USDT|0.159730|-3.07|-5.60|-2.08|34053243|0.63|
|QNT_USDT|189.560000|-2.99|-4.20|-2.00|60024065|3.69|
|LINK_USDT|10.823000|-2.96|-5.48|-1.97|166039740|1.85|
|ARB_USDT|0.155360|-2.82|-7.79|-1.83|17055989|0.64|
|OP_USDT|0.107340|-2.79|-3.57|-1.80|9064456|0.93|
|FARTCOIN_USDT|0.116140|-2.69|-10.85|-1.70|11171425|0.86|
|AAVE_USDT|125.150000|-2.56|-5.66|-1.57|21781208|0.80|
|AVAX_USDT|8.360000|-2.49|-5.56|-1.50|19304887|1.20|
|DASH_USDT|45.000000|-2.47|-16.92|-1.48|10765890|4.45|
|TAO_USDT|222.060000|-2.39|-11.59|-1.40|33078844|1.35|
|NEAR_USDT|3.776000|-2.15|-17.22|-1.16|67145405|2.65|
|ADA_USDT|0.186800|-2.14|-9.14|-1.15|20706998|5.36|
|TIA_USDT|0.426600|-2.11|-20.42|-1.12|12742588|2.34|
|HBAR_USDT|0.068590|-2.05|-9.89|-1.06|5784970|1.46|
|SOL_USDT|91.800000|-2.04|-9.03|-1.05|485604115|1.09|
|XRP_USDT|1.254900|-2.02|-4.97|-1.03|265209595|0.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.150000|125.180000|125.150000|7.23|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.003789|0.003829|0.003790|0.64|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155360|0.154780|0.155360|2.43|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.360000|8.378000|8.360000|4.61|Y|Y/Y|Y/N|Y|N|
|DASH_USDT|45.000000|45.100000|45.000000|3.44|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.116140|0.116210|0.116140|1.91|Y|Y/N|Y/Y|Y|N|
|HYPE_USDT|83.178000|83.134000|83.177000|3.08|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.823000|10.828000|10.822000|3.86|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.107340|0.107070|0.107340|1.80|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.560000|189.360000|189.560000|1.10|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.041630|0.041620|0.041630|4.74|N|Y/Y|Y/N|Y|N|
|TAO_USDT|222.060000|221.120000|222.060000|3.16|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.513000|1.504000|1.513000|5.29|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.159730|0.158870|0.159720|2.00|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061720|0.061340|0.061720|4.40|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=128.110000, depth_time=2026-11-04T01:15:35+00:00, book20_bid_proxy_usdt=355887, book20_ask_proxy_usdt=268987, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=21781208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.004047, depth_time=2026-11-04T01:15:08+00:00, book20_bid_proxy_usdt=56032, book20_ask_proxy_usdt=54848, funding_indicative=-0.000713, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.83%, turnover=13359494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.159660, depth_time=2026-11-04T01:15:28+00:00, book20_bid_proxy_usdt=82340, book20_ask_proxy_usdt=91124, funding_indicative=0.000032, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=17055989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=8.594000, depth_time=2026-11-04T01:15:38+00:00, book20_bid_proxy_usdt=837032, book20_ask_proxy_usdt=825096, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=19304887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=46.700000, depth_time=2026-11-04T01:15:39+00:00, book20_bid_proxy_usdt=337097, book20_ask_proxy_usdt=448557, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=10765890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.120280, depth_time=2026-11-04T01:15:33+00:00, book20_bid_proxy_usdt=50011, book20_ask_proxy_usdt=125968, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=11171425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=85.946000, depth_time=2026-11-04T01:15:17+00:00, book20_bid_proxy_usdt=45242, book20_ask_proxy_usdt=277869, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.77%, turnover=67629690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=11.152000, depth_time=2026-11-04T01:15:26+00:00, book20_bid_proxy_usdt=338908, book20_ask_proxy_usdt=373884, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=166039740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.110510, depth_time=2026-11-04T01:15:31+00:00, book20_bid_proxy_usdt=65599, book20_ask_proxy_usdt=88046, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=9064456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=193.440000, depth_time=2026-11-04T01:15:24+00:00, book20_bid_proxy_usdt=67924, book20_ask_proxy_usdt=60741, funding_indicative=-0.000028, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=60024065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.042850, depth_time=2026-11-04T01:15:13+00:00, book20_bid_proxy_usdt=223150, book20_ask_proxy_usdt=323954, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=5457403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-04T01:14:59+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=227.970000, depth_time=2026-11-04T01:15:42+00:00, book20_bid_proxy_usdt=282032, book20_ask_proxy_usdt=227730, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=33078844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=1.602000, depth_time=2026-11-04T01:15:11+00:00, book20_bid_proxy_usdt=1854077, book20_ask_proxy_usdt=1988888, funding_indicative=0.000024, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.90%, turnover=6574970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.163410, depth_time=2026-11-04T01:15:21+00:00, book20_bid_proxy_usdt=105222, book20_ask_proxy_usdt=129440, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=34053243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T01:15:00+00:00, last15m_closed_end=2026-11-04T01:15+00:00, prior8high=0.064100, depth_time=2026-11-04T01:15:19+00:00, book20_bid_proxy_usdt=355810, book20_ask_proxy_usdt=348602, funding_indicative=0.000046, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=7431025. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
