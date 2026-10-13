# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T14:45:43Z**
- feed_generated_utc: 2026-10-13T14:45:46+00:00
- source_sha256: `36b91a0cbb676e972a3f5fbc363d81a6801fb0084a8d7c9d604bc2e118b26d46`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T14:45+00:00, close=83642.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T14:00+00:00, close=83232.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T12:00+00:00, close=83325.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.217700|-24.80|2.20|-25.96|9476985|4.59|
|W_USDT|0.018107|-24.74|28.02|-25.90|14881372|0.55|
|ZRO_USDT|2.025100|-10.43|-1.00|-11.59|17215364|0.49|
|QNT_USDT|207.290000|-9.23|-19.27|-10.39|93650871|0.48|
|NEAR_USDT|5.096000|-8.16|1.47|-9.32|284855543|1.96|
|RLC_USDT|0.914300|-7.51|66.84|-8.67|6555445|1.09|
|LIT_USDT|3.360100|-7.31|-11.62|-8.47|8197391|0.30|
|USELESS_USDT|0.171270|-5.68|-24.46|-6.84|6111827|1.75|
|ONDO_USDT|0.471100|-5.42|-3.62|-6.58|66915322|2.12|
|GRASS_USDT|0.708300|-5.18|0.43|-6.34|5452410|5.65|
|SEI_USDT|0.063110|-4.91|-12.23|-6.07|10459776|4.76|
|PUMPFUN_USDT|0.005049|-4.89|-20.29|-6.05|34856297|1.98|
|JUP_USDT|0.327500|-4.49|-3.07|-5.65|8734108|3.06|
|STRK_USDT|0.087420|-3.58|67.76|-4.74|54780599|1.14|
|HYPE_USDT|81.812000|-3.03|-11.69|-4.19|81550366|0.37|
|MAGIC_USDT|0.119000|-2.42|91.96|-3.58|8028301|2.52|
|SILVER_USDT|59.580000|-1.30|-2.67|-2.46|194919814|1.68|
|XAU_USDT|4174.990000|0.05|0.83|-1.11|308725189|0.07|
|XAUT_USDT|4165.690000|0.05|0.69|-1.11|186050152|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.217700|0.216900|0.217700|1.20|N|Y/Y|Y/Y|N|N|
|GRASS_USDT|0.708300|0.697900|0.708300|0.49|N|Y/Y|Y/N|N|N|
|HYPE_USDT|81.812000|81.003000|81.812000|0.62|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.327500|0.323100|0.327500|1.12|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.360100|3.290200|3.360100|1.41|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.096000|4.968000|5.095000|1.01|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.471100|0.462900|0.471100|0.60|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005049|0.004916|0.005054|0.45|N|Y/Y|Y/Y|N|N|
|QNT_USDT|207.290000|201.440000|207.400000|0.75|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.914300|0.896200|0.914300|1.49|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.063110|0.061780|0.063110|1.34|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087420|0.086240|0.087420|0.68|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.171270|0.165250|0.171270|0.50|N|Y/Y|Y/Y|N|N|
|W_USDT|0.018107|0.017894|0.018117|0.99|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.025100|2.003400|2.025100|0.48|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.222500, depth_time=2026-10-13T14:45:08+00:00, book20_bid_proxy_usdt=95230, book20_ask_proxy_usdt=124897, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.80%, turnover=9476985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- GRASS_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.718600, depth_time=2026-10-13T14:45:30+00:00, book20_bid_proxy_usdt=162329, book20_ask_proxy_usdt=198082, funding_indicative=0.000050, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.18%, turnover=5452410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=82.304000, depth_time=2026-10-13T14:45:43+00:00, book20_bid_proxy_usdt=236794, book20_ask_proxy_usdt=32631, funding_indicative=0.000037, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=81550366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.330500, depth_time=2026-10-13T14:45:36+00:00, book20_bid_proxy_usdt=616683, book20_ask_proxy_usdt=445713, funding_indicative=-0.000051, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.49%, turnover=8734108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=3.404100, depth_time=2026-10-13T14:45:23+00:00, book20_bid_proxy_usdt=19520, book20_ask_proxy_usdt=30701, funding_indicative=0.000044, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.31%, turnover=8197391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=5.132000, depth_time=2026-10-13T14:45:18+00:00, book20_bid_proxy_usdt=2700991, book20_ask_proxy_usdt=333944, funding_indicative=-0.000035, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.16%, turnover=284855543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.474700, depth_time=2026-10-13T14:45:28+00:00, book20_bid_proxy_usdt=1598565, book20_ask_proxy_usdt=1816430, funding_indicative=-0.000069, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.42%, turnover=66915322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.005077, depth_time=2026-10-13T14:45:36+00:00, book20_bid_proxy_usdt=1699630, book20_ask_proxy_usdt=1761958, funding_indicative=-0.000010, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=34856297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=210.460000, depth_time=2026-10-13T14:45:16+00:00, book20_bid_proxy_usdt=61072, book20_ask_proxy_usdt=59549, funding_indicative=-0.000240, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.23%, turnover=93650871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.914100, depth_time=2026-10-13T14:45:21+00:00, book20_bid_proxy_usdt=53307, book20_ask_proxy_usdt=56650, funding_indicative=-0.000657, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.51%, turnover=6555445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.063460, depth_time=2026-10-13T14:45:32+00:00, book20_bid_proxy_usdt=240643, book20_ask_proxy_usdt=160411, funding_indicative=0.000045, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=10459776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.090860, depth_time=2026-10-13T14:45:40+00:00, book20_bid_proxy_usdt=133475, book20_ask_proxy_usdt=155568, funding_indicative=0.000035, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=54780599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.172750, depth_time=2026-10-13T14:45:25+00:00, book20_bid_proxy_usdt=18941, book20_ask_proxy_usdt=19719, funding_indicative=0.000061, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.68%, turnover=6111827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T14:45:00+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=0.018781, depth_time=2026-10-13T14:45:10+00:00, book20_bid_proxy_usdt=23773, book20_ask_proxy_usdt=18030, funding_indicative=-0.000379, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.74%, turnover=14881372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T14:45:01+00:00, last15m_closed_end=2026-10-13T14:45+00:00, prior8high=2.072500, depth_time=2026-10-13T14:45:13+00:00, book20_bid_proxy_usdt=57244, book20_ask_proxy_usdt=22572, funding_indicative=-0.000014, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.43%, turnover=17215364. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
