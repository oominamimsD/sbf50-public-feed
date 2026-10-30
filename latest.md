# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T17:00:16Z**
- feed_generated_utc: 2026-10-30T17:00:18+00:00
- source_sha256: `85023899a645b19ad28600f44094ad1a02cab4ba99ea60a18799d88b3f6018bd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T17:00+00:00, close=77318.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T17:00+00:00, close=77318.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009152|-7.09|12.14|-6.75|17528789|1.09|
|BTW_USDT|1.159600|-4.73|-31.88|-4.39|9561245|0.86|
|PARTI_USDT|0.047960|-3.22|42.52|-2.88|9794793|2.08|
|LIT_USDT|2.776400|-3.05|-16.47|-2.71|12804657|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009152|0.009234|0.009126|1.17|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.159600|1.153100|1.159600|0.52|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.776400|2.790900|2.776400|1.73|Y|Y/Y|Y/Y|Y|Y|
|PARTI_USDT|0.047960|0.047990|0.047960|0.94|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T17:00:01+00:00, last15m_closed_end=2026-10-30T17:00+00:00, prior8high=0.013569, depth_time=2026-10-30T17:00:08+00:00, book20_bid_proxy_usdt=9849, book20_ask_proxy_usdt=16334, funding_indicative=0.000111, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.09%, turnover=17528789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T17:00:02+00:00, last15m_closed_end=2026-10-30T17:00+00:00, prior8high=1.231000, depth_time=2026-10-30T17:00:10+00:00, book20_bid_proxy_usdt=16750, book20_ask_proxy_usdt=10413, funding_indicative=-0.000090, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=9561245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T17:00:02+00:00, last15m_closed_end=2026-10-30T17:00+00:00, prior8high=2.938300, depth_time=2026-10-30T17:00:15+00:00, book20_bid_proxy_usdt=29733, book20_ask_proxy_usdt=32628, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=12804657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PARTI_USDT: quote_utc=2026-10-30T17:00:01+00:00, last15m_closed_end=2026-10-30T17:00+00:00, prior8high=0.051150, depth_time=2026-10-30T17:00:13+00:00, book20_bid_proxy_usdt=140840, book20_ask_proxy_usdt=99029, funding_indicative=-0.000008, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.22%, turnover=9794793. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
