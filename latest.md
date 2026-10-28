# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T15:15:42Z**
- feed_generated_utc: 2026-10-28T15:15:47+00:00
- source_sha256: `99c28617e395dfe25cc32a3747a44752aa3e092a70b4f7e31f7e8e610f7c75ad`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T15:15+00:00, close=80657, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T15:00+00:00, close=80572.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BEAT_USDT|0.079900|-12.28|6.94|-12.42|11596831|3.76|
|AIN_USDT|0.141850|-9.53|249.72|-9.67|11147461|3.52|
|Q_USDT|0.057800|-9.09|-52.91|-9.23|17012611|1.73|
|AKE_USDT|0.019239|-8.92|-38.12|-9.06|6754709|3.64|
|ENA_USDT|0.195210|-8.25|2.80|-8.39|84908427|0.51|
|INJ_USDT|7.780000|-5.02|-9.53|-5.16|24481065|1.28|
|DASH_USDT|53.030000|-2.10|6.18|-2.24|14157228|1.89|
|QNT_USDT|194.230000|-1.84|-0.47|-1.98|67000868|1.54|
|PUMPFUN_USDT|0.004210|-1.75|-6.67|-1.89|13319595|2.38|
|SILVER_USDT|53.760000|-1.61|-7.23|-1.75|249966726|1.86|
|UNI_USDT|7.058000|-1.41|-2.92|-1.55|13952033|1.42|
|ASTER_USDT|0.703000|-1.40|-1.54|-1.54|5631534|1.42|
|ADA_USDT|0.202900|-1.31|-8.35|-1.45|38132038|4.93|
|ZEC_USDT|1276.310000|-1.27|7.15|-1.41|1560609028|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.202900|0.201100|0.202900|1.23|N|Y/Y|N/N|Y|N|
|AIN_USDT|0.141850|0.133450|0.141770|0.72|N|N/Y|N/N|Y|N|
|AKE_USDT|0.019239|0.019128|0.019239|0.96|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.703000|0.701400|0.703200|0.73|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.079900|0.078520|0.079880|0.33|N|Y/Y|Y/N|Y|N|
|DASH_USDT|53.030000|52.690000|53.030000|0.12|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.195210|0.192810|0.195210|0.81|N|Y/Y|Y/N|Y|N|
|INJ_USDT|7.780000|7.748000|7.789000|0.63|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004210|0.004162|0.004210|1.56|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.230000|192.380000|194.230000|0.91|N|Y/Y|N/N|Y|N|
|Q_USDT|0.057800|0.052780|0.057800|1.66|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.760000|53.600000|53.770000|0.51|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.058000|6.969000|7.058000|0.86|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1276.310000|1268.350000|1276.610000|0.94|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.203700, depth_time=2026-10-28T15:15:38+00:00, book20_bid_proxy_usdt=7139180, book20_ask_proxy_usdt=6116586, funding_indicative=-0.000067, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=38132038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AIN_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.151980, depth_time=2026-10-28T15:15:11+00:00, book20_bid_proxy_usdt=8062, book20_ask_proxy_usdt=8283, funding_indicative=0.000460, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.53%, turnover=11147461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.019953, depth_time=2026-10-28T15:15:16+00:00, book20_bid_proxy_usdt=4975, book20_ask_proxy_usdt=5885, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.92%, turnover=6754709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.707400, depth_time=2026-10-28T15:15:35+00:00, book20_bid_proxy_usdt=954460, book20_ask_proxy_usdt=895500, funding_indicative=0.000023, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=5631534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.080810, depth_time=2026-10-28T15:15:09+00:00, book20_bid_proxy_usdt=13131, book20_ask_proxy_usdt=7239, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.28%, turnover=11596831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=53.400000, depth_time=2026-10-28T15:15:21+00:00, book20_bid_proxy_usdt=917274, book20_ask_proxy_usdt=728018, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=14157228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.199970, depth_time=2026-10-28T15:15:19+00:00, book20_bid_proxy_usdt=208663, book20_ask_proxy_usdt=132227, funding_indicative=-0.000041, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.25%, turnover=84908427. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=7.877000, depth_time=2026-10-28T15:15:21+00:00, book20_bid_proxy_usdt=462799, book20_ask_proxy_usdt=243887, funding_indicative=0.000087, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.02%, turnover=24481065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.004262, depth_time=2026-10-28T15:15:28+00:00, book20_bid_proxy_usdt=2116186, book20_ask_proxy_usdt=2200461, funding_indicative=0.000013, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=13319595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=198.160000, depth_time=2026-10-28T15:15:26+00:00, book20_bid_proxy_usdt=175840, book20_ask_proxy_usdt=87673, funding_indicative=-0.000211, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=67000868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=0.058440, depth_time=2026-10-28T15:15:13+00:00, book20_bid_proxy_usdt=15969, book20_ask_proxy_usdt=23942, funding_indicative=-0.000659, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.09%, turnover=17012611. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=54.480000, depth_time=2026-10-28T15:15:30+00:00, book20_bid_proxy_usdt=44468796, book20_ask_proxy_usdt=41419662, funding_indicative=0.000038, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=249966726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=7.068000, depth_time=2026-10-28T15:15:33+00:00, book20_bid_proxy_usdt=3015050, book20_ask_proxy_usdt=2738982, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=13952033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-28T15:15:02+00:00, last15m_closed_end=2026-10-28T15:15+00:00, prior8high=1292.460000, depth_time=2026-10-28T15:15:41+00:00, book20_bid_proxy_usdt=1970906, book20_ask_proxy_usdt=478560, funding_indicative=0.000090, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=1560609028. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
