# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T23:00:14Z**
- feed_generated_utc: 2026-11-04T23:00:15+00:00
- source_sha256: `1a3c81acd5173b3f02d8a19152eb2550ab1be8a08c000e826150854068c6b32a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T23:00+00:00, close=80682, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T23:00+00:00, close=80682, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002551|-20.00|-87.30|-20.51|16425377|3.92|
|TRUMPOFFICIAL_USDT|1.274000|-10.65|-25.45|-11.16|26463277|7.86|
|IDOL_USDT|0.021515|-2.84|148.52|-3.35|6231921|4.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002551|0.002479|0.002551|0.97|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021515|0.020994|0.021515|0.74|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.274000|1.257000|1.274000|0.50|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T23:00:01+00:00, last15m_closed_end=2026-11-04T23:00+00:00, prior8high=0.002701, depth_time=2026-11-04T23:00:08+00:00, book20_bid_proxy_usdt=98560, book20_ask_proxy_usdt=47331, funding_indicative=-0.000889, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-20.00%, turnover=16425377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T23:00:00+00:00, last15m_closed_end=2026-11-04T23:00+00:00, prior8high=0.021759, depth_time=2026-11-04T23:00:13+00:00, book20_bid_proxy_usdt=12505, book20_ask_proxy_usdt=4125, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=6231921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T23:00:01+00:00, last15m_closed_end=2026-11-04T23:00+00:00, prior8high=1.294000, depth_time=2026-11-04T23:00:11+00:00, book20_bid_proxy_usdt=819753, book20_ask_proxy_usdt=1008554, funding_indicative=-0.000203, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.65%, turnover=26463277. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
