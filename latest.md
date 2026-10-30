# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T23:45:24Z**
- feed_generated_utc: 2026-10-30T23:45:26+00:00
- source_sha256: `f9f893b478196aac8ff90a789fc8d4c329d5d445b13d3c44a5de059c109d1053`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T23:45+00:00, close=77315.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T23:00+00:00, close=76917, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013925|-26.40|-60.21|-26.06|5656144|5.73|
|EVAA_USDT|1.145300|-10.66|118.19|-10.32|6704060|0.87|
|BTW_USDT|1.149500|-4.16|-32.47|-3.82|10270259|0.87|
|HYPE_USDT|90.168000|-2.35|15.00|-2.01|146256744|0.11|
|XMR_USDT|590.010000|-1.91|-2.79|-1.57|10550810|0.17|
|BLESS_USDT|0.009677|-1.76|18.57|-1.42|12753621|3.10|
|TRX_USDT|0.330510|-1.48|0.35|-1.14|10848845|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013925|0.013039|0.013925|1.59|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009677|0.009411|0.009677|0.18|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.149500|1.135400|1.149500|0.33|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.145300|1.083700|1.145300|0.58|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|90.168000|89.002000|90.168000|0.84|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.330510|0.328370|0.330510|1.15|N|Y/Y|Y/N|Y|N|
|XMR_USDT|590.010000|588.670000|590.010000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=0.014277, depth_time=2026-10-30T23:45:08+00:00, book20_bid_proxy_usdt=3964, book20_ask_proxy_usdt=5182, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-26.40%, turnover=5656144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=0.010060, depth_time=2026-10-30T23:45:20+00:00, book20_bid_proxy_usdt=14968, book20_ask_proxy_usdt=9562, funding_indicative=0.000103, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=12753621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=1.174900, depth_time=2026-10-30T23:45:11+00:00, book20_bid_proxy_usdt=16649, book20_ask_proxy_usdt=27154, funding_indicative=-0.000231, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=10270259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=1.147800, depth_time=2026-10-30T23:45:10+00:00, book20_bid_proxy_usdt=12763, book20_ask_proxy_usdt=3945, funding_indicative=0.000203, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.66%, turnover=6704060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=90.120000, depth_time=2026-10-30T23:45:15+00:00, book20_bid_proxy_usdt=126738, book20_ask_proxy_usdt=138714, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=146256744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=0.331360, depth_time=2026-10-30T23:45:21+00:00, book20_bid_proxy_usdt=89223, book20_ask_proxy_usdt=93247, funding_indicative=-0.000426, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=10848845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-30T23:45:00+00:00, last15m_closed_end=2026-10-30T23:45+00:00, prior8high=595.630000, depth_time=2026-10-30T23:45:15+00:00, book20_bid_proxy_usdt=15089, book20_ask_proxy_usdt=6787, funding_indicative=0.000409, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=10550810. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
