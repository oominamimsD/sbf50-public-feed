# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T05:45:18Z**
- feed_generated_utc: 2026-10-14T05:45:20+00:00
- source_sha256: `199b6592c09b6bf59025e3bd73d35db2ab1844b8275133deeae6ba086819de78`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T05:45+00:00, close=83505, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T05:00+00:00, close=83704.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.081200|-6.59|55.58|-6.72|30445479|1.23|
|MAGIC_USDT|0.112720|-4.99|65.47|-5.12|5549298|1.77|
|W_USDT|0.016051|-4.47|10.60|-4.60|7092778|3.74|
|UNI_USDT|7.323000|-3.28|-15.48|-3.41|19920230|1.36|
|TIA_USDT|0.568900|-1.45|19.44|-1.58|46071509|3.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.112720|0.113190|0.112720|1.74|Y|Y/Y|Y/N|N|N|
|STRK_USDT|0.081200|0.081770|0.081160|6.71|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.568900|0.566800|0.568900|2.24|N|N/Y|N/N|N|N|
|UNI_USDT|7.323000|7.397000|7.323000|3.02|Y|Y/Y|Y/N|N|N|
|W_USDT|0.016051|0.016080|0.016051|2.40|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T05:45:00+00:00, last15m_closed_end=2026-10-14T05:45+00:00, prior8high=0.116420, depth_time=2026-10-14T05:45:10+00:00, book20_bid_proxy_usdt=167585, book20_ask_proxy_usdt=183303, funding_indicative=-0.000109, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=5549298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T05:45:00+00:00, last15m_closed_end=2026-10-14T05:45+00:00, prior8high=0.085530, depth_time=2026-10-14T05:45:07+00:00, book20_bid_proxy_usdt=225401, book20_ask_proxy_usdt=380849, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.59%, turnover=30445479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T05:45:00+00:00, last15m_closed_end=2026-10-14T05:45+00:00, prior8high=0.581500, depth_time=2026-10-14T05:45:17+00:00, book20_bid_proxy_usdt=148179, book20_ask_proxy_usdt=218633, funding_indicative=-0.000014, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=46071509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T05:45:00+00:00, last15m_closed_end=2026-10-14T05:45+00:00, prior8high=7.542000, depth_time=2026-10-14T05:45:15+00:00, book20_bid_proxy_usdt=1668253, book20_ask_proxy_usdt=1914857, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=19920230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T05:45:00+00:00, last15m_closed_end=2026-10-14T05:45+00:00, prior8high=0.016644, depth_time=2026-10-14T05:45:12+00:00, book20_bid_proxy_usdt=22856, book20_ask_proxy_usdt=32909, funding_indicative=-0.000134, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.47%, turnover=7092778. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
