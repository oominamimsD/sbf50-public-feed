# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T22:00:19Z**
- feed_generated_utc: 2026-11-03T22:00:21+00:00
- source_sha256: `d453230f855939fffc9511760bfdee36920d9dcd3194fbb4217619aca5b90405`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T22:00+00:00, close=77870.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T22:00+00:00, close=77870.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.448800|-4.74|107.35|-5.00|5208689|0.69|
|AKE_USDT|0.003994|-3.89|-81.09|-4.15|13567023|5.01|
|OP_USDT|0.109640|-1.38|-1.50|-1.64|8387799|1.82|
|TIA_USDT|0.434300|-1.27|-18.98|-1.53|11789362|2.30|
|QNT_USDT|192.880000|-0.94|-2.53|-1.20|56941247|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003994|0.003851|0.003984|1.28|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.448800|1.427900|1.448800|0.85|N|Y/Y|N/N|Y|N|
|OP_USDT|0.109640|0.108590|0.109640|1.19|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.880000|190.330000|192.880000|1.48|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.434300|0.427600|0.434300|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T22:00:03+00:00, last15m_closed_end=2026-11-03T22:00+00:00, prior8high=0.004134, depth_time=2026-11-03T22:00:11+00:00, book20_bid_proxy_usdt=68074, book20_ask_proxy_usdt=43267, funding_indicative=-0.000501, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=13567023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-03T22:00:03+00:00, last15m_closed_end=2026-11-03T22:00+00:00, prior8high=1.490000, depth_time=2026-11-03T22:00:08+00:00, book20_bid_proxy_usdt=7837, book20_ask_proxy_usdt=12483, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.74%, turnover=5208689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T22:00:03+00:00, last15m_closed_end=2026-11-03T22:00+00:00, prior8high=0.109990, depth_time=2026-11-03T22:00:13+00:00, book20_bid_proxy_usdt=115730, book20_ask_proxy_usdt=122849, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=8387799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T22:00:03+00:00, last15m_closed_end=2026-11-03T22:00+00:00, prior8high=193.640000, depth_time=2026-11-03T22:00:18+00:00, book20_bid_proxy_usdt=58548, book20_ask_proxy_usdt=117150, funding_indicative=0.000078, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=56941247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T22:00:03+00:00, last15m_closed_end=2026-11-03T22:00+00:00, prior8high=0.436600, depth_time=2026-11-03T22:00:14+00:00, book20_bid_proxy_usdt=328183, book20_ask_proxy_usdt=414236, funding_indicative=0.000006, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=11789362. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
