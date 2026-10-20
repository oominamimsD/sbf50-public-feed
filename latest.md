# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T03:00:13Z**
- feed_generated_utc: 2026-10-20T03:00:15+00:00
- source_sha256: `a396c3090fbb56021e08f1bd8cdbaa36942db5abf508387446a9172b9bc29aa2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T03:00+00:00, close=81763.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T03:00+00:00, close=81763.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|SAND_USDT|0.058400|-1.94|-5.94|-1.76|9004998|1.71|
|AVAX_USDT|9.561000|-1.31|-10.48|-1.13|125464274|1.05|
|NEAR_USDT|4.840000|-1.30|-12.77|-1.12|165691224|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|9.561000|9.423000|9.561000|1.07|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.840000|4.785000|4.836000|1.28|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058400|0.057130|0.058400|3.92|N|Y/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-20T03:00:00+00:00, last15m_closed_end=2026-10-20T03:00+00:00, prior8high=9.568000, depth_time=2026-10-20T03:00:10+00:00, book20_bid_proxy_usdt=1108604, book20_ask_proxy_usdt=928288, funding_indicative=0.000013, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=125464274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T03:00:00+00:00, last15m_closed_end=2026-10-20T03:00+00:00, prior8high=4.885000, depth_time=2026-10-20T03:00:12+00:00, book20_bid_proxy_usdt=4203939, book20_ask_proxy_usdt=2592558, funding_indicative=0.000066, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=165691224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T03:00:00+00:00, last15m_closed_end=2026-10-20T03:00+00:00, prior8high=0.058560, depth_time=2026-10-20T03:00:06+00:00, book20_bid_proxy_usdt=801873, book20_ask_proxy_usdt=867919, funding_indicative=-0.002167, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=9004998. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
