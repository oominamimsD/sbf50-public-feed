# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T07:15:18Z**
- feed_generated_utc: 2026-10-28T07:15:21+00:00
- source_sha256: `47a64209acac9f1f574a3b8af839f5b53f79756285583790d4a1110cbcf05bcf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T07:15+00:00, close=80888.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T07:00+00:00, close=80839.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055800|-12.24|-54.54|-12.68|31617924|7.18|
|NIL_USDT|0.085000|-8.29|-4.34|-8.73|6075835|5.88|
|INJ_USDT|7.931000|-3.18|-7.77|-3.62|24329608|1.26|
|AKE_USDT|0.020662|-2.19|-33.54|-2.63|5771661|3.39|
|TIA_USDT|0.530100|-1.11|-14.87|-1.55|12869753|3.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020662|0.020734|0.020662|1.68|Y|Y/Y|Y/Y|N|Y|
|INJ_USDT|7.931000|7.931000|7.931000|0.55|N|Y/Y|N/N|N|N|
|NIL_USDT|0.085000|0.081520|0.084860|0.79|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.055800|0.047660|0.055940|1.30|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.530100|0.531100|0.530100|3.24|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T07:15:01+00:00, last15m_closed_end=2026-10-28T07:15+00:00, prior8high=0.022041, depth_time=2026-10-28T07:15:14+00:00, book20_bid_proxy_usdt=7482, book20_ask_proxy_usdt=5296, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=5771661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T07:15:01+00:00, last15m_closed_end=2026-10-28T07:15+00:00, prior8high=8.002000, depth_time=2026-10-28T07:15:12+00:00, book20_bid_proxy_usdt=308941, book20_ask_proxy_usdt=234640, funding_indicative=0.000201, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=24329608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T07:15:01+00:00, last15m_closed_end=2026-10-28T07:15+00:00, prior8high=0.085350, depth_time=2026-10-28T07:15:09+00:00, book20_bid_proxy_usdt=10436, book20_ask_proxy_usdt=2475, funding_indicative=-0.000582, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.29%, turnover=6075835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T07:15:01+00:00, last15m_closed_end=2026-10-28T07:15+00:00, prior8high=0.074627, depth_time=2026-10-28T07:15:08+00:00, book20_bid_proxy_usdt=25053, book20_ask_proxy_usdt=24651, funding_indicative=-0.001090, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.24%, turnover=31617924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T07:15:01+00:00, last15m_closed_end=2026-10-28T07:15+00:00, prior8high=0.536700, depth_time=2026-10-28T07:15:17+00:00, book20_bid_proxy_usdt=246569, book20_ask_proxy_usdt=283597, funding_indicative=-0.000027, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=12869753. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
