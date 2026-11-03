# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T12:00:44Z**
- feed_generated_utc: 2026-11-03T12:00:47+00:00
- source_sha256: `b9c41893c359e10483b95e37728af30ab64cd8d185b7a1542031f22080c3b964`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004461|-18.92|-85.50|-18.42|11997835|2.24|
|BTW_USDT|0.941200|-13.68|-21.28|-13.18|9953077|1.07|
|XPL_USDT|0.064460|-8.60|-13.23|-8.10|11554192|1.55|
|ZEC_USDT|1181.310000|-5.80|-5.32|-5.30|1780254439|0.09|
|NEAR_USDT|3.873000|-4.93|-15.30|-4.43|77416521|2.58|
|SILVER_USDT|49.100000|-4.04|-9.45|-3.54|421545873|2.04|
|TIA_USDT|0.442500|-3.57|-17.39|-3.07|12804498|2.26|
|ENA_USDT|0.171430|-3.45|-18.51|-2.95|72660575|0.58|
|TRUMPOFFICIAL_USDT|1.585000|-3.05|-6.15|-2.55|9179567|6.31|
|FARTCOIN_USDT|0.116800|-2.94|-8.98|-2.44|9514320|0.86|
|DASH_USDT|45.820000|-2.92|-12.25|-2.42|9144236|2.18|
|XLM_USDT|0.162970|-2.76|-3.90|-2.26|34158705|0.61|
|TAO_USDT|224.060000|-2.31|-11.61|-1.81|39597063|0.89|
|APT_USDT|0.617400|-1.92|-12.05|-1.42|5162309|1.62|
|SOL_USDT|92.510000|-1.90|-9.16|-1.40|663874190|1.08|
|LINK_USDT|11.138000|-1.75|-3.38|-1.25|168293510|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004461|0.004436|0.004466|0.40|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.617400|0.611300|0.617400|0.55|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.941200|0.870600|0.941200|1.91|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.820000|45.630000|45.820000|1.17|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171430|0.169020|0.171430|12.57|N|N/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116800|0.115950|0.116800|1.14|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.873000|3.821000|3.873000|2.12|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.100000|48.970000|49.100000|0.35|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|92.510000|92.150000|92.510000|1.39|N|N/N|Y/Y|Y|N|
|TAO_USDT|224.060000|222.150000|224.060000|0.75|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.442500|0.437200|0.442500|2.49|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.585000|1.584000|1.585000|0.30|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162970|0.161580|0.162980|0.69|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064460|0.063400|0.064460|6.15|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1181.310000|1142.240000|1181.710000|1.47|N|N/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.004632, depth_time=2026-11-03T12:00:07+00:00, book20_bid_proxy_usdt=57143, book20_ask_proxy_usdt=47632, funding_indicative=-0.001937, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.92%, turnover=11997835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.619600, depth_time=2026-11-03T12:00:41+00:00, book20_bid_proxy_usdt=179717, book20_ask_proxy_usdt=169697, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=5162309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.973900, depth_time=2026-11-03T12:00:10+00:00, book20_bid_proxy_usdt=14442, book20_ask_proxy_usdt=24529, funding_indicative=-0.000248, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.68%, turnover=9953077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=45.990000, depth_time=2026-11-03T12:00:33+00:00, book20_bid_proxy_usdt=845595, book20_ask_proxy_usdt=642918, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=9144236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.171360, depth_time=2026-11-03T12:00:25+00:00, book20_bid_proxy_usdt=205074, book20_ask_proxy_usdt=227792, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=72660575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.117380, depth_time=2026-11-03T12:00:30+00:00, book20_bid_proxy_usdt=109550, book20_ask_proxy_usdt=60051, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=9514320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=3.868000, depth_time=2026-11-03T12:00:18+00:00, book20_bid_proxy_usdt=5287789, book20_ask_proxy_usdt=2322912, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.93%, turnover=77416521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=49.240000, depth_time=2026-11-03T12:00:19+00:00, book20_bid_proxy_usdt=55793771, book20_ask_proxy_usdt=44066742, funding_indicative=0.000085, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=421545873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=92.790000, depth_time=2026-11-03T12:00:44+00:00, book20_bid_proxy_usdt=14680319, book20_ask_proxy_usdt=13016950, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=663874190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=224.590000, depth_time=2026-11-03T12:00:39+00:00, book20_bid_proxy_usdt=308060, book20_ask_proxy_usdt=336182, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=39597063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.442100, depth_time=2026-11-03T12:00:22+00:00, book20_bid_proxy_usdt=394830, book20_ask_proxy_usdt=337616, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=12804498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=1.602000, depth_time=2026-11-03T12:00:28+00:00, book20_bid_proxy_usdt=1959737, book20_ask_proxy_usdt=2376422, funding_indicative=0.000001, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=9179567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.163180, depth_time=2026-11-03T12:00:36+00:00, book20_bid_proxy_usdt=201478, book20_ask_proxy_usdt=125724, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=34158705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=0.064850, depth_time=2026-11-03T12:00:13+00:00, book20_bid_proxy_usdt=448319, book20_ask_proxy_usdt=367773, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.60%, turnover=11554192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T12:00:02+00:00, last15m_closed_end=2026-11-03T12:00+00:00, prior8high=1182.570000, depth_time=2026-11-03T12:00:15+00:00, book20_bid_proxy_usdt=367418, book20_ask_proxy_usdt=558495, funding_indicative=0.000013, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.80%, turnover=1780254439. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
