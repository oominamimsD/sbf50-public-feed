# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T21:00:20Z**
- feed_generated_utc: 2026-10-13T21:00:23+00:00
- source_sha256: `628db1ce31c773cc9cab40ed3b3fb29609d7b0790d0a511aafc5e7e847da42ca`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T21:00+00:00, close=83379.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T21:00+00:00, close=83379.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.078510|-5.22|0.87|-5.19|6019685|3.82|
|CT_USDT|0.364550|-4.29|-1.89|-4.26|5700536|3.29|
|OGN_USDT|0.034890|-2.94|55.68|-2.91|5626579|2.87|
|DOS_USDT|0.209400|-2.74|-2.83|-2.71|8606499|9.56|
|RLC_USDT|0.891200|-1.88|8.70|-1.85|5460882|1.12|
|STRK_USDT|0.084200|-1.42|61.33|-1.39|41171829|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.364550|0.351000|0.364550|1.57|N|N/Y|N/N|N|N|
|DOS_USDT|0.209400|0.206400|0.209400|0.75|N|Y/Y|Y/Y|N|N|
|OGN_USDT|0.034890|0.034870|0.034890|0.39|N|Y/Y|N/N|N|N|
|PYTH_USDT|0.078510|0.077920|0.078510|0.20|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.891200|0.878300|0.891200|0.59|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084200|0.084430|0.084200|0.52|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T21:00:00+00:00, last15m_closed_end=2026-10-13T21:00+00:00, prior8high=0.361890, depth_time=2026-10-13T21:00:10+00:00, book20_bid_proxy_usdt=10874, book20_ask_proxy_usdt=9007, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=5700536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T21:00:00+00:00, last15m_closed_end=2026-10-13T21:00+00:00, prior8high=0.214000, depth_time=2026-10-13T21:00:15+00:00, book20_bid_proxy_usdt=105734, book20_ask_proxy_usdt=100870, funding_indicative=-0.000149, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=8606499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-13T21:00:00+00:00, last15m_closed_end=2026-10-13T21:00+00:00, prior8high=0.036110, depth_time=2026-10-13T21:00:11+00:00, book20_bid_proxy_usdt=202728, book20_ask_proxy_usdt=129381, funding_indicative=-0.000241, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=5626579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T21:00:00+00:00, last15m_closed_end=2026-10-13T21:00+00:00, prior8high=0.080290, depth_time=2026-10-13T21:00:06+00:00, book20_bid_proxy_usdt=125123, book20_ask_proxy_usdt=167498, funding_indicative=0.000023, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.22%, turnover=6019685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T21:00:00+00:00, last15m_closed_end=2026-10-13T21:00+00:00, prior8high=0.908000, depth_time=2026-10-13T21:00:15+00:00, book20_bid_proxy_usdt=64136, book20_ask_proxy_usdt=59423, funding_indicative=-0.000483, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=5460882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T21:00:00+00:00, last15m_closed_end=2026-10-13T21:00+00:00, prior8high=0.089710, depth_time=2026-10-13T21:00:19+00:00, book20_bid_proxy_usdt=199494, book20_ask_proxy_usdt=150440, funding_indicative=0.000019, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=41171829. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
