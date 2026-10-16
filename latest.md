# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T00:00:15Z**
- feed_generated_utc: 2026-10-16T00:00:17+00:00
- source_sha256: `e430b48d1d37a63be9211af3a157a62b225f6acb4954ad268527279e6cdb9d0a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1827.100000|-6.56|-9.68|-6.35|7058375|1.37|
|WAL_USDT|0.050610|-5.04|52.02|-4.83|7454119|1.98|
|BTW_USDT|1.814400|-4.87|30.69|-4.66|23282003|3.86|
|NIL_USDT|0.085200|-1.93|-1.60|-1.72|12880679|2.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1827.100000|1790.150000|1827.100000|1.08|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.814400|1.805400|1.814700|1.04|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.085200|0.083300|0.085200|0.46|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050610|0.050140|0.050610|0.55|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-10-15T23:59:59+00:00, last15m_closed_end=2026-10-16T00:00+00:00, prior8high=1899.570000, depth_time=2026-10-16T00:00:07+00:00, book20_bid_proxy_usdt=10003, book20_ask_proxy_usdt=9136, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.56%, turnover=7058375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-15T23:59:59+00:00, last15m_closed_end=2026-10-16T00:00+00:00, prior8high=1.942300, depth_time=2026-10-16T00:00:12+00:00, book20_bid_proxy_usdt=8179, book20_ask_proxy_usdt=21657, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=23282003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T23:59:59+00:00, last15m_closed_end=2026-10-16T00:00+00:00, prior8high=0.085180, depth_time=2026-10-16T00:00:15+00:00, book20_bid_proxy_usdt=35346, book20_ask_proxy_usdt=23038, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=12880679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T23:59:59+00:00, last15m_closed_end=2026-10-16T00:00+00:00, prior8high=0.051590, depth_time=2026-10-16T00:00:09+00:00, book20_bid_proxy_usdt=179540, book20_ask_proxy_usdt=101450, funding_indicative=-0.000412, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=7454119. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
