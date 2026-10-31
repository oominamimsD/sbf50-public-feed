# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T23:15:35Z**
- feed_generated_utc: 2026-10-31T23:15:38+00:00
- source_sha256: `9502956a1d35236bae6d1842702fb4e9a9bb86d3b49c1e5a622e5c1e03db93ed`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T23:15+00:00, close=77486.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T23:00+00:00, close=77498.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.247710|-16.35|47.51|-16.26|28419582|2.42|
|BLESS_USDT|0.009381|-11.19|15.62|-11.10|7811641|5.32|
|TRX_USDT|0.301320|-3.52|-8.39|-3.43|10240181|0.33|
|INJ_USDT|7.230000|-3.41|-3.77|-3.32|20463988|1.38|
|ZEC_USDT|1247.940000|-2.85|8.97|-2.76|1049708829|0.08|
|ENA_USDT|0.189240|-2.45|1.31|-2.36|45922863|0.53|
|FET_USDT|0.159900|-2.08|-7.19|-1.99|5707256|6.26|
|BTW_USDT|1.099100|-2.03|-36.88|-1.94|5453222|0.91|
|Q_USDT|0.031480|-1.87|-60.11|-1.78|10558426|6.36|
|WLD_USDT|0.398900|-1.36|-13.65|-1.27|34604846|2.51|
|FARTCOIN_USDT|0.120320|-1.36|-1.36|-1.27|6502760|0.83|
|AKE_USDT|0.010994|-1.29|-62.38|-1.20|11855447|1.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010994|0.011017|0.010994|0.31|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009381|0.009313|0.009381|1.63|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.099100|1.086300|1.099100|0.90|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.189240|0.187500|0.189230|0.77|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120320|0.119850|0.120320|2.56|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159900|0.159500|0.159900|1.30|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.230000|7.198000|7.230000|0.57|N|Y/N|Y/Y|Y|N|
|LSK_USDT|0.247710|0.237060|0.247730|0.69|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031480|0.031320|0.031480|0.77|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.301320|0.300760|0.301320|0.05|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398900|0.394900|0.398900|1.01|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1247.940000|1246.700000|1247.950000|1.94|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.011405, depth_time=2026-10-31T23:15:34+00:00, book20_bid_proxy_usdt=14320, book20_ask_proxy_usdt=6879, funding_indicative=-0.000442, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=11855447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.009629, depth_time=2026-10-31T23:15:10+00:00, book20_bid_proxy_usdt=11070, book20_ask_proxy_usdt=17313, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.19%, turnover=7811641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=1.131000, depth_time=2026-10-31T23:15:25+00:00, book20_bid_proxy_usdt=25335, book20_ask_proxy_usdt=16155, funding_indicative=-0.000109, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=5453222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T23:14:59+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.191470, depth_time=2026-10-31T23:15:20+00:00, book20_bid_proxy_usdt=114898, book20_ask_proxy_usdt=147402, funding_indicative=-0.000031, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=45922863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.121480, depth_time=2026-10-31T23:15:32+00:00, book20_bid_proxy_usdt=64496, book20_ask_proxy_usdt=74166, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=6502760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.161300, depth_time=2026-10-31T23:15:22+00:00, book20_bid_proxy_usdt=1309005, book20_ask_proxy_usdt=801669, funding_indicative=-0.000230, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=5707256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=7.312000, depth_time=2026-10-31T23:15:15+00:00, book20_bid_proxy_usdt=309893, book20_ask_proxy_usdt=470519, funding_indicative=0.000108, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=20463988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T23:14:59+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.249390, depth_time=2026-10-31T23:15:08+00:00, book20_bid_proxy_usdt=9696, book20_ask_proxy_usdt=8582, funding_indicative=-0.001058, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.35%, turnover=28419582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.032570, depth_time=2026-10-31T23:15:27+00:00, book20_bid_proxy_usdt=53941, book20_ask_proxy_usdt=64723, funding_indicative=-0.001272, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=1, 24h_change=-1.87%, turnover=10558426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.305440, depth_time=2026-10-31T23:15:11+00:00, book20_bid_proxy_usdt=240931, book20_ask_proxy_usdt=86332, funding_indicative=-0.001145, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=10240181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T23:15:00+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=0.400500, depth_time=2026-10-31T23:15:29+00:00, book20_bid_proxy_usdt=2623573, book20_ask_proxy_usdt=3646327, funding_indicative=0.000069, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=34604846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-31T23:14:59+00:00, last15m_closed_end=2026-10-31T23:15+00:00, prior8high=1284.960000, depth_time=2026-10-31T23:15:17+00:00, book20_bid_proxy_usdt=218598, book20_ask_proxy_usdt=797938, funding_indicative=-0.000029, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=1049708829. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
