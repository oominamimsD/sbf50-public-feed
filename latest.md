# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T15:15:21Z**
- feed_generated_utc: 2026-10-25T15:15:24+00:00
- source_sha256: `4de1167abbbe3ce91553526564c55cc6403b0f43899d2b5701bf97b647e95d06`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T15:15+00:00, close=80660.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T15:00+00:00, close=80618, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047180|-30.00|52.43|-31.12|5020824|4.24|
|IRYS_USDT|0.035960|-21.91|181.81|-23.03|24233203|8.35|
|BTW_USDT|1.675200|-3.79|-26.18|-4.91|11833750|1.19|
|STRK_USDT|0.045240|-3.18|-31.60|-4.30|10609136|4.42|
|SUI_USDT|0.917100|-0.85|-6.58|-1.97|62329594|1.09|
|APT_USDT|0.699600|-0.32|-12.27|-1.44|5225234|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.699600|0.689900|0.699600|0.89|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.675200|1.650000|1.674900|0.81|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035960|0.033150|0.035940|0.71|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047180|0.045800|0.047180|1.14|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.045240|0.044430|0.045230|1.14|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.917100|0.907500|0.917100|1.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T15:15:02+00:00, last15m_closed_end=2026-10-25T15:15+00:00, prior8high=0.699900, depth_time=2026-10-25T15:15:20+00:00, book20_bid_proxy_usdt=142044, book20_ask_proxy_usdt=151218, funding_indicative=-0.000095, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.32%, turnover=5225234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T15:15:02+00:00, last15m_closed_end=2026-10-25T15:15+00:00, prior8high=1.701100, depth_time=2026-10-25T15:15:13+00:00, book20_bid_proxy_usdt=8209, book20_ask_proxy_usdt=6039, funding_indicative=-0.009284, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=11833750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T15:15:02+00:00, last15m_closed_end=2026-10-25T15:15+00:00, prior8high=0.040280, depth_time=2026-10-25T15:15:11+00:00, book20_bid_proxy_usdt=100605, book20_ask_proxy_usdt=40588, funding_indicative=-0.000143, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-21.91%, turnover=24233203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T15:15:02+00:00, last15m_closed_end=2026-10-25T15:15+00:00, prior8high=0.048570, depth_time=2026-10-25T15:15:09+00:00, book20_bid_proxy_usdt=69601, book20_ask_proxy_usdt=76482, funding_indicative=-0.001106, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-30.00%, turnover=5020824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T15:15:02+00:00, last15m_closed_end=2026-10-25T15:15+00:00, prior8high=0.045690, depth_time=2026-10-25T15:15:15+00:00, book20_bid_proxy_usdt=950077, book20_ask_proxy_usdt=825975, funding_indicative=0.000017, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=10609136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T15:15:02+00:00, last15m_closed_end=2026-10-25T15:15+00:00, prior8high=0.919500, depth_time=2026-10-25T15:15:18+00:00, book20_bid_proxy_usdt=1874744, book20_ask_proxy_usdt=1098347, funding_indicative=-0.000016, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=62329594. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
