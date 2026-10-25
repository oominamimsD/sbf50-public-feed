# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T07:00:46Z**
- feed_generated_utc: 2026-10-25T07:00:50+00:00
- source_sha256: `834a296f1d8d45ecaf5bd4b8de3522aaec2b445ea00ee6e66ad98ce4e70949c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T07:00+00:00, close=80457.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T07:00+00:00, close=80457.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.082940|-24.92|70.93|-25.79|6424661|4.83|
|ORDER_USDT|0.055320|-17.92|78.73|-18.79|13805719|1.81|
|IRYS_USDT|0.039880|-13.39|212.53|-14.26|33688877|2.51|
|BTW_USDT|1.603900|-7.89|-29.32|-8.76|11092637|5.62|
|STRK_USDT|0.046030|-2.70|-30.41|-3.57|8421285|2.17|
|DOT_USDT|1.021400|-1.70|-8.59|-2.57|11864249|1.96|
|PENGU_USDT|0.007440|-1.45|-0.17|-2.32|5617530|1.34|
|SUI_USDT|0.915100|-1.35|-6.79|-2.22|66462169|1.09|
|TIA_USDT|0.527400|-1.23|-19.84|-2.10|20575453|1.90|
|ARB_USDT|0.165450|-1.03|-10.04|-1.90|14775576|0.60|
|SEI_USDT|0.052780|-0.97|-14.88|-1.84|9616637|1.89|
|APT_USDT|0.700000|-0.93|-12.22|-1.80|5841919|2.86|
|LINK_USDT|11.356000|-0.90|-4.61|-1.77|48384373|0.88|
|AKE_USDT|0.028827|-0.90|-0.46|-1.77|6515532|3.12|
|ONDO_USDT|0.403000|-0.39|-8.32|-1.26|14893934|2.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028827|0.029027|0.028827|1.34|Y|Y/Y|Y/Y|Y|Y|
|APT_USDT|0.700000|0.698800|0.700000|1.40|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165450|0.165670|0.165450|1.70|Y|Y/Y|Y/Y|Y|Y|
|BIRB_USDT|0.082940|0.081650|0.082940|0.59|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.603900|1.700300|1.598500|10.66|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|1.021400|1.027100|1.022400|15.34|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.039880|0.039230|0.039870|0.42|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.356000|11.370000|11.356000|2.16|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.403000|0.403100|0.403000|1.61|Y|Y/Y|Y/Y|Y|Y|
|ORDER_USDT|0.055320|0.054500|0.055310|0.50|N|Y/N|N/N|Y|N|
|PENGU_USDT|0.007440|0.007444|0.007440|1.61|Y|Y/Y|Y/Y|Y|Y|
|SEI_USDT|0.052780|0.052880|0.052780|4.79|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.046030|0.045690|0.046030|1.63|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.915100|0.914900|0.915100|6.82|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.527400|0.528400|0.527400|1.65|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.031066, depth_time=2026-10-25T07:00:42+00:00, book20_bid_proxy_usdt=13797, book20_ask_proxy_usdt=11993, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=6515532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.713900, depth_time=2026-10-25T07:00:38+00:00, book20_bid_proxy_usdt=120579, book20_ask_proxy_usdt=188672, funding_indicative=-0.000028, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=5841919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.168320, depth_time=2026-10-25T07:00:31+00:00, book20_bid_proxy_usdt=103384, book20_ask_proxy_usdt=119252, funding_indicative=0.000019, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=14775576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.090200, depth_time=2026-10-25T07:00:09+00:00, book20_bid_proxy_usdt=17671, book20_ask_proxy_usdt=16157, funding_indicative=-0.012035, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-24.92%, turnover=6424661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=1.912800, depth_time=2026-10-25T07:00:17+00:00, book20_bid_proxy_usdt=3836, book20_ask_proxy_usdt=8322, funding_indicative=-0.005316, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.89%, turnover=11092637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=1.042400, depth_time=2026-10-25T07:00:22+00:00, book20_bid_proxy_usdt=286198, book20_ask_proxy_usdt=296997, funding_indicative=-0.000107, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=11864249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.046460, depth_time=2026-10-25T07:00:15+00:00, book20_bid_proxy_usdt=25005, book20_ask_proxy_usdt=45348, funding_indicative=-0.002197, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-13.39%, turnover=33688877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=11.595000, depth_time=2026-10-25T07:00:40+00:00, book20_bid_proxy_usdt=370876, book20_ask_proxy_usdt=473270, funding_indicative=0.000068, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=48384373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.410100, depth_time=2026-10-25T07:00:45+00:00, book20_bid_proxy_usdt=2312900, book20_ask_proxy_usdt=3054971, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=14893934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.063890, depth_time=2026-10-25T07:00:12+00:00, book20_bid_proxy_usdt=74265, book20_ask_proxy_usdt=68703, funding_indicative=-0.001402, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-17.92%, turnover=13805719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.007591, depth_time=2026-10-25T07:00:25+00:00, book20_bid_proxy_usdt=182547, book20_ask_proxy_usdt=342908, funding_indicative=-0.000031, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=5617530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.053800, depth_time=2026-10-25T07:00:35+00:00, book20_bid_proxy_usdt=205784, book20_ask_proxy_usdt=389420, funding_indicative=-0.000076, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=9616637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.047320, depth_time=2026-10-25T07:00:19+00:00, book20_bid_proxy_usdt=754585, book20_ask_proxy_usdt=783710, funding_indicative=0.000042, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=8421285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.933700, depth_time=2026-10-25T07:00:27+00:00, book20_bid_proxy_usdt=1386068, book20_ask_proxy_usdt=1232361, funding_indicative=0.000028, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=66462169. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T07:00:01+00:00, last15m_closed_end=2026-10-25T07:00+00:00, prior8high=0.534400, depth_time=2026-10-25T07:00:28+00:00, book20_bid_proxy_usdt=253953, book20_ask_proxy_usdt=228262, funding_indicative=-0.000005, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=20575453. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
