# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T04:30:18Z**
- feed_generated_utc: 2026-10-19T04:30:19+00:00
- source_sha256: `8fb50e43d7dbdc392e4b88ec1e80c47976b01efc911c6532700764edf352d86f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T04:30+00:00, close=82465.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059540|-3.28|-50.07|-4.91|17191876|1.68|
|HBAR_USDT|0.083880|-2.21|-10.55|-3.84|50917996|1.19|
|BAT_USDT|0.172600|-1.58|3.57|-3.21|6117945|0.58|
|TIA_USDT|0.608600|-1.50|3.38|-3.13|56484379|3.29|
|BTW_USDT|2.304800|-0.02|37.01|-1.65|21830826|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.172600|0.170000|0.172600|0.57|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.304800|2.217800|2.304800|1.15|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.083880|0.083740|0.083880|0.26|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.059540|0.059710|0.059540|0.62|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.608600|0.611600|0.608600|1.26|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-19T04:29:59+00:00, last15m_closed_end=2026-10-19T04:30+00:00, prior8high=0.173900, depth_time=2026-10-19T04:30:12+00:00, book20_bid_proxy_usdt=17943, book20_ask_proxy_usdt=23462, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=6117945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T04:29:59+00:00, last15m_closed_end=2026-10-19T04:30+00:00, prior8high=2.320700, depth_time=2026-10-19T04:30:17+00:00, book20_bid_proxy_usdt=10620, book20_ask_proxy_usdt=10632, funding_indicative=-0.000118, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.02%, turnover=21830826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T04:29:59+00:00, last15m_closed_end=2026-10-19T04:30+00:00, prior8high=0.084590, depth_time=2026-10-19T04:30:09+00:00, book20_bid_proxy_usdt=601170, book20_ask_proxy_usdt=986338, funding_indicative=-0.000038, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=50917996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T04:29:59+00:00, last15m_closed_end=2026-10-19T04:30+00:00, prior8high=0.061460, depth_time=2026-10-19T04:30:08+00:00, book20_bid_proxy_usdt=725003, book20_ask_proxy_usdt=698598, funding_indicative=0.000029, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=17191876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T04:29:59+00:00, last15m_closed_end=2026-10-19T04:30+00:00, prior8high=0.630300, depth_time=2026-10-19T04:30:15+00:00, book20_bid_proxy_usdt=285961, book20_ask_proxy_usdt=332752, funding_indicative=0.000024, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=56484379. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
