# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T23:00:43Z**
- feed_generated_utc: 2026-10-21T23:00:46+00:00
- source_sha256: `c683646d1a2ff5f33c40dd1adb665d0b6e576fcea02557dab46b09096b8f4d8b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T23:00+00:00, close=84408, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T23:00+00:00, close=84408, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002323|-18.31|63.82|-18.21|9169390|4.30|
|BR_USDT|0.489470|-9.61|20.04|-9.51|15099448|4.29|
|AKE_USDT|0.024617|-7.76|-4.88|-7.66|10786043|0.41|
|ZRO_USDT|1.951700|-6.93|3.05|-6.83|7840325|0.51|
|STRK_USDT|0.058270|-5.97|-24.50|-5.87|24022475|1.72|
|TIA_USDT|0.607600|-3.93|13.88|-3.83|40283853|1.65|
|ARB_USDT|0.190950|-2.87|4.83|-2.77|34459686|0.52|
|DOT_USDT|1.149800|-2.55|2.24|-2.45|16773548|0.87|
|FET_USDT|0.195700|-2.44|-4.02|-2.34|7759689|5.11|
|LDO_USDT|0.405700|-2.28|-0.02|-2.18|5288619|2.46|
|OP_USDT|0.129040|-2.16|-6.72|-2.06|6915655|1.55|
|AVAX_USDT|9.703000|-2.14|-1.16|-2.04|158042883|1.03|
|ICP_USDT|2.909000|-1.92|-2.93|-1.82|5712691|3.44|
|APT_USDT|0.820700|-1.78|3.79|-1.68|8290803|1.22|
|AAVE_USDT|155.770000|-1.72|-0.07|-1.62|134531099|0.64|
|TAO_USDT|272.910000|-1.66|1.84|-1.56|62233285|1.10|
|UNI_USDT|7.500000|-1.57|4.98|-1.47|26900458|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.770000|155.610000|155.770000|0.56|N|Y/N|N/N|N|N|
|AKE_USDT|0.024617|0.024377|0.024616|1.68|N|Y/Y|Y/Y|N|N|
|APT_USDT|0.820700|0.820100|0.820700|1.56|N|Y/Y|N/N|N|N|
|ARB_USDT|0.190950|0.191040|0.190950|0.59|N|Y/N|N/N|N|N|
|AVAX_USDT|9.703000|9.705000|9.703000|0.78|N|Y/N|N/N|N|N|
|BR_USDT|0.489470|0.476760|0.489470|0.35|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002323|0.002312|0.002323|0.79|N|Y/Y|N/N|N|N|
|DOT_USDT|1.149800|1.150100|1.149800|0.62|N|Y/Y|N/N|N|N|
|FET_USDT|0.195700|0.195300|0.195700|0.86|N|Y/N|N/N|N|N|
|ICP_USDT|2.909000|2.910000|2.909000|8.58|Y|Y/Y|N/N|N|N|
|LDO_USDT|0.405700|0.405600|0.405700|1.46|N|Y/Y|N/N|N|N|
|OP_USDT|0.129040|0.129320|0.129040|2.06|Y|Y/Y|N/N|N|N|
|STRK_USDT|0.058270|0.058690|0.058270|1.16|N|Y/N|N/N|N|N|
|TIA_USDT|0.607600|0.607700|0.607600|1.50|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.951700|1.932700|1.951700|0.77|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=157.700000, depth_time=2026-10-21T23:00:42+00:00, book20_bid_proxy_usdt=385891, book20_ask_proxy_usdt=335774, funding_indicative=-0.000026, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=134531099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.025946, depth_time=2026-10-21T23:00:13+00:00, book20_bid_proxy_usdt=24114, book20_ask_proxy_usdt=10426, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.76%, turnover=10786043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.833200, depth_time=2026-10-21T23:00:39+00:00, book20_bid_proxy_usdt=134569, book20_ask_proxy_usdt=138672, funding_indicative=0.000056, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=8290803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.196260, depth_time=2026-10-21T23:00:22+00:00, book20_bid_proxy_usdt=84863, book20_ask_proxy_usdt=58194, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=34459686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=9.877000, depth_time=2026-10-21T23:00:34+00:00, book20_bid_proxy_usdt=1855867, book20_ask_proxy_usdt=1293348, funding_indicative=0.000077, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=158042883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.504950, depth_time=2026-10-21T23:00:10+00:00, book20_bid_proxy_usdt=3693, book20_ask_proxy_usdt=4281, funding_indicative=-0.000169, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.61%, turnover=15099448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.002536, depth_time=2026-10-21T23:00:08+00:00, book20_bid_proxy_usdt=248904, book20_ask_proxy_usdt=140209, funding_indicative=-0.000005, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=1, 24h_change=-18.31%, turnover=9169390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=1.174000, depth_time=2026-10-21T23:00:25+00:00, book20_bid_proxy_usdt=342702, book20_ask_proxy_usdt=316545, funding_indicative=-0.000121, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=16773548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.200300, depth_time=2026-10-21T23:00:27+00:00, book20_bid_proxy_usdt=1451323, book20_ask_proxy_usdt=1090617, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=7759689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=2.959000, depth_time=2026-10-21T23:00:34+00:00, book20_bid_proxy_usdt=1081448, book20_ask_proxy_usdt=999853, funding_indicative=-0.000008, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=5712691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.412500, depth_time=2026-10-21T23:00:28+00:00, book20_bid_proxy_usdt=432260, book20_ask_proxy_usdt=550087, funding_indicative=-0.000003, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=5288619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.132480, depth_time=2026-10-21T23:00:32+00:00, book20_bid_proxy_usdt=113706, book20_ask_proxy_usdt=119190, funding_indicative=-0.000003, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=6915655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.061590, depth_time=2026-10-21T23:00:16+00:00, book20_bid_proxy_usdt=407105, book20_ask_proxy_usdt=520261, funding_indicative=-0.000002, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.97%, turnover=24022475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=0.625800, depth_time=2026-10-21T23:00:20+00:00, book20_bid_proxy_usdt=371656, book20_ask_proxy_usdt=254321, funding_indicative=-0.000136, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=40283853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T22:59:59+00:00, last15m_closed_end=2026-10-21T23:00+00:00, prior8high=2.015800, depth_time=2026-10-21T23:00:15+00:00, book20_bid_proxy_usdt=32626, book20_ask_proxy_usdt=41540, funding_indicative=-0.000028, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.93%, turnover=7840325. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
