# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T06:30:37Z**
- feed_generated_utc: 2026-10-30T06:30:40+00:00
- source_sha256: `07d688eaf3ff7d1eec3b7df6c2d17459a356575c02199549641612b5cbb56b0a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T06:30+00:00, close=78666.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T06:00+00:00, close=78524.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.275900|-17.88|-24.88|-14.13|8151170|3.62|
|TIA_USDT|0.461800|-15.91|-18.75|-12.16|19010394|2.16|
|PYTH_USDT|0.061810|-15.54|-16.67|-11.79|5276725|3.23|
|LDO_USDT|0.331400|-12.42|-13.35|-8.67|6516054|3.02|
|FARTCOIN_USDT|0.118990|-11.46|-16.69|-7.71|15347768|0.84|
|BTW_USDT|1.456600|-11.07|-18.62|-7.32|11066851|2.75|
|PENGU_USDT|0.007241|-10.94|-6.30|-7.19|9992047|1.38|
|ETHFI_USDT|0.607800|-10.55|-8.22|-6.80|5978221|1.65|
|FET_USDT|0.165500|-10.44|-10.68|-6.69|14187879|6.04|
|TRUMPOFFICIAL_USDT|1.565000|-9.43|-10.26|-5.68|11185749|6.39|
|INJ_USDT|7.403000|-8.96|-6.66|-5.21|31165116|2.70|
|JASMY_USDT|0.003700|-6.37|-18.78|-2.62|5839420|5.40|
|ETH_USDT|2250.300000|-4.97|-6.14|-1.22|2477544492|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.456600|1.445300|1.458100|0.68|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.275900|0.267600|0.275800|3.27|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.607800|0.596800|0.607800|0.85|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2250.300000|2233.910000|2250.490000|0.70|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118990|0.117800|0.118990|0.79|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.165500|0.159400|0.165400|3.71|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.403000|7.296000|7.402000|0.38|N|Y/Y|Y/Y|Y|N|
|JASMY_USDT|0.003700|0.003639|0.003700|2.01|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.331400|0.320400|0.332200|5.48|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007241|0.007108|0.007240|0.47|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061810|0.060400|0.061810|1.17|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.461800|0.453800|0.461800|1.37|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.565000|1.545000|1.565000|1.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=1.528200, depth_time=2026-10-30T06:30:20+00:00, book20_bid_proxy_usdt=20094, book20_ask_proxy_usdt=28579, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.07%, turnover=11066851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.276700, depth_time=2026-10-30T06:30:08+00:00, book20_bid_proxy_usdt=380371, book20_ask_proxy_usdt=586664, funding_indicative=-0.000121, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-17.88%, turnover=8151170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.614200, depth_time=2026-10-30T06:30:25+00:00, book20_bid_proxy_usdt=114654, book20_ask_proxy_usdt=128485, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.55%, turnover=5978221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-10-30T06:30:03+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=2252.740000, depth_time=2026-10-30T06:30:37+00:00, book20_bid_proxy_usdt=2480634, book20_ask_proxy_usdt=3455849, funding_indicative=0.000026, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.97%, turnover=2477544492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.120530, depth_time=2026-10-30T06:30:18+00:00, book20_bid_proxy_usdt=37349, book20_ask_proxy_usdt=116309, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.46%, turnover=15347768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.164100, depth_time=2026-10-30T06:30:27+00:00, book20_bid_proxy_usdt=836613, book20_ask_proxy_usdt=608288, funding_indicative=-0.000277, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.44%, turnover=14187879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=7.440000, depth_time=2026-10-30T06:30:31+00:00, book20_bid_proxy_usdt=160053, book20_ask_proxy_usdt=118650, funding_indicative=-0.000027, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.96%, turnover=31165116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.003797, depth_time=2026-10-30T06:30:32+00:00, book20_bid_proxy_usdt=56040, book20_ask_proxy_usdt=65383, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.37%, turnover=5839420. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.328100, depth_time=2026-10-30T06:30:15+00:00, book20_bid_proxy_usdt=1829063, book20_ask_proxy_usdt=284208, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-12.42%, turnover=6516054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.007269, depth_time=2026-10-30T06:30:22+00:00, book20_bid_proxy_usdt=61221, book20_ask_proxy_usdt=82315, funding_indicative=-0.000011, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.94%, turnover=9992047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.062440, depth_time=2026-10-30T06:30:13+00:00, book20_bid_proxy_usdt=93356, book20_ask_proxy_usdt=231715, funding_indicative=-0.000201, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.54%, turnover=5276725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=0.466000, depth_time=2026-10-30T06:30:11+00:00, book20_bid_proxy_usdt=194798, book20_ask_proxy_usdt=196601, funding_indicative=0.000025, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.91%, turnover=19010394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T06:30:04+00:00, last15m_closed_end=2026-10-30T06:30+00:00, prior8high=1.573000, depth_time=2026-10-30T06:30:29+00:00, book20_bid_proxy_usdt=1400307, book20_ask_proxy_usdt=1004124, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.43%, turnover=11185749. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
