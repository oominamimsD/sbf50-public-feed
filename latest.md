# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T17:00:41Z**
- feed_generated_utc: 2026-10-16T17:00:43+00:00
- source_sha256: `e0216d0d011c878a6de9a3217da72420ea5619a4a8e4781ebebebce17ec5199c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T17:00+00:00, close=81405.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T17:00+00:00, close=81405.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|2.009000|-7.16|-1.36|-7.27|15008241|1.00|
|NEAR_USDT|5.049000|-3.29|6.27|-3.40|184469837|1.98|
|WLD_USDT|0.507900|-3.05|3.12|-3.16|88115151|3.94|
|ZEC_USDT|1153.720000|-2.88|-5.30|-2.99|1488795000|0.17|
|AAVE_USDT|155.910000|-2.65|-8.20|-2.76|31360092|1.28|
|HBAR_USDT|0.083270|-2.65|-8.35|-2.76|21541498|1.20|
|PUMPFUN_USDT|0.004302|-2.13|-21.79|-2.24|17455271|2.32|
|PEPE_USDT|0.000004|-1.90|2.11|-2.01|77922059|0.25|
|ARB_USDT|0.193530|-1.87|7.04|-1.98|34166493|0.52|
|ONDO_USDT|0.454900|-1.72|-5.24|-1.83|29380651|4.39|
|LINK_USDT|12.340000|-1.40|-3.66|-1.51|60297622|0.81|
|OP_USDT|0.138050|-1.39|12.03|-1.50|13937274|2.17|
|LTC_USDT|59.730000|-1.28|-6.08|-1.39|9499306|3.35|
|DOGE_USDT|0.080470|-1.17|-4.88|-1.28|84339347|1.24|
|QNT_USDT|203.410000|-1.09|-18.45|-1.20|65134262|0.98|
|FARTCOIN_USDT|0.153030|-1.09|-6.32|-1.20|7429259|0.65|
|TAO_USDT|278.100000|-0.89|1.24|-1.00|76066868|1.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.910000|156.790000|155.930000|1.26|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.193530|0.193590|0.193530|0.71|N|Y/N|N/N|Y|N|
|DOGE_USDT|0.080470|0.080160|0.080470|1.15|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.083270|0.083510|0.083270|0.52|N|Y/Y|Y/N|Y|N|
|LINK_USDT|12.340000|12.289000|12.340000|0.83|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|59.730000|59.710000|59.730000|1.48|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|5.049000|5.026000|5.049000|1.52|N|Y/Y|Y/N|Y|N|
|ONDO_USDT|0.454900|0.453700|0.454900|0.77|N|Y/Y|Y/N|Y|N|
|OP_USDT|0.138050|0.137330|0.138020|0.65|N|Y/N|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.72|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004302|0.004277|0.004302|3.25|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|203.410000|200.590000|203.410000|0.69|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.507900|0.506300|0.507900|0.65|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1153.720000|1161.220000|1152.990000|1.85|Y|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.009000|2.074500|2.009700|2.47|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=160.940000, depth_time=2026-10-16T17:00:16+00:00, book20_bid_proxy_usdt=335151, book20_ask_proxy_usdt=427348, funding_indicative=0.000073, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=31360092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.199440, depth_time=2026-10-16T17:00:26+00:00, book20_bid_proxy_usdt=29945, book20_ask_proxy_usdt=69586, funding_indicative=0.000019, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=34166493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.082150, depth_time=2026-10-16T17:00:37+00:00, book20_bid_proxy_usdt=3446460, book20_ask_proxy_usdt=4353131, funding_indicative=0.000001, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=84339347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.086520, depth_time=2026-10-16T17:00:18+00:00, book20_bid_proxy_usdt=1313676, book20_ask_proxy_usdt=1107575, funding_indicative=0.000093, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=21541498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=12.643000, depth_time=2026-10-16T17:00:31+00:00, book20_bid_proxy_usdt=314094, book20_ask_proxy_usdt=537302, funding_indicative=-0.000006, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=60297622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=60.960000, depth_time=2026-10-16T17:00:35+00:00, book20_bid_proxy_usdt=956562, book20_ask_proxy_usdt=1379300, funding_indicative=0.000042, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=9499306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=5.283000, depth_time=2026-10-16T17:00:09+00:00, book20_bid_proxy_usdt=1491438, book20_ask_proxy_usdt=2825531, funding_indicative=0.000019, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=184469837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.467900, depth_time=2026-10-16T17:00:28+00:00, book20_bid_proxy_usdt=1283099, book20_ask_proxy_usdt=1632414, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=29380651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.142960, depth_time=2026-10-16T17:00:32+00:00, book20_bid_proxy_usdt=31969, book20_ask_proxy_usdt=25937, funding_indicative=0.000057, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=13937274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.000004, depth_time=2026-10-16T17:00:23+00:00, book20_bid_proxy_usdt=41064, book20_ask_proxy_usdt=219448, funding_indicative=-0.000080, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=77922059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.004461, depth_time=2026-10-16T17:00:20+00:00, book20_bid_proxy_usdt=1726648, book20_ask_proxy_usdt=1734414, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=17455271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=207.760000, depth_time=2026-10-16T17:00:40+00:00, book20_bid_proxy_usdt=68631, book20_ask_proxy_usdt=59680, funding_indicative=-0.000032, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=65134262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=0.529500, depth_time=2026-10-16T17:00:11+00:00, book20_bid_proxy_usdt=1109613, book20_ask_proxy_usdt=1740133, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=88115151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=1226.700000, depth_time=2026-10-16T17:00:14+00:00, book20_bid_proxy_usdt=81987, book20_ask_proxy_usdt=570624, funding_indicative=0.000020, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=1488795000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T17:00:02+00:00, last15m_closed_end=2026-10-16T17:00+00:00, prior8high=2.187000, depth_time=2026-10-16T17:00:07+00:00, book20_bid_proxy_usdt=45366, book20_ask_proxy_usdt=60522, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.16%, turnover=15008241. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
