# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T16:15:19Z**
- feed_generated_utc: 2026-10-12T16:15:22+00:00
- source_sha256: `669531e6316b52b901fbb46951b491f4a943de1bd25bd4481e1305d581aabbd8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T16:15+00:00, close=82850.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|7.740000|-1.55|3.28|-1.75|33327760|1.29|
|CKB_USDT|0.001629|-1.55|22.93|-1.75|5690490|1.84|
|S_USDT|0.056650|-1.28|31.89|-1.48|31211472|1.76|
|PONS_USDT|0.291500|-1.08|-23.98|-1.28|6266648|3.43|
|MAGIC_USDT|0.120780|-0.96|94.83|-1.16|12644417|2.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CKB_USDT|0.001629|0.001600|0.001630|1.66|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.740000|7.600000|7.740000|1.33|N|Y/Y|N/N|Y|N|
|MAGIC_USDT|0.120780|0.116500|0.120860|0.74|N|Y/Y|N/N|Y|N|
|PONS_USDT|0.291500|0.285300|0.291500|0.16|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.056650|0.056520|0.056650|0.62|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CKB_USDT: quote_utc=2026-10-12T16:15:01+00:00, last15m_closed_end=2026-10-12T16:15+00:00, prior8high=0.001674, depth_time=2026-10-12T16:15:10+00:00, book20_bid_proxy_usdt=21564, book20_ask_proxy_usdt=20712, funding_indicative=-0.000803, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=5690490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-12T16:15:01+00:00, last15m_closed_end=2026-10-12T16:15+00:00, prior8high=7.961000, depth_time=2026-10-12T16:15:08+00:00, book20_bid_proxy_usdt=215422, book20_ask_proxy_usdt=170657, funding_indicative=0.000225, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=33327760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-12T16:15:01+00:00, last15m_closed_end=2026-10-12T16:15+00:00, prior8high=0.123710, depth_time=2026-10-12T16:15:17+00:00, book20_bid_proxy_usdt=174589, book20_ask_proxy_usdt=173221, funding_indicative=-0.000235, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=12644417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-12T16:15:01+00:00, last15m_closed_end=2026-10-12T16:15+00:00, prior8high=0.309100, depth_time=2026-10-12T16:15:14+00:00, book20_bid_proxy_usdt=205354, book20_ask_proxy_usdt=202507, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=6266648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-12T16:15:01+00:00, last15m_closed_end=2026-10-12T16:15+00:00, prior8high=0.061100, depth_time=2026-10-12T16:15:11+00:00, book20_bid_proxy_usdt=135995, book20_ask_proxy_usdt=128886, funding_indicative=0.000026, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=31211472. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
