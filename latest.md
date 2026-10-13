# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T16:00:25Z**
- feed_generated_utc: 2026-10-13T16:00:29+00:00
- source_sha256: `5f48ddde4c9571491bf73f92f3165dec10f2949cf97c15dd72ed70846a87d9d1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.055000|-22.09|25.85|-22.09|19780021|1.82|
|PYTH_USDT|0.077900|-5.96|0.08|-5.96|8368906|1.28|
|DOT_USDT|1.156900|-2.33|-3.70|-2.33|20021179|1.73|
|OGN_USDT|0.035200|-2.08|57.07|-2.08|8495109|5.69|
|RENDER_USDT|1.987000|-1.58|-6.71|-1.58|21224655|5.03|
|DOS_USDT|0.215300|-1.37|-0.09|-1.37|9478673|9.30|
|ZRO_USDT|1.986300|-1.02|-11.77|-1.02|14368335|2.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.215300|0.214700|0.215300|0.78|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.156900|1.159000|1.156900|1.82|Y|Y/Y|Y/Y|N|Y|
|OGN_USDT|0.035200|0.035080|0.035200|0.84|N|Y/Y|N/N|N|N|
|PYTH_USDT|0.077900|0.077960|0.077900|4.21|Y|Y/Y|Y/N|N|N|
|RENDER_USDT|1.987000|1.992000|1.987000|1.52|Y|Y/Y|Y/N|N|N|
|S_USDT|0.055000|0.060750|0.055000|3.44|Y|Y/N|N/N|N|N|
|ZRO_USDT|1.986300|1.988900|1.986300|0.54|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=0.221100, depth_time=2026-10-13T16:00:19+00:00, book20_bid_proxy_usdt=112151, book20_ask_proxy_usdt=99176, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=9478673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=1.207200, depth_time=2026-10-13T16:00:14+00:00, book20_bid_proxy_usdt=230378, book20_ask_proxy_usdt=234069, funding_indicative=0.000015, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=20021179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=0.036790, depth_time=2026-10-13T16:00:17+00:00, book20_bid_proxy_usdt=262161, book20_ask_proxy_usdt=153628, funding_indicative=-0.001270, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=8495109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=0.083530, depth_time=2026-10-13T16:00:12+00:00, book20_bid_proxy_usdt=49469, book20_ask_proxy_usdt=93763, funding_indicative=-0.000033, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=8368906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=2.061000, depth_time=2026-10-13T16:00:19+00:00, book20_bid_proxy_usdt=1623667, book20_ask_proxy_usdt=1412290, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=21224655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=0.072640, depth_time=2026-10-13T16:00:10+00:00, book20_bid_proxy_usdt=41477, book20_ask_proxy_usdt=74409, funding_indicative=-0.000075, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-22.09%, turnover=19780021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T16:00:02+00:00, last15m_closed_end=2026-10-13T16:00+00:00, prior8high=2.039600, depth_time=2026-10-13T16:00:24+00:00, book20_bid_proxy_usdt=34834, book20_ask_proxy_usdt=37057, funding_indicative=-0.000027, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.02%, turnover=14368335. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
