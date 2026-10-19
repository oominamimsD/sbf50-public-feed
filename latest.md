# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T08:45:21Z**
- feed_generated_utc: 2026-10-19T08:45:23+00:00
- source_sha256: `75fb62550fb56e543bb7cacc853f5bec34931d9a79d5187fcb676f76dcc77389`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T08:45+00:00, close=82852.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059510|-3.33|-50.10|-5.44|18064008|3.36|
|ICNT_USDT|0.173900|-3.06|64.05|-5.17|6845988|5.75|
|TIA_USDT|0.610700|-1.16|3.73|-3.27|57833578|3.27|
|BTW_USDT|2.290900|-0.62|36.18|-2.73|21638061|1.31|
|SAND_USDT|0.059200|0.74|-10.89|-1.37|22150108|1.69|
|Q_USDT|0.122983|0.82|334.23|-1.29|15385391|0.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.290900|2.206900|2.290900|0.46|N|Y/Y|N/N|N|N|
|ICNT_USDT|0.173900|0.167000|0.173900|0.87|N|Y/Y|Y/N|N|N|
|Q_USDT|0.122983|0.115540|0.122970|0.46|N|Y/N|N/N|N|N|
|SAND_USDT|0.059200|0.058430|0.059210|0.40|N|N/N|N/N|N|N|
|STRK_USDT|0.059510|0.059240|0.059510|1.42|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.610700|0.606000|0.610700|1.05|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T08:45:00+00:00, last15m_closed_end=2026-10-19T08:45+00:00, prior8high=2.321000, depth_time=2026-10-19T08:45:15+00:00, book20_bid_proxy_usdt=8874, book20_ask_proxy_usdt=13208, funding_indicative=-0.000377, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.62%, turnover=21638061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T08:45:00+00:00, last15m_closed_end=2026-10-19T08:45+00:00, prior8high=0.174800, depth_time=2026-10-19T08:45:07+00:00, book20_bid_proxy_usdt=120131, book20_ask_proxy_usdt=95900, funding_indicative=-0.000229, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=6845988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T08:45:00+00:00, last15m_closed_end=2026-10-19T08:45+00:00, prior8high=0.167385, depth_time=2026-10-19T08:45:21+00:00, book20_bid_proxy_usdt=18556, book20_ask_proxy_usdt=20067, funding_indicative=-0.000968, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=0.82%, turnover=15385391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T08:45:01+00:00, last15m_closed_end=2026-10-19T08:45+00:00, prior8high=0.061520, depth_time=2026-10-19T08:45:15+00:00, book20_bid_proxy_usdt=538877, book20_ask_proxy_usdt=373317, funding_indicative=-0.005988, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.74%, turnover=22150108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T08:45:01+00:00, last15m_closed_end=2026-10-19T08:45+00:00, prior8high=0.060350, depth_time=2026-10-19T08:45:07+00:00, book20_bid_proxy_usdt=807967, book20_ask_proxy_usdt=573261, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=18064008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T08:45:00+00:00, last15m_closed_end=2026-10-19T08:45+00:00, prior8high=0.620500, depth_time=2026-10-19T08:45:12+00:00, book20_bid_proxy_usdt=752504, book20_ask_proxy_usdt=224131, funding_indicative=-0.000039, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=57833578. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
