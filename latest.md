# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T13:00:38Z**
- feed_generated_utc: 2026-10-28T13:00:42+00:00
- source_sha256: `35d34153c285e6586071ac77e1fd0a94b471d21aa0d64a2c38f7560bad816c4b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T13:00+00:00, close=80708.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T13:00+00:00, close=80708.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053730|-15.49|-56.22|-15.71|19439690|1.86|
|BEAT_USDT|0.079740|-12.46|6.73|-12.68|16029125|2.51|
|AKE_USDT|0.019757|-6.47|-36.45|-6.69|6626275|0.51|
|ENA_USDT|0.199130|-6.41|4.87|-6.63|80466858|0.50|
|INJ_USDT|7.826000|-2.10|-9.00|-2.32|24170913|1.28|
|ARB_USDT|0.164470|-2.06|-12.95|-2.28|15868088|0.61|
|WLD_USDT|0.428300|-1.76|-23.89|-1.98|66297341|2.34|
|DASH_USDT|53.350000|-1.33|6.82|-1.55|15823971|1.88|
|UNI_USDT|7.023000|-1.32|-3.41|-1.54|13778860|1.42|
|BULLA_USDT|0.058110|-1.08|-17.46|-1.30|9560863|5.16|
|STRK_USDT|0.046040|-1.03|-16.97|-1.25|5005837|2.17|
|ADA_USDT|0.202900|-0.87|-8.35|-1.09|33329042|4.93|
|HBAR_USDT|0.075300|-0.79|-9.66|-1.01|9383341|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.202900|0.203200|0.202900|3.10|Y|Y/Y|N/N|N|N|
|AKE_USDT|0.019757|0.019578|0.019757|1.14|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.164470|0.164890|0.164470|3.41|Y|Y/Y|Y/Y|N|Y|
|BEAT_USDT|0.079740|0.074400|0.079740|0.22|N|Y/Y|Y/N|N|N|
|BULLA_USDT|0.058110|0.056250|0.058110|0.23|N|Y/Y|Y/Y|N|N|
|DASH_USDT|53.350000|53.370000|53.350000|1.38|Y|Y/Y|N/N|N|N|
|ENA_USDT|0.199130|0.199880|0.199130|1.49|Y|Y/Y|Y/N|N|N|
|HBAR_USDT|0.075300|0.075180|0.075300|2.05|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.826000|7.826000|7.826000|5.14|N|Y/Y|N/N|N|N|
|Q_USDT|0.053730|0.053250|0.053730|1.73|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.046040|0.046000|0.046040|2.04|N|Y/N|N/Y|N|N|
|UNI_USDT|7.023000|7.019000|7.023000|0.73|N|Y/Y|N/N|N|N|
|WLD_USDT|0.428300|0.425300|0.428300|2.49|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.207700, depth_time=2026-10-28T13:00:36+00:00, book20_bid_proxy_usdt=7301127, book20_ask_proxy_usdt=5498622, funding_indicative=-0.000069, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.87%, turnover=33329042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.020260, depth_time=2026-10-28T13:00:13+00:00, book20_bid_proxy_usdt=10816, book20_ask_proxy_usdt=4229, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.47%, turnover=6626275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.169380, depth_time=2026-10-28T13:00:21+00:00, book20_bid_proxy_usdt=82390, book20_ask_proxy_usdt=103702, funding_indicative=-0.000061, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=15868088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T12:59:59+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.086190, depth_time=2026-10-28T13:00:10+00:00, book20_bid_proxy_usdt=7023, book20_ask_proxy_usdt=9801, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.46%, turnover=16029125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T12:59:59+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.063450, depth_time=2026-10-28T13:00:31+00:00, book20_bid_proxy_usdt=19717, book20_ask_proxy_usdt=8310, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=9560863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=53.830000, depth_time=2026-10-28T13:00:26+00:00, book20_bid_proxy_usdt=633551, book20_ask_proxy_usdt=668916, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=15823971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T12:59:59+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.207950, depth_time=2026-10-28T13:00:16+00:00, book20_bid_proxy_usdt=179711, book20_ask_proxy_usdt=264766, funding_indicative=-0.000018, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=80466858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.076630, depth_time=2026-10-28T13:00:37+00:00, book20_bid_proxy_usdt=1182138, book20_ask_proxy_usdt=1015572, funding_indicative=0.000035, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=9383341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=7.964000, depth_time=2026-10-28T13:00:18+00:00, book20_bid_proxy_usdt=208324, book20_ask_proxy_usdt=315650, funding_indicative=0.000194, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=24170913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T12:59:59+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.058330, depth_time=2026-10-28T13:00:07+00:00, book20_bid_proxy_usdt=22000, book20_ask_proxy_usdt=43489, funding_indicative=-0.000661, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.49%, turnover=19439690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.048070, depth_time=2026-10-28T13:00:33+00:00, book20_bid_proxy_usdt=499266, book20_ask_proxy_usdt=806068, funding_indicative=-0.000012, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=5005837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T13:00:00+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=7.188000, depth_time=2026-10-28T13:00:29+00:00, book20_bid_proxy_usdt=1904579, book20_ask_proxy_usdt=2634864, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=13778860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T12:59:59+00:00, last15m_closed_end=2026-10-28T13:00+00:00, prior8high=0.439300, depth_time=2026-10-28T13:00:24+00:00, book20_bid_proxy_usdt=3408752, book20_ask_proxy_usdt=3971182, funding_indicative=-0.000096, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=66297341. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
