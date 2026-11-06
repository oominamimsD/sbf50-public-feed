# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T22:45:15Z**
- feed_generated_utc: 2026-11-06T22:45:16+00:00
- source_sha256: `f059ef4bf302a8385aab94c4de2db1ab0686d7b06632718b3fcf6b899afb89f8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T22:45+00:00, close=76018.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T22:00+00:00, close=75895.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.140900|-25.84|-46.95|-26.08|33644695|7.11|
|ANTHROPIC_USDT|1342.220000|-6.21|-19.93|-6.45|7117708|1.79|
|PUMPFUN_USDT|0.003957|-2.17|-3.65|-2.41|12798551|2.53|
|LIT_USDT|3.337300|-1.62|18.16|-1.86|9972986|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1342.220000|1309.270000|1342.280000|1.04|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.337300|3.283100|3.337300|0.11|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003957|0.003935|0.003957|0.28|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.140900|0.125500|0.140900|0.46|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T22:45:02+00:00, last15m_closed_end=2026-11-06T22:45+00:00, prior8high=1364.960000, depth_time=2026-11-06T22:45:08+00:00, book20_bid_proxy_usdt=12343, book20_ask_proxy_usdt=20321, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.21%, turnover=7117708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T22:45:02+00:00, last15m_closed_end=2026-11-06T22:45+00:00, prior8high=3.375500, depth_time=2026-11-06T22:45:12+00:00, book20_bid_proxy_usdt=29895, book20_ask_proxy_usdt=26258, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=9972986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T22:45:02+00:00, last15m_closed_end=2026-11-06T22:45+00:00, prior8high=0.004011, depth_time=2026-11-06T22:45:11+00:00, book20_bid_proxy_usdt=2176908, book20_ask_proxy_usdt=2193565, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=12798551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T22:45:02+00:00, last15m_closed_end=2026-11-06T22:45+00:00, prior8high=0.149300, depth_time=2026-11-06T22:45:06+00:00, book20_bid_proxy_usdt=131945, book20_ask_proxy_usdt=135552, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-25.84%, turnover=33644695. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
