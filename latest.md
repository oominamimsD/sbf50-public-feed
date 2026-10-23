# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T04:15:31Z**
- feed_generated_utc: 2026-10-23T04:15:33+00:00
- source_sha256: `7dacf9f463852b14e1234a354e5e54fffb7e72b89adb6e126a024bf0d6a397e8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T04:15+00:00, close=81722.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004215|-8.52|112.34|-8.61|9056406|9.50|
|LIT_USDT|3.477000|-3.79|12.47|-3.88|10565322|0.29|
|SILVER_USDT|53.910000|-2.44|-5.65|-2.53|353740696|1.85|
|STRK_USDT|0.053140|-2.24|-44.85|-2.33|11804091|1.88|
|TIA_USDT|0.561700|-1.17|-6.77|-1.26|22875932|1.78|
|ZEC_USDT|1221.640000|-1.02|3.55|-1.11|1884992311|1.23|
|XAU_USDT|4018.420000|-1.01|-3.31|-1.10|731689128|0.03|
|XAUT_USDT|4015.800000|-0.94|-3.11|-1.03|281564920|0.07|
|PUMPFUN_USDT|0.004635|-0.94|2.40|-1.03|38481398|2.16|
|QNT_USDT|188.960000|-0.91|-9.11|-1.00|52073186|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004215|0.004168|0.004215|1.29|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.477000|3.420300|3.477000|1.14|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004635|0.004596|0.004636|0.11|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.960000|188.320000|188.960000|0.88|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.910000|53.570000|53.910000|1.22|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053140|0.052540|0.053140|0.12|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.561700|0.558400|0.561600|0.72|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4015.800000|3994.260000|4015.800000|3.70|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4018.420000|3989.000000|4018.420000|0.60|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1221.640000|1210.790000|1221.850000|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=0.004422, depth_time=2026-10-23T04:15:08+00:00, book20_bid_proxy_usdt=54823, book20_ask_proxy_usdt=28962, funding_indicative=0.000083, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.52%, turnover=9056406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=3.544400, depth_time=2026-10-23T04:15:08+00:00, book20_bid_proxy_usdt=23542, book20_ask_proxy_usdt=23629, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=10565322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=0.004691, depth_time=2026-10-23T04:15:28+00:00, book20_bid_proxy_usdt=2098326, book20_ask_proxy_usdt=1576776, funding_indicative=0.000019, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=38481398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=191.220000, depth_time=2026-10-23T04:15:28+00:00, book20_bid_proxy_usdt=80672, book20_ask_proxy_usdt=122058, funding_indicative=-0.000146, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=52073186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=54.410000, depth_time=2026-10-23T04:15:13+00:00, book20_bid_proxy_usdt=36689156, book20_ask_proxy_usdt=28556030, funding_indicative=0.000108, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=353740696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=0.053500, depth_time=2026-10-23T04:15:15+00:00, book20_bid_proxy_usdt=475392, book20_ask_proxy_usdt=648925, funding_indicative=0.000004, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=11804091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=0.566300, depth_time=2026-10-23T04:15:17+00:00, book20_bid_proxy_usdt=381815, book20_ask_proxy_usdt=393155, funding_indicative=0.000003, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=22875932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=4030.690000, depth_time=2026-10-23T04:15:25+00:00, book20_bid_proxy_usdt=102016, book20_ask_proxy_usdt=251274, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=281564920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=4032.600000, depth_time=2026-10-23T04:15:23+00:00, book20_bid_proxy_usdt=178119, book20_ask_proxy_usdt=2154151, funding_indicative=0.000082, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=731689128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T04:15:00+00:00, last15m_closed_end=2026-10-23T04:15+00:00, prior8high=1238.200000, depth_time=2026-10-23T04:15:20+00:00, book20_bid_proxy_usdt=276886, book20_ask_proxy_usdt=354042, funding_indicative=-0.000001, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=1884992311. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
