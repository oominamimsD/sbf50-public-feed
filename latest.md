# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T19:15:16Z**
- feed_generated_utc: 2026-10-20T19:15:18+00:00
- source_sha256: `48edb1fe9bd4766db1c5a9c89daeda6cb6003b1f5f52c2e99e6892358c2c2718`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T19:15+00:00, close=82500, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T19:00+00:00, close=82503.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.726300|-6.66|-11.58|-6.57|30644040|4.06|
|AGT_USDT|0.062549|-3.21|286.65|-3.12|7261475|0.32|
|AKE_USDT|0.030651|-1.41|22.27|-1.32|6529904|1.30|
|SEI_USDT|0.060940|-1.11|-2.29|-1.02|6231544|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062549|0.061234|0.062391|0.81|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.030651|0.030663|0.030651|0.33|N|Y/N|N/N|N|N|
|BTW_USDT|1.726300|1.665000|1.727400|0.96|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.060940|0.061020|0.060940|1.00|N|N/N|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T19:15:01+00:00, last15m_closed_end=2026-10-20T19:15+00:00, prior8high=0.063975, depth_time=2026-10-20T19:15:10+00:00, book20_bid_proxy_usdt=13904, book20_ask_proxy_usdt=14423, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=7261475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T19:15:01+00:00, last15m_closed_end=2026-10-20T19:15+00:00, prior8high=0.031326, depth_time=2026-10-20T19:15:08+00:00, book20_bid_proxy_usdt=12174, book20_ask_proxy_usdt=11940, funding_indicative=0.000050, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=6529904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T19:15:01+00:00, last15m_closed_end=2026-10-20T19:15+00:00, prior8high=1.812200, depth_time=2026-10-20T19:15:08+00:00, book20_bid_proxy_usdt=14482, book20_ask_proxy_usdt=7251, funding_indicative=-0.002460, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.66%, turnover=30644040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T19:15:02+00:00, last15m_closed_end=2026-10-20T19:15+00:00, prior8high=0.061880, depth_time=2026-10-20T19:15:15+00:00, book20_bid_proxy_usdt=250181, book20_ask_proxy_usdt=236286, funding_indicative=0.000050, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=6231544. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
