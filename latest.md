# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T14:00:22Z**
- feed_generated_utc: 2026-10-20T14:00:24+00:00
- source_sha256: `a5608ecb8d4c1128097e4f4622ad0a0f8756127e7c34b46f47b3e94fb952efcc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T14:00+00:00, close=82114, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T14:00+00:00, close=82114, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.066094|-22.56|296.67|-22.80|8355215|2.57|
|BTW_USDT|1.662300|-13.10|-5.32|-13.34|35016783|4.80|
|NEAR_USDT|4.753000|-3.07|-14.34|-3.31|161595847|2.10|
|ARB_USDT|0.192110|-2.81|1.93|-3.05|96903919|0.52|
|SAND_USDT|0.057680|-2.46|-7.10|-2.70|5051215|1.73|
|AKE_USDT|0.030173|-1.92|28.17|-2.16|6477655|0.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066094|0.065000|0.066098|1.57|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030173|0.029930|0.030176|0.22|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192110|0.187280|0.192110|3.08|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.662300|1.677600|1.662700|0.28|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.753000|4.641000|4.751000|1.57|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057680|0.056510|0.057710|0.36|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T14:00:00+00:00, last15m_closed_end=2026-10-20T14:00+00:00, prior8high=0.069163, depth_time=2026-10-20T14:00:08+00:00, book20_bid_proxy_usdt=3711, book20_ask_proxy_usdt=7188, funding_indicative=0.000056, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.56%, turnover=8355215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T14:00:00+00:00, last15m_closed_end=2026-10-20T14:00+00:00, prior8high=0.030788, depth_time=2026-10-20T14:00:21+00:00, book20_bid_proxy_usdt=10439, book20_ask_proxy_usdt=14493, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=6477655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T14:00:00+00:00, last15m_closed_end=2026-10-20T14:00+00:00, prior8high=0.190060, depth_time=2026-10-20T14:00:16+00:00, book20_bid_proxy_usdt=58575, book20_ask_proxy_usdt=82042, funding_indicative=0.000033, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=96903919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T14:00:00+00:00, last15m_closed_end=2026-10-20T14:00+00:00, prior8high=1.839100, depth_time=2026-10-20T14:00:10+00:00, book20_bid_proxy_usdt=12333, book20_ask_proxy_usdt=13351, funding_indicative=-0.002959, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.10%, turnover=35016783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T14:00:00+00:00, last15m_closed_end=2026-10-20T14:00+00:00, prior8high=4.728000, depth_time=2026-10-20T14:00:14+00:00, book20_bid_proxy_usdt=487725, book20_ask_proxy_usdt=1872226, funding_indicative=-0.000038, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=161595847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T14:00:01+00:00, last15m_closed_end=2026-10-20T14:00+00:00, prior8high=0.057480, depth_time=2026-10-20T14:00:18+00:00, book20_bid_proxy_usdt=716761, book20_ask_proxy_usdt=743270, funding_indicative=-0.001782, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=5051215. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
