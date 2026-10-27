# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T23:15:19Z**
- feed_generated_utc: 2026-10-27T23:15:22+00:00
- source_sha256: `c7c087fe854026d16291bd08f8810518d3a9f697a2a60661446aae7313009a07`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T23:15+00:00, close=80895.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T23:00+00:00, close=80874.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053559|-15.76|-56.36|-16.21|44658120|0.19|
|INJ_USDT|7.935000|-3.13|-7.73|-3.58|23469915|1.26|
|ARB_USDT|0.166420|-1.23|-11.92|-1.68|14902409|0.60|
|NIL_USDT|0.091600|-1.17|3.08|-1.62|5593224|5.46|
|SYN_USDT|0.179400|-1.10|-2.28|-1.55|5797275|5.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166420|0.165630|0.166420|1.84|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.935000|7.913000|7.935000|1.77|N|Y/N|N/N|N|N|
|NIL_USDT|0.091600|0.091090|0.091670|0.46|N|Y/Y|N/N|N|N|
|Q_USDT|0.053559|0.052810|0.053566|0.88|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.179400|0.178700|0.179500|0.96|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-27T23:15:01+00:00, last15m_closed_end=2026-10-27T23:15+00:00, prior8high=0.169030, depth_time=2026-10-27T23:15:13+00:00, book20_bid_proxy_usdt=121273, book20_ask_proxy_usdt=87722, funding_indicative=-0.000019, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=14902409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T23:15:01+00:00, last15m_closed_end=2026-10-27T23:15+00:00, prior8high=8.171000, depth_time=2026-10-27T23:15:12+00:00, book20_bid_proxy_usdt=298595, book20_ask_proxy_usdt=349857, funding_indicative=0.000218, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=23469915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-27T23:15:01+00:00, last15m_closed_end=2026-10-27T23:15+00:00, prior8high=0.093680, depth_time=2026-10-27T23:15:14+00:00, book20_bid_proxy_usdt=12695, book20_ask_proxy_usdt=2682, funding_indicative=-0.000436, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=5593224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T23:15:01+00:00, last15m_closed_end=2026-10-27T23:15+00:00, prior8high=0.055980, depth_time=2026-10-27T23:15:09+00:00, book20_bid_proxy_usdt=4908, book20_ask_proxy_usdt=3361, funding_indicative=-0.000044, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.76%, turnover=44658120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-27T23:15:01+00:00, last15m_closed_end=2026-10-27T23:15+00:00, prior8high=0.183400, depth_time=2026-10-27T23:15:18+00:00, book20_bid_proxy_usdt=98407, book20_ask_proxy_usdt=99024, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=5797275. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
