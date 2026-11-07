# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T02:00:46Z**
- feed_generated_utc: 2026-11-07T02:00:48+00:00
- source_sha256: `b63df9a90fda5352c9495b8a9bed51b3d989292732a6d12e3c75b000f462deb1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T02:00+00:00, close=76000, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T02:00+00:00, close=76000, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CYBER_USDT|0.317800|-10.22|16.32|-10.46|6425667|6.29|
|ANTHROPIC_USDT|1336.050000|-8.08|-20.30|-8.32|7200993|2.02|
|TRUMPOFFICIAL_USDT|1.198000|-4.46|-23.79|-4.70|10982592|8.34|
|DOT_USDT|0.905000|-3.43|-6.62|-3.67|6694701|1.10|
|ARB_USDT|0.164540|-2.88|1.49|-3.12|26095117|0.61|
|PUMPFUN_USDT|0.003940|-2.59|-4.06|-2.83|12376738|2.54|
|ENA_USDT|0.163580|-2.34|-13.85|-2.58|30425016|0.61|
|APT_USDT|0.603400|-2.26|-3.87|-2.50|5108500|1.66|
|OP_USDT|0.105140|-2.03|-2.83|-2.27|5846498|0.95|
|ONDO_USDT|0.371300|-1.32|-7.03|-1.56|10467449|2.69|
|FARTCOIN_USDT|0.118490|-1.28|-1.50|-1.52|12758627|0.84|
|UNI_USDT|6.957000|-1.26|0.14|-1.50|27437352|4.31|
|HBAR_USDT|0.067750|-0.95|-5.70|-1.19|5008794|1.48|
|XRP_USDT|1.178000|-0.79|-6.09|-1.03|328181590|0.85|
|XLM_USDT|0.153830|-0.79|-10.68|-1.03|22528684|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1336.050000|1330.670000|1336.050000|0.19|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.603400|0.602100|0.603400|1.72|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164540|0.164120|0.164540|1.29|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.317800|0.316100|0.318000|1.01|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.905000|0.904500|0.905000|1.53|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163580|0.163260|0.163590|3.11|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118490|0.117630|0.118490|0.36|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067750|0.067340|0.067750|0.04|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.371300|0.369900|0.371300|0.27|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.105140|0.104920|0.105140|0.54|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003940|0.003901|0.003941|1.25|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.198000|1.196000|1.198000|1.75|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.957000|6.875000|6.957000|0.41|N|N/Y|Y/Y|Y|N|
|XLM_USDT|0.153830|0.153080|0.153810|0.77|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.178000|1.177000|1.178000|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=1354.930000, depth_time=2026-11-07T02:00:11+00:00, book20_bid_proxy_usdt=20246, book20_ask_proxy_usdt=116539, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.08%, turnover=7200993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T01:59:59+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.604900, depth_time=2026-11-07T02:00:25+00:00, book20_bid_proxy_usdt=148379, book20_ask_proxy_usdt=167872, funding_indicative=0.000018, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=5108500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.165540, depth_time=2026-11-07T02:00:16+00:00, book20_bid_proxy_usdt=112108, book20_ask_proxy_usdt=63065, funding_indicative=-0.000004, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=26095117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.336400, depth_time=2026-11-07T02:00:08+00:00, book20_bid_proxy_usdt=113589, book20_ask_proxy_usdt=143551, funding_indicative=-0.002277, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=6425667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.913700, depth_time=2026-11-07T02:00:16+00:00, book20_bid_proxy_usdt=422567, book20_ask_proxy_usdt=335227, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=6694701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.164540, depth_time=2026-11-07T02:00:24+00:00, book20_bid_proxy_usdt=486281, book20_ask_proxy_usdt=266936, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=30425016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T01:59:59+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.118900, depth_time=2026-11-07T02:00:28+00:00, book20_bid_proxy_usdt=64315, book20_ask_proxy_usdt=80547, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=12758627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T01:59:59+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.067850, depth_time=2026-11-07T02:00:40+00:00, book20_bid_proxy_usdt=906222, book20_ask_proxy_usdt=636986, funding_indicative=-0.000045, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=5008794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.372400, depth_time=2026-11-07T02:00:31+00:00, book20_bid_proxy_usdt=1769834, book20_ask_proxy_usdt=1845045, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=10467449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T01:59:59+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.105740, depth_time=2026-11-07T02:00:27+00:00, book20_bid_proxy_usdt=134368, book20_ask_proxy_usdt=126669, funding_indicative=-0.000026, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=5846498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.003941, depth_time=2026-11-07T02:00:21+00:00, book20_bid_proxy_usdt=2358277, book20_ask_proxy_usdt=2229052, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=12376738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=1.207000, depth_time=2026-11-07T02:00:13+00:00, book20_bid_proxy_usdt=1359904, book20_ask_proxy_usdt=1521988, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=10982592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=6.962000, depth_time=2026-11-07T02:00:38+00:00, book20_bid_proxy_usdt=2207495, book20_ask_proxy_usdt=2613919, funding_indicative=0.000068, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=27437352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=0.154380, depth_time=2026-11-07T02:00:45+00:00, book20_bid_proxy_usdt=273297, book20_ask_proxy_usdt=299708, funding_indicative=0.000015, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=22528684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T02:00:03+00:00, last15m_closed_end=2026-11-07T02:00+00:00, prior8high=1.182100, depth_time=2026-11-07T02:00:42+00:00, book20_bid_proxy_usdt=5035876, book20_ask_proxy_usdt=4393919, funding_indicative=0.000053, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=328181590. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
