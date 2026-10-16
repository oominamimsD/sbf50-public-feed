# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T20:45:41Z**
- feed_generated_utc: 2026-10-16T20:45:43+00:00
- source_sha256: `589e6f805c9c9ed6aef159f17a42b2dd308e0b47f86133716bd3552daa7fa586`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T20:45+00:00, close=81687.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.196350|-4.23|61.39|-4.67|20507129|1.02|
|INJ_USDT|8.604000|-4.16|24.17|-4.60|116836087|1.16|
|ZEC_USDT|1147.040000|-3.44|-5.85|-3.88|1496740423|0.09|
|RIVER_USDT|1.092000|-3.01|-7.61|-3.45|5981112|9.15|
|OP_USDT|0.136140|-2.75|10.48|-3.19|15048896|0.73|
|FILECOIN_USDT|1.135600|-2.67|6.13|-3.11|25119330|0.88|
|TAO_USDT|274.240000|-2.27|-0.15|-2.71|82345731|1.09|
|STRK_USDT|0.072640|-1.77|-3.54|-2.21|24214157|4.13|
|PYTH_USDT|0.084820|-1.69|-0.66|-2.13|5158557|1.18|
|APT_USDT|0.842200|-1.62|5.20|-2.06|12758586|1.19|
|HBAR_USDT|0.082850|-1.49|-8.81|-1.93|21253535|1.21|
|ARB_USDT|0.192050|-1.48|6.22|-1.92|33506790|0.52|
|FARTCOIN_USDT|0.152880|-1.18|-6.42|-1.62|7467982|0.65|
|NEAR_USDT|4.996000|-0.99|5.15|-1.43|177052961|2.00|
|ICP_USDT|3.010000|-0.92|-0.29|-1.36|9215222|3.32|
|AVAX_USDT|10.000000|-0.82|-1.88|-1.26|127758521|3.00|
|ENA_USDT|0.198390|-0.77|-7.97|-1.21|40612732|0.50|
|AAVE_USDT|156.060000|-0.77|-8.11|-1.21|32333920|0.64|
|ONDO_USDT|0.453700|-0.74|-5.49|-1.18|29566297|2.21|
|ETH_USDT|2413.660000|-0.68|-2.97|-1.12|1793274917|0.04|
|WLD_USDT|0.505700|-0.58|2.68|-1.02|95608996|1.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.842200|0.829800|0.842200|1.19|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192050|0.190240|0.192050|0.25|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.196350|0.193710|0.196350|0.41|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.152880|0.151250|0.152880|0.11|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.135600|1.126700|1.135600|0.79|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.082850|0.082050|0.082850|1.09|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.010000|2.985000|3.010000|0.36|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.604000|8.542000|8.604000|2.00|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.996000|4.952000|4.997000|0.47|N|Y/Y|Y/N|Y|N|
|OP_USDT|0.136140|0.134240|0.136140|0.20|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.084820|0.083060|0.084820|0.55|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.092000|1.066000|1.092000|0.81|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.072640|0.071560|0.072640|0.38|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.240000|272.300000|274.240000|0.36|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1147.040000|1131.850000|1147.040000|0.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.845100, depth_time=2026-10-16T20:45:28+00:00, book20_bid_proxy_usdt=199309, book20_ask_proxy_usdt=145598, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=12758586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.194080, depth_time=2026-10-16T20:45:33+00:00, book20_bid_proxy_usdt=51119, book20_ask_proxy_usdt=48511, funding_indicative=-0.000002, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=33506790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T20:44:59+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.199860, depth_time=2026-10-16T20:45:07+00:00, book20_bid_proxy_usdt=35212, book20_ask_proxy_usdt=22099, funding_indicative=-0.000127, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=20507129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.153850, depth_time=2026-10-16T20:45:36+00:00, book20_bid_proxy_usdt=76516, book20_ask_proxy_usdt=70430, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=7467982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=1.145500, depth_time=2026-10-16T20:45:19+00:00, book20_bid_proxy_usdt=453421, book20_ask_proxy_usdt=595373, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=25119330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.083130, depth_time=2026-10-16T20:45:29+00:00, book20_bid_proxy_usdt=1324038, book20_ask_proxy_usdt=706784, funding_indicative=0.000014, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=21253535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=3.024000, depth_time=2026-10-16T20:45:40+00:00, book20_bid_proxy_usdt=1172619, book20_ask_proxy_usdt=1145653, funding_indicative=0.000083, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=9215222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=8.745000, depth_time=2026-10-16T20:45:10+00:00, book20_bid_proxy_usdt=190213, book20_ask_proxy_usdt=186075, funding_indicative=-0.000026, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=116836087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-16T20:44:59+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=5.051000, depth_time=2026-10-16T20:45:38+00:00, book20_bid_proxy_usdt=4746363, book20_ask_proxy_usdt=3113425, funding_indicative=0.000016, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=177052961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.137590, depth_time=2026-10-16T20:45:17+00:00, book20_bid_proxy_usdt=56958, book20_ask_proxy_usdt=50315, funding_indicative=0.000026, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=15048896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.084430, depth_time=2026-10-16T20:45:25+00:00, book20_bid_proxy_usdt=134889, book20_ask_proxy_usdt=52509, funding_indicative=-0.000072, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=5158557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=1.102000, depth_time=2026-10-16T20:45:15+00:00, book20_bid_proxy_usdt=571919, book20_ask_proxy_usdt=370681, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=5981112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=0.073170, depth_time=2026-10-16T20:45:23+00:00, book20_bid_proxy_usdt=402235, book20_ask_proxy_usdt=319402, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=24214157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T20:45:00+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=276.400000, depth_time=2026-10-16T20:45:22+00:00, book20_bid_proxy_usdt=245948, book20_ask_proxy_usdt=173020, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=82345731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T20:44:59+00:00, last15m_closed_end=2026-10-16T20:45+00:00, prior8high=1154.950000, depth_time=2026-10-16T20:45:12+00:00, book20_bid_proxy_usdt=143354, book20_ask_proxy_usdt=463048, funding_indicative=0.000096, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=1496740423. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
