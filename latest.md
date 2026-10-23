# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T05:00:34Z**
- feed_generated_utc: 2026-10-23T05:00:36+00:00
- source_sha256: `376f8e61627f6c00bb68dcb542a2bb46836ce0ed39211c2174edae30e330aba6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T05:00+00:00, close=81561.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T05:00+00:00, close=81561.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.460300|-4.25|11.93|-4.15|10395731|0.29|
|STRK_USDT|0.052980|-3.56|-45.01|-3.46|11403597|1.89|
|TIA_USDT|0.558400|-3.00|-7.31|-2.90|22890538|3.58|
|SILVER_USDT|53.860000|-2.77|-5.74|-2.67|355232590|1.86|
|QNT_USDT|188.960000|-2.04|-9.11|-1.94|50877287|0.53|
|PUMPFUN_USDT|0.004605|-2.04|1.74|-1.94|38367129|2.17|
|ZRO_USDT|1.766800|-1.98|-16.80|-1.88|5772723|0.57|
|PHA_USDT|0.061740|-1.42|22.20|-1.32|6997472|1.62|
|ZEC_USDT|1217.100000|-1.38|3.16|-1.28|1851043401|0.08|
|XAUT_USDT|4010.140000|-1.28|-3.25|-1.18|282104649|0.07|
|NEAR_USDT|4.926000|-1.22|-3.77|-1.12|136334342|2.03|
|XAU_USDT|4013.370000|-1.14|-3.43|-1.04|725711653|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.460300|3.441500|3.459700|1.22|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.926000|4.904000|4.926000|1.32|N|Y/N|Y/Y|Y|N|
|PHA_USDT|0.061740|0.060030|0.061740|0.51|N|N/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004605|0.004602|0.004605|0.72|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.960000|188.560000|188.960000|1.53|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.860000|53.730000|53.860000|0.37|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052980|0.052700|0.052980|0.18|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.558400|0.558200|0.558400|1.30|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4010.140000|4009.590000|4010.140000|1.42|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4013.370000|4012.360000|4013.320000|0.87|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1217.100000|1213.440000|1216.760000|0.84|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.766800|1.768500|1.766800|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=3.544400, depth_time=2026-10-23T05:00:06+00:00, book20_bid_proxy_usdt=29956, book20_ask_proxy_usdt=26954, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=10395731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=5.003000, depth_time=2026-10-23T05:00:30+00:00, book20_bid_proxy_usdt=492432, book20_ask_proxy_usdt=3123516, funding_indicative=-0.000032, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=136334342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=0.062580, depth_time=2026-10-23T05:00:23+00:00, book20_bid_proxy_usdt=77211, book20_ask_proxy_usdt=58845, funding_indicative=-0.000443, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=6997472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=0.004680, depth_time=2026-10-23T05:00:19+00:00, book20_bid_proxy_usdt=1919763, book20_ask_proxy_usdt=1657606, funding_indicative=0.000022, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=38367129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=191.220000, depth_time=2026-10-23T05:00:16+00:00, book20_bid_proxy_usdt=58395, book20_ask_proxy_usdt=79456, funding_indicative=-0.000138, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=50877287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=54.380000, depth_time=2026-10-23T05:00:14+00:00, book20_bid_proxy_usdt=40357187, book20_ask_proxy_usdt=34338571, funding_indicative=0.000138, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=355232590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=0.053370, depth_time=2026-10-23T05:00:09+00:00, book20_bid_proxy_usdt=573050, book20_ask_proxy_usdt=655772, funding_indicative=0.000010, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=11403597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=0.565900, depth_time=2026-10-23T05:00:12+00:00, book20_bid_proxy_usdt=330256, book20_ask_proxy_usdt=311802, funding_indicative=0.000016, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=22890538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=4030.690000, depth_time=2026-10-23T05:00:27+00:00, book20_bid_proxy_usdt=358258, book20_ask_proxy_usdt=83453, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=282104649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=4032.600000, depth_time=2026-10-23T05:00:33+00:00, book20_bid_proxy_usdt=1351306, book20_ask_proxy_usdt=4205420, funding_indicative=0.000089, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=725711653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=1234.010000, depth_time=2026-10-23T05:00:26+00:00, book20_bid_proxy_usdt=74807, book20_ask_proxy_usdt=1219902, funding_indicative=-0.000003, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=1851043401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-23T05:00:01+00:00, last15m_closed_end=2026-10-23T05:00+00:00, prior8high=1.815300, depth_time=2026-10-23T05:00:21+00:00, book20_bid_proxy_usdt=48041, book20_ask_proxy_usdt=49650, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=5772723. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
