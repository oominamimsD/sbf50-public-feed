# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T06:15:44Z**
- feed_generated_utc: 2026-10-18T06:15:46+00:00
- source_sha256: `59663a907fadce61373322309b963cb571fabb548cb9bf86a266d77e764a9a5f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T06:15+00:00, close=81711, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T06:00+00:00, close=81700.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062570|-5.41|-33.03|-5.89|13975364|1.60|
|TIA_USDT|0.624400|-5.10|21.71|-5.58|61645999|1.60|
|FILECOIN_USDT|1.045500|-3.85|-7.29|-4.33|19821728|0.96|
|EIGEN_USDT|0.246900|-3.66|4.79|-4.14|8380843|4.05|
|QNT_USDT|193.940000|-3.22|-20.88|-3.70|69440453|0.52|
|PUMPFUN_USDT|0.004283|-2.92|-25.18|-3.40|23401133|2.33|
|OP_USDT|0.125530|-2.68|-9.39|-3.16|9638267|2.39|
|XPL_USDT|0.078120|-2.50|-9.95|-2.98|5114876|1.28|
|ZRO_USDT|1.839500|-2.42|-8.96|-2.90|7215006|0.54|
|DOT_USDT|1.096500|-1.87|-12.76|-2.35|16582916|1.82|
|WLD_USDT|0.486900|-1.75|-12.89|-2.23|59743920|2.05|
|APT_USDT|0.785300|-1.52|-5.01|-2.00|10307213|1.27|
|ARB_USDT|0.181230|-1.46|-2.91|-1.94|30779971|0.55|
|ENA_USDT|0.187120|-1.07|-15.72|-1.55|28273154|0.53|
|AVAX_USDT|9.725000|-0.95|-7.60|-1.43|79029860|1.03|
|ZEC_USDT|1130.530000|-0.94|-8.21|-1.42|1156814989|0.09|
|ICP_USDT|2.905000|-0.78|-7.74|-1.26|6308096|3.44|
|FARTCOIN_USDT|0.147010|-0.70|-10.31|-1.18|6090914|0.68|
|TAO_USDT|266.240000|-0.66|-6.28|-1.14|52226684|1.13|
|SUI_USDT|0.975600|-0.63|-13.19|-1.11|74609503|1.02|
|PEPE_USDT|0.000004|-0.55|-4.14|-1.03|58254669|0.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.785300|0.780900|0.785300|2.57|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.181230|0.180100|0.181230|0.90|N|Y/Y|Y/Y|N|N|
|AVAX_USDT|9.725000|9.701000|9.725000|0.76|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.096500|1.089000|1.096500|1.54|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.246900|0.244000|0.246900|1.34|N|Y/Y|N/Y|N|N|
|ENA_USDT|0.187120|0.186180|0.187120|1.17|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.045500|1.040400|1.045500|1.79|N|Y/Y|Y/Y|N|N|
|OP_USDT|0.125530|0.124920|0.125530|1.22|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004283|0.004262|0.004283|0.34|N|Y/Y|Y/Y|N|N|
|QNT_USDT|193.940000|191.970000|193.940000|0.91|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.062570|0.062540|0.062570|1.10|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.624400|0.623900|0.624300|3.23|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.486900|0.483600|0.486900|0.72|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.078120|0.077620|0.078120|5.88|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.839500|1.827700|1.839500|0.55|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.796700, depth_time=2026-10-18T06:15:36+00:00, book20_bid_proxy_usdt=130258, book20_ask_proxy_usdt=159611, funding_indicative=-0.000115, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=10307213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.185520, depth_time=2026-10-18T06:15:38+00:00, book20_bid_proxy_usdt=105572, book20_ask_proxy_usdt=95912, funding_indicative=-0.000058, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=30779971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=9.869000, depth_time=2026-10-18T06:15:42+00:00, book20_bid_proxy_usdt=1428753, book20_ask_proxy_usdt=732803, funding_indicative=0.000003, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=79029860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=1.115300, depth_time=2026-10-18T06:15:30+00:00, book20_bid_proxy_usdt=387038, book20_ask_proxy_usdt=249809, funding_indicative=-0.000067, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=16582916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.252900, depth_time=2026-10-18T06:15:15+00:00, book20_bid_proxy_usdt=623968, book20_ask_proxy_usdt=397877, funding_indicative=-0.000038, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=8380843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.191430, depth_time=2026-10-18T06:15:41+00:00, book20_bid_proxy_usdt=211443, book20_ask_proxy_usdt=170026, funding_indicative=0.000001, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.07%, turnover=28273154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=1.070500, depth_time=2026-10-18T06:15:13+00:00, book20_bid_proxy_usdt=743291, book20_ask_proxy_usdt=623638, funding_indicative=-0.000104, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=19821728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.129220, depth_time=2026-10-18T06:15:23+00:00, book20_bid_proxy_usdt=83268, book20_ask_proxy_usdt=74011, funding_indicative=-0.000177, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=9638267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.004382, depth_time=2026-10-18T06:15:21+00:00, book20_bid_proxy_usdt=2129181, book20_ask_proxy_usdt=1355324, funding_indicative=0.000037, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=23401133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=196.530000, depth_time=2026-10-18T06:15:19+00:00, book20_bid_proxy_usdt=99728, book20_ask_proxy_usdt=121620, funding_indicative=-0.000075, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=69440453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.063720, depth_time=2026-10-18T06:15:09+00:00, book20_bid_proxy_usdt=579036, book20_ask_proxy_usdt=481918, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.41%, turnover=13975364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.637700, depth_time=2026-10-18T06:15:11+00:00, book20_bid_proxy_usdt=301398, book20_ask_proxy_usdt=238797, funding_indicative=-0.000013, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.10%, turnover=61645999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.496700, depth_time=2026-10-18T06:15:33+00:00, book20_bid_proxy_usdt=2017472, book20_ask_proxy_usdt=1839548, funding_indicative=-0.000127, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=59743920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T06:15:01+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=0.079410, depth_time=2026-10-18T06:15:26+00:00, book20_bid_proxy_usdt=699410, book20_ask_proxy_usdt=467885, funding_indicative=0.000013, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=5114876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T06:15:00+00:00, last15m_closed_end=2026-10-18T06:15+00:00, prior8high=1.906600, depth_time=2026-10-18T06:15:29+00:00, book20_bid_proxy_usdt=93430, book20_ask_proxy_usdt=58763, funding_indicative=0.000027, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=7215006. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
