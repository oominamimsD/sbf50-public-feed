# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T22:30:45Z**
- feed_generated_utc: 2026-11-02T22:30:48+00:00
- source_sha256: `f1fd54cef20ba13350f4b6e3fb87e3098e1c1b01614536913956c727e4dfcb40`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T22:30+00:00, close=76857.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T22:00+00:00, close=76830.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.985700|-10.12|-17.56|-9.30|9610978|9.14|
|ZEC_USDT|1151.170000|-8.20|-7.73|-7.38|1882679477|0.09|
|XPL_USDT|0.066740|-4.08|-10.16|-3.26|10551545|3.00|
|QNT_USDT|194.370000|-3.99|-7.56|-3.17|49957847|0.51|
|PUMPFUN_USDT|0.003943|-3.92|-8.89|-3.10|9434955|2.54|
|ZRO_USDT|1.702200|-3.73|-0.28|-2.91|6070706|0.59|
|NEAR_USDT|3.879000|-3.26|-15.17|-2.44|83931148|2.58|
|AAVE_USDT|126.940000|-2.77|-7.16|-1.95|23483191|0.79|
|XLM_USDT|0.163290|-2.57|-3.71|-1.75|33529896|0.61|
|ENA_USDT|0.170730|-2.46|-18.84|-1.64|75338310|0.59|
|TIA_USDT|0.445700|-2.45|-16.80|-1.63|12423925|2.24|
|DASH_USDT|46.190000|-2.13|-11.54|-1.31|10299758|2.16|
|ARB_USDT|0.155960|-2.11|-8.25|-1.29|13583482|0.64|
|TRUMPOFFICIAL_USDT|1.602000|-2.07|-5.15|-1.25|12557789|6.24|
|OP_USDT|0.110170|-2.01|-1.36|-1.19|12159224|0.91|
|LIT_USDT|3.047700|-1.90|-2.26|-1.08|10503542|0.33|
|HYPE_USDT|84.111000|-1.86|7.22|-1.04|106648287|0.12|
|SOL_USDT|91.790000|-1.83|-9.86|-1.01|770387816|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.940000|126.730000|126.940000|0.78|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155960|0.155130|0.155960|1.95|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.985700|1.052400|0.984800|3.98|Y|N/N|Y/Y|Y|N|
|DASH_USDT|46.190000|45.690000|46.190000|0.17|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170730|0.169020|0.170770|1.15|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.879000|3.856000|3.879000|1.21|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.110170|0.109650|0.110190|0.78|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003943|0.003913|0.003944|0.18|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.370000|192.940000|194.310000|1.14|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.445700|0.441500|0.445700|0.92|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.602000|1.576000|1.602000|0.78|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163290|0.163520|0.163300|0.62|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066740|0.066130|0.066700|1.47|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1151.170000|1135.710000|1151.760000|0.67|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.702200|1.692200|1.702700|2.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T22:30:02+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=128.160000, depth_time=2026-11-02T22:30:24+00:00, book20_bid_proxy_usdt=382493, book20_ask_proxy_usdt=416539, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=23483191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.157480, depth_time=2026-11-02T22:30:38+00:00, book20_bid_proxy_usdt=79910, book20_ask_proxy_usdt=91724, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=13583482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=1.087000, depth_time=2026-11-02T22:30:08+00:00, book20_bid_proxy_usdt=20814, book20_ask_proxy_usdt=15253, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.12%, turnover=9610978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=46.500000, depth_time=2026-11-02T22:30:30+00:00, book20_bid_proxy_usdt=571678, book20_ask_proxy_usdt=610570, funding_indicative=0.000047, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=10299758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T22:30:02+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.172390, depth_time=2026-11-02T22:30:29+00:00, book20_bid_proxy_usdt=208246, book20_ask_proxy_usdt=105018, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=75338310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T22:30:02+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=3.936000, depth_time=2026-11-02T22:30:21+00:00, book20_bid_proxy_usdt=3530428, book20_ask_proxy_usdt=4041922, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=83931148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.111180, depth_time=2026-11-02T22:30:45+00:00, book20_bid_proxy_usdt=94890, book20_ask_proxy_usdt=95327, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=12159224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.003996, depth_time=2026-11-02T22:30:16+00:00, book20_bid_proxy_usdt=1633005, book20_ask_proxy_usdt=1918916, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=9434955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T22:30:02+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=197.490000, depth_time=2026-11-02T22:30:15+00:00, book20_bid_proxy_usdt=65311, book20_ask_proxy_usdt=69642, funding_indicative=0.000090, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=49957847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.452100, depth_time=2026-11-02T22:30:33+00:00, book20_bid_proxy_usdt=238434, book20_ask_proxy_usdt=237033, funding_indicative=0.000046, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=12423925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=1.612000, depth_time=2026-11-02T22:30:40+00:00, book20_bid_proxy_usdt=2082684, book20_ask_proxy_usdt=1926008, funding_indicative=-0.000014, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=12557789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.165410, depth_time=2026-11-02T22:30:27+00:00, book20_bid_proxy_usdt=127603, book20_ask_proxy_usdt=129074, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=33529896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=0.067390, depth_time=2026-11-02T22:30:13+00:00, book20_bid_proxy_usdt=361958, book20_ask_proxy_usdt=519212, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=10551545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T22:30:02+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=1164.850000, depth_time=2026-11-02T22:30:10+00:00, book20_bid_proxy_usdt=383258, book20_ask_proxy_usdt=66638, funding_indicative=0.000046, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.20%, turnover=1882679477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T22:30:03+00:00, last15m_closed_end=2026-11-02T22:30+00:00, prior8high=1.727400, depth_time=2026-11-02T22:30:20+00:00, book20_bid_proxy_usdt=61659, book20_ask_proxy_usdt=69923, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=6070706. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
