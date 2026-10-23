# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T15:00:35Z**
- feed_generated_utc: 2026-10-23T15:00:38+00:00
- source_sha256: `00ed7220b977780d14b57f2d0d04533efcbce94259ecb5c2423a06c49f59304c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T15:00+00:00, close=81750, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T15:00+00:00, close=81750, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.358500|-7.07|8.64|-7.19|8682742|0.30|
|QNT_USDT|181.440000|-5.94|-12.73|-6.06|57842147|1.10|
|TIA_USDT|0.544900|-5.35|-9.56|-5.47|24784061|1.83|
|STRK_USDT|0.052360|-3.67|-45.66|-3.79|11483632|1.91|
|WLD_USDT|0.532200|-2.72|5.91|-2.84|135989949|1.88|
|ARB_USDT|0.179410|-2.47|-5.54|-2.59|25943474|0.56|
|INJ_USDT|7.877000|-2.17|-1.64|-2.29|25146368|2.54|
|OP_USDT|0.117740|-1.78|-15.21|-1.90|6529132|1.70|
|XAUT_USDT|4004.680000|-1.41|-3.38|-1.53|229664496|0.07|
|XAU_USDT|4009.080000|-1.24|-3.53|-1.36|619711220|0.03|
|HBAR_USDT|0.079320|-1.23|-5.06|-1.35|19450202|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.179410|0.175900|0.179410|2.59|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.079320|0.078580|0.079290|1.61|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.877000|7.747000|7.877000|1.69|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.358500|3.279300|3.355300|1.89|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.117740|0.115530|0.117740|0.83|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.440000|177.480000|181.440000|0.64|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052360|0.051770|0.052340|0.56|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.544900|0.535200|0.544400|1.26|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.532200|0.526800|0.532200|1.16|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4004.680000|3978.250000|4004.680000|2.26|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4009.080000|3985.020000|4009.620000|2.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T15:00:01+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=0.182320, depth_time=2026-10-23T15:00:21+00:00, book20_bid_proxy_usdt=96526, book20_ask_proxy_usdt=54566, funding_indicative=-0.000014, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=25943474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T15:00:01+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=0.080450, depth_time=2026-10-23T15:00:34+00:00, book20_bid_proxy_usdt=836944, book20_ask_proxy_usdt=1015849, funding_indicative=0.000030, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=19450202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-23T15:00:00+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=8.009000, depth_time=2026-10-23T15:00:23+00:00, book20_bid_proxy_usdt=229177, book20_ask_proxy_usdt=309280, funding_indicative=0.000137, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=25146368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T15:00:01+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=3.409500, depth_time=2026-10-23T15:00:08+00:00, book20_bid_proxy_usdt=24969, book20_ask_proxy_usdt=19459, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.07%, turnover=8682742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T15:00:01+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=0.118860, depth_time=2026-10-23T15:00:27+00:00, book20_bid_proxy_usdt=128604, book20_ask_proxy_usdt=74121, funding_indicative=-0.000033, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=6529132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T15:00:00+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=183.630000, depth_time=2026-10-23T15:00:11+00:00, book20_bid_proxy_usdt=57181, book20_ask_proxy_usdt=83738, funding_indicative=-0.000181, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.94%, turnover=57842147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T15:00:01+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=0.053090, depth_time=2026-10-23T15:00:15+00:00, book20_bid_proxy_usdt=770274, book20_ask_proxy_usdt=536551, funding_indicative=-0.000012, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.67%, turnover=11483632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T15:00:01+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=0.552300, depth_time=2026-10-23T15:00:12+00:00, book20_bid_proxy_usdt=278945, book20_ask_proxy_usdt=343896, funding_indicative=-0.000008, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.35%, turnover=24784061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-23T15:00:00+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=0.541700, depth_time=2026-10-23T15:00:18+00:00, book20_bid_proxy_usdt=1905706, book20_ask_proxy_usdt=1323618, funding_indicative=0.000064, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=135989949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T15:00:00+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=4035.760000, depth_time=2026-10-23T15:00:29+00:00, book20_bid_proxy_usdt=87159, book20_ask_proxy_usdt=245701, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=229664496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T15:00:00+00:00, last15m_closed_end=2026-10-23T15:00+00:00, prior8high=4042.750000, depth_time=2026-10-23T15:00:32+00:00, book20_bid_proxy_usdt=2115241, book20_ask_proxy_usdt=2270445, funding_indicative=0.000180, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=619711220. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
