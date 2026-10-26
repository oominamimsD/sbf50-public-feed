# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T03:45:31Z**
- feed_generated_utc: 2026-10-26T03:45:34+00:00
- source_sha256: `bd17e7fac62e08418a83accb31d0abe0994fc08766027e798443068ff42669d5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T03:45+00:00, close=79567.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T03:00+00:00, close=79535.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.034630|-16.17|27.12|-14.89|12147015|2.90|
|T_USDT|0.004958|-7.89|5.44|-6.61|6936282|4.04|
|IRYS_USDT|0.036580|-4.83|199.83|-3.55|17262938|2.73|
|DASH_USDT|50.260000|-4.10|4.97|-2.82|13821181|5.97|
|LIT_USDT|3.065300|-3.55|4.60|-2.27|6162593|0.33|
|WLD_USDT|0.440800|-3.46|-7.45|-2.18|73694570|2.27|
|PUMPFUN_USDT|0.004150|-3.15|-1.07|-1.87|17642906|2.41|
|XMR_USDT|590.700000|-2.72|1.40|-1.44|6816016|0.17|
|PEPE_USDT|0.000004|-2.51|11.17|-1.23|71051895|1.64|
|HYPE_USDT|75.182000|-2.35|-3.04|-1.07|29030918|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034630|0.032120|0.034630|1.44|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.260000|50.270000|50.260000|0.76|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|75.182000|75.020000|75.182000|0.76|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036580|0.036220|0.036530|0.47|N|N/Y|Y/Y|Y|N|
|LIT_USDT|3.065300|3.094400|3.065300|1.60|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000004|0.000004|0.000004|1.03|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004150|0.004152|0.004151|4.77|Y|Y/Y|Y/Y|Y|Y|
|T_USDT|0.004958|0.004873|0.004959|0.27|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.440800|0.441300|0.440800|1.10|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.700000|588.410000|590.700000|0.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=0.037800, depth_time=2026-10-26T03:45:08+00:00, book20_bid_proxy_usdt=62966, book20_ask_proxy_usdt=94597, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.17%, turnover=12147015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=51.150000, depth_time=2026-10-26T03:45:14+00:00, book20_bid_proxy_usdt=1097675, book20_ask_proxy_usdt=697149, funding_indicative=0.000034, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=13821181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=76.506000, depth_time=2026-10-26T03:45:30+00:00, book20_bid_proxy_usdt=286838, book20_ask_proxy_usdt=65310, funding_indicative=0.000007, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=29030918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=0.040400, depth_time=2026-10-26T03:45:13+00:00, book20_bid_proxy_usdt=27120, book20_ask_proxy_usdt=62014, funding_indicative=-0.000545, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=1, 24h_change=-4.83%, turnover=17262938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=3.166400, depth_time=2026-10-26T03:45:17+00:00, book20_bid_proxy_usdt=32204, book20_ask_proxy_usdt=31910, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=6162593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=0.000004, depth_time=2026-10-26T03:45:26+00:00, book20_bid_proxy_usdt=64372, book20_ask_proxy_usdt=57870, funding_indicative=-0.000017, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=71051895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=0.004234, depth_time=2026-10-26T03:45:23+00:00, book20_bid_proxy_usdt=1894878, book20_ask_proxy_usdt=1895228, funding_indicative=0.000042, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=17642906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=0.004998, depth_time=2026-10-26T03:45:10+00:00, book20_bid_proxy_usdt=60252, book20_ask_proxy_usdt=51189, funding_indicative=-0.001759, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=1, 24h_change=-7.89%, turnover=6936282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=0.447900, depth_time=2026-10-26T03:45:20+00:00, book20_bid_proxy_usdt=2653207, book20_ask_proxy_usdt=2461914, funding_indicative=0.000090, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=73694570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T03:45:02+00:00, last15m_closed_end=2026-10-26T03:45+00:00, prior8high=598.030000, depth_time=2026-10-26T03:45:24+00:00, book20_bid_proxy_usdt=22073, book20_ask_proxy_usdt=10026, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=6816016. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
