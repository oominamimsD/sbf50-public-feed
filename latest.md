# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T17:15:42Z**
- feed_generated_utc: 2026-10-16T17:15:45+00:00
- source_sha256: `5a3d1e6ef061aa09862953772c35540d81e132d0d61ba6aab2136b1a1aa43822`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T17:15+00:00, close=81123, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T17:00+00:00, close=81405.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.193100|-5.81|58.72|-5.57|21189264|0.52|
|ZRO_USDT|1.994300|-5.09|-2.08|-4.85|15349725|2.51|
|ZEC_USDT|1146.940000|-3.45|-5.86|-3.21|1514214579|0.09|
|OP_USDT|0.135650|-3.10|10.08|-2.86|14389517|1.47|
|PYTH_USDT|0.083910|-2.74|-1.73|-2.50|5867555|1.19|
|TAO_USDT|274.710000|-2.10|0.01|-1.86|78233835|1.09|
|APT_USDT|0.838300|-2.07|4.72|-1.83|11681691|1.19|
|WLD_USDT|0.498400|-2.02|1.19|-1.78|89804821|2.01|
|FARTCOIN_USDT|0.151850|-1.85|-7.05|-1.61|6829970|0.66|
|STRK_USDT|0.072820|-1.52|-3.30|-1.28|28120865|2.75|
|AAVE_USDT|154.900000|-1.51|-8.79|-1.27|31706288|0.65|
|HBAR_USDT|0.082970|-1.35|-8.68|-1.11|22001917|1.21|
|ENA_USDT|0.197240|-1.34|-8.50|-1.10|32796844|0.51|
|ARB_USDT|0.192350|-1.32|6.38|-1.08|35001000|0.52|
|LIT_USDT|3.054000|-1.32|-16.92|-1.08|6453478|0.33|
|NEAR_USDT|4.980000|-1.30|4.82|-1.06|187148260|2.01|
|ONDO_USDT|0.451200|-1.29|-6.01|-1.05|29940764|2.22|
|BCH_USDT|274.460000|-1.29|-0.31|-1.05|5831842|7.28|
|UNI_USDT|7.146000|-1.28|-3.02|-1.04|14538031|1.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.900000|155.440000|154.900000|1.07|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.838300|0.843800|0.838300|4.04|Y|Y/N|N/N|Y|N|
|ARB_USDT|0.192350|0.192620|0.192350|2.37|Y|Y/N|N/N|Y|N|
|BAT_USDT|0.193100|0.199580|0.193170|2.70|Y|N/N|N/N|Y|N|
|ENA_USDT|0.197240|0.197480|0.197240|1.92|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.151850|0.152290|0.151850|2.98|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.082970|0.083200|0.082970|1.83|Y|Y/Y|Y/N|Y|N|
|LIT_USDT|3.054000|3.056500|3.054000|1.01|N|Y/N|Y/Y|Y|N|
|OP_USDT|0.135650|0.137100|0.135660|1.98|Y|Y/N|N/N|Y|N|
|PYTH_USDT|0.083910|0.085560|0.083910|2.81|Y|Y/Y|Y/N|Y|N|
|STRK_USDT|0.072820|0.073390|0.072820|1.52|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|274.710000|276.820000|274.800000|2.46|Y|Y/Y|N/N|Y|N|
|WLD_USDT|0.498400|0.502800|0.500000|1.63|Y|Y/Y|N/N|Y|N|
|ZEC_USDT|1146.940000|1145.050000|1146.950000|1.37|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|1.994300|2.008900|1.994300|1.96|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=160.160000, depth_time=2026-10-16T17:15:32+00:00, book20_bid_proxy_usdt=279566, book20_ask_proxy_usdt=249820, funding_indicative=0.000079, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=31706288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.866500, depth_time=2026-10-16T17:15:23+00:00, book20_bid_proxy_usdt=90267, book20_ask_proxy_usdt=94004, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=11681691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.197400, depth_time=2026-10-16T17:15:39+00:00, book20_bid_proxy_usdt=39950, book20_ask_proxy_usdt=34575, funding_indicative=0.000020, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=35001000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.209940, depth_time=2026-10-16T17:15:08+00:00, book20_bid_proxy_usdt=32773, book20_ask_proxy_usdt=25420, funding_indicative=-0.000268, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.81%, turnover=21189264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.204480, depth_time=2026-10-16T17:15:37+00:00, book20_bid_proxy_usdt=132094, book20_ask_proxy_usdt=157466, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=32796844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.157120, depth_time=2026-10-16T17:15:28+00:00, book20_bid_proxy_usdt=47783, book20_ask_proxy_usdt=51033, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=6829970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.085570, depth_time=2026-10-16T17:15:35+00:00, book20_bid_proxy_usdt=1540271, book20_ask_proxy_usdt=646761, funding_indicative=0.000088, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=22001917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=3.235100, depth_time=2026-10-16T17:15:42+00:00, book20_bid_proxy_usdt=33648, book20_ask_proxy_usdt=29499, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=6453478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.141500, depth_time=2026-10-16T17:15:15+00:00, book20_bid_proxy_usdt=43242, book20_ask_proxy_usdt=33433, funding_indicative=0.000051, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=14389517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T17:14:59+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.088690, depth_time=2026-10-16T17:15:18+00:00, book20_bid_proxy_usdt=179993, book20_ask_proxy_usdt=106201, funding_indicative=-0.000044, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=5867555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.076490, depth_time=2026-10-16T17:15:30+00:00, book20_bid_proxy_usdt=395274, book20_ask_proxy_usdt=313644, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=28120865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=285.930000, depth_time=2026-10-16T17:15:21+00:00, book20_bid_proxy_usdt=165808, book20_ask_proxy_usdt=56402, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=78233835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=0.524200, depth_time=2026-10-16T17:15:25+00:00, book20_bid_proxy_usdt=1444104, book20_ask_proxy_usdt=1507103, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=89804821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=1208.970000, depth_time=2026-10-16T17:15:14+00:00, book20_bid_proxy_usdt=140394, book20_ask_proxy_usdt=454593, funding_indicative=0.000027, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=1514214579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T17:14:58+00:00, last15m_closed_end=2026-10-16T17:15+00:00, prior8high=2.164000, depth_time=2026-10-16T17:15:11+00:00, book20_bid_proxy_usdt=23014, book20_ask_proxy_usdt=64229, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=15349725. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
