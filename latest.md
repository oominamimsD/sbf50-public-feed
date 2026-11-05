# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T10:15:45Z**
- feed_generated_utc: 2026-11-05T10:15:46+00:00
- source_sha256: `c65ce65e36fc0e0eefa9301524cc1dccd7882e463b88be83fb5c87496df1a205`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T10:15+00:00, close=80374.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T10:00+00:00, close=80443.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T08:00+00:00, close=80362.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002243|-20.17|-88.83|-20.29|16877255|4.45|
|TRUMPOFFICIAL_USDT|1.263000|-11.30|-26.09|-11.42|25611322|7.92|
|BTW_USDT|1.028300|-6.43|-40.83|-6.55|5141464|1.95|
|ZRO_USDT|1.772500|-4.94|3.53|-5.06|7484104|0.56|
|FARTCOIN_USDT|0.124790|-4.08|-4.73|-4.20|16184367|1.60|
|WLD_USDT|0.377400|-3.74|-12.80|-3.86|61948313|2.65|
|HYPE_USDT|82.808000|-3.60|3.69|-3.72|78112860|0.12|
|PEPE_USDT|0.000005|-3.49|2.92|-3.61|122146121|0.20|
|PENGU_USDT|0.007218|-3.00|-6.93|-3.12|6340815|1.39|
|FET_USDT|0.158500|-2.93|-12.76|-3.05|7480337|6.31|
|NEAR_USDT|4.036000|-2.60|-12.81|-2.72|68001544|2.48|
|ENA_USDT|0.181080|-2.52|-7.69|-2.64|88302613|0.55|
|SEI_USDT|0.049010|-2.38|-7.26|-2.50|5813255|2.04|
|AVAX_USDT|8.764000|-2.04|-1.38|-2.16|21652954|1.14|
|ONDO_USDT|0.405100|-1.67|-3.36|-1.79|20829173|2.47|
|DOT_USDT|0.957000|-1.23|-4.64|-1.35|11998017|1.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002243|0.002070|0.002243|1.52|N|Y/Y|Y/Y|N|N|
|AVAX_USDT|8.764000|8.721000|8.764000|0.80|N|N/N|N/N|N|N|
|BTW_USDT|1.028300|1.016200|1.028300|0.98|N|Y/Y|Y/Y|N|N|
|ENA_USDT|0.181080|0.179150|0.181080|0.46|N|N/N|N/N|N|N|
|FARTCOIN_USDT|0.124790|0.123820|0.124790|1.77|N|N/N|N/N|N|N|
|FET_USDT|0.158500|0.157900|0.158500|0.73|N|Y/Y|N/N|N|N|
|HYPE_USDT|82.808000|83.126000|82.808000|4.43|Y|Y/Y|Y/Y|N|Y|
|NEAR_USDT|4.036000|4.006000|4.036000|0.83|N|N/N|Y/Y|N|N|
|ONDO_USDT|0.405100|0.404900|0.405100|2.02|N|Y/N|N/N|N|N|
|PENGU_USDT|0.007218|0.007163|0.007218|0.68|N|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.87|N|N/Y|N/N|N|N|
|SEI_USDT|0.049010|0.048400|0.049010|1.87|N|N/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.263000|1.254000|1.263000|1.53|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377400|0.373400|0.377300|1.21|N|N/N|Y/Y|N|N|
|ZRO_USDT|1.772500|1.771200|1.772500|2.54|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.002757, depth_time=2026-11-05T10:15:08+00:00, book20_bid_proxy_usdt=58201, book20_ask_proxy_usdt=43064, funding_indicative=-0.009689, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.17%, turnover=16877255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=8.808000, depth_time=2026-11-05T10:15:41+00:00, book20_bid_proxy_usdt=2239309, book20_ask_proxy_usdt=705234, funding_indicative=0.000097, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=21652954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=1.051000, depth_time=2026-11-05T10:15:13+00:00, book20_bid_proxy_usdt=15290, book20_ask_proxy_usdt=14907, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.43%, turnover=5141464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.182070, depth_time=2026-11-05T10:15:33+00:00, book20_bid_proxy_usdt=171711, book20_ask_proxy_usdt=111587, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=88302613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.125790, depth_time=2026-11-05T10:15:17+00:00, book20_bid_proxy_usdt=90964, book20_ask_proxy_usdt=74187, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=16184367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.160700, depth_time=2026-11-05T10:15:29+00:00, book20_bid_proxy_usdt=2002130, book20_ask_proxy_usdt=1188843, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=7480337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=84.033000, depth_time=2026-11-05T10:15:23+00:00, book20_bid_proxy_usdt=84955, book20_ask_proxy_usdt=138689, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.60%, turnover=78112860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T10:15:00+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=4.051000, depth_time=2026-11-05T10:15:34+00:00, book20_bid_proxy_usdt=3810774, book20_ask_proxy_usdt=5378606, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=68001544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.411600, depth_time=2026-11-05T10:15:44+00:00, book20_bid_proxy_usdt=2210298, book20_ask_proxy_usdt=2035126, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=20829173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.007286, depth_time=2026-11-05T10:15:28+00:00, book20_bid_proxy_usdt=323263, book20_ask_proxy_usdt=243286, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=6340815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.000005, depth_time=2026-11-05T10:15:25+00:00, book20_bid_proxy_usdt=51349, book20_ask_proxy_usdt=43442, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=122146121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.049230, depth_time=2026-11-05T10:15:39+00:00, book20_bid_proxy_usdt=317514, book20_ask_proxy_usdt=294810, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=5813255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=1.278000, depth_time=2026-11-05T10:15:10+00:00, book20_bid_proxy_usdt=1508364, book20_ask_proxy_usdt=1543389, funding_indicative=-0.000335, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.30%, turnover=25611322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=0.382100, depth_time=2026-11-05T10:15:21+00:00, book20_bid_proxy_usdt=2724818, book20_ask_proxy_usdt=2329486, funding_indicative=-0.000178, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=61948313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T10:15:01+00:00, last15m_closed_end=2026-11-05T10:15+00:00, prior8high=1.820200, depth_time=2026-11-05T10:15:14+00:00, book20_bid_proxy_usdt=73540, book20_ask_proxy_usdt=32610, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.94%, turnover=7484104. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
