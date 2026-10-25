# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T15:00:25Z**
- feed_generated_utc: 2026-10-25T15:00:28+00:00
- source_sha256: `9414aea901af184c5d45bde3384e6f92fd32adb9c95226a2405dac7762246dca`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T15:00+00:00, close=80618, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T15:00+00:00, close=80618, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035220|-38.12|176.01|-39.19|24112142|2.84|
|STRK_USDT|0.045230|-4.39|-31.62|-5.46|10447365|2.21|
|BTW_USDT|1.669900|-3.95|-26.41|-5.02|11738326|1.80|
|PENGU_USDT|0.007429|-1.60|-0.32|-2.67|5374571|1.35|
|SUI_USDT|0.913800|-1.21|-6.92|-2.28|61661714|1.09|
|APT_USDT|0.699000|-1.07|-12.35|-2.14|5199570|1.43|
|SEI_USDT|0.052840|-0.07|-14.78|-1.14|5114766|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.699000|0.689900|0.699000|1.06|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.669900|1.657000|1.670000|1.41|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035220|0.033150|0.035220|1.63|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007429|0.007340|0.007429|1.14|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052840|0.052220|0.052830|1.37|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045230|0.044430|0.045230|2.93|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.913800|0.907500|0.914000|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T15:00:01+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=0.698000, depth_time=2026-10-25T15:00:22+00:00, book20_bid_proxy_usdt=168084, book20_ask_proxy_usdt=174267, funding_indicative=-0.000100, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=5199570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T15:00:00+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=1.701100, depth_time=2026-10-25T15:00:14+00:00, book20_bid_proxy_usdt=8659, book20_ask_proxy_usdt=8503, funding_indicative=-0.008838, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.95%, turnover=11738326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T15:00:00+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=0.040280, depth_time=2026-10-25T15:00:09+00:00, book20_bid_proxy_usdt=52812, book20_ask_proxy_usdt=34841, funding_indicative=-0.000096, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-38.12%, turnover=24112142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T15:00:01+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=0.007403, depth_time=2026-10-25T15:00:16+00:00, book20_bid_proxy_usdt=241469, book20_ask_proxy_usdt=212851, funding_indicative=-0.000043, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=5374571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T15:00:01+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=0.052590, depth_time=2026-10-25T15:00:24+00:00, book20_bid_proxy_usdt=213268, book20_ask_proxy_usdt=314862, funding_indicative=0.000008, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.07%, turnover=5114766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T15:00:01+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=0.045750, depth_time=2026-10-25T15:00:12+00:00, book20_bid_proxy_usdt=693429, book20_ask_proxy_usdt=833582, funding_indicative=0.000018, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.39%, turnover=10447365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T15:00:00+00:00, last15m_closed_end=2026-10-25T15:00+00:00, prior8high=0.919500, depth_time=2026-10-25T15:00:19+00:00, book20_bid_proxy_usdt=1014691, book20_ask_proxy_usdt=2283940, funding_indicative=-0.000028, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=61661714. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
