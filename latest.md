# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T05:45:35Z**
- feed_generated_utc: 2026-11-09T05:45:37+00:00
- source_sha256: `14e7a787b055e4daae23af8563b8cce1a2f2ed15280f8988e79a7fbcf268e076`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T05:45+00:00, close=74333.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T05:00+00:00, close=74800, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001622|-17.13|39.32|-14.89|10135619|0.62|
|AKE_USDT|0.004634|-13.49|-49.41|-11.25|11460333|2.16|
|JCT_USDT|0.008756|-10.96|75.85|-8.72|68875868|5.72|
|ASTER_USDT|0.639100|-5.98|-8.62|-3.74|5166471|1.56|
|ETH_USDT|2126.910000|-5.09|-6.12|-2.85|1248419438|0.05|
|XRP_USDT|1.097800|-5.01|-12.16|-2.77|236633955|0.91|
|PUMPFUN_USDT|0.003559|-4.76|-15.62|-2.52|9415579|2.81|
|TAO_USDT|216.400000|-4.26|-7.85|-2.02|32875229|1.39|
|TRUMPOFFICIAL_USDT|1.139000|-4.20|-33.62|-1.96|6881827|8.78|
|HYPE_USDT|74.188000|-4.18|-15.39|-1.94|40163847|0.14|
|XLM_USDT|0.146010|-3.43|-13.27|-1.19|24890672|0.69|
|SOL_USDT|86.760000|-3.25|-8.44|-1.01|562172615|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004634|0.004549|0.004634|1.50|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.639100|0.637000|0.639100|0.27|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2126.910000|2129.140000|2126.960000|1.74|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|74.188000|74.125000|74.188000|0.34|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008756|0.007861|0.008755|1.15|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001622|0.001621|0.001622|1.72|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003559|0.003539|0.003559|1.07|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.760000|86.940000|86.760000|0.56|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|216.400000|215.950000|216.400000|1.17|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.139000|1.140000|1.139000|1.79|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.146010|0.146330|0.146010|0.86|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.097800|1.100400|1.097900|2.09|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=0.004938, depth_time=2026-11-09T05:45:09+00:00, book20_bid_proxy_usdt=61404, book20_ask_proxy_usdt=32548, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.49%, turnover=11460333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=0.645100, depth_time=2026-11-09T05:45:14+00:00, book20_bid_proxy_usdt=720640, book20_ask_proxy_usdt=622840, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.98%, turnover=5166471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=2146.900000, depth_time=2026-11-09T05:45:16+00:00, book20_bid_proxy_usdt=2575540, book20_ask_proxy_usdt=2399661, funding_indicative=-0.000041, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.09%, turnover=1248419438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=75.000000, depth_time=2026-11-09T05:45:29+00:00, book20_bid_proxy_usdt=42378, book20_ask_proxy_usdt=159492, funding_indicative=0.000041, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.18%, turnover=40163847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=0.010737, depth_time=2026-11-09T05:45:12+00:00, book20_bid_proxy_usdt=15904, book20_ask_proxy_usdt=25390, funding_indicative=0.001661, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.96%, turnover=68875868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=0.001693, depth_time=2026-11-09T05:45:06+00:00, book20_bid_proxy_usdt=10015, book20_ask_proxy_usdt=15840, funding_indicative=-0.000156, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.13%, turnover=10135619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=0.003640, depth_time=2026-11-09T05:45:21+00:00, book20_bid_proxy_usdt=2858556, book20_ask_proxy_usdt=2654830, funding_indicative=0.000048, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.76%, turnover=9415579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=87.910000, depth_time=2026-11-09T05:45:34+00:00, book20_bid_proxy_usdt=18273592, book20_ask_proxy_usdt=14028521, funding_indicative=-0.000089, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=562172615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=218.700000, depth_time=2026-11-09T05:45:23+00:00, book20_bid_proxy_usdt=97011, book20_ask_proxy_usdt=115184, funding_indicative=0.000049, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=32875229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=1.155000, depth_time=2026-11-09T05:45:26+00:00, book20_bid_proxy_usdt=2453525, book20_ask_proxy_usdt=2232920, funding_indicative=-0.000057, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=6881827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=0.147940, depth_time=2026-11-09T05:45:31+00:00, book20_bid_proxy_usdt=74328, book20_ask_proxy_usdt=141124, funding_indicative=0.000054, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=24890672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T05:45:00+00:00, last15m_closed_end=2026-11-09T05:45+00:00, prior8high=1.116100, depth_time=2026-11-09T05:45:17+00:00, book20_bid_proxy_usdt=3048796, book20_ask_proxy_usdt=3340756, funding_indicative=-0.000007, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.01%, turnover=236633955. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
