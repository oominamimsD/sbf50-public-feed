# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T12:00:21Z**
- feed_generated_utc: 2026-10-26T12:00:23+00:00
- source_sha256: `6bdc43fe7ad1caa9eda1e5ac5cdf34cd6dff71f4956f1851dbe50699cf0635c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.071680|-32.09|7.78|-31.82|7065096|4.18|
|IRYS_USDT|0.028500|-19.08|133.60|-18.81|12022624|7.02|
|XMR_USDT|590.820000|-2.87|1.42|-2.60|5673098|0.85|
|WLD_USDT|0.440100|-2.67|-7.60|-2.40|60128268|2.27|
|STRK_USDT|0.044700|-2.27|-27.38|-2.00|9020411|2.24|
|LIT_USDT|3.100600|-2.13|5.80|-1.86|5347853|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CAP_USDT|0.071680|0.073440|0.071680|1.11|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.028500|0.027970|0.028500|0.97|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.100600|3.066900|3.100600|2.02|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044700|0.044530|0.044740|1.62|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.440100|0.435800|0.440100|0.49|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.820000|588.790000|590.820000|1.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CAP_USDT: quote_utc=2026-10-26T12:00:00+00:00, last15m_closed_end=2026-10-26T12:00+00:00, prior8high=0.085830, depth_time=2026-10-26T12:00:08+00:00, book20_bid_proxy_usdt=50417, book20_ask_proxy_usdt=53292, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.09%, turnover=7065096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T12:00:00+00:00, last15m_closed_end=2026-10-26T12:00+00:00, prior8high=0.029760, depth_time=2026-10-26T12:00:10+00:00, book20_bid_proxy_usdt=77922, book20_ask_proxy_usdt=53810, funding_indicative=-0.000338, next_funding_utc=2026-10-26T13:00:00+00:00, funding_cycle_h=1, 24h_change=-19.08%, turnover=12022624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T12:00:01+00:00, last15m_closed_end=2026-10-26T12:00+00:00, prior8high=3.116600, depth_time=2026-10-26T12:00:19+00:00, book20_bid_proxy_usdt=16290, book20_ask_proxy_usdt=16813, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=5347853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T12:00:01+00:00, last15m_closed_end=2026-10-26T12:00+00:00, prior8high=0.045830, depth_time=2026-10-26T12:00:18+00:00, book20_bid_proxy_usdt=955627, book20_ask_proxy_usdt=863157, funding_indicative=-0.000046, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=9020411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T12:00:00+00:00, last15m_closed_end=2026-10-26T12:00+00:00, prior8high=0.442900, depth_time=2026-10-26T12:00:15+00:00, book20_bid_proxy_usdt=3050158, book20_ask_proxy_usdt=2828325, funding_indicative=-0.000142, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=60128268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T12:00:01+00:00, last15m_closed_end=2026-10-26T12:00+00:00, prior8high=591.000000, depth_time=2026-10-26T12:00:11+00:00, book20_bid_proxy_usdt=32452, book20_ask_proxy_usdt=32767, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=5673098. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
