# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T07:00:44Z**
- feed_generated_utc: 2026-10-30T07:00:48+00:00
- source_sha256: `8b5c857802780ae7762e0496060fae471e67fde9e636b81ce1afb541b97829ba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T07:00+00:00, close=78619.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T07:00+00:00, close=78619.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.275800|-17.91|-24.91|-14.11|8237566|3.62|
|TIA_USDT|0.460500|-16.15|-18.98|-12.35|18334632|4.34|
|PYTH_USDT|0.062200|-15.01|-16.14|-11.21|5255979|3.21|
|LDO_USDT|0.329600|-11.54|-13.83|-7.74|6485282|3.03|
|BTW_USDT|1.499500|-11.52|-16.22|-7.72|10843134|3.33|
|APT_USDT|0.624300|-11.23|-19.15|-7.43|12431188|1.60|
|FET_USDT|0.164500|-10.25|-11.22|-6.45|13991986|6.08|
|FARTCOIN_USDT|0.118140|-9.72|-17.29|-5.92|15188125|2.54|
|SEI_USDT|0.048510|-9.22|-16.46|-5.42|7241699|2.06|
|ETHFI_USDT|0.611300|-9.00|-7.70|-5.20|5833138|1.64|
|TRUMPOFFICIAL_USDT|1.555000|-8.79|-10.83|-4.99|11034357|6.43|
|PENGU_USDT|0.007214|-8.30|-6.65|-4.50|9918834|1.39|
|INJ_USDT|7.352000|-8.16|-7.31|-4.36|31019964|1.36|
|SHIB_USDT|0.000005|-5.04|-5.63|-1.24|7646324|2.12|
|BEAT_USDT|0.098160|-4.96|46.00|-1.16|27556971|1.02|
|ETH_USDT|2252.910000|-4.86|-6.03|-1.06|2467118246|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.624300|0.617100|0.624400|1.30|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098160|0.096560|0.098160|0.21|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.499500|1.445000|1.499000|1.14|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.275800|0.267600|0.275700|1.71|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.611300|0.596800|0.611300|3.02|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118140|0.117800|0.118140|1.20|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.164500|0.161100|0.164500|0.99|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.352000|7.311000|7.352000|2.22|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.329600|0.322600|0.329600|1.18|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007214|0.007118|0.007214|1.13|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.062200|0.060400|0.062230|0.71|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048510|0.047950|0.048480|1.50|N|Y/Y|Y/Y|Y|N|
|SHIB_USDT|0.000005|0.000005|0.000005|0.50|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.460500|0.453800|0.460300|1.12|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.555000|1.545000|1.555000|0.41|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.629600, depth_time=2026-10-30T07:00:21+00:00, book20_bid_proxy_usdt=107651, book20_ask_proxy_usdt=106363, funding_indicative=-0.000046, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.23%, turnover=12431188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-30T07:00:01+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.101880, depth_time=2026-10-30T07:00:43+00:00, book20_bid_proxy_usdt=9680, book20_ask_proxy_usdt=9309, funding_indicative=0.000252, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.96%, turnover=27556971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=1.528200, depth_time=2026-10-30T07:00:19+00:00, book20_bid_proxy_usdt=16200, book20_ask_proxy_usdt=15621, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.52%, turnover=10843134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.276100, depth_time=2026-10-30T07:00:07+00:00, book20_bid_proxy_usdt=509839, book20_ask_proxy_usdt=449100, funding_indicative=-0.000163, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-17.91%, turnover=8237566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.614200, depth_time=2026-10-30T07:00:26+00:00, book20_bid_proxy_usdt=233819, book20_ask_proxy_usdt=108182, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.00%, turnover=5833138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.120530, depth_time=2026-10-30T07:00:26+00:00, book20_bid_proxy_usdt=42056, book20_ask_proxy_usdt=40631, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.72%, turnover=15188125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.166100, depth_time=2026-10-30T07:00:23+00:00, book20_bid_proxy_usdt=1080879, book20_ask_proxy_usdt=670791, funding_indicative=-0.000176, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.25%, turnover=13991986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T07:00:01+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=7.440000, depth_time=2026-10-30T07:00:38+00:00, book20_bid_proxy_usdt=207804, book20_ask_proxy_usdt=173524, funding_indicative=-0.000025, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.16%, turnover=31019964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.332300, depth_time=2026-10-30T07:00:17+00:00, book20_bid_proxy_usdt=289484, book20_ask_proxy_usdt=296965, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.54%, turnover=6485282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.007269, depth_time=2026-10-30T07:00:36+00:00, book20_bid_proxy_usdt=74198, book20_ask_proxy_usdt=114323, funding_indicative=-0.000022, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.30%, turnover=9918834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.062440, depth_time=2026-10-30T07:00:13+00:00, book20_bid_proxy_usdt=120768, book20_ask_proxy_usdt=183146, funding_indicative=-0.000229, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.01%, turnover=5255979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.048860, depth_time=2026-10-30T07:00:28+00:00, book20_bid_proxy_usdt=170662, book20_ask_proxy_usdt=176456, funding_indicative=-0.000063, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.22%, turnover=7241699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SHIB_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.000005, depth_time=2026-10-30T07:00:40+00:00, book20_bid_proxy_usdt=157043, book20_ask_proxy_usdt=164955, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.04%, turnover=7646324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=0.465200, depth_time=2026-10-30T07:00:11+00:00, book20_bid_proxy_usdt=250713, book20_ask_proxy_usdt=300170, funding_indicative=0.000007, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.15%, turnover=18334632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T07:00:02+00:00, last15m_closed_end=2026-10-30T07:00+00:00, prior8high=1.573000, depth_time=2026-10-30T07:00:33+00:00, book20_bid_proxy_usdt=1570584, book20_ask_proxy_usdt=1258762, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.79%, turnover=11034357. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
