# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T12:45:39Z**
- feed_generated_utc: 2026-10-18T12:45:41+00:00
- source_sha256: `6c0912e9a22fdde86abfa87408e65317c8c2b6e86c40ecbf5f2c77bfbca201dd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T12:45+00:00, close=81906.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.239500|-6.55|1.65|-7.27|6111577|4.17|
|STRK_USDT|0.062240|-5.91|-33.38|-6.63|15892524|1.61|
|PUMPFUN_USDT|0.004260|-3.44|-25.58|-4.16|22353535|2.35|
|SAND_USDT|0.061160|-2.98|-9.10|-3.70|45511968|1.64|
|ZRO_USDT|1.830000|-2.93|-9.43|-3.65|6376975|0.55|
|TIA_USDT|0.640600|-2.64|24.87|-3.36|59008951|1.56|
|FILECOIN_USDT|1.058700|-2.63|-6.12|-3.35|17941818|0.94|
|XPL_USDT|0.078370|-2.19|-9.67|-2.91|5823358|1.28|
|INJ_USDT|8.308000|-1.81|13.90|-2.53|40340490|1.20|
|OP_USDT|0.126710|-1.77|-8.54|-2.49|8886440|0.79|
|ZEC_USDT|1125.300000|-1.40|-8.64|-2.12|1223778240|0.09|
|DOT_USDT|1.105700|-1.04|-12.02|-1.76|16747198|0.90|
|ICP_USDT|2.907000|-0.71|-7.68|-1.43|6101745|3.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.105700|1.102600|1.105700|0.57|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.239500|0.240100|0.239500|1.48|Y|Y/Y|Y/Y|N|Y|
|FILECOIN_USDT|1.058700|1.053700|1.058700|0.67|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.907000|2.889000|2.907000|0.88|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.308000|8.312000|8.308000|1.86|Y|Y/Y|Y/N|N|N|
|OP_USDT|0.126710|0.125830|0.126720|2.00|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004260|0.004269|0.004260|2.15|Y|Y/Y|Y/Y|N|Y|
|SAND_USDT|0.061160|0.060210|0.061160|1.82|N|Y/Y|N/N|N|N|
|STRK_USDT|0.062240|0.061150|0.062240|1.94|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.640600|0.632400|0.640600|0.97|N|Y/Y|N/Y|N|N|
|XPL_USDT|0.078370|0.078080|0.078370|0.48|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1125.300000|1123.060000|1125.670000|1.09|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.830000|1.829300|1.830000|1.11|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=1.116900, depth_time=2026-10-18T12:45:35+00:00, book20_bid_proxy_usdt=260796, book20_ask_proxy_usdt=267060, funding_indicative=-0.000033, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=16747198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.247500, depth_time=2026-10-18T12:45:07+00:00, book20_bid_proxy_usdt=680877, book20_ask_proxy_usdt=522041, funding_indicative=0.000011, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.55%, turnover=6111577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=1.068400, depth_time=2026-10-18T12:45:22+00:00, book20_bid_proxy_usdt=500908, book20_ask_proxy_usdt=700018, funding_indicative=0.000045, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=17941818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=2.920000, depth_time=2026-10-18T12:45:38+00:00, book20_bid_proxy_usdt=813501, book20_ask_proxy_usdt=1177569, funding_indicative=0.000071, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=6101745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=8.527000, depth_time=2026-10-18T12:45:28+00:00, book20_bid_proxy_usdt=256680, book20_ask_proxy_usdt=276782, funding_indicative=0.000184, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=40340490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.127610, depth_time=2026-10-18T12:45:30+00:00, book20_bid_proxy_usdt=84222, book20_ask_proxy_usdt=67906, funding_indicative=-0.000176, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=8886440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.004339, depth_time=2026-10-18T12:45:11+00:00, book20_bid_proxy_usdt=2665445, book20_ask_proxy_usdt=1306542, funding_indicative=0.000024, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=22353535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.061400, depth_time=2026-10-18T12:45:15+00:00, book20_bid_proxy_usdt=828296, book20_ask_proxy_usdt=447248, funding_indicative=-0.004230, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=45511968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.062570, depth_time=2026-10-18T12:45:11+00:00, book20_bid_proxy_usdt=259646, book20_ask_proxy_usdt=309112, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.91%, turnover=15892524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.658000, depth_time=2026-10-18T12:45:21+00:00, book20_bid_proxy_usdt=177850, book20_ask_proxy_usdt=234921, funding_indicative=-0.000061, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=59008951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=0.079080, depth_time=2026-10-18T12:45:25+00:00, book20_bid_proxy_usdt=494161, book20_ask_proxy_usdt=397498, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=5823358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=1140.020000, depth_time=2026-10-18T12:45:33+00:00, book20_bid_proxy_usdt=176607, book20_ask_proxy_usdt=344712, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=1223778240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T12:45:00+00:00, last15m_closed_end=2026-10-18T12:45+00:00, prior8high=1.862000, depth_time=2026-10-18T12:45:18+00:00, book20_bid_proxy_usdt=37266, book20_ask_proxy_usdt=55922, funding_indicative=-0.000022, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=6376975. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
