# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T23:30:21Z**
- feed_generated_utc: 2026-10-30T23:30:22+00:00
- source_sha256: `7fb5090b39aa9dfa187506498ea868fe3f94f12313674084a4af4ba49b75c98b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T23:30+00:00, close=77135.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T23:00+00:00, close=76917, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.014078|-25.59|-59.77|-25.02|5482220|2.13|
|EVAA_USDT|1.140000|-11.08|117.18|-10.51|6687251|2.63|
|BTW_USDT|1.149900|-4.13|-32.45|-3.56|10240712|1.74|
|HYPE_USDT|89.757000|-2.80|14.48|-2.23|145759083|0.11|
|BLESS_USDT|0.009614|-2.40|17.80|-1.83|12736382|3.12|
|XMR_USDT|590.390000|-1.85|-2.73|-1.28|10520693|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.014078|0.013039|0.014072|1.60|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009614|0.009363|0.009611|0.88|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.149900|1.135400|1.150300|0.31|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.140000|1.083700|1.138600|0.84|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.757000|89.002000|89.757000|0.62|N|Y/Y|N/N|Y|N|
|XMR_USDT|590.390000|588.720000|590.390000|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T23:30:02+00:00, last15m_closed_end=2026-10-30T23:30+00:00, prior8high=0.013633, depth_time=2026-10-30T23:30:07+00:00, book20_bid_proxy_usdt=6375, book20_ask_proxy_usdt=3608, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-25.59%, turnover=5482220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-30T23:30:01+00:00, last15m_closed_end=2026-10-30T23:30+00:00, prior8high=0.010060, depth_time=2026-10-30T23:30:17+00:00, book20_bid_proxy_usdt=11801, book20_ask_proxy_usdt=12362, funding_indicative=0.000068, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=12736382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T23:30:02+00:00, last15m_closed_end=2026-10-30T23:30+00:00, prior8high=1.190100, depth_time=2026-10-30T23:30:13+00:00, book20_bid_proxy_usdt=16572, book20_ask_proxy_usdt=18905, funding_indicative=-0.000224, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.13%, turnover=10240712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T23:30:01+00:00, last15m_closed_end=2026-10-30T23:30+00:00, prior8high=1.138600, depth_time=2026-10-30T23:30:09+00:00, book20_bid_proxy_usdt=7519, book20_ask_proxy_usdt=8720, funding_indicative=0.000209, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.08%, turnover=6687251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T23:30:01+00:00, last15m_closed_end=2026-10-30T23:30+00:00, prior8high=90.344000, depth_time=2026-10-30T23:30:15+00:00, book20_bid_proxy_usdt=91501, book20_ask_proxy_usdt=135539, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.80%, turnover=145759083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-30T23:30:02+00:00, last15m_closed_end=2026-10-30T23:30+00:00, prior8high=596.540000, depth_time=2026-10-30T23:30:20+00:00, book20_bid_proxy_usdt=23563, book20_ask_proxy_usdt=8144, funding_indicative=0.000377, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=10520693. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
