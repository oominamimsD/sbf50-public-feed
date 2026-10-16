# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T22:30:44Z**
- feed_generated_utc: 2026-10-16T22:30:46+00:00
- source_sha256: `5dcc419904851f48f1608b01f6001f548adbc5d56a6a4e82a5ae45d50f8e6bc5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T22:30+00:00, close=81756.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T22:00+00:00, close=81648.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1143.870000|-3.71|-6.11|-4.24|1433371348|0.09|
|INJ_USDT|8.696000|-3.14|25.50|-3.67|117016938|1.15|
|FILECOIN_USDT|1.132500|-2.93|5.84|-3.46|23265721|0.88|
|ZRO_USDT|2.043400|-2.75|0.32|-3.28|15990409|1.47|
|RIVER_USDT|1.096000|-2.66|-7.27|-3.19|5690943|9.12|
|APT_USDT|0.834300|-2.54|4.22|-3.07|12417425|1.20|
|OP_USDT|0.136560|-2.45|10.82|-2.98|14465173|0.73|
|TAO_USDT|273.860000|-2.40|-0.29|-2.93|82251072|1.09|
|BAT_USDT|0.200120|-2.39|64.49|-2.92|18249130|1.00|
|ARB_USDT|0.191300|-1.86|5.80|-2.39|32529255|0.52|
|AAVE_USDT|155.000000|-1.44|-8.73|-1.97|31661655|0.65|
|DOT_USDT|1.155600|-1.29|-2.72|-1.82|21852792|0.86|
|ICP_USDT|3.007000|-1.02|-0.39|-1.55|8812270|3.33|
|AVAX_USDT|9.982000|-1.00|-2.06|-1.53|127812242|1.00|
|STRK_USDT|0.073310|-0.86|-2.65|-1.39|21892261|1.36|
|LTC_USDT|59.380000|-0.80|-6.63|-1.33|9871955|3.37|
|ENA_USDT|0.198360|-0.78|-7.98|-1.31|40802048|0.50|
|HBAR_USDT|0.083490|-0.73|-8.11|-1.26|20815887|1.20|
|FARTCOIN_USDT|0.153710|-0.65|-5.91|-1.18|7087171|0.65|
|ONDO_USDT|0.454600|-0.54|-5.31|-1.07|28454146|2.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.000000|153.830000|155.050000|1.13|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.834300|0.834500|0.834700|0.15|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191300|0.190740|0.191330|0.45|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.982000|9.920000|9.982000|0.25|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.200120|0.195230|0.200120|0.60|N|N/Y|N/N|Y|N|
|DOT_USDT|1.155600|1.145400|1.155600|0.46|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.132500|1.120000|1.132500|0.24|N|Y/Y|N/N|Y|N|
|ICP_USDT|3.007000|2.984000|3.007000|0.51|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.696000|8.469000|8.696000|0.59|N|Y/Y|N/N|Y|N|
|OP_USDT|0.136560|0.135160|0.136560|0.13|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.096000|1.072000|1.096000|0.37|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.073310|0.071640|0.073310|0.51|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.860000|270.100000|273.900000|0.23|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1143.870000|1134.590000|1144.000000|0.69|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.043400|2.038900|2.043400|0.29|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=156.200000, depth_time=2026-10-16T22:30:31+00:00, book20_bid_proxy_usdt=276074, book20_ask_proxy_usdt=315920, funding_indicative=0.000067, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=31661655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=0.848000, depth_time=2026-10-16T22:30:20+00:00, book20_bid_proxy_usdt=144309, book20_ask_proxy_usdt=137318, funding_indicative=0.000055, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=12417425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=0.193380, depth_time=2026-10-16T22:30:30+00:00, book20_bid_proxy_usdt=66790, book20_ask_proxy_usdt=67004, funding_indicative=-0.000094, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=32529255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=10.024000, depth_time=2026-10-16T22:30:41+00:00, book20_bid_proxy_usdt=901332, book20_ask_proxy_usdt=597001, funding_indicative=-0.000004, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=127812242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T22:29:58+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=0.202830, depth_time=2026-10-16T22:30:28+00:00, book20_bid_proxy_usdt=17671, book20_ask_proxy_usdt=19169, funding_indicative=-0.000111, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=18249130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=1.162700, depth_time=2026-10-16T22:30:35+00:00, book20_bid_proxy_usdt=201082, book20_ask_proxy_usdt=293526, funding_indicative=0.000037, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=21852792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T22:29:58+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=1.143200, depth_time=2026-10-16T22:30:11+00:00, book20_bid_proxy_usdt=526410, book20_ask_proxy_usdt=524612, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=23265721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=3.019000, depth_time=2026-10-16T22:30:38+00:00, book20_bid_proxy_usdt=950524, book20_ask_proxy_usdt=957724, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=8812270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T22:29:58+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=8.679000, depth_time=2026-10-16T22:30:10+00:00, book20_bid_proxy_usdt=209470, book20_ask_proxy_usdt=232514, funding_indicative=-0.000057, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=117016938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=0.137470, depth_time=2026-10-16T22:30:21+00:00, book20_bid_proxy_usdt=56897, book20_ask_proxy_usdt=83931, funding_indicative=0.000067, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=14465173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=1.112000, depth_time=2026-10-16T22:30:14+00:00, book20_bid_proxy_usdt=486964, book20_ask_proxy_usdt=388235, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=5690943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T22:29:59+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=0.073820, depth_time=2026-10-16T22:30:43+00:00, book20_bid_proxy_usdt=596229, book20_ask_proxy_usdt=293669, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.86%, turnover=21892261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T22:29:58+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=275.700000, depth_time=2026-10-16T22:30:25+00:00, book20_bid_proxy_usdt=71561, book20_ask_proxy_usdt=132324, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=82251072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T22:29:58+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=1153.360000, depth_time=2026-10-16T22:30:07+00:00, book20_bid_proxy_usdt=294063, book20_ask_proxy_usdt=1029644, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=1433371348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T22:29:58+00:00, last15m_closed_end=2026-10-16T22:30+00:00, prior8high=2.113300, depth_time=2026-10-16T22:30:15+00:00, book20_bid_proxy_usdt=44497, book20_ask_proxy_usdt=94287, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=15990409. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
