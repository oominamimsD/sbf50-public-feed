# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T22:00:19Z**
- feed_generated_utc: 2026-10-13T22:00:22+00:00
- source_sha256: `bd8bb0cffb76d9728676841c029f54305dadffb449c4b10ad2862ab0eaea8064`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T22:00+00:00, close=83487.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T22:00+00:00, close=83487.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.078410|-5.34|0.74|-5.45|5631349|3.83|
|CT_USDT|0.359250|-3.36|-3.32|-3.47|5521516|0.28|
|W_USDT|0.017390|-3.23|19.83|-3.34|9019305|7.47|
|ICP_USDT|3.108000|-1.05|-8.64|-1.16|14031960|3.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.359250|0.351000|0.359500|0.32|N|Y/Y|N/N|N|N|
|ICP_USDT|3.108000|3.074000|3.108000|2.70|N|Y/Y|Y/Y|N|N|
|PYTH_USDT|0.078410|0.077920|0.078410|0.50|N|Y/Y|Y/Y|N|N|
|W_USDT|0.017390|0.016459|0.017390|0.65|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T22:00:02+00:00, last15m_closed_end=2026-10-13T22:00+00:00, prior8high=0.367810, depth_time=2026-10-13T22:00:11+00:00, book20_bid_proxy_usdt=11898, book20_ask_proxy_usdt=11211, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=5521516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T22:00:02+00:00, last15m_closed_end=2026-10-13T22:00+00:00, prior8high=3.180000, depth_time=2026-10-13T22:00:18+00:00, book20_bid_proxy_usdt=852246, book20_ask_proxy_usdt=628149, funding_indicative=0.000092, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=14031960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-13T22:00:02+00:00, last15m_closed_end=2026-10-13T22:00+00:00, prior8high=0.080290, depth_time=2026-10-13T22:00:08+00:00, book20_bid_proxy_usdt=139751, book20_ask_proxy_usdt=211383, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.34%, turnover=5631349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T22:00:02+00:00, last15m_closed_end=2026-10-13T22:00+00:00, prior8high=0.017719, depth_time=2026-10-13T22:00:14+00:00, book20_bid_proxy_usdt=22934, book20_ask_proxy_usdt=32936, funding_indicative=-0.000455, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=9019305. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
