# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T08:45:44Z**
- feed_generated_utc: 2026-10-18T08:45:46+00:00
- source_sha256: `974ae25f8f71c65b6242e35c30790bd94cbe898c8f75c213bafa3933ddc2c5fe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T08:45+00:00, close=81691.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063310|-4.29|-32.23|-4.75|14379950|1.58|
|EIGEN_USDT|0.246400|-3.86|4.58|-4.32|7334430|4.06|
|FILECOIN_USDT|1.046200|-3.78|-7.23|-4.24|19634309|0.96|
|PUMPFUN_USDT|0.004265|-3.33|-25.50|-3.79|23405565|2.35|
|ZRO_USDT|1.827200|-3.08|-9.57|-3.54|7162325|0.55|
|QNT_USDT|194.670000|-2.86|-20.58|-3.32|68827596|0.51|
|XPL_USDT|0.077940|-2.73|-10.16|-3.19|5529724|1.28|
|OP_USDT|0.125660|-2.58|-9.30|-3.04|9271416|3.18|
|TIA_USDT|0.642000|-2.43|25.14|-2.89|59347296|1.56|
|ZEC_USDT|1122.130000|-1.68|-8.90|-2.14|1196011851|0.18|
|ARB_USDT|0.180870|-1.65|-3.10|-2.11|31632186|0.55|
|DOT_USDT|1.100200|-1.53|-12.46|-1.99|16431941|0.91|
|WLD_USDT|0.488500|-1.43|-12.61|-1.89|59253152|2.05|
|ENA_USDT|0.186710|-1.29|-15.91|-1.75|28022839|0.54|
|FARTCOIN_USDT|0.146200|-1.24|-10.80|-1.70|5828882|0.68|
|ONDO_USDT|0.435000|-1.04|-12.05|-1.50|22131908|2.30|
|APT_USDT|0.789300|-1.02|-4.53|-1.48|9916256|1.27|
|PEPE_USDT|0.000004|-0.80|-4.38|-1.26|57966208|0.26|
|ICP_USDT|2.907000|-0.71|-7.68|-1.17|6116728|3.44|
|TAO_USDT|266.390000|-0.61|-6.23|-1.07|54843666|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180870|0.180960|0.180870|1.85|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|1.100200|1.098300|1.100200|0.64|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.246400|0.246100|0.246300|0.54|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.186710|0.186730|0.186720|1.82|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.146200|0.146320|0.146190|0.82|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.046200|1.045000|1.046100|1.83|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.125660|0.125750|0.125650|2.04|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004265|0.004250|0.004265|0.32|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.670000|192.710000|194.670000|1.14|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063310|0.062200|0.063290|0.96|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.642000|0.624400|0.642000|1.90|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.488500|0.487300|0.488300|0.93|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.077940|0.078090|0.077930|2.02|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1122.130000|1119.150000|1122.110000|0.95|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.827200|1.824400|1.827200|2.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.184140, depth_time=2026-10-18T08:45:33+00:00, book20_bid_proxy_usdt=84256, book20_ask_proxy_usdt=60365, funding_indicative=-0.000030, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=31632186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=1.107500, depth_time=2026-10-18T08:45:36+00:00, book20_bid_proxy_usdt=407977, book20_ask_proxy_usdt=259114, funding_indicative=-0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=16431941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.249000, depth_time=2026-10-18T08:45:07+00:00, book20_bid_proxy_usdt=632679, book20_ask_proxy_usdt=338932, funding_indicative=-0.000004, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=7334430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.188860, depth_time=2026-10-18T08:45:40+00:00, book20_bid_proxy_usdt=238602, book20_ask_proxy_usdt=85858, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=28022839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.148100, depth_time=2026-10-18T08:45:43+00:00, book20_bid_proxy_usdt=41683, book20_ask_proxy_usdt=49098, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=5828882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=1.056500, depth_time=2026-10-18T08:45:13+00:00, book20_bid_proxy_usdt=504143, book20_ask_proxy_usdt=711263, funding_indicative=-0.000057, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=19634309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.127350, depth_time=2026-10-18T08:45:25+00:00, book20_bid_proxy_usdt=99819, book20_ask_proxy_usdt=58713, funding_indicative=-0.000173, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=9271416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.004309, depth_time=2026-10-18T08:45:14+00:00, book20_bid_proxy_usdt=2311353, book20_ask_proxy_usdt=1448123, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=23405565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=195.310000, depth_time=2026-10-18T08:45:20+00:00, book20_bid_proxy_usdt=65947, book20_ask_proxy_usdt=79009, funding_indicative=-0.000065, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=68827596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.064330, depth_time=2026-10-18T08:45:08+00:00, book20_bid_proxy_usdt=611969, book20_ask_proxy_usdt=262883, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=14379950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.643200, depth_time=2026-10-18T08:45:27+00:00, book20_bid_proxy_usdt=309813, book20_ask_proxy_usdt=980510, funding_indicative=-0.000077, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=59347296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.494400, depth_time=2026-10-18T08:45:38+00:00, book20_bid_proxy_usdt=2416111, book20_ask_proxy_usdt=1640039, funding_indicative=-0.000098, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=59253152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T08:45:02+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=0.078880, depth_time=2026-10-18T08:45:22+00:00, book20_bid_proxy_usdt=511911, book20_ask_proxy_usdt=525489, funding_indicative=0.000038, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=5529724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=1142.650000, depth_time=2026-10-18T08:45:30+00:00, book20_bid_proxy_usdt=293484, book20_ask_proxy_usdt=215269, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=1196011851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T08:45:01+00:00, last15m_closed_end=2026-10-18T08:45+00:00, prior8high=1.853200, depth_time=2026-10-18T08:45:18+00:00, book20_bid_proxy_usdt=56198, book20_ask_proxy_usdt=47260, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=7162325. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
