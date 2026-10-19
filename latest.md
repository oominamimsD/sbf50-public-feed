# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T03:00:23Z**
- feed_generated_utc: 2026-10-19T03:00:24+00:00
- source_sha256: `e5ba3a2e511f0ec59d8c509d34d1d192fe1deb732eac9c60a7785a450c9adad9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T03:00+00:00, close=82682.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T03:00+00:00, close=82682.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.168300|-8.53|58.77|-10.44|7644988|5.95|
|BAT_USDT|0.170530|-4.30|2.33|-6.21|6259870|0.59|
|HBAR_USDT|0.084470|-3.24|-9.92|-5.15|51223415|1.18|
|BTW_USDT|2.255200|-2.17|34.06|-4.08|21548177|0.44|
|STRK_USDT|0.060830|-1.18|-48.99|-3.09|17113534|3.29|
|SAND_USDT|0.060340|0.18|-9.18|-1.73|32581178|1.66|
|AGT_USDT|0.067913|0.56|284.01|-1.35|7603530|4.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067913|0.061224|0.067833|2.46|N|Y/Y|N/N|N|N|
|BAT_USDT|0.170530|0.170000|0.170530|0.68|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.255200|2.230700|2.253800|1.07|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084470|0.083740|0.084470|0.43|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.168300|0.172900|0.168300|3.66|Y|Y/Y|N/N|N|N|
|SAND_USDT|0.060340|0.058570|0.060340|2.01|N|N/N|Y/Y|N|N|
|STRK_USDT|0.060830|0.059910|0.060810|0.27|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=0.065184, depth_time=2026-10-19T03:00:22+00:00, book20_bid_proxy_usdt=3744, book20_ask_proxy_usdt=2625, funding_indicative=0.000145, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.56%, turnover=7603530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=0.176060, depth_time=2026-10-19T03:00:09+00:00, book20_bid_proxy_usdt=29771, book20_ask_proxy_usdt=27813, funding_indicative=0.000097, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=6259870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=2.347600, depth_time=2026-10-19T03:00:15+00:00, book20_bid_proxy_usdt=9238, book20_ask_proxy_usdt=14658, funding_indicative=-0.000311, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=21548177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=0.084860, depth_time=2026-10-19T03:00:12+00:00, book20_bid_proxy_usdt=900440, book20_ask_proxy_usdt=796552, funding_indicative=-0.000021, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=51223415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=0.183900, depth_time=2026-10-19T03:00:07+00:00, book20_bid_proxy_usdt=159115, book20_ask_proxy_usdt=133247, funding_indicative=-0.000031, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.53%, turnover=7644988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=0.060430, depth_time=2026-10-19T03:00:19+00:00, book20_bid_proxy_usdt=851804, book20_ask_proxy_usdt=309124, funding_indicative=-0.007891, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.18%, turnover=32581178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T03:00:02+00:00, last15m_closed_end=2026-10-19T03:00+00:00, prior8high=0.061960, depth_time=2026-10-19T03:00:17+00:00, book20_bid_proxy_usdt=378265, book20_ask_proxy_usdt=368427, funding_indicative=0.000002, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=17113534. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
