# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T17:00:15Z**
- feed_generated_utc: 2026-11-07T17:00:16+00:00
- source_sha256: `a46ce6f1638599c115c0e81117bb5a40152a452ee7a1810718d4a61df14185bf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T17:00+00:00, close=75712.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T17:00+00:00, close=75712.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.003620|-3.26|-13.43|-3.25|15853743|2.76|
|NEAR_USDT|3.641000|-1.67|-18.65|-1.66|24878265|2.75|
|ENA_USDT|0.157790|-1.53|-18.66|-1.52|27477371|0.63|
|PEPE_USDT|0.000005|-1.18|-2.27|-1.17|53405306|0.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.157790|0.157380|0.157790|0.92|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.641000|3.643000|3.641000|1.49|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000005|0.000005|0.000005|1.18|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003620|0.003563|0.003620|1.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-07T17:00:00+00:00, last15m_closed_end=2026-11-07T17:00+00:00, prior8high=0.161510, depth_time=2026-11-07T17:00:10+00:00, book20_bid_proxy_usdt=143609, book20_ask_proxy_usdt=263551, funding_indicative=0.000050, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=27477371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-07T17:00:00+00:00, last15m_closed_end=2026-11-07T17:00+00:00, prior8high=3.723000, depth_time=2026-11-07T17:00:10+00:00, book20_bid_proxy_usdt=4121927, book20_ask_proxy_usdt=2931396, funding_indicative=0.000036, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=24878265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T17:00:00+00:00, last15m_closed_end=2026-11-07T17:00+00:00, prior8high=0.000005, depth_time=2026-11-07T17:00:14+00:00, book20_bid_proxy_usdt=26318, book20_ask_proxy_usdt=48366, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=53405306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T17:00:00+00:00, last15m_closed_end=2026-11-07T17:00+00:00, prior8high=0.003791, depth_time=2026-11-07T17:00:04+00:00, book20_bid_proxy_usdt=2005379, book20_ask_proxy_usdt=2545731, funding_indicative=-0.000019, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=15853743. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
