# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T19:15:43Z**
- feed_generated_utc: 2026-10-16T19:15:45+00:00
- source_sha256: `d69d98cae40b903c280118145c8c68f2d6ed26dd5bff02177415018635c6add5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T19:15+00:00, close=81368.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T19:00+00:00, close=81114.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.195810|-4.49|60.94|-4.56|21465243|1.02|
|RIVER_USDT|1.081000|-3.99|-8.54|-4.06|6112054|9.26|
|ZEC_USDT|1144.530000|-3.65|-6.06|-3.72|1500251877|0.09|
|INJ_USDT|8.650000|-3.65|24.83|-3.72|114325723|1.16|
|ZRO_USDT|2.030500|-3.36|-0.30|-3.43|15782235|0.98|
|PYTH_USDT|0.083960|-2.68|-1.67|-2.75|5483759|1.19|
|OP_USDT|0.136720|-2.34|10.95|-2.41|15127565|1.46|
|WLD_USDT|0.498100|-2.08|1.13|-2.15|93669638|2.01|
|TAO_USDT|275.160000|-1.94|0.17|-2.01|82159128|0.73|
|HBAR_USDT|0.082480|-1.93|-9.22|-2.00|22502986|1.21|
|APT_USDT|0.841800|-1.67|5.15|-1.74|13067316|1.19|
|STRK_USDT|0.072890|-1.43|-3.21|-1.50|25512760|1.37|
|ARB_USDT|0.192310|-1.34|6.36|-1.41|36329279|0.52|
|DOT_USDT|1.155800|-1.28|-2.71|-1.35|22490168|0.86|
|DASH_USDT|48.410000|-1.10|-5.70|-1.17|10957915|2.06|
|FARTCOIN_USDT|0.153100|-1.04|-6.28|-1.11|7456354|0.65|
|ATOM_USDT|1.722000|-1.03|-13.72|-1.10|7145584|5.81|
|NEAR_USDT|4.995000|-1.01|5.13|-1.08|185665012|2.00|
|SUI_USDT|1.010500|-0.97|-4.45|-1.04|99711285|0.99|
|FET_USDT|0.197700|-0.95|-8.89|-1.02|11424182|5.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.841800|0.825100|0.841800|0.55|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192310|0.189190|0.192240|0.45|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.195810|0.191460|0.195920|0.46|N|Y/Y|N/N|Y|N|
|DASH_USDT|48.410000|48.020000|48.410000|0.75|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.155800|1.134400|1.155800|0.35|N|Y/N|N/N|Y|N|
|HBAR_USDT|0.082480|0.082050|0.082480|0.69|N|Y/Y|Y/N|Y|N|
|INJ_USDT|8.650000|8.521000|8.651000|0.44|N|Y/Y|N/N|Y|N|
|OP_USDT|0.136720|0.133270|0.136660|2.13|N|Y/Y|N/N|Y|N|
|PYTH_USDT|0.083960|0.083060|0.083960|2.73|N|Y/Y|Y/N|Y|N|
|RIVER_USDT|1.081000|1.066000|1.081000|0.88|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072890|0.071560|0.072890|0.74|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.160000|272.270000|275.000000|0.85|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.498100|0.492700|0.498100|0.59|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1144.530000|1133.160000|1143.770000|0.82|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.030500|1.975000|2.030500|1.25|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.853600, depth_time=2026-10-16T19:15:32+00:00, book20_bid_proxy_usdt=97555, book20_ask_proxy_usdt=74751, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=13067316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.195640, depth_time=2026-10-16T19:15:37+00:00, book20_bid_proxy_usdt=46077, book20_ask_proxy_usdt=67369, funding_indicative=0.000041, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=36329279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.201110, depth_time=2026-10-16T19:15:07+00:00, book20_bid_proxy_usdt=22776, book20_ask_proxy_usdt=28287, funding_indicative=-0.000191, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.49%, turnover=21465243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-16T19:15:02+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=49.040000, depth_time=2026-10-16T19:15:42+00:00, book20_bid_proxy_usdt=757598, book20_ask_proxy_usdt=977232, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=10957915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=1.181200, depth_time=2026-10-16T19:15:40+00:00, book20_bid_proxy_usdt=121498, book20_ask_proxy_usdt=234509, funding_indicative=0.000063, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=22490168. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.083330, depth_time=2026-10-16T19:15:29+00:00, book20_bid_proxy_usdt=1042637, book20_ask_proxy_usdt=761273, funding_indicative=0.000027, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=22502986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=8.853000, depth_time=2026-10-16T19:15:15+00:00, book20_bid_proxy_usdt=254219, book20_ask_proxy_usdt=123826, funding_indicative=0.000232, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=114325723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.138210, depth_time=2026-10-16T19:15:22+00:00, book20_bid_proxy_usdt=46834, book20_ask_proxy_usdt=35505, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=15127565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.086180, depth_time=2026-10-16T19:15:20+00:00, book20_bid_proxy_usdt=154154, book20_ask_proxy_usdt=150826, funding_indicative=-0.000033, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=5483759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=1.129000, depth_time=2026-10-16T19:15:09+00:00, book20_bid_proxy_usdt=389594, book20_ask_proxy_usdt=326684, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=6112054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.073630, depth_time=2026-10-16T19:15:35+00:00, book20_bid_proxy_usdt=436026, book20_ask_proxy_usdt=247906, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=25512760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=279.920000, depth_time=2026-10-16T19:15:27+00:00, book20_bid_proxy_usdt=59694, book20_ask_proxy_usdt=66373, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=82159128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=0.508400, depth_time=2026-10-16T19:15:25+00:00, book20_bid_proxy_usdt=1349349, book20_ask_proxy_usdt=1797199, funding_indicative=0.000074, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=93669638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=1171.830000, depth_time=2026-10-16T19:15:13+00:00, book20_bid_proxy_usdt=198643, book20_ask_proxy_usdt=570278, funding_indicative=0.000067, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=1500251877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T19:15:01+00:00, last15m_closed_end=2026-10-16T19:15+00:00, prior8high=2.051400, depth_time=2026-10-16T19:15:17+00:00, book20_bid_proxy_usdt=80905, book20_ask_proxy_usdt=33960, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=15782235. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
