# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T21:15:15Z**
- feed_generated_utc: 2026-10-13T21:15:17+00:00
- source_sha256: `9254af6ded8da9156f492217672d4c3af308649e06a53f1949ddf38d2c9332cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T21:15+00:00, close=83329.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T21:00+00:00, close=83379.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.891000|-3.48|8.68|-3.41|5483044|4.49|
|DOS_USDT|0.210200|-2.36|-2.45|-2.29|8614047|4.76|
|STRK_USDT|0.084990|-2.23|62.84|-2.16|41435772|1.18|
|CT_USDT|0.364990|-1.82|-1.77|-1.75|5708785|7.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.364990|0.351000|0.364990|0.45|N|N/Y|N/N|N|N|
|DOS_USDT|0.210200|0.206400|0.210200|1.36|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.891000|0.878300|0.891400|0.65|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084990|0.083930|0.084990|0.90|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T21:15:02+00:00, last15m_closed_end=2026-10-13T21:15+00:00, prior8high=0.364680, depth_time=2026-10-13T21:15:11+00:00, book20_bid_proxy_usdt=11170, book20_ask_proxy_usdt=17037, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=5708785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T21:15:02+00:00, last15m_closed_end=2026-10-13T21:15+00:00, prior8high=0.214000, depth_time=2026-10-13T21:15:09+00:00, book20_bid_proxy_usdt=137620, book20_ask_proxy_usdt=85668, funding_indicative=-0.000178, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=8614047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T21:15:02+00:00, last15m_closed_end=2026-10-13T21:15+00:00, prior8high=0.908000, depth_time=2026-10-13T21:15:06+00:00, book20_bid_proxy_usdt=50037, book20_ask_proxy_usdt=32992, funding_indicative=-0.000486, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=5483044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T21:15:02+00:00, last15m_closed_end=2026-10-13T21:15+00:00, prior8high=0.089710, depth_time=2026-10-13T21:15:12+00:00, book20_bid_proxy_usdt=163267, book20_ask_proxy_usdt=166712, funding_indicative=0.000017, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=41435772. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
