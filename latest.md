# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T02:15:38Z**
- feed_generated_utc: 2026-11-07T02:15:40+00:00
- source_sha256: `e56e64a7014b42f01b905899246b03055eba3866092dc5cfdac550509b2fe2ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T02:15+00:00, close=76064.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T02:00+00:00, close=76000, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.145000|-23.68|-45.40|-23.98|35198042|6.92|
|CYBER_USDT|0.315300|-10.93|15.40|-11.23|6438204|6.34|
|ANTHROPIC_USDT|1335.960000|-6.65|-20.30|-6.95|7227895|2.99|
|TRUMPOFFICIAL_USDT|1.198000|-3.54|-23.79|-3.84|11046781|8.34|
|DOT_USDT|0.907800|-3.12|-6.33|-3.42|6720339|1.10|
|PUMPFUN_USDT|0.003953|-2.27|-3.74|-2.57|12397704|2.53|
|APT_USDT|0.604400|-2.10|-3.71|-2.40|5181191|1.65|
|OP_USDT|0.105190|-1.98|-2.79|-2.28|5755445|0.95|
|ARB_USDT|0.165160|-1.81|1.87|-2.11|26180269|0.61|
|ENA_USDT|0.164600|-1.73|-13.31|-2.03|30599911|0.61|
|ONDO_USDT|0.372200|-1.14|-6.81|-1.44|10495220|2.69|
|FARTCOIN_USDT|0.119050|-0.81|-1.03|-1.11|12224644|1.68|
|XRP_USDT|1.178500|-0.74|-6.05|-1.04|329485402|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1335.960000|1331.280000|1335.960000|0.30|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.604400|0.602100|0.604500|11.06|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165160|0.164120|0.165140|0.54|N|Y/Y|N/N|Y|N|
|CYBER_USDT|0.315300|0.314300|0.315300|0.66|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.907800|0.904500|0.907900|0.58|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.164600|0.163260|0.164600|1.54|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.119050|0.117630|0.119050|0.59|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.372200|0.369900|0.372200|0.60|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.105190|0.104920|0.105190|1.03|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003953|0.003901|0.003953|0.45|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.198000|1.196000|1.198000|1.38|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.145000|0.130700|0.145100|0.93|N|Y/Y|N/N|Y|N|
|XRP_USDT|1.178500|1.177000|1.178500|0.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=1354.930000, depth_time=2026-11-07T02:15:12+00:00, book20_bid_proxy_usdt=37480, book20_ask_proxy_usdt=20775, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.65%, turnover=7227895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.604900, depth_time=2026-11-07T02:15:22+00:00, book20_bid_proxy_usdt=230571, book20_ask_proxy_usdt=178530, funding_indicative=0.000015, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=5181191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.165540, depth_time=2026-11-07T02:15:25+00:00, book20_bid_proxy_usdt=113285, book20_ask_proxy_usdt=69907, funding_indicative=-0.000007, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=26180269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.336400, depth_time=2026-11-07T02:15:09+00:00, book20_bid_proxy_usdt=145214, book20_ask_proxy_usdt=136334, funding_indicative=-0.002245, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.93%, turnover=6438204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.913000, depth_time=2026-11-07T02:15:17+00:00, book20_bid_proxy_usdt=541161, book20_ask_proxy_usdt=383866, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=6720339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.164540, depth_time=2026-11-07T02:15:29+00:00, book20_bid_proxy_usdt=214824, book20_ask_proxy_usdt=221561, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=30599911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.118900, depth_time=2026-11-07T02:15:28+00:00, book20_bid_proxy_usdt=67091, book20_ask_proxy_usdt=52314, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.81%, turnover=12224644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.372400, depth_time=2026-11-07T02:15:33+00:00, book20_bid_proxy_usdt=1736295, book20_ask_proxy_usdt=1923110, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=10495220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.105740, depth_time=2026-11-07T02:15:23+00:00, book20_bid_proxy_usdt=202982, book20_ask_proxy_usdt=77121, funding_indicative=-0.000027, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=5755445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.003946, depth_time=2026-11-07T02:15:18+00:00, book20_bid_proxy_usdt=1854294, book20_ask_proxy_usdt=2316030, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=12397704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=1.206000, depth_time=2026-11-07T02:15:10+00:00, book20_bid_proxy_usdt=1432193, book20_ask_proxy_usdt=1164978, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=11046781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=0.145900, depth_time=2026-11-07T02:15:07+00:00, book20_bid_proxy_usdt=195610, book20_ask_proxy_usdt=140041, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-23.68%, turnover=35198042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T02:14:59+00:00, last15m_closed_end=2026-11-07T02:15+00:00, prior8high=1.182100, depth_time=2026-11-07T02:15:36+00:00, book20_bid_proxy_usdt=3590898, book20_ask_proxy_usdt=3863837, funding_indicative=0.000053, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=329485402. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
