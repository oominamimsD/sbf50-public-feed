# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T13:45:45Z**
- feed_generated_utc: 2026-10-13T13:45:48+00:00
- source_sha256: `87d5bdf12c28af93cecdd6aeabfa9f3ba1c67e2b7d7f244be87fabf5d792b5c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T13:45+00:00, close=83288.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T13:00+00:00, close=83324.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.219300|-24.24|2.95|-24.95|9473070|9.13|
|W_USDT|0.018260|-24.10|29.10|-24.81|16592379|0.55|
|QNT_USDT|203.990000|-10.67|-20.55|-11.38|91370403|1.47|
|ZRO_USDT|2.021300|-10.60|-1.18|-11.31|18786293|1.49|
|RLC_USDT|0.905400|-8.41|65.21|-9.12|6563272|1.10|
|PYTH_USDT|0.081550|-7.99|6.86|-8.70|10588562|3.68|
|LIT_USDT|3.368200|-7.08|-11.41|-7.79|8655563|0.30|
|USELESS_USDT|0.169320|-6.76|-25.32|-7.47|5993891|2.95|
|ONDO_USDT|0.466400|-6.36|-4.58|-7.07|67369137|2.14|
|ZEC_USDT|1192.010000|-5.76|-7.94|-6.47|1658811430|0.08|
|SEI_USDT|0.062610|-5.66|-12.93|-6.37|10298719|1.60|
|PUMPFUN_USDT|0.005022|-5.40|-20.72|-6.11|34945785|1.99|
|GRASS_USDT|0.713400|-4.49|1.16|-5.20|5672419|1.40|
|JUP_USDT|0.327800|-4.40|-2.98|-5.11|8906087|3.05|
|ICP_USDT|3.162000|-4.03|-8.77|-4.74|16575323|3.16|
|HYPE_USDT|81.507000|-3.39|-12.02|-4.10|84864854|0.12|
|STRK_USDT|0.087710|-3.26|68.31|-3.97|59661161|1.14|
|LTC_USDT|61.050000|-3.03|-12.73|-3.74|23514633|3.28|
|MAGIC_USDT|0.120160|-1.47|93.83|-2.18|8386948|2.50|
|SILVER_USDT|60.100000|-0.44|-1.82|-1.15|190756845|1.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.219300|0.217900|0.219300|0.67|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.713400|0.709600|0.713400|2.94|N|Y/Y|Y/N|N|N|
|ICP_USDT|3.162000|3.084000|3.162000|1.44|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.327800|0.321900|0.327800|1.75|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.368200|3.280300|3.368700|2.23|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.466400|0.461100|0.466500|1.85|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005022|0.004859|0.005022|0.97|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.081550|0.081500|0.081520|0.91|N|Y/Y|N/N|N|N|
|QNT_USDT|203.990000|201.440000|203.990000|1.29|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.905400|0.896200|0.905400|0.65|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.062610|0.061440|0.062600|3.86|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.169320|0.163600|0.169320|1.38|N|Y/Y|Y/Y|N|N|
|W_USDT|0.018260|0.018139|0.018260|1.43|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1192.010000|1174.420000|1192.950000|1.53|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.021300|2.005400|2.021300|1.92|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T13:45:00+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.222900, depth_time=2026-10-13T13:45:08+00:00, book20_bid_proxy_usdt=97842, book20_ask_proxy_usdt=100258, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.24%, turnover=9473070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.722100, depth_time=2026-10-13T13:45:39+00:00, book20_bid_proxy_usdt=78193, book20_ask_proxy_usdt=198968, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.49%, turnover=5672419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=3.175000, depth_time=2026-10-13T13:45:44+00:00, book20_bid_proxy_usdt=546608, book20_ask_proxy_usdt=1019528, funding_indicative=-0.000007, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=16575323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.329300, depth_time=2026-10-13T13:45:40+00:00, book20_bid_proxy_usdt=500307, book20_ask_proxy_usdt=433027, funding_indicative=-0.000052, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.40%, turnover=8906087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=3.331400, depth_time=2026-10-13T13:45:23+00:00, book20_bid_proxy_usdt=19350, book20_ask_proxy_usdt=30240, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.08%, turnover=8655563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T13:45:00+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.470200, depth_time=2026-10-13T13:45:29+00:00, book20_bid_proxy_usdt=1695028, book20_ask_proxy_usdt=1344176, funding_indicative=-0.000078, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.36%, turnover=67369137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T13:45:00+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.005039, depth_time=2026-10-13T13:45:36+00:00, book20_bid_proxy_usdt=959002, book20_ask_proxy_usdt=994859, funding_indicative=0.000025, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.40%, turnover=34945785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.083930, depth_time=2026-10-13T13:45:22+00:00, book20_bid_proxy_usdt=60925, book20_ask_proxy_usdt=132664, funding_indicative=-0.000029, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.99%, turnover=10588562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T13:45:00+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=209.790000, depth_time=2026-10-13T13:45:14+00:00, book20_bid_proxy_usdt=52920, book20_ask_proxy_usdt=72216, funding_indicative=-0.000186, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.67%, turnover=91370403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.928800, depth_time=2026-10-13T13:45:19+00:00, book20_bid_proxy_usdt=62855, book20_ask_proxy_usdt=50009, funding_indicative=-0.000402, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.41%, turnover=6563272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.062820, depth_time=2026-10-13T13:45:34+00:00, book20_bid_proxy_usdt=218312, book20_ask_proxy_usdt=163318, funding_indicative=0.000074, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.66%, turnover=10298719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.170200, depth_time=2026-10-13T13:45:25+00:00, book20_bid_proxy_usdt=43504, book20_ask_proxy_usdt=13276, funding_indicative=0.000063, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.76%, turnover=5993891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T13:45:00+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=0.019134, depth_time=2026-10-13T13:45:11+00:00, book20_bid_proxy_usdt=35448, book20_ask_proxy_usdt=22450, funding_indicative=-0.000421, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.10%, turnover=16592379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-13T13:45:00+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=1204.440000, depth_time=2026-10-13T13:45:32+00:00, book20_bid_proxy_usdt=154577, book20_ask_proxy_usdt=318770, funding_indicative=0.000100, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.76%, turnover=1658811430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T13:45:01+00:00, last15m_closed_end=2026-10-13T13:45+00:00, prior8high=2.072500, depth_time=2026-10-13T13:45:17+00:00, book20_bid_proxy_usdt=36119, book20_ask_proxy_usdt=52068, funding_indicative=0.000008, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.60%, turnover=18786293. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
