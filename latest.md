# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T09:00:43Z**
- feed_generated_utc: 2026-10-25T09:00:47+00:00
- source_sha256: `28fc0055f50c6980212f314f13624aff9b3b06fc72776a133e271d1080386192`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T09:00+00:00, close=80374.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T09:00+00:00, close=80374.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.049380|-27.45|59.54|-28.21|13426153|2.03|
|IRYS_USDT|0.035080|-23.82|174.92|-24.58|32987416|2.85|
|BTW_USDT|1.658200|-4.62|-26.93|-5.38|11508917|2.41|
|WLD_USDT|0.442000|-4.32|-10.81|-5.08|92372803|4.53|
|STRK_USDT|0.045340|-2.97|-31.45|-3.73|8966444|2.21|
|DOT_USDT|1.020200|-2.75|-8.69|-3.51|11804024|0.98|
|PENGU_USDT|0.007350|-2.64|-1.38|-3.40|5530866|1.36|
|SEI_USDT|0.052200|-2.06|-15.82|-2.82|7653721|3.83|
|APT_USDT|0.692500|-1.99|-13.16|-2.75|5908395|1.45|
|SUI_USDT|0.909600|-1.95|-7.35|-2.71|66345434|1.10|
|ARB_USDT|0.163910|-1.95|-10.87|-2.71|15059754|0.61|
|TIA_USDT|0.526100|-1.47|-20.04|-2.23|20488349|1.90|
|ONDO_USDT|0.398900|-1.40|-9.25|-2.16|14905746|2.51|
|OP_USDT|0.110150|-0.71|-14.61|-1.47|5854210|0.91|
|XLM_USDT|0.168490|-0.57|-4.82|-1.33|11440304|0.59|
|LINK_USDT|11.320000|-0.54|-4.92|-1.30|48832782|0.88|
|AKE_USDT|0.028954|-0.46|-0.02|-1.22|5633583|0.69|
|INJ_USDT|7.556000|-0.32|-10.70|-1.08|13215856|1.32|
|AAVE_USDT|135.500000|-0.28|-10.85|-1.04|24462263|0.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.692500|0.689400|0.692800|0.98|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.163910|0.163510|0.163910|1.66|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.658200|1.590000|1.658200|0.54|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.020200|1.017100|1.020200|2.99|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035080|0.036180|0.035090|1.27|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.398900|0.399100|0.398900|2.49|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.110150|0.110150|0.110150|2.86|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.049380|0.048780|0.049380|1.47|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007350|0.007348|0.007350|6.46|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052200|0.052260|0.052200|0.47|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045340|0.045350|0.045370|1.26|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.909600|0.908300|0.909500|1.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.526100|0.523100|0.526100|2.40|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.442000|0.450600|0.442100|5.78|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.168490|0.168670|0.168490|3.06|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.703200, depth_time=2026-10-25T09:00:28+00:00, book20_bid_proxy_usdt=103788, book20_ask_proxy_usdt=153471, funding_indicative=-0.000062, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=5908395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.166810, depth_time=2026-10-25T09:00:33+00:00, book20_bid_proxy_usdt=63370, book20_ask_proxy_usdt=103852, funding_indicative=0.000028, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=15059754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=1.915400, depth_time=2026-10-25T09:00:13+00:00, book20_bid_proxy_usdt=8310, book20_ask_proxy_usdt=8988, funding_indicative=-0.012455, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=11508917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=1.032000, depth_time=2026-10-25T09:00:20+00:00, book20_bid_proxy_usdt=281320, book20_ask_proxy_usdt=243516, funding_indicative=-0.000043, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=11804024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.040650, depth_time=2026-10-25T09:00:10+00:00, book20_bid_proxy_usdt=59843, book20_ask_proxy_usdt=37251, funding_indicative=-0.001587, next_funding_utc=2026-10-25T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.82%, turnover=32987416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.405500, depth_time=2026-10-25T09:00:38+00:00, book20_bid_proxy_usdt=2191121, book20_ask_proxy_usdt=3524751, funding_indicative=0.000044, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=14905746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.112040, depth_time=2026-10-25T09:00:40+00:00, book20_bid_proxy_usdt=56350, book20_ask_proxy_usdt=109037, funding_indicative=-0.000007, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=5854210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.055900, depth_time=2026-10-25T09:00:08+00:00, book20_bid_proxy_usdt=106028, book20_ask_proxy_usdt=91751, funding_indicative=-0.000993, next_funding_utc=2026-10-25T10:00:00+00:00, funding_cycle_h=1, 24h_change=-27.45%, turnover=13426153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.007475, depth_time=2026-10-25T09:00:22+00:00, book20_bid_proxy_usdt=202068, book20_ask_proxy_usdt=316154, funding_indicative=-0.000075, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=5530866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.052970, depth_time=2026-10-25T09:00:24+00:00, book20_bid_proxy_usdt=201752, book20_ask_proxy_usdt=407678, funding_indicative=-0.000097, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=7653721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.046630, depth_time=2026-10-25T09:00:18+00:00, book20_bid_proxy_usdt=692428, book20_ask_proxy_usdt=703749, funding_indicative=0.000037, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=8966444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.921100, depth_time=2026-10-25T09:00:30+00:00, book20_bid_proxy_usdt=607859, book20_ask_proxy_usdt=1506905, funding_indicative=0.000050, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=66345434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.533000, depth_time=2026-10-25T09:00:35+00:00, book20_bid_proxy_usdt=243512, book20_ask_proxy_usdt=256254, funding_indicative=0.000003, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=20488349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T09:00:00+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.466600, depth_time=2026-10-25T09:00:15+00:00, book20_bid_proxy_usdt=1209429, book20_ask_proxy_usdt=1796596, funding_indicative=-0.000030, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=92372803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-25T09:00:01+00:00, last15m_closed_end=2026-10-25T09:00+00:00, prior8high=0.170290, depth_time=2026-10-25T09:00:42+00:00, book20_bid_proxy_usdt=110895, book20_ask_proxy_usdt=171006, funding_indicative=0.000022, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.57%, turnover=11440304. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
