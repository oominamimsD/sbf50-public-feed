# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T09:45:35Z**
- feed_generated_utc: 2026-11-11T09:45:36+00:00
- source_sha256: `1ccc0b14a9ced1d6bf6a9920f7983b68b0f338317f5bc4a2352fb37a22c7dcbb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T09:45+00:00, close=73607.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T09:00+00:00, close=73699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.189170|-24.61|40.66|-25.19|68382198|1.59|
|AKE_USDT|0.002512|-13.79|-39.55|-14.37|9074459|3.99|
|ONE_USDT|0.001548|-13.71|38.64|-14.29|11538691|0.65|
|ZEC_USDT|977.150000|-10.62|-18.82|-11.20|2193492602|0.10|
|BTW_USDT|1.089100|-9.13|2.85|-9.71|6006314|0.92|
|UNI_USDT|6.347000|-7.07|-13.68|-7.65|41235506|1.57|
|PEPE_USDT|0.000005|-4.91|2.06|-5.49|80448005|0.20|
|DASH_USDT|43.240000|-4.20|-6.28|-4.78|17249227|2.31|
|VVV_USDT|18.885000|-1.84|-15.54|-2.42|5499160|0.53|
|ARB_USDT|0.158580|-1.73|-0.81|-2.31|29516619|0.63|
|QNT_USDT|178.300000|-1.32|-8.76|-1.90|46068713|0.56|
|HBAR_USDT|0.065440|-0.51|-6.55|-1.09|6443785|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002512|0.002501|0.002511|0.95|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158580|0.157810|0.158580|1.65|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.089100|1.094300|1.089100|1.17|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.240000|43.050000|43.240000|0.86|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065440|0.065080|0.065440|1.08|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.189170|0.174240|0.189010|0.74|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001548|0.001553|0.001548|1.09|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.90|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.300000|176.850000|178.300000|1.07|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.347000|6.362000|6.347000|1.30|Y|Y/Y|Y/Y|Y|Y|
|VVV_USDT|18.885000|18.772000|18.885000|0.91|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|977.150000|960.750000|976.840000|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=0.002652, depth_time=2026-11-11T09:45:09+00:00, book20_bid_proxy_usdt=51018, book20_ask_proxy_usdt=56046, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.79%, turnover=9074459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=0.160150, depth_time=2026-11-11T09:45:28+00:00, book20_bid_proxy_usdt=48982, book20_ask_proxy_usdt=88437, funding_indicative=-0.000025, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=29516619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=1.146100, depth_time=2026-11-11T09:45:16+00:00, book20_bid_proxy_usdt=13632, book20_ask_proxy_usdt=22181, funding_indicative=-0.000498, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.13%, turnover=6006314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=44.240000, depth_time=2026-11-11T09:45:22+00:00, book20_bid_proxy_usdt=625594, book20_ask_proxy_usdt=814232, funding_indicative=-0.000106, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=17249227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=0.065780, depth_time=2026-11-11T09:45:32+00:00, book20_bid_proxy_usdt=780133, book20_ask_proxy_usdt=807930, funding_indicative=0.000021, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=6443785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=0.225680, depth_time=2026-11-11T09:45:07+00:00, book20_bid_proxy_usdt=10409, book20_ask_proxy_usdt=8605, funding_indicative=-0.010950, next_funding_utc=2026-11-11T10:00:00+00:00, funding_cycle_h=1, 24h_change=-24.61%, turnover=68382198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=0.001637, depth_time=2026-11-11T09:45:11+00:00, book20_bid_proxy_usdt=26044, book20_ask_proxy_usdt=18331, funding_indicative=-0.001003, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.71%, turnover=11538691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=0.000005, depth_time=2026-11-11T09:45:17+00:00, book20_bid_proxy_usdt=31994, book20_ask_proxy_usdt=21654, funding_indicative=-0.000124, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=80448005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=179.710000, depth_time=2026-11-11T09:45:31+00:00, book20_bid_proxy_usdt=111226, book20_ask_proxy_usdt=94404, funding_indicative=-0.000152, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=46068713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=6.481000, depth_time=2026-11-11T09:45:13+00:00, book20_bid_proxy_usdt=3273487, book20_ask_proxy_usdt=3211157, funding_indicative=-0.000010, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.07%, turnover=41235506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=19.191000, depth_time=2026-11-11T09:45:24+00:00, book20_bid_proxy_usdt=19415, book20_ask_proxy_usdt=35377, funding_indicative=-0.000013, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=5499160. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T09:45:02+00:00, last15m_closed_end=2026-11-11T09:45+00:00, prior8high=1003.100000, depth_time=2026-11-11T09:45:14+00:00, book20_bid_proxy_usdt=284584, book20_ask_proxy_usdt=86468, funding_indicative=0.000016, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.62%, turnover=2193492602. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
