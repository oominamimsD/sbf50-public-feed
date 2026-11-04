# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T00:45:43Z**
- feed_generated_utc: 2026-11-04T00:45:46+00:00
- source_sha256: `fe5b9c3891ad92584d671582af24c8b8544d0c7c281387e9ab32bf21842f423e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T00:45+00:00, close=76895.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003898|-6.20|-81.54|-5.22|13652035|7.71|
|STRK_USDT|0.041810|-5.25|-9.34|-4.27|5357086|2.39|
|HYPE_USDT|83.384000|-4.54|4.94|-3.56|67494604|0.12|
|TRUMPOFFICIAL_USDT|1.543000|-4.04|-8.59|-3.06|6173359|6.48|
|XPL_USDT|0.061700|-3.66|-16.41|-2.68|7365931|1.62|
|XLM_USDT|0.159890|-2.97|-5.50|-1.99|34862020|0.62|
|QNT_USDT|189.710000|-2.92|-4.13|-1.94|61019154|0.53|
|ARB_USDT|0.155390|-2.80|-7.78|-1.82|17813767|0.64|
|OP_USDT|0.107410|-2.73|-3.51|-1.75|9092830|0.93|
|LINK_USDT|10.870000|-2.54|-5.07|-1.56|163226807|0.92|
|AAVE_USDT|125.370000|-2.39|-5.50|-1.41|21220230|0.80|
|FARTCOIN_USDT|0.116540|-2.36|-10.54|-1.38|11216075|0.86|
|TAO_USDT|222.390000|-2.25|-11.46|-1.27|32869925|1.35|
|TIA_USDT|0.426700|-2.08|-20.40|-1.10|12914482|2.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.370000|125.730000|125.370000|10.02|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.003898|0.003829|0.003898|0.43|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155390|0.155320|0.155390|2.07|N|N/N|Y/Y|Y|N|
|FARTCOIN_USDT|0.116540|0.116480|0.116540|1.01|N|N/N|Y/Y|Y|N|
|HYPE_USDT|83.384000|83.580000|83.365000|4.21|Y|Y/N|Y/Y|Y|N|
|LINK_USDT|10.870000|10.878000|10.864000|2.94|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.107410|0.107600|0.107370|1.54|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|189.710000|189.930000|189.710000|2.74|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.041810|0.041840|0.041810|2.18|Y|Y/N|Y/N|Y|N|
|TAO_USDT|222.390000|221.920000|222.390000|3.11|N|Y/N|Y/Y|Y|N|
|TIA_USDT|0.426700|0.424000|0.426800|1.70|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.543000|1.535000|1.543000|3.30|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.159890|0.158870|0.159970|1.88|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061700|0.061340|0.061720|1.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=128.110000, depth_time=2026-11-04T00:45:35+00:00, book20_bid_proxy_usdt=232246, book20_ask_proxy_usdt=358201, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=21220230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T00:45:03+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.004047, depth_time=2026-11-04T00:45:08+00:00, book20_bid_proxy_usdt=33770, book20_ask_proxy_usdt=41241, funding_indicative=-0.000827, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.20%, turnover=13652035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.159660, depth_time=2026-11-04T00:45:27+00:00, book20_bid_proxy_usdt=80064, book20_ask_proxy_usdt=89985, funding_indicative=0.000026, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=17813767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.120280, depth_time=2026-11-04T00:45:37+00:00, book20_bid_proxy_usdt=63338, book20_ask_proxy_usdt=104730, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=11216075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T00:45:03+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=85.946000, depth_time=2026-11-04T00:45:14+00:00, book20_bid_proxy_usdt=183466, book20_ask_proxy_usdt=60897, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.54%, turnover=67494604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=11.152000, depth_time=2026-11-04T00:45:31+00:00, book20_bid_proxy_usdt=333711, book20_ask_proxy_usdt=519729, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=163226807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.110510, depth_time=2026-11-04T00:45:29+00:00, book20_bid_proxy_usdt=76777, book20_ask_proxy_usdt=115152, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=9092830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=193.440000, depth_time=2026-11-04T00:45:24+00:00, book20_bid_proxy_usdt=64424, book20_ask_proxy_usdt=76194, funding_indicative=-0.000001, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=61019154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.042850, depth_time=2026-11-04T00:45:11+00:00, book20_bid_proxy_usdt=219978, book20_ask_proxy_usdt=362201, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.25%, turnover=5357086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=227.970000, depth_time=2026-11-04T00:45:40+00:00, book20_bid_proxy_usdt=348908, book20_ask_proxy_usdt=251502, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=32869925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.439200, depth_time=2026-11-04T00:45:42+00:00, book20_bid_proxy_usdt=214091, book20_ask_proxy_usdt=369661, funding_indicative=-0.000015, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=12914482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=1.602000, depth_time=2026-11-04T00:45:16+00:00, book20_bid_proxy_usdt=1917772, book20_ask_proxy_usdt=1944780, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=6173359. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.163410, depth_time=2026-11-04T00:45:22+00:00, book20_bid_proxy_usdt=140323, book20_ask_proxy_usdt=150529, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=34862020. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T00:45:04+00:00, last15m_closed_end=2026-11-04T00:45+00:00, prior8high=0.064100, depth_time=2026-11-04T00:45:19+00:00, book20_bid_proxy_usdt=329694, book20_ask_proxy_usdt=423259, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=7365931. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
