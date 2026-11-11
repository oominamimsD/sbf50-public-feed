# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T06:00:21Z**
- feed_generated_utc: 2026-11-11T06:00:23+00:00
- source_sha256: `8d5c004c1f4485625246a3d277b300efecfed88eaefc6809e8631005359153a4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T06:00+00:00, close=73895.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T06:00+00:00, close=73895.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1017.630000|-6.92|-15.46|-7.89|2126725747|0.10|
|UNI_USDT|6.665000|-5.66|-9.35|-6.63|36238241|1.50|
|VVV_USDT|19.186000|-3.18|-14.19|-4.15|5298487|0.52|
|DOT_USDT|0.844100|-2.13|-10.44|-3.10|7958890|1.19|
|HBAR_USDT|0.065790|-1.68|-6.05|-2.65|5659942|1.52|
|SOL_USDT|83.350000|-1.13|-11.06|-2.10|602740593|1.20|
|QNT_USDT|180.450000|-0.13|-7.66|-1.10|45279414|1.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.844100|0.841400|0.844100|0.83|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065790|0.065430|0.065790|1.12|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|180.450000|179.480000|180.450000|0.72|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|83.350000|82.600000|83.350000|2.00|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.665000|6.629000|6.665000|1.36|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.186000|19.006000|19.186000|0.93|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1017.630000|1002.510000|1016.960000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=0.849100, depth_time=2026-11-11T06:00:13+00:00, book20_bid_proxy_usdt=600999, book20_ask_proxy_usdt=534176, funding_indicative=0.000043, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=7958890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=0.066120, depth_time=2026-11-11T06:00:15+00:00, book20_bid_proxy_usdt=689667, book20_ask_proxy_usdt=816405, funding_indicative=-0.000008, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=5659942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=181.590000, depth_time=2026-11-11T06:00:20+00:00, book20_bid_proxy_usdt=73313, book20_ask_proxy_usdt=52958, funding_indicative=-0.000090, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.13%, turnover=45279414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=83.430000, depth_time=2026-11-11T06:00:18+00:00, book20_bid_proxy_usdt=18337137, book20_ask_proxy_usdt=14560081, funding_indicative=0.000086, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=602740593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=6.722000, depth_time=2026-11-11T06:00:09+00:00, book20_bid_proxy_usdt=2996011, book20_ask_proxy_usdt=3525613, funding_indicative=0.000028, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.66%, turnover=36238241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=19.417000, depth_time=2026-11-11T06:00:09+00:00, book20_bid_proxy_usdt=41345, book20_ask_proxy_usdt=19869, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=5298487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T06:00:01+00:00, last15m_closed_end=2026-11-11T06:00+00:00, prior8high=1035.400000, depth_time=2026-11-11T06:00:06+00:00, book20_bid_proxy_usdt=254858, book20_ask_proxy_usdt=198028, funding_indicative=0.000090, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.92%, turnover=2126725747. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
