# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T18:45:21Z**
- feed_generated_utc: 2026-10-13T18:45:23+00:00
- source_sha256: `9449e9bf73f195cce37148ca7f758f9776c305de68fd534fab830544599b2ff2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T18:45+00:00, close=83057.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T18:00+00:00, close=83063.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.016030|-4.60|10.46|-4.20|10824738|8.10|
|CT_USDT|0.357710|-3.77|-3.73|-3.37|5903402|0.56|
|RLC_USDT|0.892000|-3.37|8.80|-2.97|5930170|1.12|
|DOS_USDT|0.208100|-3.34|-3.43|-2.94|9521638|4.80|
|STRK_USDT|0.084940|-2.28|62.75|-1.88|47223716|2.35|
|STX_USDT|0.412800|-1.97|9.99|-1.57|18732425|2.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.357710|0.361440|0.357710|0.52|N|N/N|N/N|N|N|
|DOS_USDT|0.208100|0.208400|0.208100|0.92|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.892000|0.874600|0.892000|0.75|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084940|0.082420|0.084880|1.06|N|Y/Y|Y/Y|N|N|
|STX_USDT|0.412800|0.411800|0.412800|0.56|N|Y/N|N/N|N|N|
|W_USDT|0.016030|0.016093|0.016030|1.84|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T18:45:00+00:00, last15m_closed_end=2026-10-13T18:45+00:00, prior8high=0.383340, depth_time=2026-10-13T18:45:10+00:00, book20_bid_proxy_usdt=10348, book20_ask_proxy_usdt=8271, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=5903402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T18:45:00+00:00, last15m_closed_end=2026-10-13T18:45+00:00, prior8high=0.218600, depth_time=2026-10-13T18:45:14+00:00, book20_bid_proxy_usdt=119336, book20_ask_proxy_usdt=116385, funding_indicative=-0.000060, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=9521638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T18:45:00+00:00, last15m_closed_end=2026-10-13T18:45+00:00, prior8high=0.926400, depth_time=2026-10-13T18:45:13+00:00, book20_bid_proxy_usdt=54286, book20_ask_proxy_usdt=45917, funding_indicative=-0.000630, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=5930170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T18:45:00+00:00, last15m_closed_end=2026-10-13T18:45+00:00, prior8high=0.086100, depth_time=2026-10-13T18:45:17+00:00, book20_bid_proxy_usdt=195244, book20_ask_proxy_usdt=220992, funding_indicative=0.000035, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=47223716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STX_USDT: quote_utc=2026-10-13T18:45:00+00:00, last15m_closed_end=2026-10-13T18:45+00:00, prior8high=0.437700, depth_time=2026-10-13T18:45:20+00:00, book20_bid_proxy_usdt=236627, book20_ask_proxy_usdt=190785, funding_indicative=-0.000190, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=18732425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T18:45:00+00:00, last15m_closed_end=2026-10-13T18:45+00:00, prior8high=0.017236, depth_time=2026-10-13T18:45:08+00:00, book20_bid_proxy_usdt=35122, book20_ask_proxy_usdt=36264, funding_indicative=-0.000340, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.60%, turnover=10824738. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
