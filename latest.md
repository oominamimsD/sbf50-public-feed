# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T10:00:40Z**
- feed_generated_utc: 2026-11-08T10:00:41+00:00
- source_sha256: `c96dc5135f47330a170e94ca373f8bb64fd819e8f03e6c22632d3472623302a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T10:00+00:00, close=75899.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T10:00+00:00, close=75899.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.426700|-3.24|-12.93|-3.46|7353788|2.34|
|ENA_USDT|0.153970|-2.66|-20.63|-2.88|27958268|0.65|
|WLD_USDT|0.327900|-2.52|-18.91|-2.74|23890982|3.05|
|PUMPFUN_USDT|0.003667|-2.00|-12.31|-2.22|16651558|2.73|
|QNT_USDT|195.800000|-1.66|-2.61|-1.88|42091618|1.53|
|ADA_USDT|0.179700|-1.58|-7.17|-1.80|9738163|5.57|
|SUI_USDT|0.848600|-1.41|-5.92|-1.63|21279389|1.18|
|DOGE_USDT|0.070840|-1.40|-6.34|-1.62|39695970|1.41|
|AVAX_USDT|8.162000|-1.10|-4.37|-1.32|8094827|1.23|
|XLM_USDT|0.150230|-1.07|-12.52|-1.29|16584501|0.67|
|ONDO_USDT|0.360300|-1.07|-12.63|-1.29|8002144|2.78|
|AAVE_USDT|130.450000|-0.98|-3.73|-1.20|10286463|0.77|
|HYPE_USDT|77.178000|-0.84|-11.83|-1.06|20463300|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.450000|129.470000|130.450000|1.43|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179700|0.178900|0.179700|2.56|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.162000|8.114000|8.162000|1.06|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.070840|0.070450|0.070840|0.96|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153970|0.152950|0.153980|0.89|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|77.178000|76.688000|77.178000|2.47|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360300|0.358000|0.360300|1.73|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003667|0.003648|0.003667|1.91|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.800000|193.880000|195.800000|1.74|N|N/Y|Y/Y|Y|N|
|SUI_USDT|0.848600|0.846700|0.848600|0.92|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.426700|0.424900|0.426700|1.58|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327900|0.325700|0.327900|0.76|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.150230|0.149640|0.150230|0.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=130.820000, depth_time=2026-11-08T10:00:33+00:00, book20_bid_proxy_usdt=320746, book20_ask_proxy_usdt=445147, funding_indicative=0.000018, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=10286463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.180600, depth_time=2026-11-08T10:00:21+00:00, book20_bid_proxy_usdt=9415763, book20_ask_proxy_usdt=7960303, funding_indicative=-0.000036, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=9738163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=8.195000, depth_time=2026-11-08T10:00:26+00:00, book20_bid_proxy_usdt=2550670, book20_ask_proxy_usdt=2077808, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=8094827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.071310, depth_time=2026-11-08T10:00:25+00:00, book20_bid_proxy_usdt=3354788, book20_ask_proxy_usdt=6093730, funding_indicative=0.000052, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=39695970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.154850, depth_time=2026-11-08T10:00:09+00:00, book20_bid_proxy_usdt=251675, book20_ask_proxy_usdt=299696, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=27958268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=77.515000, depth_time=2026-11-08T10:00:35+00:00, book20_bid_proxy_usdt=105007, book20_ask_proxy_usdt=117453, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=20463300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.360600, depth_time=2026-11-08T10:00:34+00:00, book20_bid_proxy_usdt=2064458, book20_ask_proxy_usdt=1781370, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.07%, turnover=8002144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.003692, depth_time=2026-11-08T10:00:16+00:00, book20_bid_proxy_usdt=2664644, book20_ask_proxy_usdt=2297401, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=16651558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=196.110000, depth_time=2026-11-08T10:00:14+00:00, book20_bid_proxy_usdt=88548, book20_ask_proxy_usdt=67820, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=42091618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.855500, depth_time=2026-11-08T10:00:23+00:00, book20_bid_proxy_usdt=1551162, book20_ask_proxy_usdt=1112563, funding_indicative=-0.000017, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=21279389. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.431400, depth_time=2026-11-08T10:00:07+00:00, book20_bid_proxy_usdt=350058, book20_ask_proxy_usdt=351055, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.24%, turnover=7353788. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.330400, depth_time=2026-11-08T10:00:09+00:00, book20_bid_proxy_usdt=4070113, book20_ask_proxy_usdt=3786350, funding_indicative=-0.000065, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=23890982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-08T10:00:01+00:00, last15m_closed_end=2026-11-08T10:00+00:00, prior8high=0.151030, depth_time=2026-11-08T10:00:30+00:00, book20_bid_proxy_usdt=198834, book20_ask_proxy_usdt=222565, funding_indicative=-0.000046, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=16584501. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
