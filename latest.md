# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T20:15:22Z**
- feed_generated_utc: 2026-10-31T20:15:24+00:00
- source_sha256: `eec117da1055d35f6253b007799b26795b60debd7a6c385c313740b903d6b6ba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T20:15+00:00, close=77554.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.241300|-18.52|43.69|-18.52|26578245|4.14|
|WLD_USDT|0.396300|-2.00|-14.22|-2.00|35546177|2.52|
|TRX_USDT|0.306080|-2.00|-6.94|-2.00|8749323|0.65|
|FET_USDT|0.160600|-1.65|-6.79|-1.65|5249145|6.22|
|DOT_USDT|0.947600|-1.18|-8.80|-1.18|5610202|1.05|
|ONDO_USDT|0.408000|-1.06|1.64|-1.06|25158260|2.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.947600|0.947700|0.947600|1.96|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.160600|0.160700|0.160600|1.57|Y|Y/Y|Y/Y|Y|Y|
|LSK_USDT|0.241300|0.240170|0.240660|1.25|N|Y/N|N/N|Y|N|
|ONDO_USDT|0.408000|0.408800|0.408000|0.89|N|Y/N|N/N|Y|N|
|TRX_USDT|0.306080|0.305290|0.306160|3.53|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396300|0.395800|0.396200|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-31T20:15:03+00:00, last15m_closed_end=2026-10-31T20:15+00:00, prior8high=0.956800, depth_time=2026-10-31T20:15:18+00:00, book20_bid_proxy_usdt=572289, book20_ask_proxy_usdt=560002, funding_indicative=0.000084, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=5610202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T20:15:03+00:00, last15m_closed_end=2026-10-31T20:15+00:00, prior8high=0.162200, depth_time=2026-10-31T20:15:13+00:00, book20_bid_proxy_usdt=1550293, book20_ask_proxy_usdt=824890, funding_indicative=-0.000143, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=5249145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T20:15:02+00:00, last15m_closed_end=2026-10-31T20:15+00:00, prior8high=0.284740, depth_time=2026-10-31T20:15:08+00:00, book20_bid_proxy_usdt=5941, book20_ask_proxy_usdt=4541, funding_indicative=-0.000773, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.52%, turnover=26578245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-31T20:15:02+00:00, last15m_closed_end=2026-10-31T20:15+00:00, prior8high=0.413300, depth_time=2026-10-31T20:15:18+00:00, book20_bid_proxy_usdt=1921094, book20_ask_proxy_usdt=1664754, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=25158260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T20:15:03+00:00, last15m_closed_end=2026-10-31T20:15+00:00, prior8high=0.310250, depth_time=2026-10-31T20:15:12+00:00, book20_bid_proxy_usdt=72896, book20_ask_proxy_usdt=72148, funding_indicative=-0.000362, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=8749323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T20:15:02+00:00, last15m_closed_end=2026-10-31T20:15+00:00, prior8high=0.400400, depth_time=2026-10-31T20:15:10+00:00, book20_bid_proxy_usdt=2244221, book20_ask_proxy_usdt=2837139, funding_indicative=-0.000040, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=35546177. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
