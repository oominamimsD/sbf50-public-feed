# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T09:15:37Z**
- feed_generated_utc: 2026-11-01T09:15:40+00:00
- source_sha256: `7479a387544d6e3a1396eb2505464e448bf363278cd51c18e322f710484761fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T09:15+00:00, close=78153.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T09:00+00:00, close=78217.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.226290|-23.59|34.76|-24.35|30300539|1.33|
|AKE_USDT|0.009086|-18.42|-68.91|-19.18|9166946|2.20|
|BLESS_USDT|0.009442|-10.62|16.38|-11.38|6038701|2.12|
|XPL_USDT|0.074180|-8.76|2.72|-9.52|6889274|1.35|
|TIA_USDT|0.477100|-2.65|-9.24|-3.41|8226790|2.10|
|ZEC_USDT|1251.950000|-2.53|9.32|-3.29|912665966|3.83|
|ENA_USDT|0.189320|-2.41|1.35|-3.17|43439341|0.53|
|NEAR_USDT|4.383000|-2.07|-0.43|-2.83|52702492|2.28|
|XLM_USDT|0.169180|-1.49|0.45|-2.25|19954584|0.59|
|WLD_USDT|0.398800|-1.38|-13.67|-2.14|31790204|2.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009086|0.008660|0.009096|0.69|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009442|0.009395|0.009442|1.39|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.189320|0.186980|0.189320|0.89|N|N/Y|Y/Y|Y|N|
|LSK_USDT|0.226290|0.219110|0.226370|0.76|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.383000|4.356000|4.382000|1.16|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.477100|0.477200|0.477100|0.88|N|N/N|Y/Y|Y|N|
|WLD_USDT|0.398800|0.398000|0.398800|1.57|N|N/N|Y/Y|Y|N|
|XLM_USDT|0.169180|0.168860|0.169170|1.40|N|N/N|N/Y|Y|N|
|XPL_USDT|0.074180|0.073080|0.074150|0.44|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1251.950000|1239.270000|1250.730000|1.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.009684, depth_time=2026-11-01T09:15:15+00:00, book20_bid_proxy_usdt=13776, book20_ask_proxy_usdt=7634, funding_indicative=-0.003006, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.42%, turnover=9166946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.009599, depth_time=2026-11-01T09:15:17+00:00, book20_bid_proxy_usdt=18522, book20_ask_proxy_usdt=17411, funding_indicative=0.000058, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.62%, turnover=6038701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.189890, depth_time=2026-11-01T09:15:28+00:00, book20_bid_proxy_usdt=206027, book20_ask_proxy_usdt=81646, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=43439341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.233750, depth_time=2026-11-01T09:15:13+00:00, book20_bid_proxy_usdt=14538, book20_ask_proxy_usdt=7907, funding_indicative=-0.002565, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.59%, turnover=30300539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=4.405000, depth_time=2026-11-01T09:15:28+00:00, book20_bid_proxy_usdt=5000129, book20_ask_proxy_usdt=3776075, funding_indicative=0.000096, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=52702492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.481400, depth_time=2026-11-01T09:15:22+00:00, book20_bid_proxy_usdt=207357, book20_ask_proxy_usdt=331194, funding_indicative=-0.000055, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=8226790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.402100, depth_time=2026-11-01T09:15:32+00:00, book20_bid_proxy_usdt=4160790, book20_ask_proxy_usdt=3093997, funding_indicative=-0.000113, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=31790204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.169550, depth_time=2026-11-01T09:15:33+00:00, book20_bid_proxy_usdt=187876, book20_ask_proxy_usdt=188693, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=19954584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=0.075800, depth_time=2026-11-01T09:15:19+00:00, book20_bid_proxy_usdt=425352, book20_ask_proxy_usdt=329039, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.76%, turnover=6889274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T09:15:05+00:00, last15m_closed_end=2026-11-01T09:15+00:00, prior8high=1254.430000, depth_time=2026-11-01T09:15:25+00:00, book20_bid_proxy_usdt=454492, book20_ask_proxy_usdt=42344, funding_indicative=-0.000052, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=912665966. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
