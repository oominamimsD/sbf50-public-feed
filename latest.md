# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T05:30:42Z**
- feed_generated_utc: 2026-10-30T05:30:45+00:00
- source_sha256: `1af4816ee40a7020be51d89a2373929defd99ecaf4466601f7dec7b6c6d47bec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T05:30+00:00, close=78645, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T05:00+00:00, close=78237, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.272500|-18.89|-25.80|-15.11|8007430|3.67|
|TIA_USDT|0.461400|-15.98|-18.82|-12.20|18998808|2.17|
|PYTH_USDT|0.062280|-14.90|-16.04|-11.12|5250752|1.61|
|LDO_USDT|0.325900|-13.87|-14.79|-10.09|6395407|3.07|
|FET_USDT|0.163200|-11.68|-11.92|-7.90|14040789|6.13|
|APT_USDT|0.626300|-10.94|-18.89|-7.16|12918032|1.60|
|PENGU_USDT|0.007248|-10.85|-6.21|-7.07|10125084|1.38|
|FARTCOIN_USDT|0.119910|-10.78|-16.05|-7.00|15137971|0.83|
|BTW_USDT|1.475500|-9.92|-17.56|-6.14|11437487|2.71|
|ETHFI_USDT|0.612500|-9.86|-7.51|-6.08|5953733|1.63|
|TRUMPOFFICIAL_USDT|1.570000|-9.14|-9.97|-5.36|11132256|6.37|
|JUP_USDT|0.256200|-9.08|-17.35|-5.30|6742235|3.90|
|INJ_USDT|7.405000|-8.93|-6.64|-5.15|30894169|2.70|
|ETH_USDT|2247.500000|-5.08|-6.26|-1.30|2491278451|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.626300|0.604100|0.626300|1.26|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.475500|1.445300|1.475500|0.94|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.272500|0.267600|0.273100|0.38|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.612500|0.580100|0.612500|0.76|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2247.500000|2210.010000|2247.990000|0.47|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.119910|0.114070|0.119900|0.63|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163200|0.155700|0.163200|0.49|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.405000|7.071000|7.405000|0.64|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.256200|0.247900|0.256100|0.60|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.325900|0.316300|0.325800|0.91|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007248|0.006841|0.007251|0.29|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.062280|0.059550|0.062280|1.00|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.461400|0.454400|0.461600|1.59|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.570000|1.526000|1.570000|2.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T05:30:02+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.625900, depth_time=2026-10-30T05:30:20+00:00, book20_bid_proxy_usdt=88997, book20_ask_proxy_usdt=121772, funding_indicative=-0.000152, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.94%, turnover=12918032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T05:30:02+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=1.528200, depth_time=2026-10-30T05:30:28+00:00, book20_bid_proxy_usdt=15367, book20_ask_proxy_usdt=12729, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.92%, turnover=11437487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.277500, depth_time=2026-10-30T05:30:08+00:00, book20_bid_proxy_usdt=350908, book20_ask_proxy_usdt=534421, funding_indicative=-0.000018, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-18.89%, turnover=8007430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.614200, depth_time=2026-10-30T05:30:31+00:00, book20_bid_proxy_usdt=195873, book20_ask_proxy_usdt=179788, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=5953733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-10-30T05:30:02+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=2252.740000, depth_time=2026-10-30T05:30:41+00:00, book20_bid_proxy_usdt=2795481, book20_ask_proxy_usdt=2197316, funding_indicative=0.000022, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.08%, turnover=2491278451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.119880, depth_time=2026-10-30T05:30:26+00:00, book20_bid_proxy_usdt=48928, book20_ask_proxy_usdt=55181, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.78%, turnover=15137971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T05:30:02+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.164100, depth_time=2026-10-30T05:30:18+00:00, book20_bid_proxy_usdt=949541, book20_ask_proxy_usdt=745621, funding_indicative=-0.000525, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.68%, turnover=14040789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T05:30:02+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=7.419000, depth_time=2026-10-30T05:30:39+00:00, book20_bid_proxy_usdt=183698, book20_ask_proxy_usdt=167080, funding_indicative=-0.000056, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.93%, turnover=30894169. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.256900, depth_time=2026-10-30T05:30:35+00:00, book20_bid_proxy_usdt=475253, book20_ask_proxy_usdt=530053, funding_indicative=-0.000062, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.08%, turnover=6742235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.327200, depth_time=2026-10-30T05:30:15+00:00, book20_bid_proxy_usdt=421470, book20_ask_proxy_usdt=251732, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.87%, turnover=6395407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.007264, depth_time=2026-10-30T05:30:23+00:00, book20_bid_proxy_usdt=104550, book20_ask_proxy_usdt=104407, funding_indicative=-0.000004, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.85%, turnover=10125084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.062410, depth_time=2026-10-30T05:30:12+00:00, book20_bid_proxy_usdt=159173, book20_ask_proxy_usdt=242720, funding_indicative=-0.000141, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.90%, turnover=5250752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T05:30:02+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=0.466000, depth_time=2026-10-30T05:30:10+00:00, book20_bid_proxy_usdt=292821, book20_ask_proxy_usdt=228122, funding_indicative=0.000013, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.98%, turnover=18998808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T05:30:03+00:00, last15m_closed_end=2026-10-30T05:30+00:00, prior8high=1.573000, depth_time=2026-10-30T05:30:33+00:00, book20_bid_proxy_usdt=1376783, book20_ask_proxy_usdt=1520727, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.14%, turnover=11132256. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
