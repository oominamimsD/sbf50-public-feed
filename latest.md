# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T21:30:16Z**
- feed_generated_utc: 2026-10-13T21:30:18+00:00
- source_sha256: `ef74068835045f240df6b8f464bcb0a368d8f765a2bc612ca87dde46b6ff53db`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T21:30+00:00, close=83300.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T21:00+00:00, close=83379.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.891500|-3.43|8.74|-3.32|5514960|3.36|
|CT_USDT|0.361420|-2.78|-2.73|-2.67|5720786|3.60|
|DOS_USDT|0.210000|-2.46|-2.55|-2.35|8620284|9.53|
|STRK_USDT|0.085310|-1.86|63.46|-1.75|41532642|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.361420|0.351000|0.361420|0.71|N|N/Y|N/N|N|N|
|DOS_USDT|0.210000|0.207500|0.210000|1.07|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.891500|0.878300|0.891500|0.74|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085310|0.083530|0.085310|0.34|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T21:30:00+00:00, last15m_closed_end=2026-10-13T21:30+00:00, prior8high=0.367810, depth_time=2026-10-13T21:30:10+00:00, book20_bid_proxy_usdt=12081, book20_ask_proxy_usdt=14249, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=5720786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T21:30:00+00:00, last15m_closed_end=2026-10-13T21:30+00:00, prior8high=0.214000, depth_time=2026-10-13T21:30:12+00:00, book20_bid_proxy_usdt=90673, book20_ask_proxy_usdt=112123, funding_indicative=-0.000244, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=8620284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T21:30:00+00:00, last15m_closed_end=2026-10-13T21:30+00:00, prior8high=0.907100, depth_time=2026-10-13T21:30:06+00:00, book20_bid_proxy_usdt=78734, book20_ask_proxy_usdt=70516, funding_indicative=-0.000465, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=5514960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T21:30:00+00:00, last15m_closed_end=2026-10-13T21:30+00:00, prior8high=0.089710, depth_time=2026-10-13T21:30:14+00:00, book20_bid_proxy_usdt=248668, book20_ask_proxy_usdt=177104, funding_indicative=0.000017, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=41532642. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
