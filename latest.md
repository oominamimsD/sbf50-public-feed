# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T04:45:33Z**
- feed_generated_utc: 2026-11-04T04:45:35+00:00
- source_sha256: `e851bf6f812cb83c99ea198c14adfb641bcf3fa0da60738cade8483e7708ff29`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T04:45+00:00, close=76958.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.036910|-31.40|-22.32|-30.50|12003960|5.41|
|AKE_USDT|0.003354|-19.29|-84.12|-18.39|12360624|2.99|
|ICNT_USDT|0.211300|-9.50|19.17|-8.60|5192068|4.72|
|TRUMPOFFICIAL_USDT|1.509000|-6.15|-10.60|-5.25|8231584|6.62|
|HYPE_USDT|83.501000|-4.40|5.08|-3.50|75393846|0.12|
|XPL_USDT|0.061520|-3.95|-16.66|-3.05|7461673|1.62|
|XLM_USDT|0.160010|-2.90|-5.43|-2.00|37758124|0.62|
|LINK_USDT|10.859000|-2.64|-5.16|-1.74|197144294|0.92|
|DASH_USDT|45.020000|-2.42|-16.89|-1.52|14346223|2.22|
|HBAR_USDT|0.068550|-2.11|-9.94|-1.21|6798757|1.46|
|LTC_USDT|53.270000|-1.95|-5.94|-1.05|5001593|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.036910|0.036920|0.036700|1.69|Y|Y/Y|N/N|Y|N|
|AKE_USDT|0.003354|0.003340|0.003370|1.48|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.020000|44.030000|44.990000|0.59|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.068550|0.067550|0.068550|0.86|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|83.501000|80.647000|83.466000|0.56|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.211300|0.210900|0.211400|0.93|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.859000|10.623000|10.861000|0.98|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|53.270000|52.090000|53.260000|0.17|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.509000|1.475000|1.509000|0.24|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.160010|0.156990|0.160040|0.87|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061520|0.060070|0.061520|1.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T04:45:02+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=0.039240, depth_time=2026-11-04T04:45:08+00:00, book20_bid_proxy_usdt=27997, book20_ask_proxy_usdt=37996, funding_indicative=0.000047, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.40%, turnover=12003960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T04:45:02+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=0.003794, depth_time=2026-11-04T04:45:11+00:00, book20_bid_proxy_usdt=47667, book20_ask_proxy_usdt=36666, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.29%, turnover=12360624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-04T04:45:03+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=45.270000, depth_time=2026-11-04T04:45:26+00:00, book20_bid_proxy_usdt=332640, book20_ask_proxy_usdt=529928, funding_indicative=0.000022, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=14346223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-04T04:45:03+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=0.068790, depth_time=2026-11-04T04:45:30+00:00, book20_bid_proxy_usdt=1257017, book20_ask_proxy_usdt=1177592, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=6798757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T04:45:02+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=83.613000, depth_time=2026-11-04T04:45:18+00:00, book20_bid_proxy_usdt=245565, book20_ask_proxy_usdt=85224, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.40%, turnover=75393846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-11-04T04:45:02+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=0.220500, depth_time=2026-11-04T04:45:12+00:00, book20_bid_proxy_usdt=127850, book20_ask_proxy_usdt=124593, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.50%, turnover=5192068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T04:45:02+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=10.898000, depth_time=2026-11-04T04:45:25+00:00, book20_bid_proxy_usdt=360770, book20_ask_proxy_usdt=506820, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=197144294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-11-04T04:45:03+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=53.470000, depth_time=2026-11-04T04:45:32+00:00, book20_bid_proxy_usdt=1080851, book20_ask_proxy_usdt=1517564, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=5001593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T04:45:03+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=1.518000, depth_time=2026-11-04T04:45:15+00:00, book20_bid_proxy_usdt=2420118, book20_ask_proxy_usdt=2025770, funding_indicative=-0.000211, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.15%, turnover=8231584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T04:45:03+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=0.160540, depth_time=2026-11-04T04:45:22+00:00, book20_bid_proxy_usdt=158599, book20_ask_proxy_usdt=153266, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=37758124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T04:45:03+00:00, last15m_closed_end=2026-11-04T04:45+00:00, prior8high=0.061950, depth_time=2026-11-04T04:45:20+00:00, book20_bid_proxy_usdt=403736, book20_ask_proxy_usdt=453514, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.95%, turnover=7461673. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
