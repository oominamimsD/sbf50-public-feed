# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T06:00:37Z**
- feed_generated_utc: 2026-10-31T06:00:40+00:00
- source_sha256: `a69e41253add28d143cb0f8a23fcf2a073efa0091fe87e7cbb14d0a76ed08db7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T06:00+00:00, close=77232.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T06:00+00:00, close=77232.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011807|-37.59|-66.26|-37.15|6692969|3.39|
|Q_USDT|0.030080|-36.64|-74.58|-36.20|19478269|3.32|
|BLESS_USDT|0.010464|-22.51|28.21|-22.07|12995437|4.78|
|BEAT_USDT|0.097060|-7.69|33.70|-7.25|8426869|1.03|
|EVAA_USDT|1.200900|-6.89|128.78|-6.45|6080479|5.00|
|HYPE_USDT|88.388000|-4.69|12.73|-4.25|106335692|0.11|
|PEPE_USDT|0.000005|-4.09|-0.16|-3.65|130530469|0.62|
|BTW_USDT|1.157700|-3.48|-31.99|-3.04|9399511|3.46|
|TRX_USDT|0.325130|-3.35|-1.27|-2.91|6606975|0.31|
|FET_USDT|0.162600|-2.40|-13.18|-1.96|6437632|6.15|
|DASH_USDT|48.000000|-2.12|-10.86|-1.68|14688655|2.08|
|WLD_USDT|0.396200|-1.80|-25.58|-1.36|48281582|2.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011807|0.010838|0.011833|1.19|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097060|0.096950|0.097100|0.26|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.010464|0.010095|0.010464|0.33|N|Y/N|Y/Y|Y|N|
|BTW_USDT|1.157700|1.108600|1.154600|1.02|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.000000|47.930000|47.940000|3.87|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.200900|1.141300|1.200900|0.93|N|N/N|N/N|Y|N|
|FET_USDT|0.162600|0.162200|0.162500|0.68|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.388000|88.393000|88.388000|1.35|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.42|N|Y/Y|N/N|Y|N|
|Q_USDT|0.030080|0.027250|0.030020|0.54|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.325130|0.322650|0.325130|0.05|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396200|0.392600|0.396200|0.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.011774, depth_time=2026-10-31T06:00:08+00:00, book20_bid_proxy_usdt=9182, book20_ask_proxy_usdt=4471, funding_indicative=-0.000042, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-37.59%, turnover=6692969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.100320, depth_time=2026-10-31T06:00:14+00:00, book20_bid_proxy_usdt=13314, book20_ask_proxy_usdt=9656, funding_indicative=0.000119, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.69%, turnover=8426869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.010813, depth_time=2026-10-31T06:00:14+00:00, book20_bid_proxy_usdt=13859, book20_ask_proxy_usdt=23626, funding_indicative=0.000117, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.51%, turnover=12995437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=1.210000, depth_time=2026-10-31T06:00:25+00:00, book20_bid_proxy_usdt=18888, book20_ask_proxy_usdt=9689, funding_indicative=-0.000419, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=9399511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=48.470000, depth_time=2026-10-31T06:00:33+00:00, book20_bid_proxy_usdt=865611, book20_ask_proxy_usdt=555622, funding_indicative=0.000042, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=14688655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=1.249300, depth_time=2026-10-31T06:00:19+00:00, book20_bid_proxy_usdt=3856, book20_ask_proxy_usdt=6658, funding_indicative=0.000219, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.89%, turnover=6080479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.164600, depth_time=2026-10-31T06:00:29+00:00, book20_bid_proxy_usdt=1159331, book20_ask_proxy_usdt=817246, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=6437632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=89.538000, depth_time=2026-10-31T06:00:21+00:00, book20_bid_proxy_usdt=119784, book20_ask_proxy_usdt=60589, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.69%, turnover=106335692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.000005, depth_time=2026-10-31T06:00:24+00:00, book20_bid_proxy_usdt=26970, book20_ask_proxy_usdt=27323, funding_indicative=-0.000061, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=130530469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.033110, depth_time=2026-10-31T06:00:11+00:00, book20_bid_proxy_usdt=45813, book20_ask_proxy_usdt=46923, funding_indicative=-0.000965, next_funding_utc=2026-10-31T07:00:00+00:00, funding_cycle_h=1, 24h_change=-36.64%, turnover=19478269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.327310, depth_time=2026-10-31T06:00:28+00:00, book20_bid_proxy_usdt=67548, book20_ask_proxy_usdt=31180, funding_indicative=-0.001017, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=6606975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T06:00:03+00:00, last15m_closed_end=2026-10-31T06:00+00:00, prior8high=0.401100, depth_time=2026-10-31T06:00:34+00:00, book20_bid_proxy_usdt=2670471, book20_ask_proxy_usdt=3206144, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=48281582. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
