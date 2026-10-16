# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T23:45:34Z**
- feed_generated_utc: 2026-10-16T23:45:36+00:00
- source_sha256: `dc8f935e3a786bf87ff3b368ab015c194ef2afdc90b61db2e15a0e8cefb5072a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T23:45+00:00, close=81583.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T23:00+00:00, close=81750.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.197570|-3.63|62.39|-3.95|17354208|2.02|
|ZEC_USDT|1149.890000|-3.20|-5.62|-3.52|1410941536|0.09|
|RIVER_USDT|1.092000|-3.01|-7.61|-3.33|5593763|9.15|
|INJ_USDT|8.730000|-2.76|25.99|-3.08|117257740|1.15|
|ZRO_USDT|2.045400|-2.66|0.42|-2.98|16306426|1.47|
|ARB_USDT|0.191400|-1.81|5.86|-2.13|31333824|0.52|
|TAO_USDT|275.930000|-1.67|0.45|-1.99|83480031|1.09|
|AAVE_USDT|155.130000|-1.36|-8.66|-1.68|31596235|0.65|
|APT_USDT|0.844600|-1.34|5.50|-1.66|12396615|1.18|
|AVAX_USDT|9.963000|-1.19|-2.24|-1.51|126986615|1.00|
|QNT_USDT|200.070000|-0.73|-19.78|-1.05|68208449|0.50|
|HBAR_USDT|0.083530|-0.68|-8.06|-1.00|21066101|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.130000|153.830000|155.150000|0.78|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.844600|0.833500|0.844600|0.53|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191400|0.190500|0.191400|2.13|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.963000|9.920000|9.963000|0.29|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.197570|0.194970|0.197570|0.71|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.083530|0.083040|0.083530|1.77|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.730000|8.552000|8.730000|0.86|N|Y/Y|N/N|Y|N|
|QNT_USDT|200.070000|198.640000|200.170000|0.56|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.092000|1.087000|1.092000|0.40|N|Y/Y|Y/N|Y|N|
|TAO_USDT|275.930000|271.290000|275.900000|1.58|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1149.890000|1134.590000|1149.890000|0.61|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.045400|2.027800|2.045400|0.47|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T23:45:01+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=155.410000, depth_time=2026-10-16T23:45:22+00:00, book20_bid_proxy_usdt=573192, book20_ask_proxy_usdt=255872, funding_indicative=0.000058, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=31596235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T23:45:01+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=0.844800, depth_time=2026-10-16T23:45:26+00:00, book20_bid_proxy_usdt=109611, book20_ask_proxy_usdt=158552, funding_indicative=0.000048, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=12396615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=0.192400, depth_time=2026-10-16T23:45:19+00:00, book20_bid_proxy_usdt=42478, book20_ask_proxy_usdt=49129, funding_indicative=-0.000119, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=31333824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=9.997000, depth_time=2026-10-16T23:45:27+00:00, book20_bid_proxy_usdt=687311, book20_ask_proxy_usdt=733541, funding_indicative=0.000008, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=126986615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=0.202830, depth_time=2026-10-16T23:45:07+00:00, book20_bid_proxy_usdt=31032, book20_ask_proxy_usdt=31852, funding_indicative=-0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=17354208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T23:45:01+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=0.083810, depth_time=2026-10-16T23:45:33+00:00, book20_bid_proxy_usdt=645154, book20_ask_proxy_usdt=1477863, funding_indicative=-0.000022, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=21066101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=8.731000, depth_time=2026-10-16T23:45:14+00:00, book20_bid_proxy_usdt=244668, book20_ask_proxy_usdt=288054, funding_indicative=-0.000111, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=117257740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=203.680000, depth_time=2026-10-16T23:45:30+00:00, book20_bid_proxy_usdt=76970, book20_ask_proxy_usdt=89282, funding_indicative=0.000006, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=68208449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T23:45:01+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=1.112000, depth_time=2026-10-16T23:45:12+00:00, book20_bid_proxy_usdt=524965, book20_ask_proxy_usdt=402661, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=5593763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=275.700000, depth_time=2026-10-16T23:45:21+00:00, book20_bid_proxy_usdt=239011, book20_ask_proxy_usdt=109810, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=83480031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=1151.290000, depth_time=2026-10-16T23:45:08+00:00, book20_bid_proxy_usdt=660769, book20_ask_proxy_usdt=461178, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.20%, turnover=1410941536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T23:45:00+00:00, last15m_closed_end=2026-10-16T23:45+00:00, prior8high=2.070600, depth_time=2026-10-16T23:45:17+00:00, book20_bid_proxy_usdt=23641, book20_ask_proxy_usdt=70288, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=16306426. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
