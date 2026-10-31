# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T23:45:42Z**
- feed_generated_utc: 2026-10-31T23:45:45+00:00
- source_sha256: `5dd5f337bbf0b803c187d30d308734c7e54aee941bc61e81749eca5a3db784f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T23:45+00:00, close=77470.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T23:00+00:00, close=77498.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009389|-11.12|15.72|-11.01|7901461|1.06|
|INJ_USDT|7.194000|-3.90|-4.25|-3.79|20814779|1.39|
|TIA_USDT|0.472700|-3.55|-10.08|-3.44|9363285|2.12|
|TRX_USDT|0.302100|-3.27|-8.15|-3.16|10374546|1.66|
|ENA_USDT|0.188810|-2.68|1.08|-2.57|46184588|0.53|
|Q_USDT|0.031270|-2.52|-60.38|-2.41|10617897|3.20|
|FET_USDT|0.159300|-2.44|-7.54|-2.33|5893896|6.28|
|AKE_USDT|0.010870|-2.40|-62.81|-2.29|11914389|0.92|
|IDOL_USDT|0.017110|-2.34|116.58|-2.23|6168955|2.34|
|ZEC_USDT|1255.330000|-2.27|9.61|-2.16|1073377792|0.64|
|BTW_USDT|1.099200|-2.02|-36.87|-1.91|5494114|1.82|
|FARTCOIN_USDT|0.120170|-1.49|-1.48|-1.38|6631246|0.83|
|WLD_USDT|0.399400|-1.23|-13.54|-1.12|34786781|2.50|
|APT_USDT|0.633100|-1.20|-9.80|-1.09|5041136|1.58|
|XLM_USDT|0.169730|-1.17|0.78|-1.06|21966435|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010870|0.010913|0.010870|0.49|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.633100|0.631000|0.633100|8.63|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009389|0.009300|0.009389|0.34|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.099200|1.086300|1.099200|0.56|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188810|0.187820|0.188810|0.21|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120170|0.119850|0.120170|0.44|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159300|0.159300|0.159300|1.06|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.017110|0.016831|0.017111|0.35|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.194000|7.198000|7.194000|1.24|N|Y/N|Y/Y|Y|N|
|Q_USDT|0.031270|0.031320|0.031270|0.75|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.472700|0.473500|0.472700|1.17|N|N/Y|Y/Y|Y|N|
|TRX_USDT|0.302100|0.300760|0.302060|0.58|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399400|0.396700|0.399400|0.44|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169730|0.169620|0.169730|0.87|N|N/N|N/N|Y|N|
|ZEC_USDT|1255.330000|1243.100000|1255.270000|1.32|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.011387, depth_time=2026-10-31T23:45:24+00:00, book20_bid_proxy_usdt=9400, book20_ask_proxy_usdt=10652, funding_indicative=-0.000363, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=11914389. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-31T23:45:00+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.638000, depth_time=2026-10-31T23:45:39+00:00, book20_bid_proxy_usdt=155637, book20_ask_proxy_usdt=186960, funding_indicative=0.000068, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=5041136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.009620, depth_time=2026-10-31T23:45:08+00:00, book20_bid_proxy_usdt=12723, book20_ask_proxy_usdt=9098, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.12%, turnover=7901461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T23:45:00+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=1.118000, depth_time=2026-10-31T23:45:32+00:00, book20_bid_proxy_usdt=28540, book20_ask_proxy_usdt=18584, funding_indicative=-0.000093, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=5494114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.191470, depth_time=2026-10-31T23:45:15+00:00, book20_bid_proxy_usdt=123500, book20_ask_proxy_usdt=159616, funding_indicative=-0.000014, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=46184588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T23:45:00+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.121480, depth_time=2026-10-31T23:45:34+00:00, book20_bid_proxy_usdt=79924, book20_ask_proxy_usdt=75983, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=6631246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T23:45:00+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.161300, depth_time=2026-10-31T23:45:22+00:00, book20_bid_proxy_usdt=1268389, book20_ask_proxy_usdt=955355, funding_indicative=-0.000196, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=5893896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.017310, depth_time=2026-10-31T23:45:27+00:00, book20_bid_proxy_usdt=7893, book20_ask_proxy_usdt=5019, funding_indicative=0.000096, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=6168955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=7.312000, depth_time=2026-10-31T23:45:10+00:00, book20_bid_proxy_usdt=502232, book20_ask_proxy_usdt=264650, funding_indicative=0.000077, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=20814779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.032570, depth_time=2026-10-31T23:45:20+00:00, book20_bid_proxy_usdt=49180, book20_ask_proxy_usdt=33894, funding_indicative=-0.001111, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=1, 24h_change=-2.52%, turnover=10617897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-31T23:45:00+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.478400, depth_time=2026-10-31T23:45:13+00:00, book20_bid_proxy_usdt=224435, book20_ask_proxy_usdt=217272, funding_indicative=-0.000141, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=9363285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.305440, depth_time=2026-10-31T23:45:15+00:00, book20_bid_proxy_usdt=127243, book20_ask_proxy_usdt=105763, funding_indicative=-0.001271, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=10374546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.400500, depth_time=2026-10-31T23:45:37+00:00, book20_bid_proxy_usdt=2710795, book20_ask_proxy_usdt=3467706, funding_indicative=0.000096, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=34786781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-31T23:45:00+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=0.170750, depth_time=2026-10-31T23:45:42+00:00, book20_bid_proxy_usdt=174957, book20_ask_proxy_usdt=203465, funding_indicative=-0.000089, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=21966435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-31T23:44:59+00:00, last15m_closed_end=2026-10-31T23:45+00:00, prior8high=1284.960000, depth_time=2026-10-31T23:45:30+00:00, book20_bid_proxy_usdt=781201, book20_ask_proxy_usdt=893435, funding_indicative=-0.000039, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=1073377792. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
