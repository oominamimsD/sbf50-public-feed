# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T04:15:20Z**
- feed_generated_utc: 2026-10-19T04:15:22+00:00
- source_sha256: `41cf986e95e0946ed8f1d0ec14fe1a5cc822f4a11f1aec63b62bf301f4cb9644`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T04:15+00:00, close=82465, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059740|-2.95|-49.91|-4.58|17114378|1.67|
|ICNT_USDT|0.174300|-2.84|64.43|-4.47|7516369|5.73|
|HBAR_USDT|0.084250|-1.78|-10.16|-3.41|50870412|1.19|
|BAT_USDT|0.173070|-1.31|3.85|-2.94|6106383|0.58|
|TIA_USDT|0.613000|-0.79|4.12|-2.42|55903784|1.63|
|BTW_USDT|2.310800|0.23|37.36|-1.40|21675354|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.173070|0.170000|0.173070|2.12|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.310800|2.217800|2.310800|1.83|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084250|0.083740|0.084250|0.36|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.174300|0.163100|0.174300|0.62|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059740|0.060000|0.059740|0.61|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.613000|0.611600|0.613000|0.67|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-19T04:14:59+00:00, last15m_closed_end=2026-10-19T04:15+00:00, prior8high=0.174570, depth_time=2026-10-19T04:15:15+00:00, book20_bid_proxy_usdt=18410, book20_ask_proxy_usdt=30343, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=6106383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T04:14:59+00:00, last15m_closed_end=2026-10-19T04:15+00:00, prior8high=2.325800, depth_time=2026-10-19T04:15:18+00:00, book20_bid_proxy_usdt=12673, book20_ask_proxy_usdt=10610, funding_indicative=-0.000159, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.23%, turnover=21675354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T04:14:59+00:00, last15m_closed_end=2026-10-19T04:15+00:00, prior8high=0.084590, depth_time=2026-10-19T04:15:12+00:00, book20_bid_proxy_usdt=545609, book20_ask_proxy_usdt=1186433, funding_indicative=-0.000033, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=50870412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T04:14:59+00:00, last15m_closed_end=2026-10-19T04:15+00:00, prior8high=0.180700, depth_time=2026-10-19T04:15:10+00:00, book20_bid_proxy_usdt=221310, book20_ask_proxy_usdt=130964, funding_indicative=-0.000092, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=7516369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T04:14:59+00:00, last15m_closed_end=2026-10-19T04:15+00:00, prior8high=0.061960, depth_time=2026-10-19T04:15:07+00:00, book20_bid_proxy_usdt=644798, book20_ask_proxy_usdt=590694, funding_indicative=0.000022, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=17114378. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T04:14:59+00:00, last15m_closed_end=2026-10-19T04:15+00:00, prior8high=0.631600, depth_time=2026-10-19T04:15:16+00:00, book20_bid_proxy_usdt=312274, book20_ask_proxy_usdt=250760, funding_indicative=0.000016, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=55903784. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
