# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T00:00:22Z**
- feed_generated_utc: 2026-10-21T00:00:24+00:00
- source_sha256: `ac9ab6d85f6144cd6d68ee7573fb743070257b9831f0d42ff3c5f3ca8edc8e21`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.194500|-10.94|9.65|-10.64|10018078|0.52|
|ARB_USDT|0.187510|-4.59|1.54|-4.29|83132228|0.53|
|PHA_USDT|0.057990|-3.71|5.37|-3.41|10818904|1.72|
|XMR_USDT|598.270000|-3.58|13.32|-3.28|14976074|0.33|
|QNT_USDT|194.880000|-3.21|-4.69|-2.91|70985309|0.51|
|TIA_USDT|0.624200|-2.60|8.12|-2.30|45022458|1.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.187510|0.186350|0.187510|1.17|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.194500|0.193360|0.194500|0.16|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057990|0.057740|0.057990|1.05|N|Y/Y|N/N|N|N|
|QNT_USDT|194.880000|194.050000|194.880000|0.80|N|Y/N|Y/Y|N|N|
|TIA_USDT|0.624200|0.616700|0.624200|0.21|N|Y/Y|Y/Y|N|N|
|XMR_USDT|598.270000|588.100000|598.270000|4.08|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-21T00:00:01+00:00, last15m_closed_end=2026-10-21T00:00+00:00, prior8high=0.190710, depth_time=2026-10-21T00:00:10+00:00, book20_bid_proxy_usdt=108859, book20_ask_proxy_usdt=52845, funding_indicative=-0.000079, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=83132228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T00:00:01+00:00, last15m_closed_end=2026-10-21T00:00+00:00, prior8high=0.197100, depth_time=2026-10-21T00:00:08+00:00, book20_bid_proxy_usdt=21170, book20_ask_proxy_usdt=19620, funding_indicative=0.000060, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.94%, turnover=10018078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T00:00:01+00:00, last15m_closed_end=2026-10-21T00:00+00:00, prior8high=0.059700, depth_time=2026-10-21T00:00:13+00:00, book20_bid_proxy_usdt=84191, book20_ask_proxy_usdt=98087, funding_indicative=-0.000049, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=10818904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-21T00:00:01+00:00, last15m_closed_end=2026-10-21T00:00+00:00, prior8high=197.210000, depth_time=2026-10-21T00:00:18+00:00, book20_bid_proxy_usdt=104078, book20_ask_proxy_usdt=70468, funding_indicative=-0.000006, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=70985309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T00:00:01+00:00, last15m_closed_end=2026-10-21T00:00+00:00, prior8high=0.629700, depth_time=2026-10-21T00:00:21+00:00, book20_bid_proxy_usdt=166756, book20_ask_proxy_usdt=209440, funding_indicative=-0.000087, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=45022458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T00:00:01+00:00, last15m_closed_end=2026-10-21T00:00+00:00, prior8high=624.900000, depth_time=2026-10-21T00:00:16+00:00, book20_bid_proxy_usdt=11067, book20_ask_proxy_usdt=20858, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=14976074. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
