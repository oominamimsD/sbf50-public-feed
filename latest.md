# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T23:00:44Z**
- feed_generated_utc: 2026-10-22T23:00:48+00:00
- source_sha256: `176edf5ccb741ab343f2504928b9d45efb2feb49ddf81d6ae14656dec3ee0af6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T23:00+00:00, close=81314.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T23:00+00:00, close=81314.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-22T20:00+00:00, close=81462.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.421100|-6.02|10.66|-5.62|14749050|0.29|
|XMR_USDT|596.510000|-3.87|9.66|-3.47|26761707|0.17|
|STRK_USDT|0.052860|-3.78|-45.14|-3.38|13481809|1.89|
|PUMPFUN_USDT|0.004546|-3.29|0.44|-2.89|36688680|2.20|
|XPL_USDT|0.075550|-3.27|-10.84|-2.87|5510782|1.32|
|APT_USDT|0.753700|-2.87|-8.83|-2.47|8807693|1.33|
|ARB_USDT|0.178840|-2.78|-5.84|-2.38|32498692|0.56|
|PHA_USDT|0.060950|-2.68|20.64|-2.28|8392132|3.28|
|ZEC_USDT|1208.150000|-2.61|2.40|-2.21|1844860102|0.08|
|NEAR_USDT|4.864000|-2.46|-4.98|-2.06|148365598|2.06|
|EIGEN_USDT|0.217200|-2.25|-12.41|-1.85|6054460|4.60|
|INJ_USDT|7.882000|-2.11|-1.58|-1.71|29118644|1.27|
|QNT_USDT|186.710000|-2.09|-10.19|-1.69|59352421|1.61|
|ADA_USDT|0.211500|-1.90|-8.24|-1.50|32599625|4.73|
|CRV_USDT|0.362200|-1.84|2.22|-1.44|5365419|2.76|
|OP_USDT|0.117730|-1.79|-15.22|-1.39|6923188|0.85|
|TIA_USDT|0.558300|-1.77|-7.33|-1.37|23578860|1.79|
|SEI_USDT|0.057040|-1.77|-7.19|-1.37|10726530|1.75|
|ICP_USDT|2.709000|-1.74|-11.52|-1.34|7289897|3.69|
|ZRO_USDT|1.775600|-1.49|-16.39|-1.09|6510194|0.56|
|HYPE_USDT|77.152000|-1.45|-5.52|-1.05|66949163|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.211500|0.210200|0.211500|0.13|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.753700|0.754200|0.753700|1.12|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.178840|0.178300|0.178840|0.56|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.362200|0.362400|0.362200|0.46|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.217200|0.216400|0.217200|0.73|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.882000|7.853000|7.882000|0.33|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.421100|3.378800|3.421100|1.56|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.864000|4.842000|4.864000|0.20|N|Y/Y|Y/Y|Y|N|
|PHA_USDT|0.060950|0.060580|0.060950|0.30|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004546|0.004552|0.004548|6.90|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|186.710000|186.570000|186.670000|0.76|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052860|0.052550|0.052860|0.93|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|596.510000|586.430000|596.510000|0.42|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.075550|0.075180|0.075550|0.47|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1208.150000|1204.920000|1208.150000|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.212900, depth_time=2026-10-22T23:00:40+00:00, book20_bid_proxy_usdt=6712735, book20_ask_proxy_usdt=5181756, funding_indicative=-0.000111, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=32599625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.764700, depth_time=2026-10-22T23:00:20+00:00, book20_bid_proxy_usdt=182610, book20_ask_proxy_usdt=121460, funding_indicative=-0.000046, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=8807693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.182560, depth_time=2026-10-22T23:00:24+00:00, book20_bid_proxy_usdt=82119, book20_ask_proxy_usdt=82050, funding_indicative=-0.000139, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=32498692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-22T23:00:01+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.366600, depth_time=2026-10-22T23:00:41+00:00, book20_bid_proxy_usdt=403764, book20_ask_proxy_usdt=381360, funding_indicative=-0.000080, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=5365419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-22T23:00:01+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.220100, depth_time=2026-10-22T23:00:30+00:00, book20_bid_proxy_usdt=630789, book20_ask_proxy_usdt=435387, funding_indicative=-0.000006, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=6054460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=7.966000, depth_time=2026-10-22T23:00:35+00:00, book20_bid_proxy_usdt=277516, book20_ask_proxy_usdt=305323, funding_indicative=0.000163, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=29118644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=3.594800, depth_time=2026-10-22T23:00:09+00:00, book20_bid_proxy_usdt=26211, book20_ask_proxy_usdt=70450, funding_indicative=0.000043, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.02%, turnover=14749050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=4.941000, depth_time=2026-10-22T23:00:30+00:00, book20_bid_proxy_usdt=2386365, book20_ask_proxy_usdt=1884228, funding_indicative=0.000055, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=148365598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.062320, depth_time=2026-10-22T23:00:25+00:00, book20_bid_proxy_usdt=100282, book20_ask_proxy_usdt=72953, funding_indicative=-0.000447, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=8392132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.004685, depth_time=2026-10-22T23:00:16+00:00, book20_bid_proxy_usdt=1485338, book20_ask_proxy_usdt=2523297, funding_indicative=0.000010, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=36688680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=190.190000, depth_time=2026-10-22T23:00:37+00:00, book20_bid_proxy_usdt=135299, book20_ask_proxy_usdt=84068, funding_indicative=-0.000159, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=59352421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.053720, depth_time=2026-10-22T23:00:13+00:00, book20_bid_proxy_usdt=736920, book20_ask_proxy_usdt=634786, funding_indicative=0.000035, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.78%, turnover=13481809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=612.120000, depth_time=2026-10-22T23:00:12+00:00, book20_bid_proxy_usdt=7830, book20_ask_proxy_usdt=13988, funding_indicative=0.000100, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=26761707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-22T23:00:01+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=0.076450, depth_time=2026-10-22T23:00:19+00:00, book20_bid_proxy_usdt=502332, book20_ask_proxy_usdt=722992, funding_indicative=0.000006, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=5510782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-22T23:00:00+00:00, last15m_closed_end=2026-10-22T23:00+00:00, prior8high=1225.760000, depth_time=2026-10-22T23:00:28+00:00, book20_bid_proxy_usdt=507526, book20_ask_proxy_usdt=190765, funding_indicative=0.000065, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=1844860102. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
