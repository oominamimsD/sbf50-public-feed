# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T23:30:20Z**
- feed_generated_utc: 2026-10-20T23:30:22+00:00
- source_sha256: `70e3af0b0999cf410e7ee6c4840cf3d200030ff0726793e03fa422d5fef85983`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T23:30+00:00, close=82874.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T23:00+00:00, close=83059.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.057000|-11.80|252.35|-12.15|7079234|4.21|
|BAT_USDT|0.194600|-9.81|9.70|-10.16|10033854|1.03|
|XMR_USDT|601.750000|-2.97|13.98|-3.32|14617567|0.17|
|DOT_USDT|1.144600|-1.12|-1.06|-1.47|12837167|0.87|
|ARB_USDT|0.187240|-0.90|1.40|-1.25|84302397|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.057000|0.056252|0.057000|0.80|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.187240|0.187140|0.187240|0.82|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.194600|0.193360|0.194600|0.36|N|Y/Y|N/N|N|N|
|DOT_USDT|1.144600|1.145700|1.144600|1.50|Y|Y/N|N/N|N|N|
|XMR_USDT|601.750000|598.000000|601.740000|29.07|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T23:30:00+00:00, last15m_closed_end=2026-10-20T23:30+00:00, prior8high=0.059058, depth_time=2026-10-20T23:30:09+00:00, book20_bid_proxy_usdt=10013, book20_ask_proxy_usdt=15627, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.80%, turnover=7079234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T23:30:00+00:00, last15m_closed_end=2026-10-20T23:30+00:00, prior8high=0.191850, depth_time=2026-10-20T23:30:19+00:00, book20_bid_proxy_usdt=99847, book20_ask_proxy_usdt=82211, funding_indicative=-0.000080, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=84302397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T23:30:00+00:00, last15m_closed_end=2026-10-20T23:30+00:00, prior8high=0.200820, depth_time=2026-10-20T23:30:11+00:00, book20_bid_proxy_usdt=16639, book20_ask_proxy_usdt=33623, funding_indicative=0.000035, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.81%, turnover=10033854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-20T23:30:01+00:00, last15m_closed_end=2026-10-20T23:30+00:00, prior8high=1.168800, depth_time=2026-10-20T23:30:16+00:00, book20_bid_proxy_usdt=356994, book20_ask_proxy_usdt=343135, funding_indicative=0.000033, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=12837167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-20T23:30:01+00:00, last15m_closed_end=2026-10-20T23:30+00:00, prior8high=624.900000, depth_time=2026-10-20T23:30:14+00:00, book20_bid_proxy_usdt=6801, book20_ask_proxy_usdt=20056, funding_indicative=0.000100, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=14617567. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
