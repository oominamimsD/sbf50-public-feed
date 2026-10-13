# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T14:30:45Z**
- feed_generated_utc: 2026-10-13T14:30:48+00:00
- source_sha256: `b149ddb325c2f306ce221ce612fe849f22a15f65ee505400aba282d857538a6d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T14:30+00:00, close=83613, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T14:00+00:00, close=83232.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.018161|-24.51|28.40|-25.66|14793259|9.36|
|DOS_USDT|0.219000|-24.35|2.81|-25.50|9468093|4.57|
|ZRO_USDT|2.021100|-10.61|-1.19|-11.76|17179756|0.49|
|QNT_USDT|207.810000|-9.00|-19.06|-10.15|92574146|0.48|
|NEAR_USDT|5.073000|-8.57|1.01|-9.72|281752128|1.97|
|RLC_USDT|0.908400|-8.11|65.76|-9.26|6469507|1.10|
|PYTH_USDT|0.082190|-7.27|7.70|-8.42|9509934|1.22|
|LIT_USDT|3.368500|-7.08|-11.40|-8.23|8142195|0.30|
|USELESS_USDT|0.171500|-5.56|-24.36|-6.71|6076629|2.33|
|GRASS_USDT|0.705800|-5.51|0.08|-6.66|5439025|2.83|
|ONDO_USDT|0.471400|-5.36|-3.55|-6.51|66550525|2.12|
|PUMPFUN_USDT|0.005027|-5.31|-20.64|-6.46|34733145|1.99|
|SEI_USDT|0.063110|-4.91|-12.23|-6.06|10318852|1.58|
|JUP_USDT|0.328800|-4.11|-2.69|-5.26|8633897|3.04|
|STRK_USDT|0.087000|-4.04|66.95|-5.19|54480467|4.60|
|HYPE_USDT|81.822000|-3.02|-11.68|-4.17|81189917|0.12|
|MAGIC_USDT|0.118590|-2.76|91.30|-3.91|8009027|2.53|
|SILVER_USDT|59.660000|-1.17|-2.54|-2.32|191645300|1.68|
|XAUT_USDT|4164.310000|0.01|0.66|-1.14|182206294|0.07|
|XAU_USDT|4174.120000|0.03|0.81|-1.12|307002769|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.219000|0.216900|0.219000|0.80|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.705800|0.697900|0.705800|0.83|N|Y/Y|Y/N|N|N|
|JUP_USDT|0.328800|0.321900|0.328800|0.07|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.368500|3.280300|3.370800|2.00|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.073000|4.968000|5.073000|1.17|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.471400|0.461100|0.471400|0.82|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005027|0.004859|0.005027|0.34|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.082190|0.081060|0.082190|0.76|N|Y/Y|N/N|N|N|
|QNT_USDT|207.810000|201.440000|207.870000|1.14|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.908400|0.896200|0.908700|1.08|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.063110|0.061440|0.063110|0.51|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087000|0.086240|0.087000|1.36|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.171500|0.164590|0.171420|1.31|N|Y/Y|Y/Y|N|N|
|W_USDT|0.018161|0.017894|0.018153|1.65|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.021100|2.003400|2.021100|0.66|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T14:30:01+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.222500, depth_time=2026-10-13T14:30:11+00:00, book20_bid_proxy_usdt=75212, book20_ask_proxy_usdt=105846, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.35%, turnover=9468093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.718700, depth_time=2026-10-13T14:30:32+00:00, book20_bid_proxy_usdt=155439, book20_ask_proxy_usdt=199266, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.51%, turnover=5439025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.330000, depth_time=2026-10-13T14:30:40+00:00, book20_bid_proxy_usdt=507769, book20_ask_proxy_usdt=518562, funding_indicative=-0.000043, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.11%, turnover=8633897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=3.396800, depth_time=2026-10-13T14:30:26+00:00, book20_bid_proxy_usdt=27167, book20_ask_proxy_usdt=41007, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.08%, turnover=8142195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T14:30:01+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=5.124000, depth_time=2026-10-13T14:30:19+00:00, book20_bid_proxy_usdt=2523184, book20_ask_proxy_usdt=3236944, funding_indicative=-0.000020, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.57%, turnover=281752128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T14:30:01+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.472800, depth_time=2026-10-13T14:30:34+00:00, book20_bid_proxy_usdt=1728125, book20_ask_proxy_usdt=1300329, funding_indicative=-0.000072, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=66550525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.005071, depth_time=2026-10-13T14:30:37+00:00, book20_bid_proxy_usdt=1499000, book20_ask_proxy_usdt=1055833, funding_indicative=-0.000008, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.31%, turnover=34733145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.083930, depth_time=2026-10-13T14:30:23+00:00, book20_bid_proxy_usdt=170792, book20_ask_proxy_usdt=137696, funding_indicative=-0.000026, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.27%, turnover=9509934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T14:30:01+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=209.860000, depth_time=2026-10-13T14:30:16+00:00, book20_bid_proxy_usdt=54115, book20_ask_proxy_usdt=59265, funding_indicative=-0.000233, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.00%, turnover=92574146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.918400, depth_time=2026-10-13T14:30:22+00:00, book20_bid_proxy_usdt=37970, book20_ask_proxy_usdt=63531, funding_indicative=-0.000585, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.11%, turnover=6469507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.063360, depth_time=2026-10-13T14:30:39+00:00, book20_bid_proxy_usdt=200964, book20_ask_proxy_usdt=170695, funding_indicative=0.000060, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=10318852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T14:30:01+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.090860, depth_time=2026-10-13T14:30:44+00:00, book20_bid_proxy_usdt=114792, book20_ask_proxy_usdt=177718, funding_indicative=0.000031, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=54480467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.171820, depth_time=2026-10-13T14:30:30+00:00, book20_bid_proxy_usdt=47991, book20_ask_proxy_usdt=17548, funding_indicative=0.000062, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.56%, turnover=6076629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T14:30:01+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=0.018781, depth_time=2026-10-13T14:30:09+00:00, book20_bid_proxy_usdt=18883, book20_ask_proxy_usdt=34256, funding_indicative=-0.000396, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.51%, turnover=14793259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T14:30:02+00:00, last15m_closed_end=2026-10-13T14:30+00:00, prior8high=2.072500, depth_time=2026-10-13T14:30:12+00:00, book20_bid_proxy_usdt=444260, book20_ask_proxy_usdt=26423, funding_indicative=-0.000004, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.61%, turnover=17179756. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
