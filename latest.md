# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T06:45:30Z**
- feed_generated_utc: 2026-11-01T06:45:32+00:00
- source_sha256: `d9da2da27c268a00a6b81767dc126717f5b9e93cd27c88d356928eaf896170f9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T06:45+00:00, close=77876.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T06:00+00:00, close=77875.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.237500|-19.80|41.43|-20.20|31065372|2.10|
|AKE_USDT|0.009472|-14.95|-67.59|-15.35|11706000|5.27|
|XPL_USDT|0.073080|-10.12|1.20|-10.52|5568921|2.73|
|BLESS_USDT|0.009552|-9.57|17.73|-9.97|6458782|5.23|
|Q_USDT|0.029660|-7.54|-62.42|-7.94|5013508|6.74|
|ENA_USDT|0.187610|-3.29|0.43|-3.69|44717518|0.53|
|ZEC_USDT|1245.120000|-3.06|8.72|-3.46|957898875|0.08|
|NEAR_USDT|4.373000|-2.30|-0.65|-2.70|54108533|2.29|
|XLM_USDT|0.168940|-1.63|0.31|-2.03|20617304|0.59|
|BEAT_USDT|0.097460|-1.09|45.44|-1.49|6057974|1.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009472|0.009122|0.009472|1.08|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097460|0.096700|0.097460|1.05|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009552|0.009421|0.009552|1.82|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187610|0.186890|0.187600|1.33|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.237500|0.231890|0.237180|1.24|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.373000|4.363000|4.373000|2.06|N|Y/Y|N/N|Y|N|
|Q_USDT|0.029660|0.028170|0.029670|1.36|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168940|0.168140|0.168950|0.69|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.073080|0.069100|0.073040|3.59|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1245.120000|1243.250000|1245.200000|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T06:45:03+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.010385, depth_time=2026-11-01T06:45:10+00:00, book20_bid_proxy_usdt=5324, book20_ask_proxy_usdt=17804, funding_indicative=-0.001919, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.95%, turnover=11706000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T06:45:03+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.098640, depth_time=2026-11-01T06:45:29+00:00, book20_bid_proxy_usdt=19566, book20_ask_proxy_usdt=12816, funding_indicative=0.000196, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=6057974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T06:45:03+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.009785, depth_time=2026-11-01T06:45:14+00:00, book20_bid_proxy_usdt=17203, book20_ask_proxy_usdt=17021, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.57%, turnover=6458782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T06:45:02+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.190760, depth_time=2026-11-01T06:45:20+00:00, book20_bid_proxy_usdt=153409, book20_ask_proxy_usdt=150265, funding_indicative=-0.000016, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=44717518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T06:45:02+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.247730, depth_time=2026-11-01T06:45:08+00:00, book20_bid_proxy_usdt=10686, book20_ask_proxy_usdt=9505, funding_indicative=-0.002491, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.80%, turnover=31065372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T06:45:02+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=4.417000, depth_time=2026-11-01T06:45:25+00:00, book20_bid_proxy_usdt=5011886, book20_ask_proxy_usdt=3203451, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=54108533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T06:45:02+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.031360, depth_time=2026-11-01T06:45:17+00:00, book20_bid_proxy_usdt=48525, book20_ask_proxy_usdt=41706, funding_indicative=-0.000710, next_funding_utc=2026-11-01T07:00:00+00:00, funding_cycle_h=1, 24h_change=-7.54%, turnover=5013508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T06:45:03+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.169690, depth_time=2026-11-01T06:45:27+00:00, book20_bid_proxy_usdt=199193, book20_ask_proxy_usdt=214532, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=20617304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T06:45:03+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=0.086070, depth_time=2026-11-01T06:45:12+00:00, book20_bid_proxy_usdt=387967, book20_ask_proxy_usdt=302911, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.12%, turnover=5568921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T06:45:03+00:00, last15m_closed_end=2026-11-01T06:45+00:00, prior8high=1254.820000, depth_time=2026-11-01T06:45:22+00:00, book20_bid_proxy_usdt=130981, book20_ask_proxy_usdt=995595, funding_indicative=-0.000125, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=957898875. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
